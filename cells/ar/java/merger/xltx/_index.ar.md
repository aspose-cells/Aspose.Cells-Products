---
title: دمج ملفات XLTX عبر Java 
weight: 680
url: /ar/java/merger/xltx/ 
description: Java نموذج كود لدمج مستندات XLTX في Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="دمج تنسيقات XLTX في Java" h2="دمج مستند XLTX الأصلي باستخدام واجهات برمجة تطبيقات Java من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="كيفية دمج ملفات XLTX باستخدام Java" %}}

 لدمج ملف XLTX ، سنستخدم
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API نظام أساسي للدمج غني بالميزات وقوي وسهل الاستخدام API for Java. يمكنك تنزيل أحدث إصدار مباشرة من
 [مخضرم](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 وقم بتثبيته ضمن مشروعك المستند إلى Maven عن طريق إضافة التكوينات التالية إلى ملف pom.xml.

{{% blocks/products/pf/agp/code-block title="مخزن" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="الاعتماد" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="خطوات دمج ملفات XLTX في Java" %}}

{{% blocks/products/pf/agp/text %}}

 مستند أساسي يتم دمجه والتسلسل معه
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 يمكن عمل واجهات برمجة التطبيقات ببضعة سطور من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

+ قم بتحميل أول ملف XLTX بنسخة من فئة المصنف.
+ قم بتحميل مستند XLTX الثاني بنسخة من فئة المصنف.
+ دمج الملفات باستخدام طريقة ().
+ احفظ ملف XLTX المدمج في المسار المحدد

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 يدعم Aspose.Cells for Java جميع الأنظمة الأساسية وأنظمة التشغيل الرئيسية. يرجى التأكد من توفر المتطلبات التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.- احصل على أحدث إصدار من Aspose.Cells for Java مباشرة من [مخضرم](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="دمج ملفات XLTX - Java" offSpacer="" %}}

```cs
// افتح أول ملف XLTX.
Workbook xltxFile1 = new Workbook("chartsFileWithPath.xltx");

// تحديد المصدر الثاني للكتاب.
// افتح ملف XLTX الثاني.
Workbook xltxFile2 = new Workbook("pictureFileWithPath.xltx");

// الجمع بين المصنفين
xltxFile1.combine(xltxFile2);

// احفظ ملف الكتاب الهدف.
xltxFile1.save("combinedFileWithPath.xltx");  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Cells for Java API" %}}

 يمكن استخدام Aspose.Cells API لإنشاء تنسيقات Microsoft Excel وتحريرها وتحويلها وعرضها بتنسيقات مختلفة. علاوة على ذلك ، يمكن استخدامه لرسم بياني شامل ، وإعداد تقارير قابلة للتطوير وحسابات موثوقة داخل تطبيقات البرامج. Aspose.Cells هو برنامج مستقل API ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="عروض توضيحية مباشرة لدمج XLTX عبر الإنترنت" sectionDescription="ادمج مستندات XLTX الآن من خلال زيارة موقعنا [موقع تجريبي مباشر](https://products.aspose.app/cells/merger). يحتوي العرض التوضيحي المباشر على الفوائد التالية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي كود." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="فقط قم بتحميل ملفات XLTX الخاصة بك." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" سيتم دمجها وتسلسلها على الفور." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTX" readMoreLink="https://docs.fileformat.com/spreadsheet/xltx/" >}}
تمثل الملفات ذات الملحق XLTX ملفات قالب Microsoft Excel التي تستند إلى مواصفات تنسيق ملف Office OpenXML. يتم استخدامه لإنشاء ملف قالب قياسي يمكن استخدامه لإنشاء ملفات XLSX التي تعرض نفس الإعدادات المحددة في ملف XLTX. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات الدمج المدعومة الأخرى" subTitle="باستخدام Java ، يمكن أيضًا دمج العديد من تنسيقات الملفات الأخرى بما في ذلك .." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="قيم مفصولة بفواصل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="لغة البرمجة" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="تنسيق أرشيف صفحة الويب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="المواد المستنفدة للأوزون" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="ملف TSV" description="قيم مفصولة بعلامات جدولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="رسالة قصيرة" description="مستند نصي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="تنسيق Excel الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="ملف مصنف Excel ثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="ملف Spreasheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="ملف OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="قالب Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="قالب Excel ممكّن بماكرو" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}