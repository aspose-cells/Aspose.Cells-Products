---
title:  حماية وقفل XLSM مستند via Java
weight: 9620
description: نموذج التعليمات البرمجية Java لقفل ملف XLSM باستخدام كلمة المرور في بيئة تشغيل Java لتطبيقات JSP/JSF وتطبيقات سطح المكتب.
keywords: [Java Aspose.Cells., Java Lock XLSM files., Java How to Protect and lock XLSM document., Java Protect XLSM files., Encrypt XLSM Files using Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تشفير XLSM ملفات via Java" h2="جداول بيانات Excel محمية بكلمة مرور، بما في ذلك تنسيق XLSM باستخدام مكتبة .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java/" installationsDocsLink="https://docs.aspose.com/cells/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="كيفية تأمين ملف XLSM باستخدام Java" %}}

 من أجل حماية ملف XLSM، سنستخدم
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API وهي منصة تشفير غنية بالميزات وقوية وسهلة الاستخدام API for Java. يمكنك تنزيل أحدث إصدار مباشرة من
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 وقم بتثبيته ضمن مشروعك المستند إلى Maven عن طريق إضافة التكوينات التالية إلى ملف pom.xml.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="مخزن" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات حماية XLSM ملفات via Java" %}}

{{% blocks/products/pf/agp/text %}}

 يمكن حماية المستندات باستخدام واجهات برمجة التطبيقات Aspose.Cells من خلال بضعة أسطر فقط من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1.  قم بتحميل الملف XLSM عن طريق إنشاء فئة المصنف
1.  استخدم طريقة الحماية (..) مع نوع الحماية وكلمة المرور
1.  احفظ الملف XLSM المحمي بطريقة save()

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java يدعم جميع المنصات وأنظمة التشغيل الرئيسية. يرجى التأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيقات JSP/JSF وتطبيقات سطح المكتب.
-  احصل على أحدث إصدار من Aspose.Cells for Java مباشرة من
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="الاعتماد" offSpacer="" %}}

```cs

// Open the XLSM file
Workbook wkb = new Workbook("sourceFile.xlsm");

// Protect workbook by specifying protection type
wkb.protect(ProtectionType.ALL, "12345");

// Save the XLSM file
wkb.save("lockedFile.xlsm");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="حول Aspose.Cells for Java API" %}}

 Aspose.Cells API يمكن استخدامه لإنشاء وتحرير وتحويل وتقديم Microsoft تنسيقات Excel إلى تنسيقات مختلفة. علاوة على ذلك، يمكن استخدامه للرسوم البيانية الشاملة وإعداد التقارير القابلة للتطوير والحسابات الموثوقة داخل تطبيقات البرامج. Aspose.Cells هو API مستقل ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="تطبيق مجاني للحماية XLSM" sectionDescription=" تحقق من العروض التوضيحية الحية لدينا[تشفير XLSM الملفات](https://products.aspose.app/cells/protect/xlsm) مع الفوائد التالية." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل أو إعداد أي شيء" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أو ترجمة التعليمات البرمجية" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف XLSM والضغط على زر \"فتح\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" قم بتنزيل الملف XLSM الناتج من الرابط" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
الملفات ذات الامتداد XLSM هي نوع من ملفات جداول البيانات التي تدعم وحدات الماكرو. من وجهة نظر التطبيق، الماكرو عبارة عن مجموعة من التعليمات التي يتم استخدامها لأتمتة العمليات. يتم استخدام الماكرو لتسجيل الخطوات التي يتم تنفيذها بشكل متكرر وتسهيل تنفيذ الإجراءات عن طريق تشغيل الماكرو مرة أخرى. تتم برمجة وحدات الماكرو باستخدام Visual Basic for Applications (VBA) الخاص بـ Microsoft من داخل مصنف Excel باستخدام محرر Visual Basic ويمكن تشغيلها/تصحيح الأخطاء مباشرة من هناك.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="وثائق الحماية المدعومة الأخرى" subTitle="باستخدام Java، يمكن للمرء حماية الملفات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/ods/" name="ODS" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xls/" name="XLS" description="تنسيق ثنائي إكسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsb/" name="XLSB" description="ملف مصنف Excel الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsx/" name="XLSX" description="ملف اكسيل OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
