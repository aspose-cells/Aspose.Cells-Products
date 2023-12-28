---
title:  Microsoft Conversione file Excel tramite C++
description: Aspose.Cells for C++ biblioteca. Converti EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG e altri formati con solo poche righe di codice C++.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversione documenti Excel tramite C++" h2="Salva i file Excel Microsoft<sup>&reg;</sup> nei formati foglio di calcolo, Web, immagine e layout fisso" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Per qualsiasi applicazione o soluzione di conversione di fogli di calcolo,**C++ Libreria Excel** accelera i processi di codifica, automazione e conversione durante la gestione di più file tra cui XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Consente inoltre di *convertire Excel in PDF**, XPS, HTML, MHTML, Semplice Testo e immagini popolari come JPG, TIFF, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversione dei formati Excel Microsoft" %}}
 La conversione tra formati di foglio di calcolo richiede solo il caricamento del foglio di calcolo utilizzando il file[Cartella di lavoro](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) class e salvandola nuovamente nel formato richiesto utilizzando il file[Salva](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) metodo del[Cartella di lavoro](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) classe.
{{% blocks/products/pf/feature-page-code h3="C++ Codice di esempio per la conversione del formato file Excel" %}}

```cpp

Aspose::Cells::Startup();

// Load the source excel format.
Workbook wkb(u"src_excel_file.xls");
// Save in required output format.
wkb.Save(u"output_excel_format.xlsx", SaveFormat::Xlsx);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converti formati Excel in PDF con le impostazioni del livello di conformità" %}}
C++ Excel Automation API supporta la conversione delle cartelle di lavoro in PDF oltre a supportare l'impostazione del livello di conformità e della data di creazione. Gli sviluppatori possono utilizzare[PdfSaveOptions](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) insieme a[Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) per impostare la conformità PDF. Per la conversione, metodo di salvataggio API con PdfSaveOptions come parametro e percorso del file di output specificato.
{{% blocks/products/pf/feature-page-code h3="C++ Codice di esempio per la conversione da Excel a PDF" %}}

```cpp

Aspose::Cells::Startup();

// Load the sample Excel file.
Workbook wkb(u"sample-convert-excel-to.pdf");
// Create pdf save options object.
PdfSaveOptions pdfSaveOptions;

// Set the compliance to PDF/A-1b.
pdfSaveOptions.SetCompliance(PdfCompliance::PdfA1b);

// or PdfCompliance::PdfA1a
// for normal PDF it will be PdfCompliance::None

// Save the Excel Document in PDF format
wkb.Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Salva Excel in immagini" %}}
**C++ Analizzatore Excel** ha la capacità di esportare dati sotto forma di immagini. Ogni foglio di lavoro può essere convertito in diversi formati immagine tra cui BMP, JPEG, PNG e GIF, impostati dal[Rendering::OpzioniImmagineOrStampa](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Per ogni**Converti Excel in immagini** caso, selezionare il caso rilevante dai link.
{{% blocks/products/pf/feature-page-code h3="C++ Codice per conversione Excel in immagine" %}}

```cpp

Aspose::Cells::Startup();

// Load the XLSX.
Aspose::Cells::Workbook wkb(u"source-excel-file.xlsx");

// Access first worksheet.
Aspose::Cells::Worksheet wks = wkb.GetWorksheets().Get(0);

// Create image or print options object.
Aspose::Cells::Rendering::ImageOrPrintOptions imgOptions;

// Specify the image format. Below code is for JPEG
imgOptions.SetImageType(ImageType::Jpeg);

// For other images like GIF, BMP and PNG one can use ImageType::Gif, ImageType::Bmp and ImageType::Png respectively 

// Specify horizontal and vertical resolution
imgOptions.SetHorizontalResolution(200);
imgOptions.SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
Aspose::Cells::Rendering::SheetRender sr(wks, imgOptions);

// Get page count.
int pageCount = sr.GetPageCount();

std::string sb = "";
// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++) {
	sb = ""; 
	sb += "ImagesOutputDirectoryPath/";
	sb += "outputConvertingWorksheetToImageJPEG_";
	sb += std::to_string(i);
	sb += ".jpeg";
	// Get the output image path.
	U16String outputJPEG(sb.c_str());
	// Convert worksheet to image.
	sr.ToImage(i, outputJPEG);
}

Aspose::Cells::Cleanup();
	
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
