---
title: Microsoft تحويل ملف Excel باستخدام Python via Java
description: قم بتحويل Excel XLS و XLSX و ODS و CSV إلى PDF و XPS و HTML و JPEG و HTML والعديد من التنسيقات الشائعة الأخرى مع سطور قليلة فقط من كود Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> تحويل تنسيق Excel عبر Python" h2="استيراد وتصدير ملفات Excel كجداول بيانات وويب وصورة وتنسيقات ذات تخطيط ثابت" >}}

{{% blocks/products/pf/feature-page-summary %}}
تعمل مكتبة Excel Python على تسريع برمجة جداول البيانات وعمليات التحويل مع دعم التنسيقات الشائعة بما في ذلك XLS و XLSX و XLSM و XLSB و XLTX و XLTM و CSV و SpreadsheetML و ODS. عين تنسيقات النصوص والصور الشائعة مثل TIFF و JPG و PNG و BMP و SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى XLSX و ODS و SXC و FODS" %}}
 لا يتطلب التحويل البيني لتنسيق جدول البيانات سوى تحميل جدول بيانات بمثيل[دفتر العمل](https://reference.aspose.com/cells/python/asposecells.api/Workbook) وإعادة الحفظ بالتنسيق المطلوب مع تحديد القيمة المناسبة من[SaveFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) تعداد.
{{% blocks/products/pf/feature-page-code h3="Python كود لتحويل تنسيق ملف Excel" %}}

```cs
// load the template file
workbook = Workbook("Book1.xls")
  
// save as XLSX, ODS, SXC & FODS formats
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.sxc", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى PDF ، XPS ، HTML & MD" %}}
 تتوفر الفصول المتخصصة للتحكم في عملية التحويل لتنسيقات الإخراج المحددة مثل[خيارات PdfSave](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) لتصدير ملفات Excel كـ PDF ،[XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) لبرنامج Excel لتحويل XPS ،[خيارات HtmlSave](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) لتقديم Excel كـ HTML و[Markdown حفظ الخيارات](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) لتحويل Excel إلى Markdown.
{{% blocks/products/pf/feature-page-code h3="Python كود لبرنامج Excel إلى PDF وتنسيقات الويب" %}}

```cs
// load template Excel file from disc
book = Workbook("template.xlsx")

// save Excel in PDF_A_1_B format
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// save Excel in XPS with 1 page per worksheet
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// save Excel in HTML with images as Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// save Excel in Markdown (MD) while retaining cell formatting
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="قم بتحويل JSON إلى Excel & Excel إلى JSON" %}}
يمكن للمطورين Python بسهولة تحميل وتحويل ملفات JSON إلى Excel في بضعة أسطر من التعليمات البرمجية. وبالمثل ، يمكن تصدير بيانات Excel إلى بيانات JSON.
{{% blocks/products/pf/feature-page-code h3="Python كود لتحويل JSON إلى Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python كود للتحويل من Excel إلى JSON" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل أوراق عمل Excel إلى JPG و BMP و PNG و GIF" %}}
 يمكن تحويل كل ورقة عمل من ملف Excel إلى تنسيقات صور مختلفة ، اتصل[خيارات ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions) .setImageFormat لضبط تنسيق الصورة.
{{% blocks/products/pf/feature-page-code h3="Python كود لتحويل Excel إلى صورة" %}}
```cs
// load template spreadsheet
workbook = Workbook("template.xlsx")
// create & set an instance of ImageOrPrintOptions
options = ImageOrPrintOptions()
// set output image format
options.setImageFormat(ImageFormat.getPng())
// create SheetRender for first worksheet in the collection
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// render worksheet to image
sr.toImage(0, "output.jpg")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى Word & PowerPoint" %}}
 من الممكن تحميل أي جدول بيانات وتحويله إلى ملفات Word DOCX & PowerPoint PPTX أثناء الاستخدام[DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [خيارات PptxSaveOpt](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions)الفئات كما هو موضح أدناه.
{{% blocks/products/pf/feature-page-code h3="Python كود لبرنامج Excel إلى Word و PowerPoint للتحويل" %}}
```cs
// load the template file
workbook = Workbook("template.xlsx")

// save spreadsheet as DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// save spreadsheet as PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx" >}}
