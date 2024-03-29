---
title: Microsoft تحويل ملفات Excel باستخدام Python via Java
description: Aspose.Cells for Python via Java مكتبة. تحويل EXCEL، JSON، PDF، XML، HTML، TXT، TSV، CSV، SQL والمزيد من التنسيقات مع أسطر قليلة فقط من الكود Python.
keywords: [Python Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Python]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تحويل تنسيق Excel عبر Python" h2="استيراد وتصدير ملفات Excel بتنسيقات جداول البيانات والويب والصور والتخطيطات الثابتة" >}}

{{% blocks/products/pf/feature-page-summary %}}
تعمل مكتبة Excel Python على تسريع عمليات برمجة جداول البيانات والتحويل مع دعم التنسيقات الشائعة بما في ذلك XLS، XLSX، XLSM، XLSB، XLTX، XLTM، CSV، SpreadsheetML، 07619348 1. كما يسمح بتصدير ملفات Excel إلى PDF، XPS، HTML، MHTML، عادي تنسيقات النصوص والصور الشائعة مثل TIFF وJPG وPNG وBMP وSVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى XLSX وODS وSXC وFODS" %}}
 يتطلب التحويل البيني لتنسيق جدول البيانات فقط تحميل جدول بيانات بمثيل[دفتر العمل](https://reference.aspose.com/cells/python/asposecells.api/Workbook) والحفظ مرة أخرى بالتنسيق المطلوب أثناء تحديد القيمة المناسبة من[حفظ التنسيق](https://reference.aspose.com/cells/python/asposecells.api/saveformat) تعداد.
{{% blocks/products/pf/feature-page-code h3="Python كود تحويل تنسيق ملف اكسيل" %}}

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


{{% blocks/products/pf/feature-page-section h2="تحويل Excel إلى PDF و XPS و HTML و MD" %}}
 تتوفر فئات متخصصة للتحكم في عملية التحويل لتنسيقات إخراج محددة مثل[خيارات حفظ PDF](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) لتصدير ملفات Excel كـ PDF،[خيارات XpsSave](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) لتحويل Excel إلى XPS ،[هتملسافيوبتيونس](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) لتقديم Excel كـ HTML و[خيارات تخفيض السعر](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) لتحويل Excel إلى Markdown.
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

{{% blocks/products/pf/feature-page-section h2="تحويل JSON إلى Excel و Excel إلى JSON" %}}
يمكن لمطوري Python تحميل وتحويل ملفات JSON بسهولة إلى Excel في بضعة أسطر فقط من التعليمات البرمجية. وبالمثل، يمكن تصدير بيانات Excel إلى بيانات JSON.
{{% blocks/products/pf/feature-page-code h3="Python كود تحويل JSON إلى إكسل" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python كود التحويل من Excel إلى JSON" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="تحويل أوراق عمل Excel إلى JPG، BMP، PNG وGIF" %}}
 يمكن تحويل كل ورقة عمل من ملف Excel إلى تنسيقات صور مختلفة[خيارات الصورة أو الطباعة](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat لتعيين تنسيق الصورة.
{{% blocks/products/pf/feature-page-code h3="Python كود تحويل Excel إلى صورة" %}}
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
من الممكن تحميل أي جدول بيانات وتحويله إلى ملفات Word DOCX & PowerPoint PPTX أثناء الاستخدام[DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [خيارات PptxSave](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) الطبقات كما هو موضح أدناه.
{{% blocks/products/pf/feature-page-code h3="كود Python للتحويل من Excel إلى Word والتحويل PowerPoint" %}}
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
