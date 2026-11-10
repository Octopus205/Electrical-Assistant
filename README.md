# Electrical Assistant

تطبيق مساعد مهندس الكهرباء — مشروع Android باستخدام **Kotlin** و **Jetpack Compose**.

## رفع ملفات المشروع

إذا كنت ترفع المشروع من هاتف Android، اتبع الخطوات التالية:

1. افتح تبويب **Code** في المستودع.
2. اضغط **Add file** ثم **Create new file** إذا لم يظهر README بالفعل، أو استخدم **Add file → Upload files**.
3. ارفع ملف المشروع المضغوط كما هو:
   `Electrical-Assistant-GitHub-Ready.zip`
4. اترك اسم الملف كما هو، ثم اضغط **Commit changes**.

**مهم:** لا تفك ضغط الملف على GitHub ولا ترفع ملفات ZIP الأخرى. ارفع هذا الملف وحده في المجلد الرئيسي للمستودع. بعد رفعه أخبرني هنا؛ سأجهز خطوة استخراج الملفات وبناء APK من GitHub Actions.

## بناء التطبيق

سيتم إعداد GitHub Actions لبناء نسخة **Debug APK** بعد تجهيز ملفات المشروع. عند اكتمال البناء ستجد ملف APK في:

**Actions → Android APK Build → Artifacts**

## ملاحظات الأمان

- لا ترفع مفتاح Gemini API الحقيقي إلى المستودع.
- لا تضع كلمات مرور أو مفاتيح سرية داخل ملفات المشروع.
- ملف APK الناتج نسخة Debug للاختبار، وليس إصداراً نهائياً للنشر.

## التقنيات

- Android
- Kotlin
- Jetpack Compose
