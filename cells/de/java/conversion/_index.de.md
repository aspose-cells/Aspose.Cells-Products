---
title:  Microsoft Excel-Dateikonvertierung via Java
description: Aspose.Cells for Java Bibliothek. Konvertieren Sie Excel, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG und weitere Formate mit nur wenigen Zeilen Java-Code.
keywords: [Java Aspose.Cells., excel to pdf., excel to json., html to xps., csv to json., json to pdf., xml to excel and Convert files between various formats in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konvertierung von Excel-Dateien via Java" h2="Speichern Sie Microsoft Excel-Dokumente als Tabellenkalkulation, Web, Bild und Format mit festem Layout" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Für jeden**Excel-Konverter** Anwendung oder Lösung, Java Excel-Bibliothek beschleunigt Tabellenkalkulations-Programmier- und Konvertierungsprozesse und verarbeitet gleichzeitig mehrere Formate, einschließlich XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 0761 93481. Es ermöglicht auch die *Konvertierung von Excel-Dateien in PDF**, XPS, HTML, MHTML, Nur-Text und gängige Bildformate wie TIFF, JPG, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interkonvertierung von Microsoft Excel-Formaten" %}}
 Für die gegenseitige Konvertierung des Tabellenformats ist lediglich das Laden einer Tabelle mit einer Instanz von erforderlich[Arbeitsmappe](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) und Speichern im gewünschten Format zurück, während Sie den entsprechenden Wert aus auswählen[SaveFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) Aufzählung.
{{% blocks/products/pf/feature-page-code h3="Java Beispielcode für die Konvertierung des Excel-Dateiformats" %}}

```cs
// load the source file
var wkb = new Workbook("sourceFile.xls");
// save as XLSX, ODS, SXC & FODS formats
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in PDF, XPS, HTML und MD" %}}
 Es stehen spezielle Klassen zur Verfügung, um den Konvertierungsprozess für bestimmte Ausgabeformate zu steuern, z[PDFSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) um Excel-Dateien als PDF zu konvertieren,[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) um Excel als XPS zu exportieren,[HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) um Excel als HTML darzustellen und[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) für die Konvertierung von Excel in Markdown.
{{% blocks/products/pf/feature-page-code h3="Java Beispielcode für Excel bis PDF und Webformate" %}}

```cs
// load template Excel file from disc
var bk = new Workbook("source-file.xlsx");

// convert Excel to PDF using Java
// Create PDF options
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// save Excel in XPS
bk.save("output.xps", new XpsSaveOptions());
// save Excel in HTML
bk.save("output.html", new HtmlSaveOptions());
// save Excel in Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// one can set relevant save options as of his choice before saving into relevant format
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie JSON in Excel und Excel in JSON" %}}
 JSON-Daten können mit Hilfe von in eine Instanz der Workbook-Klasse importiert werden[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) zur weiteren Verarbeitung oder einfachen Konvertierung in eines der unterstützten Formate. Ebenso können Arbeitsblattdaten als JSON exportiert werden, indem eine erstellt wird[Reichweite](https://reference.aspose.com/cells/java/com.aspose.cells/range) oder Zellen und das Aufrufen der[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) Methode.
{{% blocks/products/pf/feature-page-code h3="Java Code für die Konvertierung von JSON in Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Read File
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Set JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Import JSON Data
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Save Excel file
workbook.save(path + "excel-to-json.out.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Quellcode für Excel in JSON Konvertierung" %}}
```cs
// load XLSX file with an instance of Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// access CellsCollection of the worksheet containing data to be converted
Cells cells = workbook.getWorksheets().get(0).getCells();
// create & set ExportRangeToJsonOptions for advanced options
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// export range as JSON data
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// write data to disc in JSON format
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Speichern Sie Excel-Arbeitsblätter in Bildern" %}}
 Jedes Arbeitsblatt kann in verschiedene Bildformate konvertiert werden, einschließlich JPG, BMP, PNG und GIF, die durch die ImageType-Eigenschaft festgelegt werden. Für jeden**Konvertieren Sie Excel in Bilder** Wählen Sie den entsprechenden Fall aus den Links aus.
{{% blocks/products/pf/feature-page-code h3="Java Code für die Konvertierung von Excel in Bilder" %}}
```cs
// load template spreadsheet
var wkb = new Workbook("template.xlsx");

// Create an object for ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Set the image type
imgOptions.setImageType(ImageType.PNG);

// Get the first worksheet.
Worksheet sheet = wkb.getWorksheets().get(0);

// Create a SheetRender object for the target sheet
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Generate an image for the worksheet
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Microsoft Excel in Word und PowerPoint" %}}
Es ist möglich, jede Tabellenkalkulation zu laden und sie während der Verwendung in Word-Dateien DOCX und PowerPoint PPTX zu konvertieren[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) Klassen wie unten gezeigt.
{{% blocks/products/pf/feature-page-code h3="Java Code für Excel in Word und PowerPoint Konvertierung" %}}
```cs
// load the template file
var wkb = new Workbook("template.xlsx");
// save spreadsheet as DOCX
wkb.save("output.docx", new DocxSaveOptions());
// save spreadsheet as PPTX
wkb.save("output.pptx", new PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
