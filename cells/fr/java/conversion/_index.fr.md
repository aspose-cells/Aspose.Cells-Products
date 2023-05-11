---
title:  Microsoft Conversion de fichier Excel via Java
description: Convertir Excel XLS, XLSX, ODS, CSV à PDF, XPS, HTML, JPEG, HTML et de nombreux autres formats populaires avec seulement peu de lignes de Java et de nombreux formats populaires avec seulement des lignes de Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversion de fichiers Excel via Java" h2="Enregistrez les documents Excel Microsoft sous forme de feuille de calcul, Web, image et mise en page fixe" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Pour toute**Convertisseur Excel** application ou solution, Java Excel Library accélère les processus de programmation et de conversion de feuilles de calcul tout en gérant plusieurs formats, notamment XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 076 193481. Il permet également de *convertir les fichiers Excel en PDF**, XPS, HTML, MHTML, texte brut et formats d'image populaires tels que TIFF, JPG, PNG, BMP et SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inter-conversion des formats Excel Microsoft" %}}
 L'inter-conversion du format de feuille de calcul nécessite uniquement le chargement d'une feuille de calcul avec une instance de[Cahier](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et enregistrer dans le format souhaité tout en sélectionnant la valeur appropriée à partir de[Enregistrer le format](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) énumération.
{{% blocks/products/pf/feature-page-code h3="Java Exemple de code pour la conversion du format de fichier Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Convertir Excel en PDF, XPS, HTML & MD" %}}
 Des classes spécialisées sont disponibles pour contrôler le processus de conversion pour des formats de sortie spécifiques tels que[PdfEnregistrerOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) pour convertir les fichiers Excel en PDF,[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) pour exporter Excel en XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) pour rendre Excel comme HTML et[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) pour la conversion d'Excel en Markdown.
{{% blocks/products/pf/feature-page-code h3="Java Exemple de code pour Excel vers PDF et formats Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Convertir JSON en Excel et Excel en JSON" %}}
 JSON les données peuvent être importées dans une instance de la classe Workbook à l'aide de[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) pour un traitement ultérieur ou une simple conversion vers l'un des formats pris en charge. De même, les données de feuille de calcul peuvent être exportées en tant que JSON en créant un[Gamme](https://reference.aspose.com/cells/java/com.aspose.cells/range) ou des cellules et en appelant le[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) méthode.
{{% blocks/products/pf/feature-page-code h3="Java Code pour JSON Conversion Excel" %}}
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

{{% blocks/products/pf/feature-page-code h3="Conversion du code source Java pour Excel en JSON" %}}
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

{{% blocks/products/pf/feature-page-section h2="Enregistrer des feuilles de calcul Excel sur des images" %}}
 Chaque feuille de calcul peut être convertie en différents formats d'image, notamment JPG, BMP, PNG et GIF, définis par la propriété ImageType. Pour toute**Convertir Excel en images** cas, sélectionnez le cas pertinent à partir des liens.
{{% blocks/products/pf/feature-page-code h3="Java Code pour la conversion d\'Excel en image" %}}
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

{{% blocks/products/pf/feature-page-section h2="Convertir Microsoft Excel en Word et PowerPoint" %}}
 Il est possible de charger n'importe quelle feuille de calcul et de la convertir en fichiers Word DOCX & PowerPoint PPTX tout en utilisant[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) classes comme démontré ci-dessous.
{{% blocks/products/pf/feature-page-code h3="Java Code pour Excel vers Word et PowerPoint Conversion" %}}
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
