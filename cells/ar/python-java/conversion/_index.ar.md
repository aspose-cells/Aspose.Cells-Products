---
title: تحويل ملف Microsoft Excel عبر Python 
url: /ar/python/conversion/
description: قم بتحويل Excel XLS و XLSX و ODS و CSV إلى PDF و XPS و HTML و JPEG و HTML والعديد من التنسيقات الشائعة الأخرى باستخدام سطور قليلة فقط من Python التعليمات البرمجية.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> تحويل تنسيق Excel عبر Python" h2="استيراد وتصدير ملفات Excel كجداول بيانات وويب وصورة وتنسيقات تخطيط ثابت" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python تعمل مكتبة Excel على تسريع برمجة جداول البيانات وعمليات التحويل مع دعم التنسيقات الشائعة بما في ذلك XLS و XLSX و XLSM و XLSB و XLTX و XLTM و CSV و SpreadsheetML و ODS. كما يسمح بتصدير ملفات Excel إلى PDF و XPS و HTML و MHTML و Plain Text وتنسيقات الصور الشائعة مثل TIFF و JPG و PNG و BMP و SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى XLSX و ODS و SXC و FODS" %}}
لا يتطلب التحويل البيني لتنسيق جدول البيانات سوى تحميل جدول بيانات بمثيل [دفتر العمل](https://reference.aspose.com/cells/python/asposecells.api/Workbook) وإعادة الحفظ بالتنسيق المطلوب مع تحديد القيمة المناسبة من [SaveFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) تعداد.
{{% blocks/products/pf/feature-page-code h3="Python رمز تحويل تنسيق ملف Excel" %}}

```cs
// تحميل ملف القالب
workbook = Workbook("Book1.xls")
  
// حفظ بتنسيقات XLSX و ODS و SXC و FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="قم بتحويل Excel إلى PDF و XPS و HTML و MD" %}}
تتوفر الفصول المتخصصة للتحكم في عملية التحويل لتنسيقات الإخراج المحددة مثل [خيارات PdfSave](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) لتصدير ملفات Excel بصيغة PDF ، [XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) لتحويل Excel إلى XPS ، [خيارات HtmlSave](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) لتقديم Excel بتنسيق HTML و [تخفيض السعر](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) لبرنامج Excel لتحويل Markdown. 
{{% blocks/products/pf/feature-page-code h3="Python التعليمات البرمجية لـ Excel إلى PDF وتنسيقات الويب" %}}

```cs
// تحميل ملف إكسل قالب من القرص
book = Workbook("template.xlsx")

// احفظ Excel بتنسيق PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// حفظ Excel في XPS بصفحة واحدة لكل ورقة عمل
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// حفظ Excel بصيغة HTML بالصور باسم Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// حفظ Excel في Markdown (MD) مع الاحتفاظ بتنسيق الخلية
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل JSON إلى Excel و Excel إلى JSON" %}}
يمكن لمطوري Python تحميل ملفات JSON وتحويلها بسهولة إلى Excel في بضعة أسطر من التعليمات البرمجية. وبالمثل ، يمكن تصدير بيانات Excel إلى بيانات JSON.
{{% blocks/products/pf/feature-page-code h3="Python رمز تحويل JSON إلى Excel" %}}
```cs
//قم بتحميل ملف json المصدر الخاص بك
workbook = Workbook("Data.json")
//احفظ الملف بتنسيق xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python كود لبرنامج Excel لتحويل JSON" %}}
```cs
//قم بتحميل ملف المصدر الخاص بك xlsx
workbook = Workbook("input.xlsx")
//حفظ الملف بتنسيق json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="قم بتحويل أوراق عمل Excel إلى JPG و BMP و PNG و GIF" %}}
يمكن تحويل كل ورقة عمل من ملف Excel إلى تنسيقات صور مختلفة ، اتصل [خيارات ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat لضبط تنسيق الصورة. 
{{% blocks/products/pf/feature-page-code h3="Python كود لبرنامج Excel لتحويل الصورة" %}}
```cs
// تحميل قالب جدول البيانات
workbook = Workbook("template.xlsx")
// إنشاء وتعيين مثيل ImageOrPrintOptions
options = ImageOrPrintOptions()
// تعيين تنسيق صورة الإخراج
options.setImageFormat(ImageFormat.getPng())
// قم بإنشاء SheetRender لأول ورقة عمل في المجموعة
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// تقديم ورقة العمل للصورة
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى Word و PowerPoint" %}}
من الممكن تحميل أي جدول بيانات وتحويله إلى ملفات Word DOCX و PowerPoint PPTX أثناء استخدام [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [خيارات PptxSaveOpt](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) الفئات كما هو موضح أدناه.
{{% blocks/products/pf/feature-page-code h3="Python رمز Excel لتحويل Word و PowerPoint" %}}
```cs
// تحميل ملف القالب
workbook = Workbook("template.xlsx")

// احفظ جدول البيانات بتنسيق DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// احفظ جدول البيانات بتنسيق PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}