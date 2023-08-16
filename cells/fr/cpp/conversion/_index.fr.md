---
title:  Microsoft Conversion de fichier Excel via C++
description: Convertissez Excel XLS, XLSX, ODS, CSV en PDF, XPS, HTML, JPEG et d'autres formats avec seulement quelques lignes de code C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversion de documents Excel via C++" h2="Enregistrez les fichiers Excel Microsoft<sup>&reg;</sup> sous forme de feuille de calcul, Web, image et mise en page fixe" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Pour toute application ou solution de conversion de tableur,**C++ Bibliothèque Excel** accélère les processus de codage, d'automatisation et de conversion tout en gérant plusieurs fichiers, notamment XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Il permet également de * convertir Excel à PDF**, XPS, HTML, MHTML, Uni Texte et images populaires telles que JPG, TIFF, PNG, BMP et SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inter-conversion des formats Excel Microsoft" %}}
 L'inter-conversion du format de feuille de calcul nécessite uniquement le chargement d'une feuille de calcul avec une instance de[ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) pointeur et réenregistrer au format souhaité à l'aide de[Sauvegarder](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) méthode de[Classe IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Exemple de code pour la conversion du format de fichier Excel" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Convertir les formats Excel en PDF avec les paramètres de niveau de conformité" %}}
 C++ Excel Automation API prend en charge la conversion des classeurs en PDF ainsi que le réglage du niveau de conformité et de la date de création. Les développeurs peuvent utiliser[IPdfSaveOptionsIPdfSaveOptionsIPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) avec[Aspose :: Cells :: Rendu](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) pour définir la conformité PDF. Pour la conversion, API enregistrez la méthode ayant PdfSaveOptions comme paramètre et le chemin du fichier de sortie spécifié.
{{% blocks/products/pf/feature-page-code h3="C++ Exemple de code pour la conversion d\'Excel en PDF" %}}

```cs
// Load the sample Excel file.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Create pdf save options object.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Set the compliance to PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// or PdfCompliance_PdfA1a 
// for normal PDF it will be PdfCompliance_None

// Save the Excel Document in PDF format
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Enregistrer Excel dans les images" %}}
**C++ Analyseur Excel** a la capacité d'exporter des données sous forme d'images. Chaque feuille de calcul peut être convertie en différents formats d'image, y compris BMP, JPEG, PNG et GIF, définis par le[Rendu ::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . Pour toute**Convertir Excel en images** cas, sélectionnez le cas pertinent à partir des liens.
{{% blocks/products/pf/feature-page-code h3="C++ Code pour la conversion d\'Excel en image" %}}

```cs
// Output directory path.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Load the XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Access first worksheet.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Create image or print options object.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Specify the image format. Below code is for JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// For other images like GIF, BMP and PNG one can use GetGif(), GetBmp() and GetPng() respectively 

// Specify horizontal and vertical resolution
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Get page count.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Create string builder object for string concatenations.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++){
	// Clear string builder and create output image path with string concatenations.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Get the output image path.
	StringPtr outputJPEG = sb->ToString();
	// Convert worksheet to image.
	sr->ToImage(i, outputJPEG);
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
