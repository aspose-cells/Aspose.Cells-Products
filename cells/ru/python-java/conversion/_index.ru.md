---
title: Преобразование файлов Microsoft Excel через Python 
url: /ru/python/conversion/
description: Преобразование Excel XLS, XLSX, ODS, CSV в PDF, XPS, HTML, JPEG, HTML и многие другие популярные форматы с помощью всего нескольких строк кода Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Преобразование формата Excel через Python" h2="Импорт и экспорт файлов Excel в виде электронных таблиц, веб-сайтов, изображений и форматов с фиксированным макетом" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Библиотека Excel ускоряет программирование электронных таблиц и процессы преобразования, поддерживая популярные форматы, включая XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Он также позволяет экспортировать файлы Excel в PDF, XPS, HTML, MHTML, обычный текст и популярные форматы изображений, такие как TIFF, JPG, PNG, BMP и SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в XLSX, ODS, SXC и FODS" %}}
Взаимное преобразование формата электронной таблицы требует только загрузки электронной таблицы с экземпляром [Рабочая тетрадь](https://reference.aspose.com/cells/python/asposecells.api/Workbook) и сохранить обратно в желаемом формате, выбрав соответствующее значение из [СохранитьФормат](https://reference.aspose.com/cells/python/asposecells.api/saveformat) перечисление.
{{% blocks/products/pf/feature-page-code h3="Python Код для преобразования формата файла Excel" %}}

```cs
// загрузить файл шаблона
workbook = Workbook("Book1.xls")
  
// сохранять в форматах XLSX, ODS, SXC и FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в PDF, XPS, HTML и MD" %}}
Доступны специализированные классы для управления процессом преобразования для определенных выходных форматов, таких как [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) экспортировать файлы Excel в формате PDF, [XPsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) для преобразования Excel в XPS, [Хтмлсавеоптионс](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) отображать Excel как HTML и [MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) для преобразования Excel в Markdown. 
{{% blocks/products/pf/feature-page-code h3="Python Код для преобразования Excel в PDF и веб-форматы" %}}

```cs
// загрузить файл шаблона Excel с диска
book = Workbook("template.xlsx")

// сохранить Excel в формате PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// сохранить Excel в XPS с 1 страницей на листе
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// сохранить Excel в HTML с изображениями как Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// сохранить Excel в Markdown (MD), сохранив форматирование ячеек
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Конвертировать JSON в Excel и Excel в JSON" %}}
Разработчики Python могут легко загружать и преобразовывать файлы JSON в Excel, написав всего несколько строк кода. Точно так же данные Excel можно экспортировать в данные JSON.
{{% blocks/products/pf/feature-page-code h3="Python Код для преобразования JSON в Excel" %}}
```cs
//Загрузите исходный файл json
workbook = Workbook("Data.json")
//сохранить файл в формате xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Код для преобразования Excel в JSON" %}}
```cs
//Загрузите исходный файл xlsx
workbook = Workbook("input.xlsx")
//сохранить файл в формате json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Конвертируйте рабочие листы Excel в JPG, BMP, PNG и GIF" %}}
Каждый рабочий лист файла Excel можно преобразовать в различные форматы изображений, вызовите [Имажеорпринтоптионс](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat для установки формата изображения. 
{{% blocks/products/pf/feature-page-code h3="Python Код для преобразования Excel в изображение" %}}
```cs
// загрузить таблицу шаблонов
workbook = Workbook("template.xlsx")
// создать и установить экземпляр ImageOrPrintOptions
options = ImageOrPrintOptions()
// установить формат выходного изображения
options.setImageFormat(ImageFormat.getPng())
// создать SheetRender для первого рабочего листа в коллекции
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// визуализировать рабочий лист в изображение
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в Word и PowerPoint" %}}
Можно загрузить любую электронную таблицу и преобразовать ее в файлы Word DOCX и PowerPoint PPTX при использовании [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) классы, как показано ниже.
{{% blocks/products/pf/feature-page-code h3="Python код для преобразования Excel в Word и PowerPoint" %}}
```cs
// загрузить файл шаблона
workbook = Workbook("template.xlsx")

// сохранить таблицу как DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// сохранить электронную таблицу как PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}