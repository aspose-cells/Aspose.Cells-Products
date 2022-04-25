---
title: Conversión de archivos de Microsoft Excel a través de C++ 
url: /es/cpp/conversion/
description: Convierta Excel XLS, XLSX, ODS, CSV a PDF, XPS, HTML, JPEG y otros formatos con solo unas pocas líneas de código C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversión de documentos de Microsoft<sup>&reg;</sup> Excel a través de C++" h2="Guarde archivos de Microsoft<sup>&reg;</sup> Excel como hoja de cálculo, web, imagen y formatos de diseño fijo" >}}

{{% blocks/products/pf/feature-page-summary %}}
Para cualquier aplicación o solución de conversión de hojas de cálculo, **C++ Biblioteca de Excel** acelera los procesos de codificación, automatización y conversión mientras maneja múltiples archivos, incluidos XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. También permite **convertir Excel a PDF**, XPS, HTML, MHTML, texto sin formato e imágenes populares como JPG, TIFF, PNG, BMP y SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversión de formatos de Microsoft Excel" %}}
La interconversión del formato de hoja de cálculo solo requiere cargar una hoja de cálculo con una instancia de [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) puntero y guardar de nuevo en el formato deseado usando [Guardar](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) método de [Clase de libro de trabajo](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Código de ejemplo para conversión de formato de archivo de Excel" %}}

```cs

// Cargue el formato de Excel de origen.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Guardar en el formato de salida requerido.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Convierta formatos de Excel a PDF con la configuración del nivel de cumplimiento" %}}
C++ Automatización de Excel API admite la conversión de libros de trabajo a PDF, así como la configuración del nivel de cumplimiento y la fecha de creación. Los desarrolladores pueden usar [IPdfSaveOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) junto con [Aspose::Cells::Procesamiento](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) para configurar el cumplimiento de PDF. Para la conversión, API guarde el método con PdfSaveOptions como parámetro y la ruta del archivo de salida especificada. 
{{% blocks/products/pf/feature-page-code h3="C++ código de muestra para la conversión de Excel a PDF" %}}

```cs
// Cargue el archivo de muestra de Excel.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Crear objeto de opciones de guardado de pdf.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Establezca el cumplimiento en PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// o PdfCompliance_PdfA1a 
// para PDF normal será PdfCompliance_None

// Guarde el documento de Excel en formato PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Guardar Excel en imágenes" %}}
**C++ Excel Parser** tiene la capacidad de exportar datos en forma de imágenes. Cada hoja de trabajo se puede convertir a diferentes formatos de imagen, incluidos BMP, JPEG, PNG y GIF, establecidos por el [Representación::IImageOrPrintOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Para cualquier caso de **Convertir Excel a Imágenes**, seleccione el caso relevante de los enlaces.
{{% blocks/products/pf/feature-page-code h3="C++ Código para conversión de Excel a imagen" %}}

```cs
// Ruta del directorio de salida.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Cargue el XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Acceda a la primera hoja de trabajo.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Crear imagen o objeto de opciones de impresión.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Especifique el formato de la imagen. El siguiente código es para JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Para otras imágenes como GIF, BMP y PNG, se pueden usar GetGif(), GetBmp() y GetPng() respectivamente. 

// Especificar resolución horizontal y vertical
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Renderice la hoja con respecto a la imagen especificada o las opciones de impresión.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Obtener recuento de páginas.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Cree un objeto generador de cadenas para concatenaciones de cadenas.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Renderice cada página a imagen jpeg una por una.
for (int i = 0; i < pageCount; i++){
	// Borre el generador de cadenas y cree una ruta de imagen de salida con concatenaciones de cadenas.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Obtenga la ruta de la imagen de salida.
	StringPtr outputJPEG = sb->ToString();
	// Convertir hoja de trabajo en imagen.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}