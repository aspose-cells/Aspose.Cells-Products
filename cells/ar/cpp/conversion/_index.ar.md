---
title:  Microsoft تحويل ملف Excel عبر C++
description: تحويل Excel XLS ، XLSX ، ODS ، CSV إلى PDF ، XPS ، HTML ، JPEG وغيرها من التنسيقات ذات الأسطر القليلة فقط من C++ كود.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> تحويل مستند Excel عبر C++" h2="حفظ Microsoft <sup> & reg؛ </sup> ملفات Excel كجداول بيانات وتنسيقات ويب وصورة وتنسيقات ذات تخطيط ثابت" >}}

{{% blocks/products/pf/feature-page-summary %}}
 لأي تطبيق أو حل لتحويل جداول البيانات ،**C++ مكتبة Excel** تسريع عمليات الترميز والأتمتة والتحويل أثناء التعامل مع ملفات متعددة بما في ذلك XLSX ، XLS ، XLSM ، XLSB ، XLTX ، XLTM ، CSV ، SpreadsheetML ، ODS ، كما يسمح بتحويل Excel إلى PDF ** ، XLS ، XLS ** ، XLS ، * النصوص والصور الشائعة مثل JPG و TIFF و PNG و BMP و SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="التحويل البيني Microsoft تنسيقات Excel" %}}
 لا يتطلب التحويل البيني لتنسيق جدول البيانات سوى تحميل جدول بيانات بمثيل[ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) المؤشر والحفظ مرة أخرى بالتنسيق المطلوب باستخدام[يحفظ](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) طريقة[فئة IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ رمز مثال لتحويل تنسيق ملف Excel" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="قم بتحويل تنسيقات Excel إلى PDF باستخدام إعدادات مستوى التوافق" %}}
 C++ Excel Automation API يدعم تحويل مصنفات العمل إلى PDF بالإضافة إلى دعم إعداد مستوى التوافق وتاريخ الإنشاء. يمكن للمطورين استخدام ملفات[IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) جنبا إلى جنب مع[Aspose :: Cells :: التقديم](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) لضبط التوافق PDF. للتحويل ، API حفظ الأسلوب الذي يحتوي على PdfSaveOptions كمعامل ومسار ملف الإخراج المحدد.
{{% blocks/products/pf/feature-page-code h3="C++ نموذج كود للتحويل من Excel إلى PDF" %}}

```cs
// Load the sample Excel file.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Create pdf save options object.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Set the compliance to PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// or PdfCompliance_PdfA1a 
// for normal PDF it will be PdfCompliance_None

// Save the Excel Document in PDF format
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="حفظ Excel في الصور" %}}
**C++ محلل اكسل** لديه القدرة على تصدير البيانات في شكل صور. يمكن تحويل كل ورقة عمل إلى تنسيقات صور مختلفة بما في ذلك BMP و JPEG و PNG و GIF ، تم تعيينها بواسطة[تقديم :: IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . لأي**تحويل Excel إلى صور** الحالة ، حدد الحالة ذات الصلة من الروابط.
{{% blocks/products/pf/feature-page-code h3="C++ كود لتحويل Excel إلى صورة" %}}

```cs
// Output directory path.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Load the XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Access first worksheet.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Create image or print options object.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Specify the image format. Below code is for JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// For other images like GIF, BMP and PNG one can use GetGif(), GetBmp() and GetPng() respectively 

// Specify horizontal and vertical resolution
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Get page count.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Create string builder object for string concatenations.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++){
	// Clear string builder and create output image path with string concatenations.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Get the output image path.
	StringPtr outputJPEG = sb->ToString();
	// Convert worksheet to image.
	sr->ToImage(i, outputJPEG);
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
