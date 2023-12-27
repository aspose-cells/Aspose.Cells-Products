---
title:  Microsoft Преобразование файлов Excel через C++
description: Aspose.Cells for C++ библиотека. Конвертируйте EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG и другие форматы с помощью всего лишь нескольких строк кода C++.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Преобразование документов Excel с помощью C++" h2="Сохраняйте Microsoft<sup>&reg;</sup> файлы Excel в форматах электронных таблиц, Интернета, изображений и с фиксированным макетом." >}}

{{% blocks/products/pf/feature-page-summary %}}
 Для любого приложения или решения конвертера электронных таблиц**C++ Библиотека Excel** ускоряет процессы кодирования, автоматизации и преобразования при работе с несколькими файлами, включая XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Это также позволяет *конвертировать Excel в PDF**, XPS, HTML, MHTML, Обычный Текст и популярные изображения, такие как JPG, TIFF, PNG, BMP и SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Взаимное преобразование форматов Excel Microsoft" %}}
 Для преобразования между форматами электронных таблиц требуется только загрузить электронную таблицу с помощью[Рабочая тетрадь](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) класс и пересохраните его в нужном формате с помощью команды[Сохранять](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) метод[Рабочая тетрадь](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) сорт.
{{% blocks/products/pf/feature-page-code h3="C++ Пример кода для преобразования формата файла Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Преобразование форматов Excel в PDF с настройками уровня соответствия" %}}
C++ Excel Automation API поддерживает преобразование книг в PDF, а также поддерживает настройку уровня соответствия и даты создания. Разработчики могут использовать[PDFSaveOptions](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) вместе с[Aspose::Cells::Рендеринг](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) чтобы установить соответствие PDF. Для преобразования API используйте метод сохранения с PdfSaveOptions в качестве параметра и указанным путем к выходному файлу.
{{% blocks/products/pf/feature-page-code h3="C++ Пример кода для преобразования Excel в PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="Сохранение Excel в изображениях" %}}
**C++ Парсер Excel** имеет возможность экспорта данных в виде изображений. Каждый рабочий лист можно преобразовать в различные форматы изображений, включая BMP, JPEG, PNG и GIF, установленные[Рендеринг::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Для любого**Преобразование Excel в изображения** случай, выберите соответствующий случай из ссылок.
{{% blocks/products/pf/feature-page-code h3="C++ Код для преобразования Excel в изображения" %}}

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
