---
title: Microsoft Excel-bestandsconversie met behulp van Python via NET
description: Converteer Excel XLS, XLSX, ODS, CSV naar PDF, XPS, HTML, JPEG, HTML en vele andere populaire formaten met slechts enkele regels code Python .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversie Excel-indeling via Python" h2="Importeer en exporteer Excel-bestanden als spreadsheet-, web-, afbeeldings- en vaste lay-outindelingen" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel Library versnelt het programmeren en converteren van spreadsheets en ondersteunt populaire indelingen, waaronder XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07619348 1. Het maakt het ook mogelijk om Excel-bestanden te exporteren naar PDF, XPS, HTML, MHTML, gewoon Tekst en populaire beeldformaten zoals TIFF, JPG, PNG, BMP en SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar XLSX, ODS, SXC & FODS" %}}
 Inter-conversie van spreadsheetformaat vereist alleen het laden van een spreadsheet met een instantie van[Werkboek](https://reference.aspose.com/cells/python-net/aspose.cells/workbook/) en opslaan in het gewenste formaat terwijl u de juiste waarde selecteert uit[Formaat opslaan](https://reference.aspose.com/cells/python-net/aspose.cells/saveformat/) opsomming.
{{% blocks/products/pf/feature-page-code h3="Python Code voor conversie van Excel-bestandsindelingen" %}}

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


{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar PDF, XPS, HTML & MD" %}}
 Gespecialiseerde klassen zijn beschikbaar om het conversieproces voor specifieke uitvoerformaten zoals[PdfSaveOpties](https://reference.aspose.com/cells/python-net/aspose.cells/pdfsaveoptions/) om Excel-bestanden te exporteren als PDF,[XpsSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/xpssaveoptions/) voor Excel naar XPS conversie,[HtmlSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/htmlsaveoptions/) om Excel weer te geven als HTML en[MarkdownSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/markdownsaveoptions/) voor conversie van Excel naar Markdown.
{{% blocks/products/pf/feature-page-code h3="Python Code voor Excel naar PDF en webformaten" %}}

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

{{% blocks/products/pf/feature-page-section h2="Converteer JSON naar Excel en Excel naar JSON" %}}
Python-ontwikkelaars kunnen eenvoudig JSON-bestanden laden en converteren naar Excel in slechts een paar regels code. Evenzo kunnen Excel-gegevens worden geëxporteerd naar JSON-gegevens.
{{% blocks/products/pf/feature-page-code h3="Python Code voor JSON naar Excel-conversie" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Code voor Excel naar JSON Conversie" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer Excel-werkbladen naar JPG, BMP, PNG & GIF" %}}
 Elk werkblad van een Excel-bestand kan worden geconverteerd naar verschillende afbeeldingsindelingen, bel[ImageOrPrintOptions](https://reference.aspose.com/cells/python-net/aspose.cells.rendering/imageorprintoptions/) .setImageFormat om het afbeeldingsformaat in te stellen.
{{% blocks/products/pf/feature-page-code h3="Python Code voor conversie van Excel naar afbeelding" %}}
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

{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar Word & PowerPoint" %}}
 Het is mogelijk om elke spreadsheet te laden en te converteren naar Word DOCX & PowerPoint PPTX bestanden tijdens het gebruik[DocxSaveOpties](https://reference.aspose.com/cells/python-net/aspose.cells/docxsaveoptions/) & [PptxSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/pptxsaveoptions/) klassen zoals hieronder aangetoond.
{{% blocks/products/pf/feature-page-code h3="Python code voor Excel naar Word & PowerPoint Conversie" %}}
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
