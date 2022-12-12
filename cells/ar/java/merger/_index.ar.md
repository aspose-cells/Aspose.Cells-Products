---
title: دمج ملفات Excel المختلفة في ملف واحد في Java

description: دمج ملفات Excel باستخدام Java في أوراق متعددة أو ورقة واحدة. قم بدمج مستندات Excel أو دمجها أو دمجها في ملفات PDF والصور و HTML أيضًا.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> دمج ملفات Excel عبر Java" h2="ادمج ملفي Excel أو أكثر في جدول بيانات واحد باستخدام Java code" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java مكتبة Excel](/cells/java/) يوفر طرقًا متعددة لدمج المصنفات مع أنواع مختلفة من المحتوى مثل الصيغ والصور والبيانات والمخططات وغيرها في مستند جدول بيانات واحد. تتضمن تنسيقات الملفات المدعومة XLS و XLSX و XLSB و XLT و XLTX و XLTM و ODS و CSV و TSV والمزيد.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="ادمج ملفات Excel مع الصور والرسوم البيانية" %}}
إن أبسط طريقة لدمج ملفي Excel بهما صور ومخططات هي عن طريق استدعاء ملف [Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) طريقة. يسمح بدمج ملفات Excel من النوع المماثل في جدول بيانات واحد.
{{% blocks/products/pf/feature-page-code h3="Java رمز لدمج ملفات Excel" %}}

```cs
// قم بتحميل أول ملف Excel
var book1 = new Workbook("with-charts.xlsx");
// تحميل ملف Excel الثاني في مثيل منفصل
var book2 = new Workbook("with-images.xlsx");

// دمج مصنفين
book1.combine(book2);
// احفظ المصنف الهدف 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="دمج ملفات Excel متعددة" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) تدعم الطريقة دمج البيانات والنمط والصيغ الخاصة بملف Excel في جدول بيانات جديد من نفس التنسيق. إنها طريقة فعالة لدمج عدة ملفات أثناء استخدام التخزين المؤقت. 
{{% blocks/products/pf/feature-page-code h3="Java رمز لدمج عدة ملفات Excel" %}}

```cs
// إنشاء مصفوفة (الطول = 2)
String[] files = new String[2];
// حدد مسارات الملفات المراد دمجها
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// دمج الملفات لحفظ النتيجة
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="دمج ملفات Excel عن طريق نسخ أوراق العمل" %}}
[ورقة عمل](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)لنسخ البيانات والتنسيق من ورقة عمل مصدر إلى ورقة عمل أخرى داخل المصنفات أو بينها. الأسلوب يأخذ كائن ورقة العمل المصدر كمعلمة.
{{% blocks/products/pf/feature-page-code h3="Java كود لنسخ أوراق العمل بين المصنفات" %}}

```cs
// قم بإنشاء مصنف.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// قم بإنشاء مصنف آخر.
Workbook excelWorkbook1 = new Workbook();

// انسخ الورقة الأولى من الكتاب الأول في الكتاب الثاني.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// حفظ الملف.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
