---
title: Conversion de fichiers Microsoft Excel via Java 
url: /fr/java/conversion/
description: Convertissez Excel XLS, XLSX, ODS, CSV en PDF, XPS, HTML, JPEG, HTML et de nombreux autres formats populaires avec seulement quelques lignes de code Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversion de fichiers Excel Microsoft<sup>&reg;</sup> via Java" h2="Enregistrez des documents Microsoft Excel sous forme de feuille de calcul, Web, d\'image et de mise en page fixe" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pour toute application ou solution de **convertisseur Excel**, la bibliothèque Java Excel accélère les processus de programmation et de conversion des feuilles de calcul tout en gérant plusieurs formats, notamment XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Il permet également de **convertir des fichiers Excel en PDF**, XPS, HTML, MHTML, texte brut et formats d'image populaires tels que TIFF, JPG, PNG, BMP et SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inter-conversion des formats Microsoft Excel" %}}
L'inter-conversion du format de feuille de calcul nécessite uniquement le chargement d'une feuille de calcul avec une instance de [Cahier](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et enregistrer dans le format souhaité tout en sélectionnant la valeur appropriée à partir de [Enregistrer le format](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) énumération.
{{% blocks/products/pf/feature-page-code h3="Java Exemple de code pour la conversion du format de fichier Excel" %}}

```cs
// charger le fichier source
var wkb = new Workbook("sourceFile.xls");
// enregistrer aux formats XLSX, ODS, SXC et FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Convertissez Excel en PDF, XPS, HTML et MD" %}}
Des classes spécialisées sont disponibles pour contrôler le processus de conversion pour des formats de sortie spécifiques tels que [PdfEnregistrerOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) convertir des fichiers Excel en PDF, [XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) exporter Excel en XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) pour rendre Excel au format HTML et [MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) pour la conversion d'Excel en Markdown. 
{{% blocks/products/pf/feature-page-code h3="Java Exemple de code pour les formats Excel vers PDF et Web" %}}

```cs
// charger le modèle de fichier Excel à partir du disque
var bk = new Workbook("source-file.xlsx");

// convertir Excel en PDF en utilisant Java
// Options de création de PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// enregistrer Excel dans XPS
bk.save("output.xps", new XpsSaveOptions());
// enregistrer Excel en HTML
bk.save("output.html", new HtmlSaveOptions());
// enregistrer Excel dans Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// on peut définir les options de sauvegarde pertinentes de son choix avant de sauvegarder dans le format approprié

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir JSON en Excel et Excel en JSON" %}}
Les données JSON peuvent être importées dans une instance de la classe Workbook à l'aide de [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) pour un traitement ultérieur ou une simple conversion vers l'un des formats pris en charge. De même, les données de feuille de calcul peuvent être exportées au format JSON en créant un [Varier](https://reference.aspose.com/cells/java/com.aspose.cells/range) ou des cellules et en appelant le [exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) méthode.
{{% blocks/products/pf/feature-page-code h3="Java Code pour la conversion JSON en Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Lire le fichier
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Définir JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Importer des données JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Enregistrer le fichier Excel
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Code source pour la conversion d\'Excel en JSON" %}}
```cs
// charger le fichier XLSX avec une instance de Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// accéder à CellsCollection de la feuille de calcul contenant les données à convertir
Cells cells = workbook.getWorksheets().get(0).getCells();
// créer et définir ExportRangeToJsonOptions pour les options avancées
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// créer une plage de cellules contenant des données à exporter
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// plage d'exportation en tant que données JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// écrire des données sur le disque au format JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Enregistrer des feuilles de calcul Excel sur des images" %}}
Chaque feuille de calcul peut être convertie en différents formats d'image, notamment JPG, BMP, PNG et GIF, définis par la propriété ImageType. Pour tout cas **Convertir Excel en images**, sélectionnez le cas pertinent à partir des liens.
{{% blocks/products/pf/feature-page-code h3="Java Code pour la conversion d\'Excel en image" %}}
```cs
// charger le modèle de feuille de calcul
var wkb = new Workbook("template.xlsx");

// Créer un objet pour ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Définir le type d'image
imgOptions.setImageType(ImageType.PNG);

// Obtenez la première feuille de calcul.
Worksheet sheet = wkb.getWorksheets().get(0);

// Créer un objet SheetRender pour la feuille cible
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Générer une image pour la feuille de calcul
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir Microsoft Excel en Word et PowerPoint" %}}
Il est possible de charger n'importe quelle feuille de calcul et de la convertir en fichiers Word DOCX et PowerPoint PPTX tout en utilisant [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) classes comme démontré ci-dessous.
{{% blocks/products/pf/feature-page-code h3="Java Code pour la conversion d\'Excel en Word et PowerPoint" %}}
```cs
// charger le fichier modèle
var wkb = new Workbook("template.xlsx");
// enregistrer la feuille de calcul au format DOCX
wkb.save("output.docx", new DocxSaveOptions());
// enregistrer la feuille de calcul au format PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}