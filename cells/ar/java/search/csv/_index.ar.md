---
title:  ابحث عن مستند CSV بدون فتح via Java
weight: 390
description: نموذج التعليمات البرمجية Java للبحث عن الكلمات ذات النمط في ملف CSV على Java بيئة التشغيل لتطبيقات JSP/JSF وتطبيقات سطح المكتب.
keywords: [Java Aspose.Cells., Java search words with pattern in csv file., Java find words with pattern in csv file., Java search string with pattern in csv file., Java find words with pattern in csv file., Java search words in csv file., Java find words in csv file., Java search string in csv file., Java find string in csv file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ابحث عن CSV التنسيقات في Java" h2="بحث أصلي وعالي الأداء في المستندات CSV باستخدام واجهات برمجة التطبيقات Aspose.Cells for Java من جانب الخادم، دون استخدام أي برنامج مثل Microsoft أو Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="كيفية البحث عن ملف CSV باستخدام Java" %}}

 من أجل البحث في ملف CSV، سنستخدم
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API وهي منصة غنية بالميزات وقوية وسهلة الاستخدام. ابحث عن منصة API for Java. يمكنك تنزيل أحدث إصدار مباشرة من
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 وقم بتثبيته ضمن مشروعك المستند إلى Maven عن طريق إضافة التكوينات التالية إلى ملف pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="خطوات البحث عن الملفات CSV في Java" %}}

{{% blocks/products/pf/agp/text %}}

 يمكن إجراء بحث أساسي عن المستندات باستخدام واجهات برمجة التطبيقات Aspose.Cells باستخدام بضعة أسطر فقط من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

+ تحميل ملف CSV عن طريق إنشاء كائن مصنف.
+ الوصول إلى ورقة العمل الأولى في الملف CSV.
+ ابحث عن الخلية التي تحتوي على الصيغة المحددة.
+ إنشاء مثيل FindOptions.
+ ابحث عن الخلية التي تحتوي على قيمة سلسلة
طباعة الخلايا الموجودة بعد نتيجة البحث

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java يدعم جميع المنصات وأنظمة التشغيل الرئيسية. يرجى التأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيقات JSP/JSF وتطبيقات سطح المكتب.
-  احصل على أحدث إصدار من Aspose.Cells for Java مباشرة من
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="بحث CSV ملفات - Java" offSpacer="" %}}

```cs
// Instantiating a Workbook object
Workbook workbook = new Workbook(dataDir + "book1.csv");

// Accessing the first worksheet in the CSV file
Worksheet worksheet = workbook.getWorksheets().get(0);

// Finding the cell containing the specified formula
Cells cells = worksheet.getCells();

// Instantiate FindOptions
FindOptions findOptions = new FindOptions();

// Finding the cell containing a string value that starts with Or
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// Printing the name of the cell found after searching 
System.out.println("Name of the cell containing String: " + cell.getName());  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="حول Aspose.Cells for Java API" %}}

 Aspose.Cells API يمكن استخدامه لإنشاء وتحرير وتحويل وتقديم Microsoft تنسيقات Excel إلى تنسيقات مختلفة. علاوة على ذلك، يمكن استخدامه للرسوم البيانية الشاملة وإعداد التقارير القابلة للتطوير والحسابات الموثوقة داخل تطبيقات البرامج. Aspose.Cells هو API مستقل ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="عبر الإنترنت CSV بحث العروض الحية" sectionDescription=" ابحث عن النصوص والكلمات والعبارات ضمن CSV مستندًا الآن من خلال زيارة موقعنا[موقع العروض الحية](https://products.aspose.app/cells/search). يتمتع العرض التجريبي المباشر بالمزايا التالية" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا داعي للتحميل Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي رمز." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="فقط قم بتحميل ملفات CSV الخاصة بك." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" تظهر نتيجة البحث على الفور." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV " readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}
تمثل الملفات ذات الامتداد CSV (قيم مفصولة بفواصل) ملفات نصية عادية تحتوي على سجلات بيانات ذات قيم مفصولة بفواصل. كل سطر في ملف CSV هو سجل جديد من مجموعة السجلات الموجودة في الملف. يتم إنشاء هذه الملفات عندما يكون المقصود نقل البيانات من نظام تخزين إلى آخر. وبما أن جميع التطبيقات يمكنها التعرف على السجلات المفصولة بفاصلة، فإن استيراد ملفات البيانات هذه إلى قاعدة البيانات يتم بشكل مريح للغاية. يمكن لجميع تطبيقات جداول البيانات تقريبًا مثل Microsoft Excel أو OpenOffice Calc استيراد CSV دون بذل الكثير من الجهد. يتم ترتيب البيانات المستوردة من هذه الملفات في خلايا جدول البيانات لتمثيلها للمستخدم.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="وثائق البحث المدعومة الأخرى" subTitle="باستخدام Java، يمكن للمرء أيضًا البحث عن ملفات أخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/ods/" name="ODS" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/tsv/" name="TSV" description="قيم مفصولة بعلامات جدولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/txt/" name="TXT" description="وثيقة نصية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xls/" name="XLS" description="تنسيق ثنائي إكسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsb/" name="XLSB" description="ملف مصنف Excel الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="ملف جدول البيانات" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
