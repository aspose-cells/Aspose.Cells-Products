---
title:  Microsoft Преобразование файлов Excel через C++
description: Преобразование Excel XLS, XLSX, ODS, CSV в PDF, XPS, HTML, JPEG и другие форматы с помощью всего нескольких строк кода C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Преобразование документов Excel через C++" h2="Сохраняйте Microsoft<sup>&reg;</sup> файлы Excel в виде электронных таблиц, веб-сайтов, изображений и форматов с фиксированным макетом" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Для любого приложения или решения для преобразования электронных таблиц**C++ Библиотека Excel** ускоряет процессы кодирования, автоматизации и преобразования при обработке нескольких файлов, включая XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Это также позволяет * конвертировать Excel до PDF**, XPS, HTML, MHTML, Гладкая Текст и популярные изображения, такие как JPG, TIFF, PNG, BMP и SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Взаимное преобразование Microsoft форматов Excel" %}}
 Взаимное преобразование формата электронной таблицы требует только загрузки электронной таблицы с экземпляром[ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) указатель и сохранение обратно в нужном формате с помощью[Сохранять](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) метод[Класс iWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Пример кода для преобразования формата файла Excel" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Преобразование форматов Excel в PDF с настройками уровня соответствия" %}}
 C++ Автоматизация Excel API поддерживает преобразование рабочих книг в PDF, а также поддерживает установку уровня соответствия и даты создания. Разработчики могут использовать[IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) вместе с[Aspose::Cells::Визуализация](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) установить соответствие PDF. Для преобразования API сохраните метод с PdfSaveOptions в качестве параметра и указанным путем к выходному файлу.
{{% blocks/products/pf/feature-page-code h3="C++ Пример кода для преобразования Excel в PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Сохранить Excel в изображения" %}}
**C++ Анализатор Excel** имеет возможность экспорта данных в виде изображений. Каждый рабочий лист может быть преобразован в различные форматы изображений, включая BMP, JPEG, PNG и GIF, установленные[Рендеринг:: Имажеорпринтоптионс](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . Для любого**Преобразование Excel в изображения** случай, выберите соответствующий случай из ссылок.
{{% blocks/products/pf/feature-page-code h3="C++ Код для преобразования Excel в изображение" %}}

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
