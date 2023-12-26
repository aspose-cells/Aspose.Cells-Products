---
title:  Microsoft تحويل ملفات Excel عبر C#
description: Aspose.Cells for .NET مكتبة. تحويل EXCEL، JSON، PDF، XML، HTML، TXT، TSV، CSV، SQL، JPG، PNG والمزيد من التنسيقات مع بضعة أسطر فقط من الكود C#.
keywords: [C# Aspose.Cells., excel to pdf., excel to json., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تحويل تنسيق Excel via .NET" h2="استيراد وتصدير ملفات Excel بتنسيقات جداول البيانات والويب والصور والتخطيطات الثابتة" >}}

{{% blocks/products/pf/feature-page-summary %}}
تعمل مكتبة Excel .NET على تسريع عمليات برمجة جداول البيانات والتحويل مع دعم التنسيقات الشائعة بما في ذلك XLS، XLSX، XLSM، XLSB، XLTX، XLTM، CSV، SpreadsheetML، 07619348 1. كما يسمح بتصدير ملفات Excel إلى PDF، XPS، HTML، MHTML، عادي تنسيقات النصوص والصور الشائعة مثل TIFF وJPG وPNG وBMP وSVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى XLSX وODS وSXC وFODS" %}}
 يتطلب التحويل البيني لتنسيق جدول البيانات فقط تحميل جدول بيانات بمثيل[دفتر العمل](https://reference.aspose.com/cells/net/aspose.cells/workbook) والحفظ مرة أخرى بالتنسيق المطلوب أثناء تحديد القيمة المناسبة من[حفظ التنسيق](https://reference.aspose.com/cells/net/aspose.cells/saveformat) تعداد.
{{% blocks/products/pf/feature-page-code h3="C# كود تحويل تنسيق ملف اكسيل" %}}

```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xls");
// save as XLSX, ODS, SXC & FODS formats
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى PDF و XPS و HTML و MD" %}}
 تتوفر فئات متخصصة للتحكم في عملية التحويل لتنسيقات إخراج محددة مثل[خيارات حفظ PDF](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) لتصدير ملفات Excel كـ PDF،[خيارات XpsSave](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) لتحويل Excel إلى XPS ،[هتملسافيوبتيونس](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) لتقديم Excel كـ HTML و[خيارات تخفيض السعر](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) لتحويل Excel إلى Markdown.
{{% blocks/products/pf/feature-page-code h3="C# كود لبرنامج Excel إلى PDF وتنسيقات الويب" %}}

```cs
// load template Excel file from disc
var book = new Aspose.Cells.Workbook("template.xlsx");
// save Excel in PDF/A-1a format
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// save Excel in XPS with 1 page per worksheet
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// save Excel in HTML with images as Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// save Excel in Markdown (MD) while retaining cell formatting
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل JSON إلى Excel و Excel إلى JSON" %}}
 يمكن استيراد بيانات JSON إلى مثيل[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) الطبقة بمساعدة[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) لمزيد من المعالجة أو التحويل البسيط إلى أي من التنسيقات المدعومة. بصورة مماثلة،[ورقة عمل](https://reference.aspose.com/cells/net/aspose.cells/worksheet) يمكن تصدير البيانات كـ JSON عن طريق إنشاء ملف[يتراوح](https://reference.aspose.com/cells/net/aspose.cells/range) أو الخلايا واستدعاء[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) طريقة.
{{% blocks/products/pf/feature-page-code h3="C# كود تحويل JSON إلى إكسل" %}}
```cs
// create a Workbook object
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// read JSON data from file
string jsonInput = File.ReadAllText("Data.json");
// set JsonLayoutOptions to treat Arrays as Table
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// import JSON data to worksheet starting at cell A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// save resultant file in XLSX format
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# كود التحويل من Excel إلى JSON" %}}
```cs
// load XLSX file with an instance of Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// access CellsCollection of the worksheet containing data to be converted
var cells = workbook.Worksheets[0].Cells;
// create & set ExportRangeToJsonOptions for advanced options
var exportOptions = new Utility.ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// export range as JSON data
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// write data file to disc in JSON format
System.IO.File.WriteAllText("output.json", jsonData); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل أوراق عمل Excel إلى JPG، BMP، PNG وGIF" %}}
 يمكن تحويل كل ورقة عمل من ملف Excel إلى تنسيقات صور مختلفة يحددها ملف Excel[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) ملكية. القيمة الافتراضية هي `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# كود تحويل Excel إلى صورة" %}}
```cs
// load template spreadsheet
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// create & set an instance of ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// set output image format
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// create SheetRender for first worksheet in the collection
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// render worksheet to image
render.ToImage(0, "output.jpg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى Word & PowerPoint" %}}
من الممكن تحميل أي جدول بيانات وتحويله إلى ملفات Word DOCX & PowerPoint PPTX أثناء الاستخدام[DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [خيارات PptxSave](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) الطبقات كما هو موضح أدناه.
{{% blocks/products/pf/feature-page-code h3="كود C# للتحويل من Excel إلى Word والتحويل PowerPoint" %}}
```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// save spreadsheet as DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// save spreadsheet as PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
