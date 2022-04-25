---
title: Microsoft Excel-bestandsconversie via Java 
url: /nl/java/conversion/
description: Converteer Excel XLS, XLSX, ODS, CSV naar PDF, XPS, HTML, JPEG, HTML en vele andere populaire formaten met slechts enkele regels Java code.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-bestandenconversie via Java" h2="Sla Microsoft Excel-documenten op als spreadsheet-, web-, afbeeldings- en vaste indelingen" >}}

{{% blocks/products/pf/feature-page-summary %}}
Voor elke **Excel-converter**-toepassing of -oplossing versnelt Java Excel Library de programmeer- en conversieprocessen voor spreadsheets, terwijl meerdere indelingen worden verwerkt, waaronder XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Het maakt het ook mogelijk om **Excel-bestanden te converteren naar PDF**, XPS, HTML, MHTML, platte tekst en populaire afbeeldingsformaten zoals TIFF, JPG, PNG, BMP en SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversie van Microsoft Excel-indelingen" %}}
Interconversie van spreadsheetformaat vereist alleen het laden van een spreadsheet met een instantie van [Werkboek](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) en terug opslaan in het gewenste formaat terwijl u de juiste waarde selecteert uit [OpslaanFormaat](https://apireference.aspose.com/cells/java/com.aspose.cells/SaveFormat) opsomming.
{{% blocks/products/pf/feature-page-code h3="Java Voorbeeldcode voor conversie van Excel-bestandsindeling" %}}

```cs
// laad het bronbestand
var wkb = new Workbook("sourceFile.xls");
// opslaan als XLSX-, ODS-, SXC- en FODS-indelingen
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar PDF, XPS, HTML & MD" %}}
Er zijn gespecialiseerde klassen beschikbaar om het conversieproces voor specifieke uitvoerformaten te regelen, zoals: [PdfOpslaanOpties](https://apireference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) om Excel-bestanden naar PDF te converteren, [XpsSave-opties](https://apireference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) om Excel als XPS te exporteren, [HtmlOpslaanOpties](https://apireference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) om Excel weer te geven als HTML en [MarkdownOpslaanOpties](https://apireference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) voor Excel naar Markdown-conversie. 
{{% blocks/products/pf/feature-page-code h3="Java Voorbeeldcode voor Excel naar PDF en webformaten" %}}

```cs
// laad sjabloon Excel-bestand van schijf
var bk = new Workbook("source-file.xlsx");

// converteer Excel naar PDF met Java
// PDF-opties maken
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// sla Excel op in XPS
bk.save("output.xps", new XpsSaveOptions());
// Excel opslaan in HTML
bk.save("output.html", new HtmlSaveOptions());
// sla Excel op in Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// men kan naar eigen keuze relevante opslagopties instellen voordat deze in een relevant formaat worden opgeslagen

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer JSON naar Excel en Excel naar JSON" %}}
JSON-gegevens kunnen worden geïmporteerd in een instantie van de Workbook-klasse met behulp van: [JSONUtility.importData](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) voor verdere verwerking of eenvoudige conversie naar een van de ondersteunde formaten. Evenzo kunnen werkbladgegevens worden geëxporteerd als JSON door een [Bereik](https://apireference.aspose.com/cells/java/com.aspose.cells/range) of cellen en bellen met de [exportBereikNaarJson](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility) methode.
{{% blocks/products/pf/feature-page-code h3="Java Code voor JSON naar Excel-conversie" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Bestand lezen
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// JsonLayout-opties instellen
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// JSON-gegevens importeren
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Excel-bestand opslaan
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Broncode voor conversie van Excel naar JSON" %}}
```cs
// laad XLSX-bestand met een exemplaar van Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// toegang tot CellsVerzameling van het werkblad met gegevens die moeten worden geconverteerd
Cells cells = workbook.getWorksheets().get(0).getCells();
// maak en stel ExportRangeToJsonOptions in voor geavanceerde opties
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// maak een celbereik met gegevens om te exporteren
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// bereik exporteren als JSON-gegevens
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// gegevens naar schijf schrijven in JSON-indeling
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel-werkbladen opslaan in afbeeldingen" %}}
Elk werkblad kan worden geconverteerd naar verschillende afbeeldingsindelingen, waaronder JPG, BMP, PNG en GIF, ingesteld door de eigenschap ImageType. Voor elke **Convert Excel to Images** case, selecteer de relevante case uit de links.
{{% blocks/products/pf/feature-page-code h3="Java Code voor conversie van Excel naar afbeelding" %}}
```cs
// laad sjabloonspreadsheet
var wkb = new Workbook("template.xlsx");

// Maak een object voor ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Stel het afbeeldingstype in
imgOptions.setImageType(ImageType.PNG);

// Pak het eerste werkblad.
Worksheet sheet = wkb.getWorksheets().get(0);

// Maak een SheetRender-object voor het doelblad
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Genereer een afbeelding voor het werkblad
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer Microsoft Excel naar Word en PowerPoint" %}}
Het is mogelijk om elke spreadsheet te laden en deze te converteren naar Word DOCX & PowerPoint PPTX-bestanden tijdens gebruik [DocxSave-opties](https://apireference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxOpslaanOpties](https://apireference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) klassen zoals hieronder getoond.
{{% blocks/products/pf/feature-page-code h3="Java Code voor conversie van Excel naar Word en PowerPoint" %}}
```cs
// laad het sjabloonbestand
var wkb = new Workbook("template.xlsx");
// spreadsheet opslaan als DOCX
wkb.save("output.docx", new DocxSaveOptions());
// spreadsheet opslaan als PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}