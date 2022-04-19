---
title: Conversion de fichiers Microsoft Excel via C# 
url: /fr/net/conversion/
description: Convertissez Excel XLS, XLSX, ODS, CSV en PDF, XPS, HTML, JPEG, HTML et de nombreux autres formats populaires avec seulement quelques lignes de code C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversion de format Excel Microsoft<sup>®</sup> via .NET" h2="Importez et exportez des fichiers Excel sous forme de feuilles de calcul, Web, d\'images et de mise en page fixe" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET La bibliothèque Excel accélère les processus de programmation et de conversion des feuilles de calcul tout en prenant en charge les formats populaires tels que XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Il permet également d'exporter des fichiers Excel vers PDF, XPS, HTML, MHTML, texte brut et formats d'image populaires tels que TIFF, JPG, PNG, BMP et SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir Excel en XLSX, ODS, SXC et FODS" %}}
L'inter-conversion du format de feuille de calcul nécessite uniquement le chargement d'une feuille de calcul avec une instance de [Cahier](https://apireference.aspose.com/cells/net/aspose.cells/workbook) et enregistrer dans le format souhaité tout en sélectionnant la valeur appropriée à partir de [Enregistrer le format](https://apireference.aspose.com/cells/net/aspose.cells/saveformat) énumération.
{{% blocks/products/pf/feature-page-code h3="C# Code pour la conversion du format de fichier Excel" %}}

```cs
// charger le fichier modèle
var workbook = new Aspose.Cells.Workbook("template.xls");
// enregistrer aux formats XLSX, ODS, SXC et FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Convertissez Excel en PDF, XPS, HTML et MD" %}}
Des classes spécialisées sont disponibles pour contrôler le processus de conversion pour des formats de sortie spécifiques tels que [PdfEnregistrerOptions](https://apireference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) d'exporter des fichiers Excel au format PDF, [XpsSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/xpssaveoptions) pour la conversion Excel vers XPS, [HtmlSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) pour rendre Excel au format HTML et [MarkdownSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) pour la conversion d'Excel en Markdown. 
{{% blocks/products/pf/feature-page-code h3="C# Code pour Excel vers PDF et formats Web" %}}

```cs
// charger le modèle de fichier Excel à partir du disque
var book = new Aspose.Cells.Workbook("template.xlsx");
// enregistrer Excel au format PDF/A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// enregistrer Excel dans XPS avec 1 page par feuille de calcul
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// enregistrer Excel en HTML avec des images en Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// enregistrer Excel dans Markdown (MD) tout en conservant le formatage des cellules
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir JSON en Excel et Excel en JSON" %}}
Les données JSON peuvent être importées dans une instance de [Cells](https://apireference.aspose.com/cells/net/aspose.cells/cells) classe avec l'aide de [JsonUtility.ImportDataJsonUtility.ImportData](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) pour un traitement ultérieur ou une simple conversion vers l'un des formats pris en charge. De la même manière, [Feuille de travail](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) les données peuvent être exportées au format JSON en créant un [Varier](https://apireference.aspose.com/cells/net/aspose.cells/range) ou des cellules et en appelant le [JsonUtility.ExportRangeToJson](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) méthode.
{{% blocks/products/pf/feature-page-code h3="C# Code pour la conversion JSON en Excel" %}}
```cs
// créer un objet Workbook
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// lire les données JSON du fichier
string jsonInput = File.ReadAllText("Data.json");
// définir JsonLayoutOptions pour traiter les tableaux comme une table
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// importer des données JSON dans la feuille de calcul à partir de la cellule A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// enregistrer le fichier résultant au format XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Code pour la conversion d\'Excel en JSON" %}}
```cs
// charger le fichier XLSX avec une instance de Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// accéder à CellsCollection de la feuille de calcul contenant les données à convertir
var cells = workbook.Worksheets[0].Cells;
// créer et définir ExportRangeToJsonOptions pour les options avancées
var exportOptions = new Utility.ExportRangeToJsonOptions();
// créer une plage de cellules contenant des données à exporter
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// plage d'exportation en tant que données JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// écrire le fichier de données sur le disque au format JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir des feuilles de calcul Excel en JPG, BMP, PNG et GIF" %}}
Chaque feuille de calcul d'un fichier Excel peut être convertie en différents formats d'image définis par le [ImageOrPrintOptions.ImageTypeImageOrPrintOptions.ImageType](https://apireference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) biens. La valeur par défaut est `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Code pour la conversion d\'Excel en image" %}}
```cs
// charger le modèle de feuille de calcul
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// créer et définir une instance de ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// définir le format de l'image de sortie
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// créer SheetRender pour la première feuille de calcul de la collection
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// rendre la feuille de calcul à l'image
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir Excel en Word et PowerPoint" %}}
Il est possible de charger n'importe quelle feuille de calcul et de la convertir en fichiers Word DOCX et PowerPoint PPTX tout en utilisant [DocxSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) classes comme démontré ci-dessous.
{{% blocks/products/pf/feature-page-code h3="C# code pour la conversion d\'Excel en Word et PowerPoint" %}}
```cs
// charger le fichier modèle
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// enregistrer la feuille de calcul au format DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// enregistrer la feuille de calcul au format PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}