---
title: Преобразование файлов Microsoft Excel через C++ 
url: /ru/cpp/conversion/
description: Преобразование Excel XLS, XLSX, ODS, CSV в PDF, XPS, HTML, JPEG и другие форматы с помощью всего нескольких строк кода C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование документов Microsoft<sup>&reg;</sup> в Excel через C++" h2="Сохраняйте файлы Microsoft<sup>&reg;</sup> Excel в форматах электронных таблиц, веб-сайтов, изображений и с фиксированным макетом." >}}

{{% blocks/products/pf/feature-page-summary %}}
Для любого приложения или решения для преобразования электронных таблиц **C++Библиотека Excel** ускоряет кодирование, автоматизацию и процессы преобразования при обработке нескольких файлов, включая XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Он также позволяет **конвертировать Excel в PDF**, XPS, HTML, MHTML, обычный текст и популярные изображения, такие как JPG, TIFF, PNG, BMP и SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Взаимное преобразование форматов Microsoft Excel" %}}
Взаимное преобразование формата электронной таблицы требует только загрузки электронной таблицы с экземпляром [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) указатель и сохранение обратно в нужном формате с помощью [Сохранять](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) метод [Класс iWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Пример кода для преобразования формата файла Excel" %}}

```cs

// Загрузите исходный формат Excel.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Сохраните в требуемом формате вывода.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Преобразование форматов Excel в PDF с настройками уровня соответствия" %}}
C++ Автоматизация Excel API поддерживает преобразование книг в PDF, а также настройку уровня соответствия и даты создания. Разработчики могут использовать [IPdfSaveOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) вместе с [Aspose::Cells::Визуализация](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) для установки соответствия PDF. Для преобразования сохраните метод API с параметром PdfSaveOptions и указанным путем к выходному файлу. 
{{% blocks/products/pf/feature-page-code h3="C++ Пример кода для преобразования Excel в PDF" %}}

```cs
// Загрузите образец файла Excel.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Создайте объект параметров сохранения PDF.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Установите соответствие PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// или PdfCompliance_PdfA1a 
// для обычного PDF это будет PdfCompliance_None

// Сохраните документ Excel в формате PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Сохранить Excel в изображения" %}}
**C++Excel Parser** позволяет экспортировать данные в виде изображений. Каждый рабочий лист может быть преобразован в различные форматы изображений, включая BMP, JPEG, PNG и GIF, установленные [Рендеринг:: Имажеорпринтоптионс](https://apireference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Для любого случая **Конвертировать Excel в изображения** выберите соответствующий случай по ссылкам.
{{% blocks/products/pf/feature-page-code h3="C++ Код для преобразования Excel в изображение" %}}

```cs
// Выходной путь к каталогу.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Загрузите XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Доступ к первому рабочему листу.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Создайте изображение или объект опций печати.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Укажите формат изображения. Ниже код для JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Для других изображений, таких как GIF, BMP и PNG, можно использовать GetGif(), GetBmp() и GetPng() соответственно. 

// Укажите горизонтальное и вертикальное разрешение
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Рендеринг листа в соответствии с указанным изображением или параметрами печати.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Получить количество страниц.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Создайте объект построителя строк для конкатенации строк.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Визуализируйте каждую страницу в изображение jpeg одну за другой.
for (int i = 0; i < pageCount; i++){
	// Очистите построитель строк и создайте путь к выходному изображению с конкатенацией строк.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Получите путь к выходному изображению.
	StringPtr outputJPEG = sb->ToString();
	// Преобразование рабочего листа в изображение.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}