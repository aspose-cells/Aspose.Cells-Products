---
title:  Microsoft Преобразование файлов Excel via Java
description: Преобразование Excel XLS, XLSX, ODS, CSV в PDF, XPS, HTML, JPEG, HTML и многие другие популярные форматы с помощью всего нескольких строк кода Java .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Преобразование файлов Excel via Java" h2="Сохранение Microsoft документов Excel в форматах электронных таблиц, веб-сайтов, изображений и с фиксированным макетом" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Для любого**Преобразователь Excel**приложение или решение, Java Библиотека Excel ускоряет программирование электронных таблиц и процессы преобразования при обработке нескольких форматов, включая XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07 6193481. Также позволяет *конвертировать файлы Excel в PDF**, XPS, HTML, MHTML, обычный текст и популярные форматы изображений, такие как TIFF, JPG, PNG, BMP и SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Взаимное преобразование Microsoft форматов Excel" %}}
 Взаимное преобразование формата электронной таблицы требует только загрузки электронной таблицы с экземпляром[Рабочая тетрадь](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) и сохранить обратно в желаемом формате, выбрав соответствующее значение из[СохранитьФормат](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) перечисление.
{{% blocks/products/pf/feature-page-code h3="Java Пример кода для преобразования формата файла Excel" %}}

```cs
// load the source file
var wkb = new Workbook("sourceFile.xls");
// save as XLSX, ODS, SXC & FODS formats
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в PDF, XPS, HTML и MD" %}}
 Доступны специализированные классы для управления процессом преобразования для определенных выходных форматов, таких как[PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) конвертировать файлы Excel как PDF,[XPsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) экспортировать Excel как XPS,[Хтмлсавеоптионс](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) для отображения Excel как HTML и[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) для преобразования Excel в Markdown.
{{% blocks/products/pf/feature-page-code h3="Java Пример кода для Excel до PDF и веб-форматов" %}}

```cs
// load template Excel file from disc
var bk = new Workbook("source-file.xlsx");

// convert Excel to PDF using Java
// Create PDF options
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// save Excel in XPS
bk.save("output.xps", new XpsSaveOptions());
// save Excel in HTML
bk.save("output.html", new HtmlSaveOptions());
// save Excel in Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// one can set relevant save options as of his choice before saving into relevant format
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование JSON в Excel и Excel в JSON" %}}
 JSON данные могут быть импортированы в экземпляр класса Workbook с помощью[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) для дальнейшей обработки или простого преобразования в любой из поддерживаемых форматов. Точно так же данные рабочего листа можно экспортировать как JSON, создав[Диапазон](https://reference.aspose.com/cells/java/com.aspose.cells/range) или ячейки и вызов[экспортRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) метод.
{{% blocks/products/pf/feature-page-code h3="Java Код для преобразования JSON в Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Read File
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Set JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Import JSON Data
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Save Excel file
workbook.save(path + "excel-to-json.out.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Исходный код для преобразования Excel в JSON" %}}
```cs
// load XLSX file with an instance of Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// access CellsCollection of the worksheet containing data to be converted
Cells cells = workbook.getWorksheets().get(0).getCells();
// create & set ExportRangeToJsonOptions for advanced options
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// export range as JSON data
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// write data to disc in JSON format
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Сохранение листов Excel в изображения" %}}
 Каждый рабочий лист можно преобразовать в различные форматы изображений, включая JPG, BMP, PNG и GIF, заданные свойством ImageType. Для любого**Преобразование Excel в изображения** случай, выберите соответствующий случай из ссылок.
{{% blocks/products/pf/feature-page-code h3="Java Код для преобразования Excel в изображение" %}}
```cs
// load template spreadsheet
var wkb = new Workbook("template.xlsx");

// Create an object for ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Set the image type
imgOptions.setImageType(ImageType.PNG);

// Get the first worksheet.
Worksheet sheet = wkb.getWorksheets().get(0);

// Create a SheetRender object for the target sheet
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Generate an image for the worksheet
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование Microsoft Excel в Word и PowerPoint" %}}
 Можно загрузить любую электронную таблицу и преобразовать ее в файлы Word DOCX и PowerPoint PPTX при использовании[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions)классы, как показано ниже.
{{% blocks/products/pf/feature-page-code h3="Java Код для преобразования Excel в Word и PowerPoint Преобразование" %}}
```cs
// load the template file
var wkb = new Workbook("template.xlsx");
// save spreadsheet as DOCX
wkb.save("output.docx", new DocxSaveOptions());
// save spreadsheet as PPTX
wkb.save("output.pptx", new PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
