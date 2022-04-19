---
title: Conversion de fichiers Microsoft Excel via Python 
url: /fr/python/conversion/
description: Convertissez Excel XLS, XLSX, ODS, CSV en PDF, XPS, HTML, JPEG, HTML et de nombreux autres formats populaires avec seulement quelques lignes de code Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversion de format Excel Microsoft<sup>®</sup> via Python" h2="Importez et exportez des fichiers Excel sous forme de feuilles de calcul, Web, d\'images et de mise en page fixe" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python La bibliothèque Excel accélère les processus de programmation et de conversion des feuilles de calcul tout en prenant en charge les formats populaires tels que XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Il permet également d'exporter des fichiers Excel vers PDF, XPS, HTML, MHTML, texte brut et formats d'image populaires tels que TIFF, JPG, PNG, BMP et SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir Excel en XLSX, ODS, SXC et FODS" %}}
L'inter-conversion du format de feuille de calcul nécessite uniquement le chargement d'une feuille de calcul avec une instance de [Cahier](https://apireference.aspose.com/cells/python/asposecells.api/Workbook) et enregistrer dans le format souhaité tout en sélectionnant la valeur appropriée à partir de [Enregistrer le format](https://apireference.aspose.com/cells/python/asposecells.api/saveformat) énumération.
{{% blocks/products/pf/feature-page-code h3="Python Code pour la conversion du format de fichier Excel" %}}

```cs
// charger le fichier modèle
workbook = Workbook("Book1.xls")
  
// enregistrer aux formats XLSX, ODS, SXC et FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Convertissez Excel en PDF, XPS, HTML et MD" %}}
Des classes spécialisées sont disponibles pour contrôler le processus de conversion pour des formats de sortie spécifiques tels que [PdfEnregistrerOptions](https://apireference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) d'exporter des fichiers Excel au format PDF, [XpsSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) pour la conversion Excel vers XPS, [HtmlSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) pour rendre Excel au format HTML et [MarkdownSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) pour la conversion d'Excel en Markdown. 
{{% blocks/products/pf/feature-page-code h3="Python Code pour Excel vers PDF et formats Web" %}}

```cs
// charger le modèle de fichier Excel à partir du disque
book = Workbook("template.xlsx")

// enregistrer Excel au format PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// enregistrer Excel dans XPS avec 1 page par feuille de calcul
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// enregistrer Excel en HTML avec des images en Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// enregistrer Excel dans Markdown (MD) tout en conservant le formatage des cellules
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir JSON en Excel et Excel en JSON" %}}
Les développeurs Python peuvent facilement charger et convertir des fichiers JSON au format Excel en quelques lignes de code seulement. De même, les données Excel peuvent être exportées vers des données JSON.
{{% blocks/products/pf/feature-page-code h3="Python Code pour la conversion JSON en Excel" %}}
```cs
//Chargez votre fichier json source
workbook = Workbook("Data.json")
//enregistrer le fichier au format xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Code pour la conversion d\'Excel en JSON" %}}
```cs
//Chargez votre fichier xlsx source
workbook = Workbook("input.xlsx")
//enregistrer le fichier au format json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir des feuilles de calcul Excel en JPG, BMP, PNG et GIF" %}}
Chaque feuille de calcul d'un fichier Excel peut être convertie en différents formats d'image, appelez [Options d'image ou d'impression](https://apireference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat pour définir le format de l'image. 
{{% blocks/products/pf/feature-page-code h3="Python Code pour la conversion d\'Excel en image" %}}
```cs
// charger le modèle de feuille de calcul
workbook = Workbook("template.xlsx")
// créer et définir une instance de ImageOrPrintOptions
options = ImageOrPrintOptions()
// définir le format de l'image de sortie
options.setImageFormat(ImageFormat.getPng())
// créer SheetRender pour la première feuille de calcul de la collection
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// rendre la feuille de calcul à l'image
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir Excel en Word et PowerPoint" %}}
Il est possible de charger n'importe quelle feuille de calcul et de la convertir en fichiers Word DOCX et PowerPoint PPTX tout en utilisant [DocxSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) classes comme démontré ci-dessous.
{{% blocks/products/pf/feature-page-code h3="Python code pour la conversion d\'Excel en Word et PowerPoint" %}}
```cs
// charger le fichier modèle
workbook = Workbook("template.xlsx")

// enregistrer la feuille de calcul au format DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// enregistrer la feuille de calcul au format PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}