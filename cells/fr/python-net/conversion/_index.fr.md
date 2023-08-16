---
title: Microsoft Conversion de fichier Excel à l'aide de Python via NET
description: Convertir Excel XLS, XLSX, ODS, CSV à PDF, XPS, HTML, JPEG, HTML et de nombreux autres formats populaires avec seulement peu de lignes de Python et de nombreux formats populaires avec seulement des lignes de Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversion de format Excel via Python" h2="Importez et exportez des fichiers Excel sous forme de feuilles de calcul, Web, d\'images et de mise en page fixe" >}}

{{% blocks/products/pf/feature-page-summary %}}
La bibliothèque Excel Python accélère les processus de programmation et de conversion des feuilles de calcul tout en prenant en charge les formats populaires, notamment XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 0761934 81. Il permet également d'exporter des fichiers Excel vers PDF, XPS, HTML, MHTML, Plain Formats de texte et d'image populaires tels que TIFF, JPG, PNG, BMP et SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertir Excel en XLSX, ODS, SXC & FODS" %}}
 L'inter-conversion du format de feuille de calcul nécessite uniquement le chargement d'une feuille de calcul avec une instance de[Cahier](https://reference.aspose.com/cells/python-net/aspose.cells/workbook/) et enregistrer dans le format souhaité tout en sélectionnant la valeur appropriée à partir de[Enregistrer le format](https://reference.aspose.com/cells/python-net/aspose.cells/saveformat/) énumération.
{{% blocks/products/pf/feature-page-code h3="Python Code pour la conversion du format de fichier Excel" %}}

```cs
// load the template file
workbook = Workbook("Book1.xls")
  
// save as XLSX, ODS, SXC & FODS formats
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.sxc", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Convertir Excel en PDF, XPS, HTML & MD" %}}
 Des classes spécialisées sont disponibles pour contrôler le processus de conversion pour des formats de sortie spécifiques tels que[PdfEnregistrerOptions](https://reference.aspose.com/cells/python-net/aspose.cells/pdfsaveoptions/) pour exporter des fichiers Excel sous PDF,[XpsSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/xpssaveoptions/) pour la conversion d'Excel en XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/htmlsaveoptions/) pour rendre Excel comme HTML et[MarkdownSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/markdownsaveoptions/) pour la conversion d'Excel en Markdown.
{{% blocks/products/pf/feature-page-code h3="Python Code pour Excel vers PDF et formats Web" %}}

```cs
// load template Excel file from disc
book = Workbook("template.xlsx")

// save Excel in PDF_A_1_B format
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// save Excel in XPS with 1 page per worksheet
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// save Excel in HTML with images as Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// save Excel in Markdown (MD) while retaining cell formatting
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir JSON en Excel et Excel en JSON" %}}
Les développeurs Python peuvent facilement charger et convertir des fichiers JSON en Excel en quelques lignes de code. De même, les données Excel peuvent être exportées vers les données JSON.
{{% blocks/products/pf/feature-page-code h3="Python Code pour JSON Conversion Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Code pour Excel à JSON Conversion" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir des feuilles de calcul Excel en JPG, BMP, PNG et GIF" %}}
 Chaque feuille de calcul d'un fichier Excel peut être convertie en différents formats d'image, appelez[Options d'image ou d'impression](https://reference.aspose.com/cells/python-net/aspose.cells.rendering/imageorprintoptions/) .setImageFormat pour définir le format de l'image.
{{% blocks/products/pf/feature-page-code h3="Python Code pour la conversion d\'Excel en image" %}}
```cs
// load template spreadsheet
workbook = Workbook("template.xlsx")
// create & set an instance of ImageOrPrintOptions
options = ImageOrPrintOptions()
// set output image format
options.setImageFormat(ImageFormat.getPng())
// create SheetRender for first worksheet in the collection
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// render worksheet to image
sr.toImage(0, "output.jpg")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir Excel en Word & PowerPoint" %}}
 Il est possible de charger n'importe quelle feuille de calcul et de la convertir en fichiers Word DOCX & PowerPoint PPTX tout en utilisant[DocxSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/docxsaveoptions/) & [PptxSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/pptxsaveoptions/)classes comme démontré ci-dessous.
{{% blocks/products/pf/feature-page-code h3="Code Python pour Excel vers Word et conversion PowerPoint" %}}
```cs
// load the template file
workbook = Workbook("template.xlsx")

// save spreadsheet as DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// save spreadsheet as PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx" >}}
