---
title: Преобразование файлов Microsoft Excel через Java 
url: /ru/java/conversion/
description: Преобразование Excel XLS, XLSX, ODS, CSV в PDF, XPS, HTML, JPEG, HTML и многие другие популярные форматы с помощью всего нескольких строк кода Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Преобразование файлов Excel через Java" h2="Сохраняйте документы Microsoft Excel в виде электронных таблиц, веб-сайтов, изображений и форматов с фиксированным макетом." >}}

{{% blocks/products/pf/feature-page-summary %}}
Для любого приложения или решения **Excel Converter** библиотека JavaExcel ускоряет программирование электронных таблиц и процессы преобразования при обработке нескольких форматов, включая XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Он также позволяет **конвертировать файлы Excel в PDF**, XPS, HTML, MHTML, обычный текст и популярные форматы изображений, такие как TIFF, JPG, PNG, BMP и SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Взаимное преобразование форматов Microsoft Excel" %}}
Взаимное преобразование формата электронной таблицы требует только загрузки электронной таблицы с экземпляром [Рабочая тетрадь](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) и сохранить обратно в желаемом формате, выбрав соответствующее значение из [СохранитьФормат](https://apireference.aspose.com/cells/java/com.aspose.cells/SaveFormat) перечисление.
{{% blocks/products/pf/feature-page-code h3="Java Пример кода для преобразования формата файла Excel" %}}

```cs
// загрузить исходный файл
var wkb = new Workbook("sourceFile.xls");
// сохранять в форматах XLSX, ODS, SXC и FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в PDF, XPS, HTML и MD" %}}
Доступны специализированные классы для управления процессом преобразования для определенных выходных форматов, таких как [PdfSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) конвертировать файлы Excel в формат PDF, [XPsSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) экспортировать Excel как XPS, [Хтмлсавеоптионс](https://apireference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) отображать Excel как HTML и [MarkdownSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) для преобразования Excel в Markdown. 
{{% blocks/products/pf/feature-page-code h3="Java Пример кода для преобразования Excel в PDF и веб-форматы" %}}

```cs
// загрузить файл шаблона Excel с диска
var bk = new Workbook("source-file.xlsx");

// преобразовать Excel в PDF с помощью Java
// Создать параметры PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// сохранить Excel в XPS
bk.save("output.xps", new XpsSaveOptions());
// сохранить Excel в HTML
bk.save("output.html", new HtmlSaveOptions());
// сохранить Excel в Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// можно установить соответствующие параметры сохранения по своему выбору перед сохранением в соответствующем формате

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование JSON в Excel и Excel в JSON" %}}
Данные JSON можно импортировать в экземпляр класса Workbook с помощью [JSONUtility.importData](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) для дальнейшей обработки или простого преобразования в любой из поддерживаемых форматов. Точно так же данные рабочего листа можно экспортировать в формате JSON, создав [Диапазон](https://apireference.aspose.com/cells/java/com.aspose.cells/range) или ячейки и вызов [экспортRangeToJson](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility) метод.
{{% blocks/products/pf/feature-page-code h3="Java Код для преобразования JSON в Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Прочитать файл
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Установить JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Импорт данных JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Сохранить файл Excel
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Исходный код для преобразования Excel в JSON" %}}
```cs
// загрузить файл XLSX с экземпляром Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// получить доступ к CellsCollection рабочего листа, содержащего данные для преобразования
Cells cells = workbook.getWorksheets().get(0).getCells();
// создать и установить ExportRangeToJsonOptions для дополнительных параметров
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// создать диапазон ячеек, содержащих данные для экспорта
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// экспортировать диапазон как данные JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// записать данные на диск в формате JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Сохранение листов Excel в изображения" %}}
Каждый рабочий лист может быть преобразован в различные форматы изображений, включая JPG, BMP, PNG и GIF, установленные свойством ImageType. Для любого случая **Конвертировать Excel в изображения** выберите соответствующий случай по ссылкам.
{{% blocks/products/pf/feature-page-code h3="Java Код для преобразования Excel в изображение" %}}
```cs
// загрузить таблицу шаблонов
var wkb = new Workbook("template.xlsx");

// Создайте объект для ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Установите тип изображения
imgOptions.setImageType(ImageType.PNG);

// Получите первый рабочий лист.
Worksheet sheet = wkb.getWorksheets().get(0);

// Создайте объект SheetRender для целевого листа
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Создание изображения для рабочего листа
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование Microsoft Excel в Word и PowerPoint" %}}
Можно загрузить любую электронную таблицу и преобразовать ее в файлы Word DOCX и PowerPoint PPTX при использовании [DocxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) классы, как показано ниже.
{{% blocks/products/pf/feature-page-code h3="Java Код для преобразования Excel в Word и PowerPoint" %}}
```cs
// загрузить файл шаблона
var wkb = new Workbook("template.xlsx");
// сохранить таблицу как DOCX
wkb.save("output.docx", new DocxSaveOptions());
// сохранить электронную таблицу как PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}