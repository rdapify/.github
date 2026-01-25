<div align="center" dir="rtl">

# 🌐 RDAPify

### عميل RDAP حديث وآمن وسريع البرق

**مكتبة RDAP من الجيل التالي لـ TypeScript/JavaScript**

[![npm version](https://img.shields.io/npm/v/rdapify?color=blue&logo=npm)](https://www.npmjs.com/package/rdapify)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-16%2B-green?logo=node.js)](https://nodejs.org/)

[الموقع](https://rdapify.com) • [التوثيق](https://rdapify.com/docs) • [الملعب التفاعلي](https://rdapify.com/playground) • [مرجع API](https://rdapify.com/docs/api)

</div>

---

<div dir="rtl">

## 🚀 ما هو RDAPify؟

RDAPify هو **عميل RDAP موحد على مستوى المؤسسات** يجعل الاستعلام عن بيانات تسجيل النطاقات وعناوين IP وأرقام AS بسيطاً وآمناً وسريعاً. مبني بـ TypeScript، يوفر بديلاً حديثاً لأدوات WHOIS القديمة.

### ✨ المميزات الرئيسية

- 🔒 **الخصوصية أولاً** - إخفاء البيانات الشخصية المدمج والامتثال لـ GDPR/CCPA
- ⚡ **أداء عالي** - تخزين مؤقت ذكي وتجميع الاتصالات
- 🛡️ **أمان المؤسسات** - حماية SSRF والتحقق من المدخلات
- 🌍 **عالمي** - يعمل في Node.js و Deno و Bun والمتصفحات وبيئات Edge
- 📦 **بدون تبعيات** - بصمة صغيرة، موثوقية قصوى
- 🎯 **آمن من حيث الأنواع** - دعم كامل لـ TypeScript مع أنواع شاملة
- 🔄 **اكتشاف تلقائي** - تكامل تلقائي مع خدمة IANA bootstrap
- 📊 **قابل للمراقبة** - سجلات ومقاييس ومراقبة مدمجة

## 💻 البدء السريع

```bash
npm install rdapify
```

```typescript
import { RDAPClient } from 'rdapify';

const client = new RDAPClient();

// استعلام عن نطاق
const domain = await client.domain('example.com');
console.log(domain.registrar);

// استعلام عن عنوان IP
const ip = await client.ip('8.8.8.8');
console.log(ip.network);

// استعلام عن ASN
const asn = await client.asn(15169);
console.log(asn.name);
```

## 🎯 حالات الاستخدام

- 🔍 **بحث النطاقات** - التحقيق في ملكية النطاقات وتاريخها
- 🌐 **معلومات IP** - تحليل تخصيصات عناوين IP والشبكات
- 🔐 **عمليات الأمان** - معلومات التهديدات والاستجابة للحوادث
- 📊 **الامتثال** - جمع البيانات المتوافق مع GDPR/CCPA
- 🤖 **الأتمتة** - المعالجة الدفعية والمراقبة المجدولة
- 📈 **التحليلات** - طوبولوجيا الشبكة ورسم العلاقات

## 📦 مشاريعنا

<table dir="rtl">
<tr>
<td width="50%">

### 📚 مكتبة RDAPify
مكتبة TypeScript/JavaScript الأساسية

**المميزات:**
- استعلامات النطاقات و IP و ASN
- تخزين مؤقت ذكي وتحديد المعدل
- ضوابط الخصوصية وإخفاء البيانات الشخصية
- أمان على مستوى المؤسسات

[عرض المستودع ←](https://github.com/rdapify/RDAPify)

</td>
<td width="50%">

### 🌐 الموقع والتوثيق
توثيق وأدلة شاملة

**يتضمن:**
- أدلة البدء
- مرجع API
- أمثلة التكامل
- ملعب تفاعلي

[زيارة الموقع ←](https://rdapify.com)

</td>
</tr>
</table>

## 🎮 جربه الآن

اختبر RDAPify عملياً مع **الملعب التفاعلي**:

👉 **[تشغيل الملعب](https://rdapify.com/playground)**

اختبر الاستعلامات، استكشف الاستجابات، وشاهد النتائج في الوقت الفعلي بدون كتابة أي كود!

## 🌟 لماذا تختار RDAPify؟

| الميزة | RDAPify | WHOIS القديم |
|---------|---------|--------------|
| البروتوكول | RDAP حديث | WHOIS قديم |
| التنسيق | JSON منظم | نص غير منظم |
| الخصوصية | إخفاء البيانات الشخصية المدمج | تحليل يدوي |
| الأمان | حماية SSRF | محدود |
| الأداء | تخزين مؤقت ذكي | بدون تخزين مؤقت |
| أمان الأنواع | TypeScript كامل | لا يوجد |
| المعايير | متوافق مع RFC 7483 | متفاوت |

## 📚 التوثيق

- 📖 [البدء](https://rdapify.com/docs/getting-started)
- 🔧 [مرجع API](https://rdapify.com/docs/api)
- 🎯 [حالات الاستخدام والأمثلة](https://rdapify.com/docs/examples)
- 🔒 [الأمان والخصوصية](https://rdapify.com/docs/security)
- 🚀 [أدلة النشر](https://rdapify.com/docs/deployment)
- 🤝 [دليل المساهمة](https://github.com/rdapify/RDAPify/blob/main/CONTRIBUTING.md)

## 🤝 المجتمع والدعم

<div align="center">

### انضم إلى مجتمعنا

[![GitHub Discussions](https://img.shields.io/badge/Discussions-Join-blue?logo=github)](https://github.com/rdapify/RDAPify/discussions)
[![GitHub Issues](https://img.shields.io/badge/Issues-Report-red?logo=github)](https://github.com/rdapify/RDAPify/issues)
[![Twitter Follow](https://img.shields.io/badge/Twitter-Follow-1DA1F2?logo=twitter)](https://twitter.com/rdapify)

</div>

### 💬 احصل على المساعدة

- 💡 **أسئلة؟** اسأل في [GitHub Discussions](https://github.com/rdapify/RDAPify/discussions)
- 🐛 **وجدت خطأ؟** أبلغ عنه في [Issues](https://github.com/rdapify/RDAPify/issues)
- 📧 **تحتاج دعم؟** راسلنا على [support@rdapify.com](mailto:support@rdapify.com)
- 🔒 **مشكلة أمنية؟** راسلنا على [security@rdapify.com](mailto:security@rdapify.com)

### 📬 التواصل

- **الاستفسارات العامة**: [contact@rdapify.com](mailto:contact@rdapify.com)
- **الدعم**: [support@rdapify.com](mailto:support@rdapify.com)
- **الأمان**: [security@rdapify.com](mailto:security@rdapify.com)
- **الشراكات**: [partnerships@rdapify.com](mailto:partnerships@rdapify.com)
- **الرعاية**: [sponsors@rdapify.com](mailto:sponsors@rdapify.com)

## 🎯 خارطة الطريق

- [x] وظائف عميل RDAP الأساسية
- [x] دعم TypeScript
- [x] ضوابط الخصوصية وإخفاء البيانات الشخصية
- [x] ملعب تفاعلي
- [ ] أداة CLI
- [ ] إضافة متصفح
- [ ] GraphQL API
- [ ] لوحة مراقبة في الوقت الفعلي
- [ ] كشف الشذوذ بالتعلم الآلي

## 💖 الرعاة والمساهمون

RDAPify مشروع مفتوح المصدر يديره مطورون شغوفون. نرحب بالمساهمات من المجتمع!

### 🌟 كن راعياً

ادعم المشروع وساعدنا في بناء أدوات أفضل للجميع:

- ☕ [الرعاية على GitHub](https://github.com/sponsors/rdapify)
- 💰 [Open Collective](https://opencollective.com/rdapify)

### 🤝 المساهمة

نحب المساهمات! راجع [دليل المساهمة](https://github.com/rdapify/RDAPify/blob/main/CONTRIBUTING.md) للبدء.

## 📄 الترخيص

RDAPify مرخص بـ [MIT](https://github.com/rdapify/RDAPify/blob/main/LICENSE).

---

<div align="center">

**بُني بـ ❤️ من قبل مجتمع RDAPify**

[الموقع](https://rdapify.com) • [GitHub](https://github.com/rdapify) • [npm](https://www.npmjs.com/package/rdapify) • [Twitter](https://twitter.com/rdapify)

</div>

</div>
