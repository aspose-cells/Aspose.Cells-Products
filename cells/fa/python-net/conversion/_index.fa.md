---
title: Microsoft تبدیل فایل اکسل با استفاده از Python via NET
description: Aspose.Cells for Python از طریق کتابخانه NET. فرمت های EXCEL، JSON، PDF، XML، HTML، TXT، TSV، CSV، SQL و فرمت های بیشتر را تنها با چند خط 076194 تبدیل کنید.
keywords: [Python Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Python]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تبدیل فرمت اکسل از طریق Python" h2="فایل‌های اکسل را به‌صورت صفحه‌گسترده، وب، تصویر و قالب‌بندی ثابت وارد و صادر کنید" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel Library برنامه‌نویسی و فرآیندهای تبدیل صفحه‌گسترده را با پشتیبانی از فرمت‌های محبوب از جمله XLS، XLSX، XLSM، XLSB، XLTX، XLTX، XLTX، 0716113481، XLTX، 0716113481، XLS، XLS، XLTX، XLS، XLTX، 0716163481 6193481. همچنین اجازه می دهد تا فایل های اکسل را به PDF، XPS، HTML، MHTML، ساده صادر کنید. متن و فرمت های تصویری محبوب مانند TIFF، JPG، PNG، BMP و SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تبدیل اکسل به XLSX، ODS، SXC و FODS" %}}
 تبدیل فرمت صفحه گسترده فقط به بارگیری یک صفحه گسترده با یک نمونه از نیاز دارد[کتاب کار](https://reference.aspose.com/cells/python-net/aspose.cells/workbook/) و همزمان با انتخاب مقدار مناسب، در قالب مورد نظر ذخیره کنید[SaveFormat](https://reference.aspose.com/cells/python-net/aspose.cells/saveformat/) شمارش
{{% blocks/products/pf/feature-page-code h3="Python کد برای تبدیل فرمت فایل اکسل" %}}

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


{{% blocks/products/pf/feature-page-section h2="تبدیل اکسل به PDF، XPS، HTML و MD" %}}
 کلاس های تخصصی برای کنترل فرآیند تبدیل برای فرمت های خروجی خاص مانند[PdfSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/pdfsaveoptions/) برای صادرات فایل های اکسل به عنوان PDF،[XpsSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/xpssaveoptions/) برای تبدیل اکسل به XPS،[HtmlSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/htmlsaveoptions/) برای رندر اکسل به صورت HTML و[MarkdownSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/markdownsaveoptions/) برای تبدیل Excel به Markdown
{{% blocks/products/pf/feature-page-code h3="کد Python برای اکسل به PDF و فرمت های وب" %}}

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

{{% blocks/products/pf/feature-page-section h2="تبدیل JSON به اکسل و اکسل به JSON" %}}
توسعه دهندگان Python می توانند به راحتی فایل های JSON را تنها در چند خط کد به اکسل بارگیری و تبدیل کنند. به طور مشابه، داده های اکسل را می توان به داده های JSON صادر کرد.
{{% blocks/products/pf/feature-page-code h3="Python کد تبدیل JSON به اکسل" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python کد برای تبدیل اکسل به JSON" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="تبدیل کاربرگ های اکسل به JPG، BMP، PNG و GIF" %}}
 هر کاربرگ یک فایل اکسل را می توان به فرمت های مختلف تصویر تبدیل کرد، تماس بگیرید[ImageOrPrintOptions](https://reference.aspose.com/cells/python-net/aspose.cells.rendering/imageorprintoptions/)برای تنظیم فرمت تصویر، setImageFormat.
{{% blocks/products/pf/feature-page-code h3="Python کد برای تبدیل اکسل به تصویر" %}}
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

{{% blocks/products/pf/feature-page-section h2="اکسل را به ورد و PowerPoint تبدیل کنید" %}}
امکان بارگذاری هر صفحه گسترده و تبدیل آن به فایل های Word DOCX و PowerPoint PPTX در حین استفاده وجود دارد.[DocxSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/docxsaveoptions/) & [PptxSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/pptxsaveoptions/) کلاس هایی که در زیر نشان داده شده است.
{{% blocks/products/pf/feature-page-code h3="کد Python برای اکسل به ورد و تبدیل PowerPoint" %}}
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

{{< blocks/products/pf/feature-page-options pairs="xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx" >}}
