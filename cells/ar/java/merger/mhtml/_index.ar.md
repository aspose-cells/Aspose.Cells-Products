---
title:  دمج MHTML ملفات via Java
weight: 4420
description: نموذج التعليمات البرمجية Java لدمج MHTML مستندًا في Java بيئة التشغيل لتطبيقات JSP/JSF وتطبيقات سطح المكتب.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="دمج MHTML التنسيقات في Java" h2="دمج المستندات MHTML الأصلي باستخدام واجهات برمجة التطبيقات Java من جانب الخادم." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="كيفية دمج الملفات MHTML باستخدام Java" %}}

 من أجل دمج الملف MHTML، سنستخدم[Aspose.Cells for Java](https://products.aspose.com/cells/java) API وهي منصة دمج غنية بالميزات وقوية وسهلة الاستخدام API for Java. يمكنك تنزيل أحدث إصدار مباشرة من[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) وقم بتثبيته ضمن مشروعك المستند إلى Maven عن طريق إضافة التكوينات التالية إلى ملف pom.xml.

{{% blocks/products/pf/agp/code-block title="مخزن" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
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

{{% blocks/products/pf/agp/feature-section-col title="خطوات دمج ملفات MHTML في Java" %}}

{{% blocks/products/pf/agp/text %}}

 وثيقة أساسية دمج وتسلسل مع[Aspose.Cells for Java](https://products.aspose.com/cells/java) يمكن إنشاء واجهات برمجة التطبيقات باستخدام بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

+ قم بتحميل الملف MHTML الأول بمثيل لفئة Workbook.
+ قم بتحميل مستند MHTML الثاني بمثيل لفئة Workbook.
+ دمج الملفات باستخدام طريقة الجمع ().
+ احفظ الملف المدمج MHTML في المسار المحدد

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java يدعم جميع المنصات وأنظمة التشغيل الرئيسية. يرجى التأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيقات JSP/JSF وتطبيقات سطح المكتب.
-  احصل على أحدث إصدار من Aspose.Cells for Java مباشرة من
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="دمج MHTML ملفات - Java" offSpacer="" %}}

```cs
// Open the first MHTML file.
Workbook mhtmlFile1 = new Workbook("chartsFileWithPath.mhtml");

// Define the second source book.
// Open the second MHTML file.
Workbook mhtmlFile2 = new Workbook("pictureFileWithPath.mhtml");

// Combining the two workbooks
mhtmlFile1.combine(mhtmlFile2);

// Save the target book file.
mhtmlFile1.save("combinedFileWithPath.mhtml");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< blocks/products/pf/agp/demobox sectionTitle="عبر الإنترنت MHTML الاندماج العروض الحية" sectionDescription=" قم بدمج مستندات MHTML الآن من خلال زيارة موقعنا[موقع العروض الحية](https://products.aspose.app/cells/merger). يتمتع العرض التجريبي المباشر بالمزايا التالية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا داعي للتحميل Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي رمز." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="فقط قم بتحميل ملفات MHTML الخاصة بك." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" سيتم دمجها وتسلسلها على الفور." >}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Cells for Java API" %}}

 Aspose.Cells API يمكن استخدامه لإنشاء وتحرير وتحويل وتقديم Microsoft تنسيقات Excel إلى تنسيقات مختلفة. علاوة على ذلك، يمكن استخدامه للرسوم البيانية الشاملة وإعداد التقارير القابلة للتطوير والحسابات الموثوقة داخل تطبيقات البرامج. Aspose.Cells هو API مستقل ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}


        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}
تمثل الملفات ذات الامتداد MHTML تنسيق أرشيف صفحة الويب الذي يمكن إنشاؤه بواسطة عدد من التطبيقات المختلفة. يُعرف التنسيق باسم تنسيق الأرشيف لأنه يحفظ كود الويب HTML والموارد المرتبطة به في ملف واحد. تتضمن هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور والتطبيقات الصغيرة والرسوم المتحركة والملفات الصوتية وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. Microsoft Windows يستخدم تنسيق الملف MHTML لتسجيل سيناريوهات المشاكل التي تمت ملاحظتها أثناء استخدام أي تطبيق على Windows والتي تثير المشكلات. يقوم تنسيق الملف MHTML بتشفير محتويات الصفحة المشابهة للمواصفات المحددة في الرسالة/rfc822 وهي مواصفات متعلقة بالبريد الإلكتروني بالنص العادي. المواصفات الفعلية للتنسيق كما هو مفصل في RFC 2557.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات الدمج المدعومة الأخرى" subTitle="باستخدام Java، يمكن للمرء أيضًا دمج العديد من تنسيقات الملفات الأخرى بما في ذلك.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="قيم مفصولة بفواصل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="قيم مفصولة بعلامات جدولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="وثيقة نصية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="تنسيق ثنائي إكسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="ملف مصنف Excel الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="ملف جدول البيانات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="ملف اكسيل OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft قالب إكسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="قالب Excel مزود بماكرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltx/" name="XLTX" description="قالب Excel لمكتب OpenXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
