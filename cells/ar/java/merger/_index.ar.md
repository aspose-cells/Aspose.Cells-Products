---
title: دمج ملفات Excel المختلفة في ملف واحد في Java
description: دمج ملفات Excel باستخدام Java في أوراق متعددة أو ورقة واحدة. دمج أو دمج أو تسلسل مستندات Excel إلى PDF والصور وHTML أيضًا.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> دمج ملفات اكسيل via Java" h2="قم بدمج ملفين أو أكثر من ملفات Excel في جدول بيانات واحد باستخدام الكود Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java مكتبة اكسيل](/cells/ar/java/)يوفر طرقًا متعددة لدمج المصنفات مع أنواع مختلفة من المحتوى مثل الصيغ والصور والبيانات والمخططات وما إلى ذلك في مستند جدول بيانات واحد. تتضمن تنسيقات الملفات المدعومة XLS، XLSX، XLSB، XLT، XLTX، XLTM، ODS، CSV، TSV والمزيد.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="دمج ملفات Excel مع الصور والرسوم البيانية" %}}
 إن أبسط طريقة لدمج ملفين من ملفات Excel التي تحتوي على صور ومخططات هي عن طريق الاتصال بـ[Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) طريقة. يسمح بدمج ملفات Excel من نفس النوع في جدول بيانات واحد.
{{% blocks/products/pf/feature-page-code h3="Java كود دمج ملفات الاكسل" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="دمج ملفات Excel متعددة" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) تدعم الطريقة دمج البيانات والأسلوب والصيغ الخاصة بملف Excel في جدول بيانات جديد بنفس التنسيق. إنها طريقة فعالة لدمج عدة ملفات أثناء استخدام التخزين المؤقت.
{{% blocks/products/pf/feature-page-code h3="Java كود دمج عدة ملفات اكسل" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="دمج ملفات Excel عن طريق نسخ أوراق العمل" %}}
[ورقة عمل.نسخ](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)يمكن استخدامها لنسخ البيانات والتنسيقات من ورقة عمل مصدر إلى ورقة عمل أخرى داخل المصنفات أو بينها. تأخذ الطريقة كائن ورقة العمل المصدر كمعلمة.
{{% blocks/products/pf/feature-page-code h3="Java كود نسخ أوراق العمل بين المصنفات" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات الدمج المدعومة الأخرى" subTitle="باستخدام Java، يمكن للمرء أيضًا دمج العديد من تنسيقات الملفات الأخرى بما في ذلك.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="قيم مفصولة بفواصل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="تنسيق أرشيف صفحة الويب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="قيم مفصولة بعلامات جدولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="وثيقة نصية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="تنسيق ثنائي إكسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="ملف مصنف Excel الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="ملف جدول البيانات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="ملف اكسيل OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft قالب إكسل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="قالب Excel مزود بماكرو" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
