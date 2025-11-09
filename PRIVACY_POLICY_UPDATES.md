# Privacy Policy Updates - No-Account Approach

**Date:** January 9, 2025
**Purpose:** Update privacy policy to reflect removal of login system

---

## 🔴 SECTIONS TO REMOVE

### 1. Remove Account Creation References
Search for and remove or update any mentions of:
- "إنشاء حساب" / "Create account"
- "تسجيل الدخول" / "Login"
- "اسم المستخدم" / "Username"
- "كلمة المرور" / "Password"

---

## ✅ SECTIONS TO ADD

### Section: Device Backup (Add after "Data Storage" section)

```html
<h2 class="lang-ar">النسخ الاحتياطي التلقائي</h2>
<h2 class="lang-en">Automatic Backup</h2>

<div class="lang-ar">
    <p>يتم نسخ بياناتك احتياطياً تلقائياً عبر نظام التشغيل الخاص بجهازك:</p>
    <ul>
        <li><strong>أندرويد:</strong> النسخ الاحتياطي التلقائي من جوجل (Google Auto Backup)</li>
        <li><strong>iOS:</strong> النسخ الاحتياطي من iCloud (iCloud Backup)</li>
    </ul>
    <p>عند تثبيت التطبيق على جهاز جديد باستخدام نفس حساب جوجل أو Apple ID، سيتم استعادة بياناتك تلقائياً.</p>

    <h3>كيف يعمل النسخ الاحتياطي التلقائي؟</h3>
    <ul>
        <li>يتم النسخ الاحتياطي لقاعدة البيانات المشفرة</li>
        <li>يتم حفظ مفاتيح التشفير بشكل آمن في Keychain/Keystore</li>
        <li>لا حاجة لإنشاء حساب أو تسجيل دخول</li>
        <li>بياناتك تبقى ملكاً لك فقط</li>
    </ul>
</div>

<div class="lang-en">
    <p>Your data is automatically backed up via your device's operating system:</p>
    <ul>
        <li><strong>Android:</strong> Google Auto Backup</li>
        <li><strong>iOS:</strong> iCloud Backup</li>
    </ul>
    <p>When you install the app on a new device using the same Google account or Apple ID, your data will be automatically restored.</p>

    <h3>How Does Automatic Backup Work?</h3>
    <ul>
        <li>The encrypted database is backed up</li>
        <li>Encryption keys are securely stored in Keychain/Keystore</li>
        <li>No account creation or login required</li>
        <li>Your data remains yours only</li>
    </ul>
</div>
```

### Section: Manual Export (Add after "Automatic Backup")

```html
<h2 class="lang-ar">التصدير والاستيراد اليدوي</h2>
<h2 class="lang-en">Manual Export & Import</h2>

<div class="lang-ar">
    <p>يتيح لك التطبيق تصدير بياناتك يدوياً للحصول على نسخة احتياطية إضافية أو لنقل البيانات بين الأجهزة:</p>

    <h3>كيفية تصدير بياناتك:</h3>
    <ol>
        <li>افتح التطبيق واذهب إلى <strong>الإعدادات</strong></li>
        <li>اختر <strong>النسخ الاحتياطي والبيانات</strong></li>
        <li>اضغط على <strong>تصدير البيانات</strong></li>
        <li>سيتم إنشاء ملف JSON يحتوي على جميع بياناتك</li>
        <li>يمكنك مشاركة هذا الملف عبر البريد الإلكتروني أو خدمات التخزين السحابي</li>
    </ol>

    <h3>كيفية استيراد بياناتك:</h3>
    <ol>
        <li>افتح التطبيق واذهب إلى <strong>الإعدادات</strong></li>
        <li>اختر <strong>النسخ الاحتياطي والبيانات</strong></li>
        <li>اضغط على <strong>استيراد البيانات</strong></li>
        <li>اختر ملف النسخة الاحتياطية (JSON)</li>
        <li>سيتم دمج البيانات المستوردة مع بياناتك الحالية</li>
    </ol>

    <p><strong>ملاحظة:</strong> ملف التصدير يحتوي على:</p>
    <ul>
        <li>جميع المجموعات والأذكار</li>
        <li>العدادات الحالية</li>
        <li>الإعدادات الشخصية</li>
        <li>التاريخ والإحصائيات (إن وجدت)</li>
    </ul>
</div>

<div class="lang-en">
    <p>The app allows you to manually export your data for an additional backup or to transfer data between devices:</p>

    <h3>How to Export Your Data:</h3>
    <ol>
        <li>Open the app and go to <strong>Settings</strong></li>
        <li>Select <strong>Backup & Data</strong></li>
        <li>Tap <strong>Export Data</strong></li>
        <li>A JSON file containing all your data will be created</li>
        <li>You can share this file via email or cloud storage services</li>
    </ol>

    <h3>How to Import Your Data:</h3>
    <ol>
        <li>Open the app and go to <strong>Settings</strong></li>
        <li>Select <strong>Backup & Data</strong></li>
        <li>Tap <strong>Import Data</strong></li>
        <li>Choose your backup file (JSON)</li>
        <li>The imported data will be merged with your existing data</li>
    </ol>

    <p><strong>Note:</strong> The export file contains:</p>
    <ul>
        <li>All groups and supplications</li>
        <li>Current counters</li>
        <li>Personal settings</li>
        <li>History and statistics (if any)</li>
    </ul>
</div>
```

---

## 📝 SECTIONS TO UPDATE

### Update: "Data We Collect" Section

**OLD TEXT (Arabic):**
```
معلومات الحساب (اسم المستخدم، البريد الإلكتروني)
```

**NEW TEXT (Arabic):**
```
لا يتطلب التطبيق إنشاء حساب. جميع البيانات محفوظة محلياً على جهازك فقط.
```

**OLD TEXT (English):**
```
Account information (username, email)
```

**NEW TEXT (English):**
```
The app does not require account creation. All data is stored locally on your device only.
```

### Update: "Data Storage" Section

**ADD THIS (Arabic):**
```
<p><strong class="highlight">تخزين محلي بالكامل:</strong></p>
<ul>
    <li>لا يتم رفع بياناتك إلى أي خادم</li>
    <li>لا يوجد سحابة أو مزامنة عبر الإنترنت</li>
    <li>بياناتك موجودة على جهازك فقط</li>
    <li>تشفير قاعدة البيانات المحلية باستخدام SQLCipher</li>
</ul>
```

**ADD THIS (English):**
```
<p><strong class="highlight">Fully Local Storage:</strong></p>
<ul>
    <li>Your data is not uploaded to any server</li>
    <li>No cloud or online synchronization</li>
    <li>Your data exists only on your device</li>
    <li>Local database encryption using SQLCipher</li>
</ul>
```

### Update: "Third-Party Services" Section

**ADD CLARIFICATION (Arabic):**
```
<h3>البيانات المشاركة مع الأطراف الثالثة:</h3>
<ul>
    <li><strong>RevenueCat (إدارة الاشتراكات):</strong> معرف مجهول فقط (Anonymous User ID) - لا يتم مشاركة أي بيانات شخصية أو محتوى الأذكار</li>
    <li><strong>Google AdMob (الإعلانات):</strong> معرف الإعلانات (Advertising ID) فقط - لأغراض عرض الإعلانات المناسبة</li>
</ul>
<p><strong class="highlight">مهم:</strong> لا نشارك أبداً محتوى أذكارك، عداداتك، أو إحصائياتك مع أي طرف ثالث.</p>
```

**ADD CLARIFICATION (English):**
```
<h3>Data Shared with Third Parties:</h3>
<ul>
    <li><strong>RevenueCat (Subscription Management):</strong> Anonymous User ID only - no personal data or supplication content is shared</li>
    <li><strong>Google AdMob (Advertising):</strong> Advertising ID only - for displaying appropriate ads</li>
</ul>
<p><strong class="highlight">Important:</strong> We never share your supplication content, counters, or statistics with any third party.</p>
```

---

## 🔄 IMPLEMENTATION STEPS

1. **Open the file:** `privacy-policy.html`
2. **Search and remove** all account/login references
3. **Add new sections** for Device Backup and Manual Export (copy HTML from above)
4. **Update existing sections** with new text (use Find & Replace)
5. **Test both languages** - toggle between Arabic and English
6. **Save and commit:**
   ```bash
   cd C:/Users/saeed/tathkeer-privacy
   git add privacy-policy.html
   git commit -m "Update privacy policy: remove account system, add backup info"
   git push origin main
   ```
7. **Verify live** at: https://saeed265310.github.io/tathkeer-privacy/privacy-policy.html

---

## ✅ KEY MESSAGES TO CONVEY

### Arabic:
- **لا حاجة لإنشاء حساب** - التطبيق محلي بالكامل
- **النسخ الاحتياطي التلقائي** - عبر جوجل/آبل
- **تصدير/استيراد يدوي** - للتحكم الكامل
- **خصوصية تامة** - بياناتك على جهازك فقط

### English:
- **No account needed** - Fully local app
- **Automatic backup** - Via Google/Apple
- **Manual export/import** - Full control
- **Complete privacy** - Your data stays on your device

---

**Document Created:** January 9, 2025
**Status:** Ready for implementation
**Estimated Time:** 20-30 minutes
