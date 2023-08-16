---
title: Microsoft Excel-Dateikonvertierung mit Python via Java
description: Konvertieren Sie Excel XLS, XLSX, ODS, CSV in PDF, XPS, HTML, JPEG, HTML und viele andere beliebte Formate mit nur wenigen Zeilen Python-Code .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-Formatkonvertierung über Python" h2="Importieren und exportieren Sie Excel-Dateien als Tabellenkalkulations-, Web-, Bild- und feste Layoutformate" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Die Excel-Bibliothek beschleunigt die Programmierung und Konvertierung von Tabellenkalkulationen und unterstützt gleichzeitig gängige Formate wie XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 076193 481. Es ermöglicht auch den Export von Excel-Dateien nach PDF, XPS, HTML, MHTML, Plain Text- und gängige Bildformate wie TIFF, JPG, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in XLSX, ODS, SXC und FODS" %}}
 Für die gegenseitige Konvertierung des Tabellenformats ist lediglich das Laden einer Tabelle mit einer Instanz von erforderlich[Arbeitsmappe](https://reference.aspose.com/cells/python/asposecells.api/Workbook) und Speichern im gewünschten Format zurück, während Sie den entsprechenden Wert aus auswählen[SaveFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) Aufzählung.
{{% blocks/products/pf/feature-page-code h3="Python Code für die Konvertierung des Excel-Dateiformats" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in PDF, XPS, HTML und MD" %}}
 Es stehen spezielle Klassen zur Verfügung, um den Konvertierungsprozess für bestimmte Ausgabeformate zu steuern, z[PDFSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) um Excel-Dateien als PDF zu exportieren,[XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) für die Konvertierung von Excel in XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) um Excel als HTML darzustellen und[MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) für die Konvertierung von Excel in Markdown.
{{% blocks/products/pf/feature-page-code h3="Python Code für Excel bis PDF und Webformate" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie JSON in Excel und Excel in JSON" %}}
Python-Entwickler können JSON-Dateien problemlos in nur wenigen Codezeilen laden und in Excel konvertieren. Ebenso können Excel-Daten in JSON-Daten exportiert werden.
{{% blocks/products/pf/feature-page-code h3="Python Code für die Konvertierung von JSON in Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python-Code für Excel in JSON-Konvertierung" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Arbeitsblätter in JPG, BMP, PNG und GIF" %}}
 Jedes Arbeitsblatt einer Excel-Datei kann in verschiedene Bildformate konvertiert werden[ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions) .setImageFormat zum Festlegen des Bildformats.
{{% blocks/products/pf/feature-page-code h3="Python Code für die Konvertierung von Excel in Bilder" %}}
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

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel in Word & PowerPoint" %}}
 Es ist möglich, jede Tabellenkalkulation zu laden und sie während der Verwendung in Word-Dateien DOCX und PowerPoint PPTX zu konvertieren[DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions)Klassen wie unten gezeigt.
{{% blocks/products/pf/feature-page-code h3="Python-Code für Excel in Word und PowerPoint-Konvertierung" %}}
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

{{< blocks/products/pf/feature-page-options pairs="xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx" >}}
