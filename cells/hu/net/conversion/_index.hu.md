---
title: "Microsoft Excel fájlkonverzió a következőn keresztül: C# "
url: /hu/net/conversion/
description: Konvertálja az Excel XLS-t, XLSX-et, ODS-t, CSV-t PDF-, XPS-, HTML-, JPEG-, HTML- és sok más népszerű formátumba mindössze néhány soros C#-kóddal.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel formátum konvertálása a következőn keresztül: .NET" h2="Excel-fájlok importálása és exportálása táblázat-, web-, kép- és rögzített elrendezésű formátumokba" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Az Excel Library felgyorsítja a táblázatkezelő programozási és átalakítási folyamatokat, miközben támogatja az olyan népszerű formátumokat, mint az XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Lehetővé teszi Excel fájlok exportálását PDF, XPS, HTML, MHTML, egyszerű szöveg és olyan népszerű képformátumokba, mint a TIFF, JPG, PNG, BMP és SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Az Excel konvertálása XLSX, ODS, SXC és FODS formátumba" %}}
A táblázatformátumok közötti konvertáláshoz csak egy példányt tartalmazó táblázatot kell betölteni [Munkafüzet](https://apireference.aspose.com/cells/net/aspose.cells/workbook) és visszamenti a kívánt formátumba, miközben kiválasztja a megfelelő értéket [SaveFormat](https://apireference.aspose.com/cells/net/aspose.cells/saveformat) felsorolás.
{{% blocks/products/pf/feature-page-code h3="C# Kód az Excel fájlformátum konvertálásához" %}}

```cs
// töltse be a sablonfájlt
var workbook = new Aspose.Cells.Workbook("template.xls");
// mentse XLSX, ODS, SXC és FODS formátumban
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Az Excel konvertálása PDF, XPS, HTML és MD formátumba" %}}
Speciális osztályok állnak rendelkezésre az átalakítási folyamat vezérlésére meghatározott kimeneti formátumokhoz, mint pl [PdfSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) Excel fájlok PDF formátumban történő exportálásához, [XpsSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/xpssaveoptions) az Excel XPS konvertáláshoz, [HtmlSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) hogy az Excel HTML-ként jelenjen meg és [MarkdownSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) az Excelből Markdown konvertáláshoz. 
{{% blocks/products/pf/feature-page-code h3="C# Kód az Excel PDF- és webformátumokhoz" %}}

```cs
// sablon Excel fájl betöltése a lemezről
var book = new Aspose.Cells.Workbook("template.xlsx");
// mentse az Excelt PDF/A-1a formátumban
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// mentse az Excelt XPS-ben munkalaponként 1 oldallal
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// mentse az Excelt HTML-be képekkel Base64-ként
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// mentse az Excelt a Markdown (MD) programba, miközben megtartja a cellaformázást
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja a JSON-t Excel-be, az Excelt pedig JSON-ba" %}}
JSON-adatok importálhatók egy példányba [Cells](https://apireference.aspose.com/cells/net/aspose.cells/cells) osztály segítségével [JsonUtility.ImportData](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) további feldolgozáshoz vagy egyszerű konvertáláshoz a támogatott formátumok bármelyikére. Hasonlóképpen, [Munkalap](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) az adatok JSON-ként exportálhatók az a [Hatótávolság](https://apireference.aspose.com/cells/net/aspose.cells/range) vagy sejtek és hívja a [JsonUtility.ExportRangeToJson](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) módszer.
{{% blocks/products/pf/feature-page-code h3="C# Kód a JSON-ból Excel-be való konvertáláshoz" %}}
```cs
// hozzon létre egy munkafüzet objektumot
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// JSON-adatok olvasása a fájlból
string jsonInput = File.ReadAllText("Data.json");
// állítsa be a JsonLayoutOptions-t, hogy a tömböket táblázatként kezelje
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// importálja a JSON-adatokat az A1 cellával kezdődő munkalapra
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// mentse a kapott fájlt XLSX formátumban
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kód az Excel JSON-ba konvertálásához" %}}
```cs
// töltse be az XLSX fájlt a munkafüzet egy példányával
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// access CellsA konvertálandó adatokat tartalmazó munkalap gyűjteménye
var cells = workbook.Worksheets[0].Cells;
// Hozzon létre és állítson be ExportRangeToJsonOptions-t a speciális beállításokhoz
var exportOptions = new Utility.ExportRangeToJsonOptions();
// hozzon létre egy cellatartományt, amely exportálandó adatokat tartalmaz
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// tartomány exportálása JSON-adatokként
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// írjon adatfájlt a lemezre JSON formátumban
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja az Excel munkalapokat JPG, BMP, PNG és GIF formátumba" %}}
Egy Excel-fájl minden munkalapja konvertálható különböző képformátumokba, amelyeket a [ImageOrPrintOptions.ImageType](https://apireference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) ingatlan. Az alapértelmezett érték az `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Kód az Excel képpé konvertálásához" %}}
```cs
// sablon táblázat betöltése
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// hozzon létre és állítson be egy ImageOrPrintOptions példányt
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// állítsa be a kimeneti képformátumot
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// Hozzon létre SheetRendert a gyűjtemény első munkalapjához
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// munkalapot képpé renderelni
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Az Excel konvertálása Word és PowerPoint formátumba" %}}
Lehetőség van bármilyen táblázat betöltésére és Word DOCX és PowerPoint PPTX fájlokká konvertálására használat közben. [DocxSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) osztályok alább bemutatott módon.
{{% blocks/products/pf/feature-page-code h3="C# kód az Excel Word és PowerPoint konvertáláshoz" %}}
```cs
// töltse be a sablonfájlt
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// mentse a táblázatot DOCX-ként
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// mentse a táblázatot PPTX-ként
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}