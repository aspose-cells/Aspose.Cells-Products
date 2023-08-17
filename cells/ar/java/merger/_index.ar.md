---
title: دمج ملفات Excel المختلفة في ملف واحد في Java
description: دمج ملفات Excel باستخدام Java في أوراق متعددة أو ورقة واحدة. دمج أو دمج أو ربط مستندات Excel إلى PDF والصور و HTML أيضًا.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> دمج ملف Excel via Java" h2="ادمج ملفين أو أكثر من ملفات Excel في جدول بيانات واحد باستخدام كود Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java مكتبة Excel](/cells/ar/java/) يوفر طرقًا متعددة لدمج المصنفات مع أنواع مختلفة من المحتوى مثل الصيغ والصور والبيانات والمخططات وما إلى ذلك في مستند جدول بيانات واحد. تتضمن تنسيقات الملفات المدعومة XLS و XLSX و XLSB و XLT و XLTX و XLTM و ODS و CSV و TSV والمزيد.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="ادمج ملفات Excel مع الصور والرسوم البيانية" %}}
 إن أبسط طريقة لدمج ملفي Excel بهما صور ومخططات هي عن طريق استدعاء ملف[Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) طريقة. يسمح بدمج ملفات Excel من النوع المماثل في جدول بيانات واحد.
{{% blocks/products/pf/feature-page-code h3="Java كود لدمج ملفات Excel" %}}

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
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles)تدعم الطريقة دمج البيانات والنمط والصيغ الخاصة بملف Excel في جدول بيانات جديد من نفس التنسيق. إنها طريقة فعالة لدمج عدة ملفات أثناء استخدام التخزين المؤقت.
{{% blocks/products/pf/feature-page-code h3="Java كود لدمج عدة ملفات Excel" %}}

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
[ورقة عمل](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) لنسخ البيانات والتنسيق من ورقة عمل مصدر إلى ورقة عمل أخرى داخل المصنفات أو بينها. تأخذ الطريقة كائن ورقة العمل المصدر كمعلمة.
{{% blocks/products/pf/feature-page-code h3="Java كود لنسخ أوراق العمل بين مصنفات العمل" %}}

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

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات الدمج المدعومة الأخرى" subTitle="باستخدام Java ، يمكن أيضًا دمج العديد من تنسيقات الملفات الأخرى بما في ذلك .." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="قيم مفصولة بفواصل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="لغة ترميز النصوص التشعبية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="تنسيق أرشيف صفحة الويب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="ملف جدول بيانات OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="قيم مفصولة بعلامات جدولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="مستند نصي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="تنسيق Excel الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="ملف مصنف Excel ثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="ملف جدول البيانات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="ملف OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft قالب Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="قالب Excel ممكّن بماكرو" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
