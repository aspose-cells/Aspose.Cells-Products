---
title: تحويل XLS إلى SVG عبر Java 
weight: 9510
url: /ar/java/conversion/xls-to-svg/ 
description: نموذج Java كود التحويل لتنسيق XLS إلى ملف SVG. يمكن للمبرمجين استخدام رمز المثال هذا لتصدير جداول بيانات Excel و OpenOffice إلى SVG داخل أي تطبيق يستند إلى الويب أو سطح المكتب Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل XLS إلى SVG عبر Java" h2="XLS إلى SVG Java لتحويل صفحات مفردة أو صفحات متعددة إلى SVG باستخدام مكتبة محلية Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل XLS إلى SVG باستخدام Java" %}}

 من أجل تقديم XLS إلى SVG ، سنستخدم
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API نظام أساسي للتحويل غني بالميزات وقوي وسهل الاستخدام API for Java. يمكنك تنزيل أحدث إصدار مباشرة من
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

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل XLS إلى SVG عبر Java" %}}

{{% blocks/products/pf/agp/text %}}

 يمكن لمطوري Java بسهولة تحويل ملف XLS إلى SVG في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1. قم بتحميل ملف XLS بمثيل مصنف1. حدد الافتراضي أو أي ورقة عمل من المجموعة1. إنشاء وتعيين كائن ImageOrPrintOptions1. قم بإنشاء SheetRender باستخدام كائنات ورقة العمل و ImageOrPrintOptions1. طريقة Call SheetRender.toImage لحفظ النتيجة بتنسيق SVG
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 قبل تشغيل شفرة مصدر التحويل Java ، تأكد من توفر المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.- احصل على أحدث إصدار من Aspose.Cells for Java مباشرة من Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS إلى شفرة مصدر تحويل SVG Java" offSpacer="" %}}

```cs
// تحميل ملف XLS ليتم تقديمه
Workbook workbook = new Workbook("sourceFile.xls");
// الوصول إلى ورقة العمل الافتراضية من المجموعة
Worksheet worksheet = workbook.getWorksheets().get(0);
// تحديد المعلمات للصورة الناتجة
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.SVG);
// تحويل ورقة العمل إلى صورة بتنسيق SVG
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.svg");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLS إلى عروض تحويل SVG الحية" sectionDescription="[تحويل XLS إلى SVG](https://products.aspose.app/cells/conversion/xls-to-svg) الآن من خلال زيارة موقع Live Demos الخاص بنا ، حيث يتمتع العرض التوضيحي المباشر بالمزايا التالية" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي كود." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف XLS الخاص بك ، وسيتم تحويله على الفور إلى SVG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" سوف تحصل على رابط التحميل." >}}

    {{% blocks/products/pf/agp/content h2="Java مكتبة معالجة جداول البيانات" %}}

 يمكن استخدام Excel API لإنشاء تنسيقات Microsoft Excel وتحريرها وتحويلها وعرضها بتنسيقات مختلفة. علاوة على ذلك ، يمكن استخدامه لرسم بياني شامل ، وإعداد تقارير قابلة للتطوير وحسابات موثوقة داخل تطبيقات البرامج. Aspose.Cells هو برنامج مستقل API ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

تمثل الملفات ذات الامتداد XLS تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel بالإضافة إلى برامج جداول البيانات المماثلة الأخرى مثل OpenOffice Calc أو Apple Numbers. يُعرف الملف الذي تم حفظه بواسطة Excel باسم المصنف حيث يمكن أن يحتوي كل مصنف على ورقة عمل واحدة أو أكثر. يتم تخزين البيانات وعرضها للمستخدمين بتنسيق جدول في ورقة العمل ويمكن أن تمتد عبر القيم الرقمية والبيانات النصية والصيغ واتصالات البيانات الخارجية والصور والمخططات. تتيح لك تطبيقات مثل Microsoft Excel تصدير بيانات المصنف إلى عدة تنسيقات مختلفة بما في ذلك PDF و CSV و XLSX و TXT و HTML و XPS والعديد من التنسيقات الأخرى. تم استبدال تنسيق ملف XLS بتنسيق أكثر انفتاحًا وتنظيمًا ، وهو XLSX ، مع إصدار Microsoft Excel 2007. ولا تزال أحدث الإصدارات تقدم الدعم لإنشاء ملفات XLS وقراءتها ، على الرغم من أن XLSX هو الخيار الأول للاستخدام الآن.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/page-description-language/svg/" >}}

ملفات SVG هي ملفات رسومات متجهة قابلة للتطوير تستخدم تنسيقًا نصيًا يستند إلى XML لوصف مظهر الصورة. تشير كلمة Scalable إلى حقيقة أنه يمكن تحجيم SVG إلى أحجام مختلفة دون فقدان أي جودة. الوصف المستند إلى النص لمثل هذه الملفات يجعلها مستقلة عن الدقة. إنه أحد التنسيقات الأكثر استخدامًا لبناء مواقع الويب والرسومات المطبوعة من أجل تحقيق قابلية التوسع. لا يمكن استخدام التنسيق إلا للرسومات ثنائية الأبعاد. يمكن عرض / فتح ملفات SVG في جميع المتصفحات الحديثة تقريبًا بما في ذلك Chrome و Internet Explorer و Firefox و Safari.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="يمكنك أيضًا تحويل XLS إلى العديد من تنسيقات الملفات الأخرى بما في ذلك بعض التنسيقات المدرجة أدناه." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-bmp/" name="XLS إلى BMP" description="سيب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-csv/" name="XLS إلى CSV" description="قيم مفصولة بفواصل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-dif/" name="XLS إلى DIF" description="تنسيق تبادل البيانات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-emf/" name="XLS إلى EMF" description="تنسيق ملف التعريف المحسن" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-gif/" name="من XLS إلى GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-html/" name="XLS إلى HTML" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-jpeg/" name="XLS إلى JPEG" description="صورة JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-mhtml/" name="XLS إلى MHTML" description="تنسيق أرشيف صفحة الويب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-ods/" name="XLS إلى ODS" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-pdf/" name="XLS إلى PDF" description="نموذج المستندات المحمولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-png/" name="XLS إلى PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-tiff/" name="XLS إلى TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-tsv/" name="XLS إلى TSV" description="قيم مفصولة بعلامات جدولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-txt/" name="XLS إلى TXT" description="مستند نصي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsb/" name="XLS إلى XLSB" description="ملف مصنف Excel ثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsm/" name="XLS إلى XLSM" description="ملف Spreasheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsx/" name="من XLS إلى XLSX" description="ملف OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlt/" name="XLS إلى XLT" description="قالب Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xltm/" name="XLS إلى XLTM" description="قالب Excel ممكّن بماكرو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xltx/" name="XLS إلى XLTX" description="قالب Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xps/" name="XLS إلى XPS" description="مواصفات ورق XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-json/" name="XLS إلى JSON" description="جافا سكريبت تدوين كائن" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}