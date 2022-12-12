---
title: تحويل ملف Microsoft Excel عبر Java 

description: قم بتحويل Excel XLS و XLSX و ODS و CSV إلى PDF و XPS و HTML و JPEG و HTML والعديد من التنسيقات الشائعة الأخرى باستخدام سطور قليلة فقط من Java التعليمات البرمجية.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> تحويل ملفات Excel عبر Java" h2="احفظ مستندات Microsoft Excel على هيئة جداول بيانات وويب وصورة وتنسيقات ذات تخطيط ثابت" >}}

{{% blocks/products/pf/feature-page-summary %}}
بالنسبة إلى أي تطبيق أو حل ** محول Excel ** ، تعمل مكتبة Excel على تسريع برمجة جداول البيانات وعمليات التحويل أثناء التعامل مع تنسيقات متعددة بما في ذلك XLS و XLSX و XLSM و XLSB و XLTX و XLTM و CSV و SpreadsheetML و ODS. كما يسمح ** بتحويل ملفات Excel إلى PDF ** و XPS و HTML و MHTML و Plain Text وتنسيقات الصور الشائعة مثل TIFF و JPG و PNG و BMP و SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="التحويل البيني لتنسيقات Microsoft Excel" %}}
لا يتطلب التحويل البيني لتنسيق جدول البيانات سوى تحميل جدول بيانات بمثيل [دفتر العمل](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) وإعادة الحفظ بالتنسيق المطلوب مع تحديد القيمة المناسبة من [SaveFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) تعداد.
{{% blocks/products/pf/feature-page-code h3="Java رمز مثال لتحويل تنسيق ملف Excel" %}}

```cs
// تحميل الملف المصدر
var wkb = new Workbook("sourceFile.xls");
// حفظ بتنسيقات XLSX و ODS و SXC و FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="قم بتحويل Excel إلى PDF و XPS و HTML و MD" %}}
تتوفر الفصول المتخصصة للتحكم في عملية التحويل لتنسيقات الإخراج المحددة مثل [خيارات PdfSave](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) لتحويل ملفات Excel إلى PDF ، [XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) لتصدير Excel كـ XPS ، [خيارات HtmlSave](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) لتقديم Excel بتنسيق HTML و [تخفيض السعر](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) لبرنامج Excel لتحويل Markdown. 
{{% blocks/products/pf/feature-page-code h3="Java نموذج التعليمات البرمجية لـ Excel إلى PDF وتنسيقات الويب" %}}

```cs
// تحميل ملف إكسل قالب من القرص
var bk = new Workbook("source-file.xlsx");

// تحويل Excel إلى PDF باستخدام Java
// إنشاء خيارات PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// حفظ Excel في XPS
bk.save("output.xps", new XpsSaveOptions());
// حفظ Excel في HTML
bk.save("output.html", new HtmlSaveOptions());
// حفظ Excel في Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// يمكن للمرء تعيين خيارات الحفظ ذات الصلة حسب اختياره قبل الحفظ في التنسيق المناسب

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل JSON إلى Excel و Excel إلى JSON" %}}
يمكن استيراد بيانات JSON إلى مثيل لفئة المصنف بمساعدة [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) لمزيد من المعالجة أو التحويل البسيط إلى أي من التنسيقات المدعومة. وبالمثل ، يمكن تصدير بيانات ورقة العمل بتنسيق JSON عن طريق إنشاء ملف [يشتمل على](https://reference.aspose.com/cells/java/com.aspose.cells/range) أو الخلايا واستدعاء [ExportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) طريقة.
{{% blocks/products/pf/feature-page-code h3="Java رمز تحويل JSON إلى Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// إقرا الملف
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// قم بتعيين JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// استيراد بيانات JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// احفظ ملف Excel
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java كود المصدر لتحويل Excel إلى JSON" %}}
```cs
// تحميل ملف XLSX مع مثيل من المصنف
Workbook workbook = new Workbook("sourceFile.xlsx");
// الوصول إلى مجموعة الخلايا من ورقة العمل التي تحتوي على البيانات المراد تحويلها
Cells cells = workbook.getWorksheets().get(0).getCells();
// إنشاء وضبط ExportRangeToJsonOptions للخيارات المتقدمة
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// إنشاء نطاق من الخلايا التي تحتوي على البيانات ليتم تصديرها
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// نطاق التصدير كبيانات JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// كتابة البيانات على القرص بتنسيق JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="احفظ أوراق عمل Excel على الصور" %}}
يمكن تحويل كل ورقة عمل إلى تنسيقات صور مختلفة بما في ذلك JPG و BMP و PNG و GIF ، التي تم تعيينها بواسطة خاصية ImageType. لأي حالة ** تحويل Excel إلى صور ** ، حدد الحالة ذات الصلة من الروابط.
{{% blocks/products/pf/feature-page-code h3="Java كود لبرنامج Excel لتحويل الصورة" %}}
```cs
// تحميل قالب جدول البيانات
var wkb = new Workbook("template.xlsx");

// قم بإنشاء كائن لـ ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// اضبط نوع الصورة
imgOptions.setImageType(ImageType.PNG);

// احصل على ورقة العمل الأولى.
Worksheet sheet = wkb.getWorksheets().get(0);

// قم بإنشاء كائن SheetRender للورقة الهدف
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// قم بإنشاء صورة لورقة العمل
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل Microsoft Excel إلى Word و PowerPoint" %}}
من الممكن تحميل أي جدول بيانات وتحويله إلى ملفات Word DOCX و PowerPoint PPTX أثناء استخدام [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [خيارات PptxSaveOpt](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) الفئات كما هو موضح أدناه.
{{% blocks/products/pf/feature-page-code h3="Java Code for Excel to Word & PowerPoint Conversion" %}}
```cs
// تحميل ملف القالب
var wkb = new Workbook("template.xlsx");
// احفظ جدول البيانات بتنسيق DOCX
wkb.save("output.docx", new DocxSaveOptions());
// احفظ جدول البيانات بتنسيق PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
