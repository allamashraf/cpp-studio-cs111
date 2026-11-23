# C++ Studio — EUI C-CS111 Interactive Platform

## أسرع طريقتين لرفع الموقع أونلاين مجاناً (في دقيقة واحدة)

### الطريقة 1: Netlify Drop (بدون حساب GitHub)
1. فك الضغط عن الملف `cpp_studio_cs111_deploy.zip`.
2. افتح https://app.netlify.com/drop
3. اسحب الفولدر `cpp_studio_deploy` وارميه في الصفحة.
4. هيطلعلك لينك HTTPS دائم فوراً يشتغل على الكمبيوتر والموبايل!

### الطريقة 2: Vercel
1. ارفع الفولدر على GitHub Repository أو استخدم `npx vercel` داخل الفولدر.
2. اختار Deploy — الموقع هيبقى أونلاين فوراً.


### الطريقة 3: GitHub Pages (مجاناً مع GitHub)
1. ارفع الملفين `index.html` و `README.md` على Repository جديد (Public).
2. من إعدادات الريبو: Settings → Pages → Source: Deploy from a branch → main / (root) → Save.
3. بعد دقيقة تقريباً الموقع شغال على: https://<username>.github.io/<repo-name>/ بالـ HTTPS مجاناً.
4. أي تعديل جديد على main بيتحدث تلقائياً خلال دقيقة.

## تشغيل الكود بـ Compiler C++ حقيقي (`g++`)
داخل تبويب **IDE (17)**، غيّر المحرك من `Fast Runner (Local)` إلى `Real g++ (Judge0 CE)` عشان الكود يتنفذ على `g++` حقيقي مع رسائل أخطاء الـ Compiler الفعلية (وفي حالة انقطاع النت بيرجع تلقائياً للمشغل المحلي السريع).
