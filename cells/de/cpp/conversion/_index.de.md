---
title: Microsoft Excel-Dateikonvertierung über C++ 

description: Konvertieren Sie Excel XLS, XLSX, ODS, CSV in PDF, XPS, HTML, JPEG und andere Formate mit nur wenigen Zeilen C++-Code.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertierung von Microsoft<sup>&reg;</sup> Excel-Dokumenten über C++" h2="Speichern Sie Microsoft<sup>&reg;</sup> Excel-Dateien als Tabellenkalkulations-, Web-, Bild- und feste Layoutformate" >}}

{{% blocks/products/pf/feature-page-summary %}}
**C++ Excel Library** beschleunigt für jede Tabellenkalkulationsanwendung oder -lösung Codierungs-, Automatisierungs- und Konvertierungsprozesse und verarbeitet gleichzeitig mehrere Dateien, einschließlich XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Es ermöglicht auch die **Konvertierung von Excel in PDF**, XPS, HTML, MHTML, einfachen Text und beliebte Bilder wie JPG, TIFF, PNG, BMP und SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Zwischenkonvertierung von Microsoft Excel-Formaten" %}}
Die Konvertierung des Tabellenkalkulationsformats erfordert nur das Laden einer Tabellenkalkulation mit einer Instanz von [ aufdringlicher_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) Zeiger und speichern Sie mit im gewünschten Format zurück [Speichern](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) Methode von [IWorkbook-Klasse](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Beispielcode für die Konvertierung des Excel-Dateiformats" %}}

```cs

// Laden Sie das Excel-Quellformat.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Im erforderlichen Ausgabeformat speichern.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie Excel-Formate in PDF mit Compliance-Level-Einstellungen" %}}
C++ Excel-Automatisierung API unterstützt die Konvertierung von Arbeitsmappen in PDF sowie die Einstellung von Konformitätsstufe und Erstellungsdatum. Entwickler können verwenden [IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) zusammen mit [Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) um die PDF-Kompatibilität einzustellen. Für die Konvertierung API save-Methode mit PdfSaveOptions als Parameter und angegebenem Ausgabedateipfad. 
{{% blocks/products/pf/feature-page-code h3="C++ Beispielcode für die Umwandlung von Excel in PDF" %}}

```cs
// Laden Sie die Beispiel-Excel-Datei.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Erstellen Sie ein Objekt mit PDF-Speicheroptionen.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Legen Sie die Konformität auf PDF/A-1b fest.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// oder PdfCompliance_PdfA1a 
// für normales PDF ist es PdfCompliance_None

// Speichern Sie das Excel-Dokument im PDF-Format
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Speichern Sie Excel in Bilder" %}}
**C++ Excel Parser** kann Daten in Form von Bildern exportieren. Jedes Arbeitsblatt kann in verschiedene Bildformate konvertiert werden, einschließlich BMP, JPEG, PNG und GIF, die von eingestellt werden [Rendering::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Wählen Sie für jeden **Excel in Bilder konvertieren**-Fall den entsprechenden Fall aus den Links aus.
{{% blocks/products/pf/feature-page-code h3="C++ Code für Excel-zu-Bild-Konvertierung" %}}

```cs
// Verzeichnispfad ausgeben.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Laden Sie den XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Greifen Sie auf das erste Arbeitsblatt zu.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Bild- oder Druckoptionsobjekt erstellen.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Geben Sie das Bildformat an. Der folgende Code ist für JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Für andere Bilder wie GIF, BMP und PNG kann man GetGif(), GetBmp() bzw. GetPng() verwenden 

// Legen Sie die horizontale und vertikale Auflösung fest
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Rendern Sie das Blatt in Bezug auf die angegebenen Bild- oder Druckoptionen.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Seitenzahl erhalten.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Erstellen Sie ein String-Builder-Objekt für String-Verkettungen.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Rendern Sie jede Seite einzeln als JPEG-Bild.
for (int i = 0; i < pageCount; i++){
	// Löschen Sie den String-Builder und erstellen Sie den Ausgabebildpfad mit String-Verkettungen.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Rufen Sie den Ausgabebildpfad ab.
	StringPtr outputJPEG = sb->ToString();
	// Arbeitsblatt in Bild umwandeln.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
