# نظام إدارة أعمال المهندسة رغد الحديثي

منصة احترافية لإدارة حجوزات العملاء ومشاريع التصميم الهندسي.

## المميزات

- إدارة المستخدمين والصلاحيات (مدير، موظف، مساعد)
- إدارة العملاء (بيانات، مشاريع، مواعيد)
- نظام الحجوزات والمواعيد
- إدارة المشاريع الهندسية (معماري، داخلي، إشراف، مخططات)
- إدارة الملفات والمخططات الهندسية
- الإدارة المالية (فواتير، دفعات)
- التقارير والإحصائيات
- الإشعارات والتنبيهات
- دعم كامل للغة العربية

## التثبيت والتشغيل (ويب)

```bash
npm install
npx prisma migrate dev --name init
npm run seed
npm run dev
```

## تشغيل كتطبيق سطح مكتب (Electron)

```bash
npm run start
# في نافذة أخرى
npx electron .
```

## بناء ملف EXE

```bash
npm install --save-dev @electron-forge/cli
npx electron-forge import
npm run make
```

## حساب الإداري الافتراضي

- البريد الإلكتروني: admin@raghdah.com
- كلمة المرور: admin123

## التقنيات المستخدمة

- Next.js 16
- Prisma ORM
- SQLite
- Tailwind CSS
- NextAuth.js
- Electron