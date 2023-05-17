---
title: Microsoft Conversione file Excel utilizzando Python via NET
description: Converti Excel XLS, XLSX, ODS, CSV a PDF, XPS, HTML, JPEG, HTML e molti altri formati popolari con solo poche linee di 07613481, JPEG, HTML e molti altri formati popolari con solo poche linee di 07613481, JPEG, HTML e molti altri formati popolari con solo poche linee di 0761681, Codice.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversione formato Excel tramite Python" h2="Importa ed esporta file Excel come fogli di calcolo, Web, immagini e formati a layout fisso" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel Library velocizza la programmazione dei fogli di calcolo e i processi di conversione supportando i formati più diffusi tra cui XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07619348 1. Consente inoltre di esportare file Excel in PDF, XPS, HTML, MHTML, Plain Testo e formati immagine popolari come TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converti Excel in XLSX, ODS, SXC e FODS" %}}
 L'inter-conversione del formato del foglio di calcolo richiede solo il caricamento di un foglio di calcolo con un'istanza di[Cartella di lavoro](https://reference.aspose.com/cells/python-net/aspose.cells/workbook/) e salvare nuovamente nel formato desiderato mentre si seleziona il valore appropriato da[SalvaFormato](https://reference.aspose.com/cells/python-net/aspose.cells/saveformat/) enumerazione.
{{% blocks/products/pf/feature-page-code h3="Python Codice per Conversione Formato File Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Converti Excel in PDF, XPS, HTML e MD" %}}
 Sono disponibili classi specializzate per controllare il processo di conversione per formati di output specifici come[PdfSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/pdfsaveoptions/) per esportare file Excel come PDF,[XpsSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/xpssaveoptions/) per la conversione da Excel a XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/htmlsaveoptions/) per rendere Excel come HTML e[MarkdownSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/markdownsaveoptions/) per la conversione da Excel a Markdown.
{{% blocks/products/pf/feature-page-code h3="Python Codice per Excel a PDF e formati Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Converti JSON in Excel ed Excel in JSON" %}}
Gli sviluppatori Python possono facilmente caricare e convertire i file JSON in Excel in poche righe di codice. Allo stesso modo, i dati Excel possono essere esportati nei dati JSON.
{{% blocks/products/pf/feature-page-code h3="Python Codice per la conversione da JSON a Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Codice per conversione da Excel a JSON" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Converti fogli di lavoro Excel in JPG, BMP, PNG e GIF" %}}
 Ogni foglio di lavoro di un file Excel può essere convertito in diversi formati di immagine, chiama[ImageOrPrintOptions](https://reference.aspose.com/cells/python-net/aspose.cells.rendering/imageorprintoptions/) .setImageFormat per impostare il formato dell'immagine.
{{% blocks/products/pf/feature-page-code h3="Python Codice per la conversione da Excel a immagine" %}}
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

{{% blocks/products/pf/feature-page-section h2="Converti Excel in Word e PowerPoint" %}}
 È possibile caricare qualsiasi foglio di calcolo e convertirlo in file Word DOCX e PowerPoint PPTX durante l'utilizzo[DocxSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/docxsaveoptions/) & [PptxSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/pptxsaveoptions/) classi come illustrato di seguito.
{{% blocks/products/pf/feature-page-code h3="Python codice per conversione da Excel a Word e PowerPoint" %}}
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
