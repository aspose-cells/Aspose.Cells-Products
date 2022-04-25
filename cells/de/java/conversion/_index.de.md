---
title: Microsoft Excel-Dateikonvertierung über Java 
url: /de/java/conversion/
description: Konvertieren Sie Excel XLS, XLSX, ODS, CSV in PDF, XPS, HTML, JPEG, HTML und viele andere gängige Formate mit nur wenigen Zeilen Java-Code.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertierung von Microsoft<sup>&reg;</sup> Excel-Dateien über Java" h2="Speichern Sie Microsoft Excel-Dokumente als Tabellenkalkulations-, Web-, Bild- und Festlayoutformate" >}}

{{% blocks/products/pf/feature-page-summary %}}
Für jede **Excel-Konverter**-Anwendung oder -Lösung beschleunigt Java Excel Library die Tabellenprogrammierung und Konvertierungsprozesse und verarbeitet gleichzeitig mehrere Formate, darunter XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Es ermöglicht auch die **Konvertierung von Excel-Dateien in PDF**, XPS, HTML, MHTML, Nur-Text und gängige Bildformate wie TIFF, JPG, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Zwischenkonvertierung von Microsoft Excel-Formaten" %}}
Die Konvertierung des Tabellenkalkulationsformats erfordert nur das Laden einer Tabellenkalkulation mit einer Instanz von [Arbeitsmappe](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) und im gewünschten Format zurückspeichern, während Sie den entsprechenden Wert auswählen [Format speichern](https://apireference.aspose.com/cells/java/com.aspose.cells/SaveFormat) Aufzählung.
{{% blocks/products/pf/feature-page-code h3="Java Beispielcode für die Konvertierung des Excel-Dateiformats" %}}

```cs
// Laden Sie die Quelldatei
var wkb = new Workbook("sourceFile.xls");
// als XLSX-, ODS-, SXC- und FODS-Formate speichern
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in PDF, XPS, HTML und MD" %}}
Es sind spezialisierte Klassen verfügbar, um den Konvertierungsprozess für bestimmte Ausgabeformate wie z [PdfSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) Excel-Dateien als PDF konvertieren, [XpsSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) Excel als XPS exportieren, [HtmlSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) um Excel als HTML zu rendern und [MarkdownSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) für die Excel-zu-Markdown-Konvertierung. 
{{% blocks/products/pf/feature-page-code h3="Java Beispielcode für Excel-zu-PDF- und Webformate" %}}

```cs
// Laden Sie die Excel-Vorlagendatei von der Disc
var bk = new Workbook("source-file.xlsx");

// Konvertieren Sie Excel mit Java in PDF
// PDF-Optionen erstellen
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// Excel in XPS speichern
bk.save("output.xps", new XpsSaveOptions());
// Excel in HTML speichern
bk.save("output.html", new HtmlSaveOptions());
// Excel in Markdown (MD) speichern
bk.save("output.md", new MarkdownSaveOptions());

// Sie können relevante Speicheroptionen nach Ihrer Wahl festlegen, bevor Sie in das entsprechende Format speichern

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie JSON in Excel und Excel in JSON" %}}
JSON-Daten können mithilfe von in eine Instanz der Workbook-Klasse importiert werden [JSONUtility.importData](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) zur Weiterverarbeitung oder einfachen Konvertierung in eines der unterstützten Formate. Auf ähnliche Weise können Arbeitsblattdaten als JSON exportiert werden, indem eine [Bereich](https://apireference.aspose.com/cells/java/com.aspose.cells/range) oder Zellen und Aufruf der [exportRangeToJson](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility) Methode.
{{% blocks/products/pf/feature-page-code h3="Java Code für JSON-zu-Excel-Konvertierung" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Datei lesen
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Legen Sie JsonLayoutOptions fest
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// JSON-Daten importieren
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Excel-Datei speichern
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Quellcode für Excel-zu-JSON-Konvertierung" %}}
```cs
// XLSX-Datei mit einer Instanz von Workbook laden
Workbook workbook = new Workbook("sourceFile.xlsx");
// Greifen Sie auf die CellsCollection des Arbeitsblatts zu, das die zu konvertierenden Daten enthält
Cells cells = workbook.getWorksheets().get(0).getCells();
// ExportRangeToJsonOptions für erweiterte Optionen erstellen und festlegen
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// Erstellen Sie einen Zellbereich mit zu exportierenden Daten
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// Bereich als JSON-Daten exportieren
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// Schreiben Sie Daten im JSON-Format auf die Disc
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Speichern Sie Excel-Arbeitsblätter in Bildern" %}}
Jedes Arbeitsblatt kann in verschiedene Bildformate konvertiert werden, einschließlich JPG, BMP, PNG und GIF, die durch die ImageType-Eigenschaft festgelegt werden. Wählen Sie für jeden **Excel in Bilder konvertieren**-Fall den entsprechenden Fall aus den Links aus.
{{% blocks/products/pf/feature-page-code h3="Java Code für Excel-zu-Bild-Konvertierung" %}}
```cs
// Vorlagetabelle laden
var wkb = new Workbook("template.xlsx");

// Erstellen Sie ein Objekt für ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Legen Sie den Bildtyp fest
imgOptions.setImageType(ImageType.PNG);

// Holen Sie sich das erste Arbeitsblatt.
Worksheet sheet = wkb.getWorksheets().get(0);

// Erstellen Sie ein SheetRender-Objekt für das Zielblatt
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Generieren Sie ein Bild für das Arbeitsblatt
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Microsoft Excel in Word und PowerPoint" %}}
Es ist möglich, jede Tabelle zu laden und sie während der Verwendung in Word DOCX- und PowerPoint PPTX-Dateien zu konvertieren [DocxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) Klassen wie unten gezeigt.
{{% blocks/products/pf/feature-page-code h3="Java Code für die Umwandlung von Excel in Word und PowerPoint" %}}
```cs
// Laden Sie die Vorlagendatei
var wkb = new Workbook("template.xlsx");
// Tabelle als DOCX speichern
wkb.save("output.docx", new DocxSaveOptions());
// Tabelle als PPTX speichern
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}