---
title:  Microsoft تحويل ملف Excel via Java
description: قم بتحويل Excel XLS و XLSX و ODS و CSV إلى PDF و XPS و HTML و JPEG و HTML والعديد من التنسيقات الشائعة الأخرى مع سطور قليلة فقط من كود Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> تحويل ملفات Excel via Java" h2="احفظ Microsoft مستندات Excel بتنسيق جداول بيانات وويب وصور وتنسيقات ذات تخطيط ثابت" >}}

{{% blocks/products/pf/feature-page-summary %}}
 لأي**محول Excel** تطبيق أو حل ، Java Excel Library تسرع برمجة جداول البيانات وعمليات التحويل أثناء التعامل مع تنسيقات متعددة بما في ذلك XLS ، XLSX ، XLSM ، XLSB ، XLTX ، XLTM ، CSV ، SpreadsheetML ، ODS. XPS و HTML و MHTML والنص العادي وتنسيقات الصور الشائعة مثل TIFF و JPG و PNG و BMP و SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="التحويل البيني Microsoft تنسيقات Excel" %}}
 لا يتطلب التحويل البيني لتنسيق جدول البيانات سوى تحميل جدول بيانات بمثيل[دفتر العمل](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) وإعادة الحفظ بالتنسيق المطلوب مع تحديد القيمة المناسبة من[SaveFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) تعداد.
{{% blocks/products/pf/feature-page-code h3="Java رمز مثال لتحويل تنسيق ملف Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى PDF ، XPS ، HTML & MD" %}}
 تتوفر الفصول المتخصصة للتحكم في عملية التحويل لتنسيقات الإخراج المحددة مثل[خيارات PdfSave](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) لتحويل ملفات Excel كـ PDF ،[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) لتصدير Excel كـ XPS ،[خيارات HtmlSave](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) لتقديم Excel كـ HTML و[Markdown حفظ الخيارات](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) لتحويل Excel إلى Markdown.
{{% blocks/products/pf/feature-page-code h3="Java نموذج كود لبرنامج Excel إلى PDF وتنسيقات الويب" %}}

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

{{% blocks/products/pf/feature-page-section h2="تحويل JSON إلى Excel و Excel إلى JSON" %}}
 يمكن استيراد بيانات JSON إلى مثيل لفئة المصنف بمساعدة[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) لمزيد من المعالجة أو التحويل البسيط إلى أي من التنسيقات المدعومة. وبالمثل ، يمكن تصدير بيانات ورقة العمل كـ JSON عن طريق إنشاء ملف[يتراوح](https://reference.aspose.com/cells/java/com.aspose.cells/range) أو الخلايا واستدعاء[ExportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) طريقة.
{{% blocks/products/pf/feature-page-code h3="Java كود لتحويل JSON إلى Excel" %}}
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

{{% blocks/products/pf/feature-page-code h3="Java كود المصدر لبرنامج Excel لتحويل JSON" %}}
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

{{% blocks/products/pf/feature-page-section h2="احفظ أوراق عمل Excel على الصور" %}}
 يمكن تحويل كل ورقة عمل إلى تنسيقات صور مختلفة بما في ذلك JPG ، BMP ، PNG و GIF ، تم تعيينها بواسطة خاصية ImageType. لأي**تحويل Excel إلى صور** الحالة ، حدد الحالة ذات الصلة من الروابط.
{{% blocks/products/pf/feature-page-code h3="Java كود لتحويل Excel إلى صورة" %}}
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

{{% blocks/products/pf/feature-page-section h2="تحويل Microsoft Excel إلى Word و PowerPoint" %}}
 من الممكن تحميل أي جدول بيانات وتحويله إلى ملفات Word DOCX & PowerPoint PPTX أثناء الاستخدام[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [خيارات PptxSaveOpt](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) الفئات كما هو موضح أدناه.
{{% blocks/products/pf/feature-page-code h3="Java كود لبرنامج Excel إلى Word وتحويل PowerPoint" %}}
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
