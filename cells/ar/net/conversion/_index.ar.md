---
title: تحويل ملف Microsoft Excel عبر C# 
url: /ar/net/conversion/
description: قم بتحويل Excel XLS و XLSX و ODS و CSV إلى PDF و XPS و HTML و JPEG و HTML والعديد من التنسيقات الشائعة الأخرى باستخدام سطور قليلة فقط من C# التعليمات البرمجية.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> تحويل تنسيق Excel عبر .NET" h2="استيراد وتصدير ملفات Excel كجداول بيانات وويب وصورة وتنسيقات تخطيط ثابت" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET تعمل مكتبة Excel على تسريع برمجة جداول البيانات وعمليات التحويل مع دعم التنسيقات الشائعة بما في ذلك XLS و XLSX و XLSM و XLSB و XLTX و XLTM و CSV و SpreadsheetML و ODS. كما يسمح بتصدير ملفات Excel إلى PDF و XPS و HTML و MHTML و Plain Text وتنسيقات الصور الشائعة مثل TIFF و JPG و PNG و BMP و SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى XLSX و ODS و SXC و FODS" %}}
لا يتطلب التحويل البيني لتنسيق جدول البيانات سوى تحميل جدول بيانات بمثيل [دفتر العمل](https://apireference.aspose.com/cells/net/aspose.cells/workbook) وإعادة الحفظ بالتنسيق المطلوب مع تحديد القيمة المناسبة من [SaveFormat](https://apireference.aspose.com/cells/net/aspose.cells/saveformat) تعداد.
{{% blocks/products/pf/feature-page-code h3="C# رمز تحويل تنسيق ملف Excel" %}}

```cs
// تحميل ملف القالب
var workbook = new Aspose.Cells.Workbook("template.xls");
// حفظ بتنسيقات XLSX و ODS و SXC و FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="قم بتحويل Excel إلى PDF و XPS و HTML و MD" %}}
تتوفر الفصول المتخصصة للتحكم في عملية التحويل لتنسيقات الإخراج المحددة مثل [خيارات PdfSave](https://apireference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) لتصدير ملفات Excel بصيغة PDF ، [XpsSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/xpssaveoptions) لتحويل Excel إلى XPS ، [خيارات HtmlSave](https://apireference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) لتقديم Excel بتنسيق HTML و [تخفيض السعر](https://apireference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) لبرنامج Excel لتحويل Markdown. 
{{% blocks/products/pf/feature-page-code h3="C# التعليمات البرمجية لـ Excel إلى PDF وتنسيقات الويب" %}}

```cs
// تحميل ملف إكسل قالب من القرص
var book = new Aspose.Cells.Workbook("template.xlsx");
// حفظ Excel بتنسيق PDF / A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// حفظ Excel في XPS بصفحة واحدة لكل ورقة عمل
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// حفظ Excel بصيغة HTML بالصور باسم Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// حفظ Excel في Markdown (MD) مع الاحتفاظ بتنسيق الخلية
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل JSON إلى Excel و Excel إلى JSON" %}}
يمكن استيراد بيانات JSON إلى مثيل [Cells](https://apireference.aspose.com/cells/net/aspose.cells/cells) الطبقة بمساعدة [JsonUtility.ImportData](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) لمزيد من المعالجة أو التحويل البسيط إلى أي من التنسيقات المدعومة. بصورة مماثلة، [ورقة عمل](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) يمكن تصدير البيانات بتنسيق JSON عن طريق إنشاء ملف [يشتمل على](https://apireference.aspose.com/cells/net/aspose.cells/range) أو الخلايا واستدعاء [JsonUtility.ExportRangeToJson](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) طريقة.
{{% blocks/products/pf/feature-page-code h3="C# رمز تحويل JSON إلى Excel" %}}
```cs
// إنشاء كائن مصنف
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// قراءة بيانات JSON من الملف
string jsonInput = File.ReadAllText("Data.json");
// قم بتعيين JsonLayoutOptions لمعاملة المصفوفات كجدول
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// استيراد بيانات JSON إلى ورقة العمل بدءًا من الخلية A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// حفظ الملف الناتج بتنسيق XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# كود لبرنامج Excel لتحويل JSON" %}}
```cs
// تحميل ملف XLSX مع مثيل من المصنف
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// الوصول إلى مجموعة الخلايا من ورقة العمل التي تحتوي على البيانات المراد تحويلها
var cells = workbook.Worksheets[0].Cells;
// إنشاء وضبط ExportRangeToJsonOptions للخيارات المتقدمة
var exportOptions = new Utility.ExportRangeToJsonOptions();
// إنشاء نطاق من الخلايا التي تحتوي على البيانات ليتم تصديرها
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// نطاق التصدير كبيانات JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// كتابة ملف البيانات على القرص بتنسيق JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="قم بتحويل أوراق عمل Excel إلى JPG و BMP و PNG و GIF" %}}
يمكن تحويل كل ورقة عمل من ملف Excel إلى تنسيقات صور مختلفة تم تعيينها بواسطة [ImageOrPrintOptions.MageType](https://apireference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) منشأه. القيمة الافتراضية هي `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# كود لبرنامج Excel لتحويل الصورة" %}}
```cs
// تحميل قالب جدول البيانات
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// إنشاء وتعيين مثيل ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// تعيين تنسيق صورة الإخراج
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// قم بإنشاء SheetRender لأول ورقة عمل في المجموعة
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// تقديم ورقة العمل للصورة
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى Word و PowerPoint" %}}
من الممكن تحميل أي جدول بيانات وتحويله إلى ملفات Word DOCX و PowerPoint PPTX أثناء استخدام [DocxSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [خيارات PptxSaveOpt](https://apireference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) الفئات كما هو موضح أدناه.
{{% blocks/products/pf/feature-page-code h3="C# رمز Excel لتحويل Word و PowerPoint" %}}
```cs
// تحميل ملف القالب
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// احفظ جدول البيانات بتنسيق DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// احفظ جدول البيانات بتنسيق PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}