---
title:  Microsoft Conversion de fichiers Excel via C++
description: Aspose.Cells for C++ bibliothèque. Convertissez les formats EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG et plus avec seulement quelques lignes de code C++.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversion de documents Excel via C++" h2="Enregistrez Microsoft<sup>&reg;</sup> fichiers Excel aux formats tableur, Web, image et mise en page fixe." >}}

{{% blocks/products/pf/feature-page-summary %}}
 Pour toute application ou solution de conversion de feuille de calcul,**C++ Bibliothèque Excel** accélère les processus de codage, d'automatisation et de conversion tout en gérant plusieurs fichiers, notamment XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Il permet également de *convertir Excel en PDF**, XPS, HTML, MHTML, Uni Texte et images populaires telles que JPG, TIFF, PNG, BMP et SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inter-conversion des formats Excel Microsoft" %}}
 La conversion entre les formats de feuille de calcul nécessite uniquement de charger la feuille de calcul à l'aide du[Cahier d'exercices](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) classe et de la réenregistrer dans le format requis à l'aide du[Sauvegarder](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) méthode du[Cahier d'exercices](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) classe.
{{% blocks/products/pf/feature-page-code h3="C++ Exemple de code pour la conversion du format de fichier Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Convertir les formats Excel en PDF avec les paramètres de niveau de conformité" %}}
C++ Excel Automation API prend en charge la conversion des classeurs en PDF ainsi que la définition du niveau de conformité et de la date de création. Les développeurs peuvent utiliser[Options d'enregistrement PDF](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) avec[Aspose : Cells : Rendu](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) pour définir la conformité PDF. Pour la conversion, méthode de sauvegarde API ayant PdfSaveOptions comme paramètre et chemin de fichier de sortie spécifié.
{{% blocks/products/pf/feature-page-code h3="C++ Exemple de code pour la conversion Excel vers PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Enregistrer Excel dans des images" %}}
**C++ Analyseur Excel** a la possibilité d’exporter des données sous forme d’images. Chaque feuille de calcul peut être convertie en différents formats d'image, notamment BMP, JPEG, PNG et GIF, définis par le[Rendu ::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Pour toute**Convertir Excel en images** cas, sélectionnez le cas pertinent à partir des liens.
{{% blocks/products/pf/feature-page-code h3="C++ Code pour la conversion d\'Excel en image" %}}

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
