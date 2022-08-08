---
title: Преобразование файлов Microsoft Excel через C# 
url: /ru/net/conversion/
description: Преобразование Excel XLS, XLSX, ODS, CSV в PDF, XPS, HTML, JPEG, HTML и многие другие популярные форматы с помощью всего нескольких строк кода C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Преобразование формата Excel через .NET" h2="Импорт и экспорт файлов Excel в виде электронных таблиц, веб-сайтов, изображений и форматов с фиксированным макетом" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Библиотека Excel ускоряет программирование электронных таблиц и процессы преобразования, поддерживая популярные форматы, включая XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Он также позволяет экспортировать файлы Excel в PDF, XPS, HTML, MHTML, обычный текст и популярные форматы изображений, такие как TIFF, JPG, PNG, BMP и SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в XLSX, ODS, SXC и FODS" %}}
Взаимное преобразование формата электронной таблицы требует только загрузки электронной таблицы с экземпляром [Рабочая тетрадь](https://reference.aspose.com/cells/net/aspose.cells/workbook) и сохранить обратно в желаемом формате, выбрав соответствующее значение из [СохранитьФормат](https://reference.aspose.com/cells/net/aspose.cells/saveformat) перечисление.
{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования формата файла Excel" %}}

```cs
// загрузить файл шаблона
var workbook = new Aspose.Cells.Workbook("template.xls");
// сохранять в форматах XLSX, ODS, SXC и FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в PDF, XPS, HTML и MD" %}}
Доступны специализированные классы для управления процессом преобразования для определенных выходных форматов, таких как [PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) экспортировать файлы Excel в формате PDF, [XPsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) для преобразования Excel в XPS, [Хтмлсавеоптионс](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) отображать Excel как HTML и [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) для преобразования Excel в Markdown. 
{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования Excel в PDF и веб-форматы" %}}

```cs
// загрузить файл шаблона Excel с диска
var book = new Aspose.Cells.Workbook("template.xlsx");
// сохранить Excel в формате PDF/A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// сохранить Excel в XPS с 1 страницей на листе
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// сохранить Excel в HTML с изображениями как Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// сохранить Excel в Markdown (MD), сохранив форматирование ячеек
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Конвертировать JSON в Excel и Excel в JSON" %}}
Данные JSON можно импортировать в экземпляр [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) класс с помощью [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) для дальнейшей обработки или простого преобразования в любой из поддерживаемых форматов. Сходным образом, [Рабочий лист](https://reference.aspose.com/cells/net/aspose.cells/worksheet) данные можно экспортировать в формате JSON, создав [Диапазон](https://reference.aspose.com/cells/net/aspose.cells/range) или ячейки и вызов [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) метод.
{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования JSON в Excel" %}}
```cs
// создать объект рабочей книги
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// читать данные JSON из файла
string jsonInput = File.ReadAllText("Data.json");
// установите JsonLayoutOptions для обработки массивов как таблицы
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// импортировать данные JSON на лист, начиная с ячейки A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// сохранить полученный файл в формате XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования Excel в JSON" %}}
```cs
// загрузить файл XLSX с экземпляром Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// получить доступ к CellsCollection рабочего листа, содержащего данные для преобразования
var cells = workbook.Worksheets[0].Cells;
// создать и установить ExportRangeToJsonOptions для дополнительных параметров
var exportOptions = new Utility.ExportRangeToJsonOptions();
// создать диапазон ячеек, содержащих данные для экспорта
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// экспортировать диапазон как данные JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// записать файл данных на диск в формате JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Конвертируйте рабочие листы Excel в JPG, BMP, PNG и GIF" %}}
Каждый рабочий лист файла Excel может быть преобразован в различные форматы изображений, установленные [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) свойство. Значение по умолчанию — `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования Excel в изображение" %}}
```cs
// загрузить таблицу шаблонов
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// создать и установить экземпляр ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// установить формат выходного изображения
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// создать SheetRender для первого рабочего листа в коллекции
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// визуализировать рабочий лист в изображение
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в Word и PowerPoint" %}}
Можно загрузить любую электронную таблицу и преобразовать ее в файлы Word DOCX и PowerPoint PPTX при использовании [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) классы, как показано ниже.
{{% blocks/products/pf/feature-page-code h3="C# код для преобразования Excel в Word и PowerPoint" %}}
```cs
// загрузить файл шаблона
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// сохранить таблицу как DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// сохранить электронную таблицу как PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}