---
title: Conversion de fichiers Microsoft Excel via C++ 
url: /fr/cpp/conversion/
description: Convertissez Excel XLS, XLSX, ODS, CSV en PDF, XPS, HTML, JPEG et autres formats avec seulement quelques lignes de code C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversion de documents Microsoft<sup>&reg;</sup> Excel via C++" h2="Enregistrez les fichiers Excel Microsoft<sup>®</sup> sous forme de feuilles de calcul, Web, d\'image et de mise en page fixe" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pour toute application ou solution de conversion de feuille de calcul, **C++ Bibliothèque Excel** accélère les processus de codage, d'automatisation et de conversion tout en gérant plusieurs fichiers, notamment XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Il permet également de **convertir Excel en PDF**, XPS, HTML, MHTML, texte brut et images populaires telles que JPG, TIFF, PNG, BMP et SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inter-conversion des formats Microsoft Excel" %}}
L'inter-conversion du format de feuille de calcul nécessite uniquement le chargement d'une feuille de calcul avec une instance de [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) pointeur et réenregistrer au format souhaité à l'aide de [Sauver](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) méthode de [Classe IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Exemple de code pour la conversion du format de fichier Excel" %}}

```cs

// Chargez le format Excel source.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Enregistrez dans le format de sortie requis.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Convertir des formats Excel en PDF avec les paramètres de niveau de conformité" %}}
C++Excel AutomationAPI prend en charge la conversion des classeurs au format PDF ainsi que la prise en charge de la définition du niveau de conformité et de la date de création. Les développeurs peuvent utiliser [IPdfSaveOptionsIPdfSaveOptionsIPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) de même que [Aspose::Cells::Rendu](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) pour définir la conformité PDF. Pour la conversion, API méthode de sauvegarde ayant PdfSaveOptions comme paramètre et le chemin du fichier de sortie spécifié. 
{{% blocks/products/pf/feature-page-code h3="C++ Exemple de code pour la conversion d\'Excel en PDF" %}}

```cs
// Chargez l'exemple de fichier Excel.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Créer un objet d'options d'enregistrement pdf.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Définissez la conformité sur PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// ou PdfCompliance_PdfA1a 
// pour un PDF normal, ce sera PdfCompliance_None

// Enregistrez le document Excel au format PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Enregistrer Excel dans les images" %}}
**C++Excel Parser** a la capacité d'exporter des données sous forme d'images. Chaque feuille de calcul peut être convertie en différents formats d'image, notamment BMP, JPEG, PNG et GIF, définis par le [Rendu ::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Pour tout cas **Convertir Excel en images**, sélectionnez le cas pertinent à partir des liens.
{{% blocks/products/pf/feature-page-code h3="C++ Code pour la conversion d\'Excel en image" %}}

```cs
// Chemin du répertoire de sortie.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Chargez le XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Accéder à la première feuille de calcul.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Créez une image ou un objet d'options d'impression.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Spécifiez le format d'image. Le code ci-dessous est pour JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Pour d'autres images comme GIF, BMP et PNG, on peut utiliser respectivement GetGif(), GetBmp() et GetPng() 

// Spécifiez la résolution horizontale et verticale
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Effectuez le rendu de la feuille en fonction de l'image ou des options d'impression spécifiées.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Obtenez le nombre de pages.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Créer un objet générateur de chaînes pour les concaténations de chaînes.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Rendez chaque page en image jpeg une par une.
for (int i = 0; i < pageCount; i++){
	// Effacez le générateur de chaînes et créez le chemin de l'image de sortie avec des concaténations de chaînes.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Obtenez le chemin de l'image de sortie.
	StringPtr outputJPEG = sb->ToString();
	// Convertir la feuille de calcul en image.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}