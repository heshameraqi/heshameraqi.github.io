---
layout: post
title: Install Tensorflow for CUDA 9 without root
subtitle: No admin :-)
bigimg: /img/TF_Cuda.png
tags: [books, test]
---

At the moment latest [Tensorflow](https://www.tensorflow.org) 1.4 does not yet support [Cuda 9.0](https://developer.nvidia.com/cuda-toolkit/whatsnew). This tutorial is about how to install Tensorflow that uses Cuda 9.0 without root access.

**1- Create a temp folder to install download sources into:**

~~~
mkdir downloads
cd downloads
~~~

**2- Building and installing CMake:**

The easiest way to install CMake is from source. Head over to the [CMake downloads page](http://www.cmake.org/download) and get the latest “Unix/Linux Source” *.tar.gz file.

{% highlight bash linenos %}
wget https://cmake.org/files/v3.10/cmake-3.10.1.tar.gz
tar -xf cmake*.tar.gz
cd cmake*
./configure --prefix=$HOME
make
make install
{% endhighlight %}

You should now have the most up-to-date installation of cmake. Check the version by typing:

~~~
cmake --version
~~~

**3- Building MKL locally without root access:**

The Tensorflow wheels that we are going to install later on in this tutorial contain MKL support. If you don't have it, install MKL as follows. MKL is [Intel's deep learning kernal library](https://github.com/01org/mkl-dnn), which makes training neural nets on CPU much faster. If you don't have it, install it like the following:

{% highlight bash linenos %}
git clone https://github.com/01org/mkl-dnn.git
cd mkl-dnn/scripts && ./prepare_mkl.sh && cd ..
mkdir -p build && cd build && cmake .. && make
make install
{% endhighlight %}

At the last step, it's expected to get an error because without root access the output library can't be copied to system roots:

{: .box-error}
CMake Error at cmake_install.cmake:41 (file):
file INSTALL cannot copy file
"/home/heraqi/downloads/mkl-dnn/external/mklml_lnx_2018.0.1.20171227/lib/libmklml_intel.so"
to "/usr/local/lib/libmklml_intel.so".

To fix it, lets add it manually to the shared libraries environment variable each time a bash script is opened by adding the following line to the file "home/your_user_name/.bashrc":

~~~
export LD_LIBRARY_PATH=/home/heraqi/downloads/mkl-dnn/external/mklml_lnx_2018.0.1.20171227/lib/:$LD_LIBRARY_PATH
~~~

**4- Install Tensorflow CUDA 9.0 wheel:**

[Download a wheel files](https://github.com/mind/wheels/releases/tag/tf1.4-gpu-cuda9) that support CUDA 9.0 and install it:

~~~
pip install https://github.com/mind/wheels/releases/download/tf1.4-gpu-cuda9/tensorflow-1.4.0-cp36-cp36m-linux_x86_64.whl
~~~

Usually use conda to allow a local installation for your Python distribution because if you are not root, pip call will fail.

You have successfully installed Tensorflow for CUDA 9 without root until Google supports it :)
