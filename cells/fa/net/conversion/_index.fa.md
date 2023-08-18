---
title:  Microsoft تبدیل فایل اکسل از طریق C#
description: اکسل XLS، XLSX، ODS، CSV را به PDF، XPS، HTML، HTML، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، PDF، PDF. کد 81
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تبدیل فرمت اکسل via .NET" h2="فایل‌های اکسل را به‌صورت صفحه‌گسترده، وب، تصویر و قالب‌بندی ثابت وارد و صادر کنید" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel Library برنامه‌نویسی و فرآیندهای تبدیل صفحه‌گسترده را با پشتیبانی از فرمت‌های محبوب از جمله XLS، XLSX، XLSM، XLSB، XLTX، XLTX، XLTX، XLS، XLS، XLTX، XLS، XLS، XLTX، XLS، 076113418 ODS. همچنین اجازه می دهد تا فایل های اکسل را به PDF، XPS، HTML، MHTML، ساده صادر کنید. متن و فرمت های تصویری محبوب مانند TIFF، JPG، PNG، BMP و SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تبدیل اکسل به XLSX، ODS، SXC و FODS" %}}
 تبدیل فرمت صفحه گسترده فقط به بارگیری یک صفحه گسترده با یک نمونه از نیاز دارد[کتاب کار](https://reference.aspose.com/cells/net/aspose.cells/workbook) و همزمان با انتخاب مقدار مناسب، در قالب مورد نظر ذخیره کنید[SaveFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) شمارش
{{% blocks/products/pf/feature-page-code h3="C# کد برای تبدیل فرمت فایل اکسل" %}}

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


{{% blocks/products/pf/feature-page-section h2="تبدیل اکسل به PDF، XPS، HTML و MD" %}}
 کلاس های تخصصی برای کنترل فرآیند تبدیل برای فرمت های خروجی خاص مانند[PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) برای صادرات فایل های اکسل به عنوان PDF،[XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) برای تبدیل اکسل به XPS،[HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) برای رندر اکسل به صورت HTML و[MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) برای تبدیل Excel به Markdown
{{% blocks/products/pf/feature-page-code h3="کد C# برای اکسل به PDF و فرمت های وب" %}}

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

{{% blocks/products/pf/feature-page-section h2="تبدیل JSON به اکسل و اکسل به JSON" %}}
 داده های JSON را می توان به نمونه ای وارد کرد[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) کلاس با کمک[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata)برای پردازش بیشتر یا تبدیل ساده به هر یک از فرمت های پشتیبانی شده. به همین ترتیب،[کاربرگ](https://reference.aspose.com/cells/net/aspose.cells/worksheet) داده ها را می توان به عنوان JSON با ایجاد یک صادر کرد[دامنه](https://reference.aspose.com/cells/net/aspose.cells/range) یا سلول ها و فراخوانی[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) روش.
{{% blocks/products/pf/feature-page-code h3="C# کد تبدیل JSON به اکسل" %}}
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

{{% blocks/products/pf/feature-page-code h3="C# کد برای تبدیل اکسل به JSON" %}}
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

{{% blocks/products/pf/feature-page-section h2="تبدیل کاربرگ های اکسل به JPG، BMP، PNG و GIF" %}}
 هر کاربرگ یک فایل اکسل را می توان به فرمت های مختلف تصویری که توسط آن تنظیم شده است تبدیل کرد[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) ویژگی. مقدار پیش فرض `ImageFormat.Bmp` است.
{{% blocks/products/pf/feature-page-code h3="C# کد برای تبدیل اکسل به تصویر" %}}
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

{{% blocks/products/pf/feature-page-section h2="اکسل را به ورد و PowerPoint تبدیل کنید" %}}
 امکان بارگذاری هر صفحه گسترده و تبدیل آن به فایل های Word DOCX و PowerPoint PPTX در حین استفاده وجود دارد.[DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions)کلاس هایی که در زیر نشان داده شده است.
{{% blocks/products/pf/feature-page-code h3="کد C# برای اکسل به ورد و تبدیل PowerPoint" %}}
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
