# Digital Bussiness Cards #
### Nahdet Misr ###

### Nahdet Misr AI, heraqi@aucegypt.edu ###

**Steps to generate or editing Digital Cards for employee number 5 for example:**
1. Generate the QR code that will be printed with on the physical card:
	1. Visit this website or similar QR code generator websites: https://www.logodesign.net/qrcode-generator (You can use this front color which represents the company identity #24317E and add/or the company logo image)
	2. Add this link/URL: https://heshameraqi.github.io/bussiness-cards-nahdetmisr/card.html?employee_number=5 and generate the QR to be printed (Please note to change 5.html according to the employee number)
2. Verify the information for employee number 5 in present in row number 5 in Business Cards.CSV file in data folder (You can open the file was any Excel or any text editor as Notepad). The employee data items are separated with ; symbol, it should look like this: Name ; emails ; position and company ; phones ; LinkedIn account name
3. Send the updated Business Cards.CSV file to be uploaded to the project server
4. [Optional] Send a jpg personal photo for the employee named 5.jpg to be upload to server


<div dir="rtl">
<b>الخطوات باللغة العربية</b>

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
	ارسل للمبرمج ملف الـ Excel والصور للموظفين الجدد ليرفعها على النظام.
  </li>

  <li>
	أفتح موقع
	<br>https://www.logodesign.net/qrcode-generator
	<br>وأكتب
	<br>https://heshameraqi.github.io/bussiness-cards-nahdetmisr/card.html?employee_number=3
	<br>(استبدل آخر رقم برقم تسلسل الموظف في ملف ال Excel).
	<br>الموقع سينتج لك صورة الـ QR Code الذي ستقوم بطبعه على الكارت
	<br>بإمكانك تغيير اللون الأسود بلون الشركة الأزرق بإستخدام الكود: #24317E إذا أردت.
  </li>

</ol>

</div>

**Notes:**
- The actual GitHub HTML preview happens using:
GitHub Pages: https://heshameraqi.github.io/bussiness-cards-nahdetmisr/card.html?employee_number=5
or it can happen using raw.githack CDN service: https://raw.githack.com/heshameraqi/bussiness-cards-nahdetmisr/main/card.html?employee_number=5
- Company logo can be retrieved from https://github.com/heshameraqi/bussiness-cards-nahdetmisr/blob/main/assets/images/logo/logo.png
- Employee photo should be added to the photos folder.
- The vcards folder is not used any more as its generation process is now automated with JS

![sample](./assets/Sample.png)