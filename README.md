# OtoDesk Updates

هذا المستودع **ليس مصدر البرنامج**. هنا تُنشر ملفات التحديث والرخصة فقط.

## التحديثات (الأهم)

المثبّتات ليست في قائمة الملفات أعلاه. افتح تبويب **Releases**:

https://github.com/mfu-service/OtoDesk-updates/releases

- [أوتو ديسك 1.2.0](https://github.com/mfu-service/OtoDesk-updates/releases/tag/v1.2.0) — نافذة عرض المعرض
- [أوتو ديسك 1.1.0](https://github.com/mfu-service/OtoDesk-updates/releases/tag/v1.1.0)

النسخة المثبتة تفحص هذا المستودع تلقائياً من **هوية المحل → التحديثات**.

ملف `latest.yml` داخل كل إصدار يخبر البرنامج باسم الملف ومجموع التحقق.

## `revoked.json`

قائمة إلغاء الرخص. أضف `licenseId` هنا ثم ادفع الملف إلى `main` حتى تتوقف الرخصة الملغاة عن العمل.

مفاتيح التفعيل نفسها **لا تُحفظ هنا**.  
المفتاح الخاص محلي في `secrets/`، والرخصة بعد التفعيل على جهاز الزبون في `%APPDATA%\bicho-auto\license.dat`.

## المصدر

كود أوتو ديسك: https://github.com/mfu-service/OtoDesk
