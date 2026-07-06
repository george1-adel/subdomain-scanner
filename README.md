# Subdomain Scanner

باستخدام **puredns** لعمل brute force على subdomains.

## كيفية الاستخدام

1. **إنشاء ريبو على GitHub**:
   - روح https://github.com/new
   - سميه `subdomain-scanner` مثلاً
   - `Public` أو `Private` حسب ما تحب

2. **رفع الملفات**:
   ```bash
   cd /home/george/tools/subdomain-scanner
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<USERNAME>/subdomain-scanner.git
   git push -u origin main
   ```

3. **تشغيل الـ workflow**:
   - افتح الريبو على GitHub
   - اضغط على **Actions** > **Subdomain Brute Force**
   - اضغط **Run workflow**
   - اكتب target (مثال: `google.com`)
   - اختار wordlist
   - اضغط **Run**

4. **النتائج**:
   - تتحفظ في مجلد `results/` باسم الـ target
   - ملف `results/<target>.txt`

## الأدوات المستخدمة

- **puredns**: https://github.com/d3mondev/puredns
- **Wordlists**: assetnote.io

ملاحظة: استخدم فقط على أهداف تملكها أو لديك إذن صريح لاختبارها.
