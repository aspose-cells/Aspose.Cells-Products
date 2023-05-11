---
title:  Microsoft Konwersja plików programu Excel za pośrednictwem C#
description: Konwertuj Excel XLS, XLSX, ODS, CSV na PDF, XPS, HTML, JPEG, HTML i wiele innych popularnych formatów za pomocą zaledwie kilku linii kodu C# .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konwersja formatu programu Excel via .NET" h2="Importuj i eksportuj pliki Excel jako formaty arkuszy kalkulacyjnych, stron internetowych, obrazów i o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel Library przyspiesza procesy programowania i konwersji arkuszy kalkulacyjnych, jednocześnie obsługując popularne formaty, w tym XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 0761934 81. Umożliwia także eksport plików Excel na numery PDF, XPS, HTML, MHTML, zwykły Tekst i popularne formaty graficzne, takie jak TIFF, JPG, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na XLSX, ODS, SXC i FODS" %}}
 Wzajemna konwersja formatu arkusza kalkulacyjnego wymaga jedynie załadowania arkusza kalkulacyjnego z instancją[zeszyt ćwiczeń](https://reference.aspose.com/cells/net/aspose.cells/workbook) i zapisywanie z powrotem w żądanym formacie, wybierając odpowiednią wartość z[ZapiszFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) wyliczenie.
{{% blocks/products/pf/feature-page-code h3="C# Kod do konwersji formatu pliku programu Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na PDF, XPS, HTML & MD" %}}
 Dostępne są wyspecjalizowane klasy do sterowania procesem konwersji dla określonych formatów wyjściowych, takich jak[PdfZapiszOpcje](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) eksportować pliki Excel jako PDF,[XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) do konwersji Excela na XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) renderować program Excel jako HTML i[Opcje zapisu Markdown](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) do konwersji Excela na Markdown.
{{% blocks/products/pf/feature-page-code h3="C# Kod programu Excel na numer PDF i formaty internetowe" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konwertuj JSON na Excel i Excel na JSON" %}}
 JSON dane mogą być importowane do instancji[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) klasa z pomocą[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) do dalszego przetwarzania lub prostej konwersji do dowolnego obsługiwanego formatu. Podobnie,[Karta pracy](https://reference.aspose.com/cells/net/aspose.cells/worksheet) dane można wyeksportować jako JSON, tworząc plik[Zakres](https://reference.aspose.com/cells/net/aspose.cells/range) lub komórki i dzwoniąc pod numer[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) metoda.
{{% blocks/products/pf/feature-page-code h3="C# Kod do konwersji JSON do programu Excel" %}}
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

{{% blocks/products/pf/feature-page-code h3="C# Kod programu Excel do konwersji JSON" %}}
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

{{% blocks/products/pf/feature-page-section h2="Konwertuj arkusze programu Excel na JPG, BMP, PNG i GIF" %}}
 Każdy arkusz kalkulacyjny pliku programu Excel można przekonwertować na różne formaty obrazu ustawione przez program[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) nieruchomość. Wartość domyślna to `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Kod do konwersji programu Excel na obraz" %}}
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

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na Word i PowerPoint" %}}
 Możliwe jest załadowanie dowolnego arkusza kalkulacyjnego i przekonwertowanie go na pliki Word DOCX & PowerPoint PPTX podczas używania[Opcje DocxSave](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [Opcje PptxSave](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) klasy, jak pokazano poniżej.
{{% blocks/products/pf/feature-page-code h3="C# kod do konwersji programu Excel na Word i PowerPoint" %}}
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
