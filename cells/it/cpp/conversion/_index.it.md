---
title: Conversione file Microsoft Excel tramite C++ 
url: /it/cpp/conversion/
description: Converti Excel XLS, XLSX, ODS, CSV in PDF, XPS, HTML, JPEG e altri formati con poche righe di codice C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversione di documenti Microsoft<sup>&reg;</sup> Excel tramite C++" h2="Salva i file Microsoft<sup>&reg;</sup> Excel come fogli di calcolo, Web, immagini e formati a layout fisso" >}}

{{% blocks/products/pf/feature-page-summary %}}
Per qualsiasi applicazione o soluzione di conversione di fogli di lavoro, **C++ Libreria Excel** accelera i processi di codifica, automazione e conversione mentre gestisce più file, inclusi XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Consente inoltre di **convertire Excel in PDF**, XPS, HTML, MHTML, testo normale e immagini popolari come JPG, TIFF, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inter-conversione di formati Microsoft Excel" %}}
L'inter-conversione del formato del foglio di calcolo richiede solo il caricamento di un foglio di calcolo con un'istanza di [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) puntatore e salvando nuovamente nel formato desiderato utilizzando [Salva](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) metodo di [Classe di Cartella di lavoro](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Codice di esempio per la conversione del formato file Excel" %}}

```cs

// Carica il formato excel di origine.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Salva nel formato di output richiesto.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converti i formati Excel in PDF con le impostazioni del livello di conformità" %}}
C++ Excel Automation API supporta la conversione di cartelle di lavoro in PDF e supporta l'impostazione del livello di conformità e della data di creazione. Gli sviluppatori possono utilizzare [IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) insieme a [Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) per impostare la conformità PDF. Per la conversione, API metodo di salvataggio con PdfSaveOptions come parametro e percorso del file di output specificato. 
{{% blocks/products/pf/feature-page-code h3="C++ Codice di esempio per la conversione da Excel a PDF" %}}

```cs
// Carica il file Excel di esempio.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Crea oggetto opzioni di salvataggio pdf.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Impostare la conformità su PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// o PdfCompliance_PdfA1a 
// per il normale PDF sarà PdfCompliance_None

// Salva il documento Excel in formato PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Salva Excel in immagini" %}}
**C++ Excel Parser** ha la capacità di esportare dati sotto forma di immagini. Ogni foglio di lavoro può essere convertito in diversi formati di immagine inclusi BMP, JPEG, PNG e GIF, impostati dal [Rendering::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Per qualsiasi caso **Converti Excel in immagini**, seleziona il caso pertinente dai collegamenti.
{{% blocks/products/pf/feature-page-code h3="C++ Codice per la conversione da Excel a immagine" %}}

```cs
// Percorso della directory di output.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Carica l'XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Accedi al primo foglio di lavoro.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Crea un'immagine o un oggetto delle opzioni di stampa.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Specificare il formato dell'immagine. Sotto il codice è per JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Per altre immagini come GIF, BMP e PNG è possibile utilizzare rispettivamente GetGif(), GetBmp() e GetPng() 

// Specificare la risoluzione orizzontale e verticale
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Rendering del foglio rispetto all'immagine specificata o alle opzioni di stampa.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Ottieni il conteggio delle pagine.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Crea un oggetto generatore di stringhe per le concatenazioni di stringhe.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Esegui il rendering di ogni pagina in un'immagine jpeg una per una.
for (int i = 0; i < pageCount; i++){
	// Cancella il generatore di stringhe e crea il percorso dell'immagine di output con concatenazioni di stringhe.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Ottieni il percorso dell'immagine di output.
	StringPtr outputJPEG = sb->ToString();
	// Converti foglio di lavoro in immagine.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}