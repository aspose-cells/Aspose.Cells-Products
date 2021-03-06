---
title: البحث عن نص واستبداله في مستند XLS عبر Java 
weight: 7900
url: /ar/java/redaction/xls/ 
description: Java نموذج رمز لتنقيح المعلومات الحساسة في ملف XLS في Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تنسيقات Redact XLS في Java" h2="معلومات تنقيح حساسة لمستند XLS أصلية وعالية الأداء باستخدام واجهات برمجة تطبيقات Aspose.Cells for Java من جانب الخادم ، بدون استخدام أي برنامج مثل Microsoft أو Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="كيفية تنقيح ملف XLS باستخدام Java" %}}

 من أجل تنقيح ملف XLS ، سنستخدم
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API نظام أساسي غني بالميزات وقوي وسهل الاستخدام للتنقيح API for Java. يمكنك تنزيل أحدث إصدار مباشرة من
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

{{% blocks/products/pf/agp/feature-section-col title="خطوات لتنقيح ملفات XLS في Java" %}}

{{% blocks/products/pf/agp/text %}}

 البحث الأساسي في المستند واستبدال النص في المحتويات أو التعليقات أو البيانات الوصفية بـ
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 يمكن عمل واجهات برمجة التطبيقات ببضعة سطور من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

+ تحميل ملف XLS.
+ حدد الورقة ذات الصلة.
+ تحديد وخيارات البحث عن النوع.
+ حدد النطاق الذي تريد البحث فيه
+ قم بالتكرار خلال كل خلية واستخدم getCells (). اعثر على (...).
+ استبدل القيمة.
+ احفظ المصنف.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 يدعم Aspose.Cells for Java جميع الأنظمة الأساسية وأنظمة التشغيل الرئيسية. يرجى التأكد من توفر المتطلبات التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java Runtime Environment لتطبيق JSP / JSF وتطبيقات سطح المكتب.- احصل على أحدث إصدار من Aspose.Cells for Java مباشرة من [مخضرم](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ملفات Redact XLS - Java" offSpacer="" %}}

```cs
Workbook workbook = new Workbook(dataDir + "sourceFile.xls");

Worksheet worksheet = workbook.getWorksheets().get(0);

// حدد النطاق الذي تريد البحث فيه
// هنا النطاق هو E3: H6
CellArea area = CellArea.createCellArea("E3", "H6");

// حدد خيارات البحث
FindOptions opts = new FindOptions();
opts.setLookInType(LookInType.VALUES);
opts.setLookAtType(LookAtType.ENTIRE_CONTENT);
opts.setRange(area);

Cell cell = null;

do {
	// ابحث في الخلية مع البحث عن القيمة داخل النطاق
	cell = worksheet.getCells().find("search", cell, opts);

	// إذا لم يتم العثور على مثل هذه الخلية ، فكسر الحلقة
	if (cell == null)
		break;

	// استبدل الخلية بقيمة استبدال
	cell.putValue("replace");

} while (true);

// احفظ المصنف
workbook.save(dataDir + "output.xls");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="حول Aspose.Cells for Java API" %}}

 يمكن استخدام Aspose.Cells API لإنشاء تنسيقات Microsoft Excel وتحريرها وتحويلها وعرضها بتنسيقات مختلفة. علاوة على ذلك ، يمكن استخدامه لرسم بياني شامل ، وإعداد تقارير قابلة للتطوير وحسابات موثوقة داخل تطبيقات البرامج. Aspose.Cells هو برنامج مستقل API ولا يتطلب أي برامج مثل Microsoft أو OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="عروض توضيحية مباشرة عبر الإنترنت لـ XLS Redaction" sectionDescription="ابحث واستبدل النص في المحتويات أو التعليقات أو البيانات الوصفية في مستندات XLS الآن من خلال زيارة موقعنا [موقع تجريبي مباشر](https://products.aspose.app/cells/redaction). يحتوي العرض التوضيحي المباشر على الفوائد التالية" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي كود." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" فقط قم بتحميل ملفات XLS الخاصة بك." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" سيتم تنقيحه على الفور." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
تمثل الملفات ذات الامتداد XLS تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel بالإضافة إلى برامج جداول البيانات المماثلة الأخرى مثل OpenOffice Calc أو Apple Numbers. يُعرف الملف الذي تم حفظه بواسطة Excel باسم المصنف حيث يمكن أن يحتوي كل مصنف على ورقة عمل واحدة أو أكثر. يتم تخزين البيانات وعرضها للمستخدمين بتنسيق جدول في ورقة العمل ويمكن أن تمتد عبر القيم الرقمية والبيانات النصية والصيغ واتصالات البيانات الخارجية والصور والمخططات. تتيح لك تطبيقات مثل Microsoft Excel تصدير بيانات المصنف إلى عدة تنسيقات مختلفة بما في ذلك PDF و CSV و XLSX و TXT و HTML و XPS والعديد من التنسيقات الأخرى. تم استبدال تنسيق ملف XLS بتنسيق أكثر انفتاحًا وتنظيمًا ، وهو XLSX ، مع إصدار Microsoft Excel 2007. ولا تزال أحدث الإصدارات تقدم الدعم لإنشاء ملفات XLS وقراءتها ، على الرغم من أن XLSX هو الخيار الأول للاستخدام الآن. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="مستندات التنقيح المدعومة الأخرى" subTitle="باستخدام Java ، يمكن بسهولة تنقيح التنسيقات المختلفة بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/ods/" name="المواد المستنفدة للأوزون" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsb/" name="XLSB" description="ملف مصنف Excel ثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsm/" name="XLSM" description="ملف Spreasheet" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}