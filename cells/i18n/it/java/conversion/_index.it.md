---
title: Conversione file Microsoft Excel tramite Java 
url: /it/java/conversion/
description: Converti Excel XLS, XLSX, ODS, CSV in PDF, XPS, HTML, JPEG, HTML e molti altri formati popolari con poche righe di codice Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversione di file Microsoft<sup>&reg;</sup> Excel tramite Java" h2="Salva i documenti Microsoft Excel come fogli di calcolo, Web, immagini e formati a layout fisso" >}}

{{% blocks/products/pf/feature-page-summary %}}
Per qualsiasi applicazione o soluzione **Excel Converter**, Java Excel Library accelera la programmazione di fogli di lavoro e i processi di conversione gestendo più formati tra cui XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Consente inoltre di **convertire file Excel in PDF**, XPS, HTML, MHTML, testo normale e formati di immagine popolari come TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inter-conversione di formati Microsoft Excel" %}}
L'inter-conversione del formato del foglio di calcolo richiede solo il caricamento di un foglio di calcolo con un'istanza di [Cartella di lavoro](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) e salvando nuovamente nel formato desiderato selezionando il valore appropriato da [Salva formato](https://apireference.aspose.com/cells/java/com.aspose.cells/SaveFormat) enumerazione.
{{% blocks/products/pf/feature-page-code h3="Java Codice di esempio per la conversione del formato file Excel" %}}

```cs
// caricare il file sorgente
var wkb = new Workbook("sourceFile.xls");
// salva come formati XLSX, ODS, SXC e FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converti Excel in PDF, XPS, HTML e MD" %}}
Sono disponibili classi specializzate per controllare il processo di conversione per formati di output specifici come [PdfSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) per convertire file Excel in PDF, [XpsSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) per esportare Excel come XPS, [HtmlSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) per rendere Excel come HTML e [MarkdownSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) per la conversione da Excel a Markdown. 
{{% blocks/products/pf/feature-page-code h3="Java Codice di esempio per i formati da Excel a PDF e Web" %}}

```cs
// carica il file Excel del modello dal disco
var bk = new Workbook("source-file.xlsx");

// converti Excel in PDF utilizzando Java
// Crea opzioni PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// salva Excel in XPS
bk.save("output.xps", new XpsSaveOptions());
// salva Excel in HTML
bk.save("output.html", new HtmlSaveOptions());
// salva Excel in Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// è possibile impostare le opzioni di salvataggio pertinenti a propria scelta prima di salvare nel formato pertinente

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converti JSON in Excel ed Excel in JSON" %}}
I dati JSON possono essere importati in un'istanza della classe Workbook con l'aiuto di [JSONUtility.importData](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) per ulteriore elaborazione o semplice conversione in uno qualsiasi dei formati supportati. Allo stesso modo, i dati del foglio di lavoro possono essere esportati come JSON creando un file [Allineare](https://apireference.aspose.com/cells/java/com.aspose.cells/range) o celle e chiamando il [exportRangeToJson](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility) metodo.
{{% blocks/products/pf/feature-page-code h3="Java Codice per la conversione da JSON a Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Leggi file
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Imposta JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Importa dati JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Salva file Excel
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Codice sorgente per la conversione da Excel a JSON" %}}
```cs
// carica il file XLSX con un'istanza di Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// accedere a CellsCollection del foglio di lavoro contenente i dati da convertire
Cells cells = workbook.getWorksheets().get(0).getCells();
// crea e imposta ExportRangeToJsonOptions per opzioni avanzate
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// creare un intervallo di celle contenenti dati da esportare
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// intervallo di esportazione come dati JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// scrivere i dati su disco in formato JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Salva fogli di lavoro Excel in immagini" %}}
Ogni foglio di lavoro può essere convertito in diversi formati di immagine inclusi JPG, BMP, PNG e GIF, impostati dalla proprietà ImageType. Per qualsiasi caso **Converti Excel in immagini**, seleziona il caso pertinente dai collegamenti.
{{% blocks/products/pf/feature-page-code h3="Java Codice per la conversione da Excel a immagine" %}}
```cs
// caricare il foglio di calcolo del modello
var wkb = new Workbook("template.xlsx");

// Crea un oggetto per ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Imposta il tipo di immagine
imgOptions.setImageType(ImageType.PNG);

// Ottieni il primo foglio di lavoro.
Worksheet sheet = wkb.getWorksheets().get(0);

// Crea un oggetto SheetRender per il foglio di destinazione
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Genera un'immagine per il foglio di lavoro
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converti Microsoft Excel in Word e PowerPoint" %}}
È possibile caricare qualsiasi foglio di calcolo e convertirlo in file Word DOCX e PowerPoint PPTX durante l'utilizzo [DocxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [Opzioni di salvataggio Pptx](https://apireference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) classi come illustrato di seguito.
{{% blocks/products/pf/feature-page-code h3="Java Codice per la conversione da Excel a Word e PowerPoint" %}}
```cs
// caricare il file modello
var wkb = new Workbook("template.xlsx");
// salva il foglio di calcolo come DOCX
wkb.save("output.docx", new DocxSaveOptions());
// salva il foglio di calcolo come PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}