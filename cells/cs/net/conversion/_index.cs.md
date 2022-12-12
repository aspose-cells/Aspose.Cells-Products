---
title: Převod souborů Microsoft Excel prostřednictvím C# 

description: Převeďte Excel XLS, XLSX, ODS, CSV do PDF, XPS, HTML, JPEG, HTML a mnoha dalších oblíbených formátů pomocí pouhých několika řádků kódu C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konverze formátu Microsoft<sup>&reg;</sup> Excel prostřednictvím .NET" h2="Importujte a exportujte soubory Excel jako tabulkový procesor, web, obrázky a formáty s pevným rozložením" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Knihovna Excel urychluje programování tabulek a procesy převodu a zároveň podporuje oblíbené formáty včetně XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Umožňuje také exportovat soubory Excel do PDF, XPS, HTML, MHTML, prostého textu a populárních obrazových formátů, jako jsou TIFF, JPG, PNG, BMP a SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Převeďte Excel do XLSX, ODS, SXC & FODS" %}}
Vzájemná konverze formátu tabulky vyžaduje pouze načtení tabulky s instancí [pracovní sešit](https://reference.aspose.com/cells/net/aspose.cells/workbook) a uložení zpět v požadovaném formátu při výběru vhodné hodnoty z [UložitFormát](https://reference.aspose.com/cells/net/aspose.cells/saveformat) výčet.
{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod formátu souboru aplikace Excel" %}}

```cs
// načtěte soubor šablony
var workbook = new Aspose.Cells.Workbook("template.xls");
// uložit jako formáty XLSX, ODS, SXC a FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Převeďte Excel do PDF, XPS, HTML a MD" %}}
K dispozici jsou specializované třídy pro řízení procesu převodu pro konkrétní výstupní formáty, jako je např [Možnosti PdfSave](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) exportovat soubory Excel jako PDF, [XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) pro převod Excel na XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) vykreslit Excel jako HTML a [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) pro převod Excel na Markdown. 
{{% blocks/products/pf/feature-page-code h3="C# Kód pro formáty Excel do PDF a webové" %}}

```cs
// načíst soubor šablony Excel z disku
var book = new Aspose.Cells.Workbook("template.xlsx");
// uložit Excel ve formátu PDF/A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// uložit Excel v XPS s 1 stránkou na list
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// uložit Excel v HTML s obrázky jako Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// uložit Excel v Markdown (MD) při zachování formátování buněk
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte JSON na Excel a Excel na JSON" %}}
Data JSON lze importovat do instance [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) třídy s pomocí [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) pro další zpracování nebo jednoduchý převod do některého z podporovaných formátů. Podobně, [Pracovní list](https://reference.aspose.com/cells/net/aspose.cells/worksheet) data lze exportovat jako JSON vytvořením a [Rozsah](https://reference.aspose.com/cells/net/aspose.cells/range) nebo buňky a volání [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) metoda.
{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod JSON do Excelu" %}}
```cs
// vytvořit objekt sešitu
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// číst data JSON ze souboru
string jsonInput = File.ReadAllText("Data.json");
// nastavte JsonLayoutOptions tak, aby zacházelo s poli jako s tabulkou
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// importujte data JSON do listu počínaje buňkou A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// uložit výsledný soubor ve formátu XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod Excelu na JSON" %}}
```cs
// načíst soubor XLSX s instancí sešitu
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// přístup k CellsCollection listu obsahujícího data, která mají být převedena
var cells = workbook.Worksheets[0].Cells;
// vytvořit a nastavit ExportRangeToJsonOptions pro pokročilé možnosti
var exportOptions = new Utility.ExportRangeToJsonOptions();
// vytvořit oblast buněk obsahujících data k exportu
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// exportovat rozsah jako data JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// zapisovat datový soubor na disk ve formátu JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte pracovní listy aplikace Excel do formátu JPG, BMP, PNG a GIF" %}}
Každý list souboru aplikace Excel lze převést do různých formátů obrázků nastavených v [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) vlastnictví. Výchozí hodnota je `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod Excelu na obrázek" %}}
```cs
// načíst šablonu tabulky
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// vytvořit a nastavit instanci ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// nastavit výstupní formát obrázku
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// vytvořte SheetRender pro první list v kolekci
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// vykreslit pracovní list do obrázku
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte Excel do Wordu a PowerPointu" %}}
Při používání je možné načíst jakoukoli tabulku a převést ji na soubory Word DOCX & PowerPoint PPTX [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [Možnosti PptxSave](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) třídy, jak je ukázáno níže.
{{% blocks/products/pf/feature-page-code h3="C# kód pro převod Excelu na Word a PowerPoint" %}}
```cs
// načtěte soubor šablony
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// uložit tabulku jako DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// uložit tabulku jako PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
