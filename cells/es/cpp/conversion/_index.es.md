---
title:  Microsoft Conversión de archivos de Excel a través de C++
description: Aspose.Cells for C++ biblioteca. Convierta EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG y más formatos con solo unas pocas líneas de código C++.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversión de documentos de Excel a través de C++" h2="Guarde Microsoft<sup>&reg;</sup> archivos de Excel en formato de hoja de cálculo, web, imagen y diseño fijo." >}}

{{% blocks/products/pf/feature-page-summary %}}
 Para cualquier aplicación o solución de conversión de hojas de cálculo,**C++ Biblioteca de Excel** acelera los procesos de codificación, automatización y conversión mientras maneja múltiples archivos, incluidos XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. También permite *convertir Excel a PDF**, XPS, HTML, MHTML, Normal Texto e imágenes populares como JPG, TIFF, PNG, BMP y SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversión de formatos Excel Microsoft" %}}
 La conversión entre formatos de hojas de cálculo solo requiere cargar la hoja de cálculo usando el[Libro de trabajo](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) clase y volver a guardarla en el formato requerido usando el[Ahorrar](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) método de la[Libro de trabajo](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) clase.
{{% blocks/products/pf/feature-page-code h3="C++ Código de ejemplo para la conversión de formato de archivo de Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Convierta formatos de Excel a PDF con configuración de nivel de cumplimiento" %}}
C++ Excel Automation API admite la conversión de libros de trabajo a PDF, así como la configuración del nivel de cumplimiento y la fecha de creación. Los desarrolladores pueden utilizar[Opciones de guardar PDF](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) junto con[Aspose::Cells::Representación](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) para establecer el cumplimiento PDF. Para la conversión, guarde el método API que tenga PdfSaveOptions como parámetro y una ruta de archivo de salida especificada.
{{% blocks/products/pf/feature-page-code h3="C++ Código de muestra para conversión de Excel a PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Guardar Excel en imágenes" %}}
**C++ Analizador de Excel** tiene la capacidad de exportar datos en forma de imágenes. Cada hoja de trabajo se puede convertir a diferentes formatos de imagen, incluidos BMP, JPEG, PNG y GIF, establecidos por el[Representación::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Para cualquier**Convertir Excel a imágenes** caso, seleccione el caso relevante de los enlaces.
{{% blocks/products/pf/feature-page-code h3="C++ Código para conversión de Excel a imagen" %}}

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
