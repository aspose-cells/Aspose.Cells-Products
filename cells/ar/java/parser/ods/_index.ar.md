---
title: استخراج نص وصور من مستند ODS عبر Java 
weight: 4740
url: /ar/java/parser/ods/ 
description: Java نموذج لرمز لاستخراج النصوص والصور من ملف ODS في Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تحليل تنسيقات ODS في Java" h2="تحليل مستندات ODS الأصلي وعالي الأداء باستخدام واجهات برمجة تطبيقات Aspose.Cells for Java من جانب الخادم ، بدون استخدام أي برنامج مثل Microsoft أو Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحليل ملف ODS باستخدام Java" %}}

 من أجل تحليل ملف ODS ، سنستخدم
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API نظام أساسي للتحليل غني بالميزات وقوي وسهل الاستخدام API for Java. يمكنك تنزيل أحدث إصدار مباشرة من
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

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحليل ملفات ODS في Java" %}}

{{% blocks/products/pf/agp/text %}}

 تحليل مستند أساسي باستخدام
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 يمكن عمل واجهات برمجة التطبيقات ببضعة سطور من التعليمات البرمجية. تحليل النصوص والصور من ملفات Microsoft Excel XLS و XLSX و XLSM و XLSB و OpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

+ تحميل مستند ODS باستخدام فئة المصنف.
+ حدد الورقة المطلوبة باستخدام getWorksheets (). get method.
+ احصل على جميع خلايا الورقة المحددة باستخدام getCells ().
+ كرر على كل خلية ، احصل على نصها.
+ اطبع قيمة كل خلية أو استخدم طريقة StringBuilder append () لعرضها ككل

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 يدعم Aspose.Cells for Java جميع الأنظمة الأساسية وأنظمة التشغيل الرئيسية. يرجى التأكد من توفر المتطلبات التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.- احصل على أحدث إصدار من Aspose.Cells for Java مباشرة من [مخضرم](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="تحليل ملفات ODS - Java" offSpacer="" %}}

```cs
StringBuilder stringBuilder = new StringBuilder();
Workbook book = new Workbook(dir + "book1.ods");
Worksheet sheet = book.getWorksheets().get(0);
Cells cells = sheet.getCells();
Iterator iterator = cells.iterator();
while(iterator.hasNext())
{
Cell cell = (Cell)iterator.next();
stringBuilder.append(cell.getStringValue());
stringBuilder.append(" ");
}
System.out.println(stringBuilder.toString());  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="حول Aspose.Cells for Java API" %}}

 يمكن استخدام Aspose.Cells API لإنشاء تنسيقات Microsoft Excel وتحريرها وتحويلها وعرضها بتنسيقات مختلفة. علاوة على ذلك ، يمكن استخدامه لرسم بياني شامل ، وإعداد تقارير قابلة للتطوير وحسابات موثوقة داخل تطبيقات البرامج. Aspose.Cells هو برنامج مستقل API ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="عروض توضيحية مباشرة لمحلل ODS عبر الإنترنت" sectionDescription="استخرج النصوص والصور من مستندات ODS الآن من خلال زيارة [موقع تجريبي مباشر](https://products.aspose.app/cells/parser). يحتوي العرض التوضيحي المباشر على الفوائد التالية" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي كود." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" فقط قم بتحميل ملفات ODS الخاصة بك." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" سيتم تحليله على الفور." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
الملفات ذات ملحق ODS هي تنسيق OpenDocument Spreadsheet Document الذي يمكن للمستخدم تحريره. يتم تخزين البيانات داخل ملف ODF في صفوف وأعمدة. إنه تنسيق مستند إلى XML وهو أحد الأنواع الفرعية العديدة في عائلة تنسيقات المستندات المفتوحة (ODF). تم تحديد التنسيق كجزء من مواصفات ODF 1.2 التي تنشرها وتحتفظ بها OASIS. يمكن لعدد من التطبيقات على Windows بالإضافة إلى أنظمة التشغيل الأخرى فتح ملفات ODS للتحرير والمعالجة بما في ذلك Microsoft Excel و NeoOffice و LibreOffice. يمكن أيضًا تحويل ملفات ODS إلى تنسيقات جداول بيانات أخرى مثل XLS و XLSX وغيرها بواسطة تطبيقات مختلفة. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="مستندات التحليل المعتمدة الأخرى" subTitle="باستخدام Java ، يمكن للمرء بسهولة تحليل التنسيقات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xls/" name="XLS" description="تنسيق Excel الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xlsb/" name="XLSB" description="ملف مصنف Excel ثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xlsm/" name="XLSM" description="ملف Spreasheet" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}