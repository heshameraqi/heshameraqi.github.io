# Digital Bussiness Cards #
### Nahdet Misr ###

<div dir="rtl">
<b>الخطوات</b>

<ol>

  <li>
	حمل ملف الـ Excel المسمى Business Cards.csv وأفتحه باستخدام برنامج Notepad و أضف بيانات جميع الموظفين المُراد استخراج كارت شخصي إلكتروني لهم بهذا الملف. بيانات الموظف تكون مفصولة بحرف ;
	<br>البيانات بالترتيب هي: الأسم ; عنوان البريد الإلكتروني ; الوظيفة ; الهاتف ; حساب موقع LinkedIn (أدخل على حساب الموظف على موقع LinkedIn وأحصل على أسم الحساب من خلال آخر جزء مكتوب في عنوان الموقع).
	<br>لا داعي للقلق، أي بيانات غير موجودة يمكن استبدلها بمسافة فارغة بدون أي مشكلة في النظام.
  </li>

  <li>
	لكل موظف جديد مطلوب أدخاله على النظام، أحصل على صورة شخصية له وسميها 3.jpg إذا كان رقم تسلسل الموظف في ملف الـ Excel رقم 3 على سبيل المثال (السطر رقم 3 في الملف) وهكذا.
  </li>

  <li>
	لكل موظف جديد، أكتب ملف vcf مثل الملف المرفق وسميه 3.vcf وأكتب بداخله به بيانات الموظف. يمكن كتابة الملف وفتحه بإستخدام برنامج Notepad.
  </li>

  <li>
	ارسل للمبرمج ملف الـ Excel والصور وملفات vcf للموظفين الجدد ليرفعها على النظام.
  </li>

  <li>
	أفتح موقع https://www.logodesign.net/qrcode-generator وأكتب https://heshameraqi.github.io/bussiness-cards-nahdetmisr/card.html?employee_number=3 (استبدل آخر رقم برقم تسلسل الموظف في ملف ال Excel).
	<br>الموقع سينتج لك صورة الـ QR Code الذي سيتم طبعه على الكارت
	<br>بإمكانك تغيير اللون الأسود بلون الشركة الأزرق بإستخدام الكود: #24317E إذا أردت.
  </li>

</ol>

</div>

### Nahdet Misr AI, heraqi@aucegypt.edu ###

**Steps to generate or editing Digital Cards for employee number 5 for example (you can do that on multiple employees at once):**
1. Generate the QR code that will be printed with on the physical card:
	1. Visit this website or similar QR code generator websites: https://www.logodesign.net/qrcode-generator (You can use this front color which represents the company identity #24317E and add/or the company logo image)
	2. Add this link/URL: https://heshameraqi.github.io/bussiness-cards-nahdetmisr/card.html?employee_number=5 and generate the QR to be printed (Please note to change 5.html according to the employee number)
2. Verify the information for employee number 5 in present in row number 5 in Business Cards.CSV file in data folder (You can open the file was any Excel or any text editor as Notepad). The employee data items are separated with ; symbol, it should look like this: Name ; emails ; position and company ; phones ; LinkedIn account name
3. Create or edit the data in 5.vcf file in the folder vcards (You can open it was any text editor as Notepad).
4. Send a jpg personal photo for the employee named 5.jpg

**Notes:**
- This repository is for developers who are willing to continue development or changes to this project: 
https://github.com/heshameraqi/heshameraqi.github.io/tree/master/bussiness-cards-nahdetmisr
The actual GitHub HTML preview happens using:
GitHub Pages: https://heshameraqi.github.io/bussiness-cards-nahdetmisr/card.html?employee_number=5
or raw.githack CDN service: https://raw.githack.com/heshameraqi/bussiness-cards-nahdetmisr/main/card.html?employee_number=5
- Company logo can be retrieved from https://github.com/heshameraqi/bussiness-cards-nahdetmisr/blob/main/assets/images/logo/logo.png
- Employee photo should be added to the photos folder.

![sample](./assets/Sample.png)