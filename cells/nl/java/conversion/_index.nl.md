---
title:  Microsoft Excel-bestandsconversie via Java
description: Converteer Excel XLS, XLSX, ODS, CSV naar PDF, XPS, HTML, JPEG, HTML en vele andere populaire formaten met slechts enkele regels code Java .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversie van Excel-bestanden via Java" h2="Sla Microsoft Excel-documenten op als spreadsheet-, web-, afbeeldings- en vaste lay-outindelingen" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Voor enige**Excel-converter** toepassing of oplossing, Java Excel Library versnelt spreadsheetprogrammering en conversieprocessen terwijl meerdere formaten worden verwerkt, waaronder XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 0761 93481. Hiermee kunt u ook *Excel-bestanden converteren naar PDF**, XPS, HTML, MHTML, platte tekst en populaire beeldformaten zoals TIFF, JPG, PNG, BMP en SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversie van Microsoft Excel-indelingen" %}}
 Inter-conversie van spreadsheetformaat vereist alleen het laden van een spreadsheet met een instantie van[Werkboek](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) en opslaan in het gewenste formaat terwijl u de juiste waarde selecteert uit[Formaat opslaan](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) opsomming.
{{% blocks/products/pf/feature-page-code h3="Java Voorbeeldcode voor conversie van Excel-bestandsindelingen" %}}

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


{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar PDF, XPS, HTML & MD" %}}
 Gespecialiseerde klassen zijn beschikbaar om het conversieproces voor specifieke uitvoerformaten zoals[PdfSaveOpties](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) om Excel-bestanden te converteren als PDF,[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) om Excel te exporteren als XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) om Excel weer te geven als HTML en[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) voor conversie van Excel naar Markdown.
{{% blocks/products/pf/feature-page-code h3="Java Voorbeeldcode voor Excel naar PDF en webindelingen" %}}

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

{{% blocks/products/pf/feature-page-section h2="Converteer JSON naar Excel en Excel naar JSON" %}}
 JSON-gegevens kunnen worden geïmporteerd in een exemplaar van de Workbook-klasse met behulp van[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) voor verdere verwerking of eenvoudige conversie naar een van de ondersteunde formaten. Evenzo kunnen werkbladgegevens worden geëxporteerd als JSON door een[Bereik](https://reference.aspose.com/cells/java/com.aspose.cells/range) of cellen en bel de[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) methode.
{{% blocks/products/pf/feature-page-code h3="Java Code voor JSON naar Excel-conversie" %}}
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

{{% blocks/products/pf/feature-page-code h3="Java Broncode voor Excel naar JSON Conversie" %}}
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

{{% blocks/products/pf/feature-page-section h2="Bewaar Excel-werkbladen in afbeeldingen" %}}
 Elk werkblad kan worden geconverteerd naar verschillende afbeeldingsindelingen, waaronder JPG, BMP, PNG en GIF, ingesteld door de eigenschap ImageType. Voor enige**Converteer Excel naar afbeeldingen** geval, selecteer het relevante geval uit de links.
{{% blocks/products/pf/feature-page-code h3="Java Code voor conversie van Excel naar afbeelding" %}}
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

{{% blocks/products/pf/feature-page-section h2="Converteer Microsoft Excel naar Word en PowerPoint" %}}
 Het is mogelijk om elke spreadsheet te laden en te converteren naar Word DOCX & PowerPoint PPTX bestanden tijdens het gebruik[DocxSaveOpties](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) klassen zoals hieronder aangetoond.
{{% blocks/products/pf/feature-page-code h3="Java Code voor Excel naar Word & PowerPoint Conversie" %}}
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
