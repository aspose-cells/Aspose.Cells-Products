---
title: Conversione file Microsoft Excel tramite Python 
url: /it/python/conversion/
description: Converti Excel XLS, XLSX, ODS, CSV in PDF, XPS, HTML, JPEG, HTML e molti altri formati popolari con poche righe di codice Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversione del formato Microsoft<sup>&reg;</sup> Excel tramite Python" h2="Importa ed esporta file Excel come fogli di calcolo, Web, immagini e formati a layout fisso" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python La libreria Excel velocizza i processi di conversione e programmazione dei fogli di lavoro, supportando al contempo i formati più diffusi tra cui XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Consente inoltre di esportare file Excel in PDF, XPS, HTML, MHTML, testo normale e formati di immagine popolari come TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converti Excel in XLSX, ODS, SXC e FODS" %}}
L'inter-conversione del formato del foglio di calcolo richiede solo il caricamento di un foglio di calcolo con un'istanza di [Cartella di lavoro](https://reference.aspose.com/cells/python/asposecells.api/Workbook) e salvando nuovamente nel formato desiderato selezionando il valore appropriato da [Salva formato](https://reference.aspose.com/cells/python/asposecells.api/saveformat) enumerazione.
{{% blocks/products/pf/feature-page-code h3="Python Codice per la conversione del formato file Excel" %}}

```cs
// caricare il file modello
workbook = Workbook("Book1.xls")
  
// salva come formati XLSX, ODS, SXC e FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converti Excel in PDF, XPS, HTML e MD" %}}
Sono disponibili classi specializzate per controllare il processo di conversione per formati di output specifici come [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) per esportare file Excel come PDF, [XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) per la conversione da Excel a XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) per rendere Excel come HTML e [MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) per la conversione da Excel a Markdown. 
{{% blocks/products/pf/feature-page-code h3="Python Codice per formati da Excel a PDF e Web" %}}

```cs
// carica il file Excel del modello dal disco
book = Workbook("template.xlsx")

// salva Excel in formato PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// salva Excel in XPS con 1 pagina per foglio di lavoro
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// salva Excel in HTML con immagini come Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// salva Excel in Markdown (MD) mantenendo la formattazione della cella
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converti JSON in Excel ed Excel in JSON" %}}
Python gli sviluppatori possono caricare e convertire facilmente i file JSON in Excel in poche righe di codice. Allo stesso modo, i dati di Excel possono essere esportati in dati JSON.
{{% blocks/products/pf/feature-page-code h3="Python Codice per la conversione da JSON a Excel" %}}
```cs
//Carica il tuo file json di origine
workbook = Workbook("Data.json")
//salva il file in formato xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Codice per la conversione da Excel a JSON" %}}
```cs
//Carica il tuo file xlsx di origine
workbook = Workbook("input.xlsx")
//salva il file in formato json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Converti fogli di lavoro Excel in JPG, BMP, PNG e GIF" %}}
Ogni foglio di lavoro di un file Excel può essere convertito in diversi formati di immagine, chiama [Opzioni immagine o stampa](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat per impostare il formato dell'immagine. 
{{% blocks/products/pf/feature-page-code h3="Python Codice per la conversione da Excel a immagine" %}}
```cs
// caricare il foglio di calcolo del modello
workbook = Workbook("template.xlsx")
// creare e impostare un'istanza di ImageOrPrintOptions
options = ImageOrPrintOptions()
// imposta il formato dell'immagine di output
options.setImageFormat(ImageFormat.getPng())
// crea SheetRender per il primo foglio di lavoro nella raccolta
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// renderizzare il foglio di lavoro all'immagine
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converti Excel in Word e PowerPoint" %}}
È possibile caricare qualsiasi foglio di calcolo e convertirlo in file Word DOCX e PowerPoint PPTX durante l'utilizzo [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [Opzioni di salvataggio Pptx](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) classi come illustrato di seguito.
{{% blocks/products/pf/feature-page-code h3="Python codice per la conversione da Excel a Word e PowerPoint" %}}
```cs
// caricare il file modello
workbook = Workbook("template.xlsx")

// salva il foglio di calcolo come DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// salva il foglio di calcolo come PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}