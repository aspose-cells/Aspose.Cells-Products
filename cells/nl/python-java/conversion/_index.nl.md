---
title: Microsoft Excel-bestandsconversie via Python 

description: Converteer Excel XLS, XLSX, ODS, CSV naar PDF, XPS, HTML, JPEG, HTML en vele andere populaire formaten met slechts enkele regels Python code.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-formaatconversie via Python" h2="Importeer en exporteer Excel-bestanden als spreadsheet-, web-, afbeeldings- en vaste-layoutformaten" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel Library versnelt de programmeer- en conversieprocessen van spreadsheets en ondersteunt populaire indelingen zoals XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML en ODS. Het maakt het ook mogelijk om Excel-bestanden te exporteren naar PDF, XPS, HTML, MHTML, platte tekst en populaire afbeeldingsformaten zoals TIFF, JPG, PNG, BMP en SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar XLSX, ODS, SXC & FODS" %}}
Interconversie van spreadsheetformaat vereist alleen het laden van een spreadsheet met een instantie van [Werkboek](https://reference.aspose.com/cells/python/asposecells.api/Workbook) en terug opslaan in het gewenste formaat terwijl u de juiste waarde selecteert uit [OpslaanFormaat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) opsomming.
{{% blocks/products/pf/feature-page-code h3="Python Code voor conversie van Excel-bestandsindeling" %}}

```cs
// laad het sjabloonbestand
workbook = Workbook("Book1.xls")
  
// opslaan als XLSX-, ODS-, SXC- en FODS-indelingen
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar PDF, XPS, HTML & MD" %}}
Er zijn gespecialiseerde klassen beschikbaar om het conversieproces voor specifieke uitvoerformaten te regelen, zoals: [PdfOpslaanOpties](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) om Excel-bestanden als PDF te exporteren, [XpsSave-opties](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) voor Excel naar XPS-conversie, [HtmlOpslaanOpties](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) om Excel weer te geven als HTML en [MarkdownOpslaanOpties](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) voor Excel naar Markdown-conversie. 
{{% blocks/products/pf/feature-page-code h3="Python Code voor Excel naar PDF en webformaten" %}}

```cs
// laad sjabloon Excel-bestand van schijf
book = Workbook("template.xlsx")

// sla Excel op in PDF_A_1_B-formaat
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// sla Excel op in XPS met 1 pagina per werkblad
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// sla Excel op in HTML met afbeeldingen als Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// sla Excel op in Markdown (MD) met behoud van celopmaak
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer JSON naar Excel en Excel naar JSON" %}}
Python ontwikkelaars kunnen eenvoudig JSON-bestanden laden en converteren naar Excel in slechts een paar regels code. Evenzo kunnen Excel-gegevens worden geëxporteerd naar JSON-gegevens.
{{% blocks/products/pf/feature-page-code h3="Python Code voor JSON naar Excel-conversie" %}}
```cs
//Laad uw bron-json-bestand
workbook = Workbook("Data.json")
//bestand opslaan in xlsx-formaat
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Code voor Excel naar JSON-conversie" %}}
```cs
//Laad je bron xlsx-bestand
workbook = Workbook("input.xlsx")
//bestand opslaan in json-formaat
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer Excel-werkbladen naar JPG, BMP, PNG & GIF" %}}
Elk werkblad van een Excel-bestand kan worden geconverteerd naar verschillende afbeeldingsformaten, bel [AfbeeldingOfAfdrukopties](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat om het afbeeldingsformaat in te stellen. 
{{% blocks/products/pf/feature-page-code h3="Python Code voor conversie van Excel naar afbeelding" %}}
```cs
// laad sjabloonspreadsheet
workbook = Workbook("template.xlsx")
// maak en stel een instantie van ImageOrPrintOptions in
options = ImageOrPrintOptions()
// uitvoerbeeldformaat instellen
options.setImageFormat(ImageFormat.getPng())
// maak SheetRender voor het eerste werkblad in de verzameling
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// werkblad naar afbeelding renderen
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converteer Excel naar Word & PowerPoint" %}}
Het is mogelijk om elke spreadsheet te laden en deze te converteren naar Word DOCX & PowerPoint PPTX-bestanden tijdens gebruik [DocxSave-opties](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxOpslaanOpties](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) klassen zoals hieronder getoond.
{{% blocks/products/pf/feature-page-code h3="Python code voor conversie van Excel naar Word en PowerPoint" %}}
```cs
// laad het sjabloonbestand
workbook = Workbook("template.xlsx")

// spreadsheet opslaan als DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// spreadsheet opslaan als PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
