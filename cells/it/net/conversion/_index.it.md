---
title: Conversione file Microsoft Excel tramite C# 
url: /it/net/conversion/
description: Converti Excel XLS, XLSX, ODS, CSV in PDF, XPS, HTML, JPEG, HTML e molti altri formati popolari con poche righe di codice C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversione del formato Microsoft<sup>&reg;</sup> Excel tramite .NET" h2="Importa ed esporta file Excel come fogli di calcolo, Web, immagini e formati a layout fisso" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET La libreria Excel velocizza i processi di conversione e programmazione dei fogli di lavoro, supportando al contempo i formati più diffusi tra cui XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Consente inoltre di esportare file Excel in PDF, XPS, HTML, MHTML, testo normale e formati di immagine popolari come TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converti Excel in XLSX, ODS, SXC e FODS" %}}
L'inter-conversione del formato del foglio di calcolo richiede solo il caricamento di un foglio di calcolo con un'istanza di [Cartella di lavoro](https://reference.aspose.com/cells/net/aspose.cells/workbook) e salvando nuovamente nel formato desiderato selezionando il valore appropriato da [Salva formato](https://reference.aspose.com/cells/net/aspose.cells/saveformat) enumerazione.
{{% blocks/products/pf/feature-page-code h3="C# Codice per la conversione del formato file Excel" %}}

```cs
// caricare il file modello
var workbook = new Aspose.Cells.Workbook("template.xls");
// salva come formati XLSX, ODS, SXC e FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converti Excel in PDF, XPS, HTML e MD" %}}
Sono disponibili classi specializzate per controllare il processo di conversione per formati di output specifici come [PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) per esportare file Excel come PDF, [XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) per la conversione da Excel a XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) per rendere Excel come HTML e [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) per la conversione da Excel a Markdown. 
{{% blocks/products/pf/feature-page-code h3="C# Codice per formati da Excel a PDF e Web" %}}

```cs
// carica il file Excel del modello dal disco
var book = new Aspose.Cells.Workbook("template.xlsx");
// salva Excel in formato PDF/A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// salva Excel in XPS con 1 pagina per foglio di lavoro
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// salva Excel in HTML con immagini come Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// salva Excel in Markdown (MD) mantenendo la formattazione della cella
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converti JSON in Excel ed Excel in JSON" %}}
I dati JSON possono essere importati in un'istanza di [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) classe con l'aiuto di [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) per ulteriore elaborazione o semplice conversione in uno qualsiasi dei formati supportati. Allo stesso modo, [Foglio di lavoro](https://reference.aspose.com/cells/net/aspose.cells/worksheet) i dati possono essere esportati come JSON creando un file [Allineare](https://reference.aspose.com/cells/net/aspose.cells/range) o celle e chiamando il [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) metodo.
{{% blocks/products/pf/feature-page-code h3="C# Codice per la conversione da JSON a Excel" %}}
```cs
// creare un oggetto cartella di lavoro
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// leggere i dati JSON dal file
string jsonInput = File.ReadAllText("Data.json");
// imposta JsonLayoutOptions per trattare le matrici come tabelle
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// importa i dati JSON nel foglio di lavoro a partire dalla cella A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// salva il file risultante in formato XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Codice per la conversione da Excel a JSON" %}}
```cs
// carica il file XLSX con un'istanza di Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// accedere a CellsCollection del foglio di lavoro contenente i dati da convertire
var cells = workbook.Worksheets[0].Cells;
// crea e imposta ExportRangeToJsonOptions per opzioni avanzate
var exportOptions = new Utility.ExportRangeToJsonOptions();
// creare un intervallo di celle contenenti dati da esportare
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// intervallo di esportazione come dati JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// scrivere il file di dati su disco in formato JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Converti fogli di lavoro Excel in JPG, BMP, PNG e GIF" %}}
Ogni foglio di lavoro di un file Excel può essere convertito in diversi formati di immagine impostati dal [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) proprietà. Il valore predefinito è "ImageFormat.Bmp".
{{% blocks/products/pf/feature-page-code h3="C# Codice per la conversione da Excel a immagine" %}}
```cs
// caricare il foglio di calcolo del modello
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// creare e impostare un'istanza di ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// imposta il formato dell'immagine di output
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// crea SheetRender per il primo foglio di lavoro nella raccolta
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// renderizzare il foglio di lavoro all'immagine
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converti Excel in Word e PowerPoint" %}}
È possibile caricare qualsiasi foglio di calcolo e convertirlo in file Word DOCX e PowerPoint PPTX durante l'utilizzo [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [Opzioni di salvataggio Pptx](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) classi come illustrato di seguito.
{{% blocks/products/pf/feature-page-code h3="C# codice per la conversione da Excel a Word e PowerPoint" %}}
```cs
// caricare il file modello
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// salva il foglio di calcolo come DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// salva il foglio di calcolo come PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}