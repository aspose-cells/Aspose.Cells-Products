---
title:  Microsoft تبدیل فایل اکسل via Java
description: اکسل XLS، XLSX، ODS، CSV را به PDF، XPS، HTML، HTML، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، JPEG، PDF، PDF. کد 81
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تبدیل فایل های اکسل via Java" h2="اسناد اکسل Microsoft را به‌صورت صفحه‌گسترده، وب، تصویر و قالب‌بندی ثابت ذخیره کنید." >}}

{{% blocks/products/pf/feature-page-summary %}}
 برای هرچی**مبدل اکسل**application or solution, Java Excel Library speeds up spreadsheet programming and conversion processes while handling multiple formats including XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. It also allows to *convert Excel files to PDF**, XPS، HTML، MHTML، متن ساده و فرمت های تصویری محبوب مانند TIFF، JPG، PNG، BMP و SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تبدیل بین Microsoft فرمت های اکسل" %}}
 تبدیل فرمت صفحه گسترده فقط به بارگیری یک صفحه گسترده با یک نمونه از نیاز دارد[کتاب کار](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) و همزمان با انتخاب مقدار مناسب، در قالب مورد نظر ذخیره کنید[SaveFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) شمارش
{{% blocks/products/pf/feature-page-code h3="Java کد مثال برای تبدیل فرمت فایل اکسل" %}}

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


{{% blocks/products/pf/feature-page-section h2="تبدیل اکسل به PDF، XPS، HTML و MD" %}}
 کلاس های تخصصی برای کنترل فرآیند تبدیل برای فرمت های خروجی خاص مانند[PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) برای تبدیل فایل های اکسل به PDF،[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) برای صادرات اکسل به عنوان XPS،[HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) برای رندر اکسل به صورت HTML و[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) برای تبدیل Excel به Markdown
{{% blocks/products/pf/feature-page-code h3="Java نمونه کد اکسل به PDF و فرمت های وب" %}}

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

{{% blocks/products/pf/feature-page-section h2="تبدیل JSON به اکسل و اکسل به JSON" %}}
 داده های JSON را می توان به یک نمونه از کلاس Workbook با کمک وارد کرد[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) برای پردازش بیشتر یا تبدیل ساده به هر یک از فرمت های پشتیبانی شده. به طور مشابه، داده های کاربرگ را می توان با ایجاد یک به عنوان JSON صادر کرد[دامنه](https://reference.aspose.com/cells/java/com.aspose.cells/range) یا سلول ها و فراخوانی[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) روش.
{{% blocks/products/pf/feature-page-code h3="Java کد تبدیل JSON به اکسل" %}}
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

{{% blocks/products/pf/feature-page-code h3="تبدیل کد منبع Java برای اکسل به JSON" %}}
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

{{% blocks/products/pf/feature-page-section h2="کاربرگ های اکسل را در تصاویر ذخیره کنید" %}}
 هر کاربرگ را می توان به فرمت های تصویری مختلف از جمله JPG، BMP، PNG و GIF که توسط ویژگی ImageType تنظیم شده است، تبدیل کرد. برای هرچی**تبدیل اکسل به تصاویر** مورد، مورد مربوطه را از لینک ها انتخاب کنید.
{{% blocks/products/pf/feature-page-code h3="Java کد برای تبدیل اکسل به تصویر" %}}
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

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel را به Word و PowerPoint تبدیل کنید" %}}
 امکان بارگذاری هر صفحه گسترده و تبدیل آن به فایل های Word DOCX و PowerPoint PPTX در حین استفاده وجود دارد.[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions)کلاس هایی که در زیر نشان داده شده است.
{{% blocks/products/pf/feature-page-code h3="کد Java برای اکسل به ورد و تبدیل PowerPoint" %}}
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
