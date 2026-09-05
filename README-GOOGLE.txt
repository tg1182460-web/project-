مستشار المشاريع — ملفات Google

ضع الملفات الثلاثة الأساسية في جذر مستودع GitHub Pages:
1) index.html
2) robots.txt
3) sitemap.xml

site.webmanifest اختياري لتحسين تعريف الموقع.

مهم جدًا:
- استبدل YOUR-USERNAME و YOUR-REPOSITORY بالرابط الحقيقي للموقع داخل robots.txt و sitemap.xml.
- داخل index.html استبدل:
  حط-كود-جوجل-هنا
  بكود google-site-verification الذي يعطيه لك Google Search Console.

طريقة التحقق:
Google Search Console → إضافة موقع → اختر Domain أو URL prefix.
إذا اخترت HTML tag، انسخ وسم google-site-verification الذي يعطيه Google وضعه داخل <head> في index.html ثم اضغط Verify.
بعد نجاح التحقق أرسل sitemap.xml من Search Console.

ملاحظة:
لا يوجد ملف تحقق ثابت يمكن إنشاؤه من عندنا؛ Google يولّد رمزًا فريدًا لحسابك.
