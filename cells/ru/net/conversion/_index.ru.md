---
title:  Microsoft Преобразование файлов Excel через C#
description: Aspose.Cells for .NET библиотека. Конвертируйте EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG и другие форматы с помощью всего лишь нескольких строк кода C#.
keywords: [C# Aspose.Cells., excel to pdf., excel to json., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Преобразование формата Excel via .NET" h2="Импортируйте и экспортируйте файлы Excel в форматах электронных таблиц, веб-страниц, изображений и с фиксированным макетом." >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Библиотека Excel ускоряет процессы программирования и преобразования электронных таблиц, поддерживая популярные форматы, включая XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07619348 1. Он также позволяет экспортировать файлы Excel в PDF, XPS, HTML, MHTML, Plain. Текстовые и популярные форматы изображений, такие как TIFF, JPG, PNG, BMP и SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Преобразуйте Excel в XLSX, ODS, SXC и FODS." %}}
 Для взаимного преобразования формата электронной таблицы требуется только загрузка электронной таблицы с экземпляром[Рабочая тетрадь](https://reference.aspose.com/cells/net/aspose.cells/workbook) и сохранить обратно в желаемом формате, выбрав подходящее значение из[СохранитьФормат](https://reference.aspose.com/cells/net/aspose.cells/saveformat) перечисление.
{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования формата файла Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в PDF, XPS, HTML и MD" %}}
 Доступны специализированные классы для управления процессом преобразования для определенных выходных форматов, таких как[PDFSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) для экспорта файлов Excel как PDF,[XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) для преобразования Excel в XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) для отображения Excel как HTML и[МаркдаунСохранитьПараметры](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) для преобразования Excel в Markdown.
{{% blocks/products/pf/feature-page-code h3="C# Код для Excel для PDF и веб-форматов" %}}

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

{{% blocks/products/pf/feature-page-section h2="Преобразовать JSON в Excel и Excel в JSON" %}}
 JSON данные можно импортировать в экземпляр[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) урок с помощью[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) для дальнейшей обработки или простого конвертирования в любой из поддерживаемых форматов. Сходным образом,[Рабочий лист](https://reference.aspose.com/cells/net/aspose.cells/worksheet) данные можно экспортировать как JSON, создав[Диапазон](https://reference.aspose.com/cells/net/aspose.cells/range) или ячейки и вызывая[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) метод.
{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования JSON в Excel" %}}
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

{{% blocks/products/pf/feature-page-code h3="Код C# для преобразования Excel в JSON" %}}
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

{{% blocks/products/pf/feature-page-section h2="Преобразование листов Excel в JPG, BMP, PNG и GIF" %}}
 Каждый лист файла Excel можно преобразовать в различные форматы изображений, установленные[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) свойство. Значение по умолчанию — `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования Excel в изображения" %}}
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

{{% blocks/products/pf/feature-page-section h2="Конвертировать Excel в Word и PowerPoint" %}}
Можно загрузить любую электронную таблицу и преобразовать ее в файлы Word DOCX и PowerPoint PPTX при использовании[Параметры сохранения документа](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) классы, как показано ниже.
{{% blocks/products/pf/feature-page-code h3="Код C# для преобразования Excel в Word и PowerPoint" %}}
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
