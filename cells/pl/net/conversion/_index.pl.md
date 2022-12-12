---
title: Konwersja plików Microsoft Excel przez C# 

description: Konwertuj Excel XLS, XLSX, ODS, CSV do PDF, XPS, HTML, JPEG, HTML i wielu innych popularnych formatów za pomocą zaledwie kilku linijek kodu C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwersja formatu Microsoft<sup>&reg;</sup> Excel przez .NET" h2="Importuj i eksportuj pliki Excel jako arkusze kalkulacyjne, strony internetowe, obrazy i formaty o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Biblioteka Excela przyspiesza proces programowania i konwersji arkuszy kalkulacyjnych, jednocześnie obsługując popularne formaty, w tym XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Pozwala także eksportować pliki Excel do PDF, XPS, HTML, MHTML, Plain Text i popularnych formatów graficznych, takich jak TIFF, JPG, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na XLSX, ODS, SXC i FODS" %}}
Konwersja między formatami arkusza kalkulacyjnego wymaga tylko załadowania arkusza kalkulacyjnego z wystąpieniem [zeszyt ćwiczeń](https://reference.aspose.com/cells/net/aspose.cells/workbook) i zapisywanie z powrotem w żądanym formacie przy wyborze odpowiedniej wartości z [Zapisz format](https://reference.aspose.com/cells/net/aspose.cells/saveformat) wyliczenie.
{{% blocks/products/pf/feature-page-code h3="C# Kod konwersji formatu pliku Excel" %}}

```cs
// załaduj plik szablonu
var workbook = new Aspose.Cells.Workbook("template.xls");
// zapisz jako formaty XLSX, ODS, SXC i FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na PDF, XPS, HTML i MD" %}}
Dostępne są specjalistyczne klasy do kontrolowania procesu konwersji dla określonych formatów wyjściowych, takich jak [PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) eksportować pliki Excel jako PDF, [XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) do konwersji programu Excel do XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) renderować Excel jako HTML i [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) do konwersji programu Excel do Markdown. 
{{% blocks/products/pf/feature-page-code h3="C# Kod programu Excel do formatu PDF i internetowego" %}}

```cs
// wczytaj szablon pliku Excel z dysku
var book = new Aspose.Cells.Workbook("template.xlsx");
// zapisz Excel w formacie PDF/A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// zapisz Excel w XPS z 1 stroną na arkusz
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// zapisz Excel w HTML z obrazami jako Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// zapisz Excel w Markdown (MD), zachowując formatowanie komórek
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj JSON na Excel i Excel na JSON" %}}
Dane JSON można importować do instancji [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) zajęcia z pomocą [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) do dalszego przetwarzania lub prostej konwersji na dowolny z obsługiwanych formatów. Podobnie, [Arkusz roboczy](https://reference.aspose.com/cells/net/aspose.cells/worksheet) dane można wyeksportować w formacie JSON, tworząc plik [Zakres](https://reference.aspose.com/cells/net/aspose.cells/range) lub komórki i nazywając [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) metoda.
{{% blocks/products/pf/feature-page-code h3="C# Kod konwersji JSON na Excel" %}}
```cs
// utworzyć obiekt Workbook
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// odczytaj dane JSON z pliku
string jsonInput = File.ReadAllText("Data.json");
// ustaw JsonLayoutOptions, aby traktować tablice jako tabelę
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// importuj dane JSON do arkusza, zaczynając od komórki A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// zapisz wynikowy plik w formacie XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kod konwersji programu Excel do formatu JSON" %}}
```cs
// załaduj plik XLSX z instancją Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// dostęp do CellsCollection arkusza roboczego zawierającego dane do przekonwertowania
var cells = workbook.Worksheets[0].Cells;
// utwórz i ustaw ExportRangeToJsonOptions dla zaawansowanych opcji
var exportOptions = new Utility.ExportRangeToJsonOptions();
// utwórz zakres komórek zawierających dane do wyeksportowania
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// eksportuj zakres jako dane JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// zapisz plik danych na dysk w formacie JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj arkusze Excela na JPG, BMP, PNG i GIF" %}}
Każdy arkusz roboczy pliku Excel można przekonwertować na różne formaty obrazu ustawione przez [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) własność. Wartość domyślna to `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Kod programu Excel do konwersji obrazu" %}}
```cs
// załaduj arkusz kalkulacyjny szablonu
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// utwórz i ustaw instancję ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// ustaw format obrazu wyjściowego
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// utwórz SheetRender dla pierwszego arkusza w kolekcji
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// wyrenderuj arkusz do obrazu
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na Word i PowerPoint" %}}
Podczas używania można załadować dowolny arkusz kalkulacyjny i przekonwertować go na pliki Word DOCX i PowerPoint PPTX [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [Opcje zapisu Pptx](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) klasy, jak pokazano poniżej.
{{% blocks/products/pf/feature-page-code h3="C# kod konwersji z programu Excel do programu Word i PowerPoint" %}}
```cs
// załaduj plik szablonu
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// zapisz arkusz kalkulacyjny jako DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// zapisz arkusz kalkulacyjny jako PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
