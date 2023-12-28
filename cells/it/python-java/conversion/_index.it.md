---
title: Microsoft Conversione file Excel utilizzando Python via Java
description: Aspose.Cells for Python via Java biblioteca. Converti EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL e altri formati con solo poche righe di codice Python.
keywords: [Python Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Python]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversione formato Excel tramite Python" h2="Importa ed esporta file Excel come formati di fogli di calcolo, Web, immagini e layout fisso" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python La libreria Excel accelera i processi di programmazione e conversione dei fogli di calcolo supportando i formati più diffusi tra cui XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS Permette anche di esportare file Excel in PDF, XPS, HTML, MHTML, Plain Formati di testo e immagini popolari come TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converti Excel in XLSX, ODS, SXC e FODS" %}}
 L'interconversione del formato del foglio di calcolo richiede solo il caricamento di un foglio di calcolo con un'istanza di[Cartella di lavoro](https://reference.aspose.com/cells/python/asposecells.api/Workbook) e salvare nuovamente nel formato desiderato selezionando il valore appropriato da[Salva formato](https://reference.aspose.com/cells/python/asposecells.api/saveformat) enumerazione.
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
 Sono disponibili classi specializzate per controllare il processo di conversione per formati di output specifici come[PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) per esportare file Excel come PDF,[XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) per la conversione da Excel a XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) per rendere Excel come HTML e[MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) per la conversione da Excel a Markdown.
{{% blocks/products/pf/feature-page-code h3="Python Codice per formati Excel fino a PDF e Web" %}}

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
Gli sviluppatori Python possono caricare e convertire facilmente i file JSON in Excel in poche righe di codice. Allo stesso modo, i dati Excel possono essere esportati nei dati JSON.
{{% blocks/products/pf/feature-page-code h3="Python Codice per la conversione da JSON a Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Codice per Excel in JSON Conversione" %}}
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
 Ogni foglio di lavoro di un file Excel può essere convertito in diversi formati di immagine, call[OpzioniImmagineOrStampa](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat per impostare il formato dell'immagine.
{{% blocks/products/pf/feature-page-code h3="Python Codice per conversione Excel in immagine" %}}
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
È possibile caricare qualsiasi foglio di calcolo e convertirlo nei file Word DOCX e PowerPoint PPTX durante l'utilizzo[DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) classi come illustrato di seguito.
{{% blocks/products/pf/feature-page-code h3="Codice Python per la conversione da Excel a Word e PowerPoint" %}}
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
