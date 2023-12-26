---
title:  Microsoft تحويل ملفات Excel عبر C++
description: Aspose.Cells for C++ مكتبة. تحويل EXCEL، JSON، PDF، XML، HTML، TXT، TSV، CSV، SQL، JPG، PNG والمزيد من التنسيقات مع بضعة أسطر فقط من الكود C++.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تحويل مستندات Excel عبر C++" h2="احفظ Microsoft<sup>&reg;</sup> ملفات Excel بتنسيقات جداول البيانات والويب والصور والتخطيطات الثابتة" >}}

{{% blocks/products/pf/feature-page-summary %}}
 بالنسبة لأي تطبيق أو حل لتحويل جداول البيانات،**C++ مكتبة اكسيل** يسرع عمليات الترميز والأتمتة والتحويل أثناء التعامل مع ملفات متعددة بما في ذلك XLSX، XLS، XLSM، XLSB، XLTX، XLTM، CSV، SpreadsheetML، ODS. كما يسمح *تحويل Excel إلى PDF**, XPS, HTML, MHTML, عادي النصوص والصور الشائعة مثل JPG وTIFF وPNG وBMP وSVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="التحويل البيني لتنسيقات Excel Microsoft" %}}
 يتطلب التحويل بين تنسيقات جداول البيانات فقط تحميل جدول البيانات باستخدام ملف[دفتر العمل](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) class وإعادة حفظه بالتنسيق المطلوب باستخدام ملف[يحفظ](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) طريقة[دفتر العمل](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) فصل.
{{% blocks/products/pf/feature-page-code h3="C++ رمز المثال لتحويل تنسيق ملف Excel" %}}

```cpp

Aspose::Cells::Startup();

// Load the source excel format.
Workbook wkb(u"src_excel_file.xls");
// Save in required output format.
wkb.Save(u"output_excel_format.xlsx", SaveFormat::Xlsx);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="تحويل تنسيقات Excel إلى PDF باستخدام إعدادات مستوى الامتثال" %}}
C++ يدعم برنامج Excel Automation API تحويل المصنفات إلى PDF بالإضافة إلى دعم تحديد مستوى الامتثال وتاريخ الإنشاء. يمكن للمطورين استخدامها[خيارات حفظ PDF](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) جنبا إلى جنب مع[Aspose::Cells::تقديم](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) لتعيين الامتثال PDF. للتحويل، API طريقة حفظ تحتوي على PdfSaveOptions كمعلمة ومسار ملف الإخراج المحدد.
{{% blocks/products/pf/feature-page-code h3="C++ نموذج التعليمات البرمجية لتحويل Excel إلى PDF" %}}

```cpp

Aspose::Cells::Startup();

// Load the sample Excel file.
Workbook wkb(u"sample-convert-excel-to.pdf");
// Create pdf save options object.
PdfSaveOptions pdfSaveOptions;

// Set the compliance to PDF/A-1b.
pdfSaveOptions.SetCompliance(PdfCompliance::PdfA1b);

// or PdfCompliance::PdfA1a
// for normal PDF it will be PdfCompliance::None

// Save the Excel Document in PDF format
wkb.Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="حفظ Excel إلى الصور" %}}
**C++ محلل اكسل** لديه القدرة على تصدير البيانات في شكل صور. يمكن تحويل كل ورقة عمل إلى تنسيقات صور مختلفة بما في ذلك BMP وJPEG وPNG وGIF، والتي تم تعيينها بواسطة[تقديم::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . لأي**تحويل إكسل إلى صور** الحالة، حدد الحالة ذات الصلة من الروابط.
{{% blocks/products/pf/feature-page-code h3="C++ كود تحويل Excel إلى صورة" %}}

```cpp

Aspose::Cells::Startup();

// Load the XLSX.
Aspose::Cells::Workbook wkb(u"source-excel-file.xlsx");

// Access first worksheet.
Aspose::Cells::Worksheet wks = wkb.GetWorksheets().Get(0);

// Create image or print options object.
Aspose::Cells::Rendering::ImageOrPrintOptions imgOptions;

// Specify the image format. Below code is for JPEG
imgOptions.SetImageType(ImageType::Jpeg);

// For other images like GIF, BMP and PNG one can use ImageType::Gif, ImageType::Bmp and ImageType::Png respectively 

// Specify horizontal and vertical resolution
imgOptions.SetHorizontalResolution(200);
imgOptions.SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
Aspose::Cells::Rendering::SheetRender sr(wks, imgOptions);

// Get page count.
int pageCount = sr.GetPageCount();

std::string sb = "";
// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++) {
	sb = ""; 
	sb += "ImagesOutputDirectoryPath/";
	sb += "outputConvertingWorksheetToImageJPEG_";
	sb += std::to_string(i);
	sb += ".jpeg";
	// Get the output image path.
	U16String outputJPEG(sb.c_str());
	// Convert worksheet to image.
	sr.ToImage(i, outputJPEG);
}

Aspose::Cells::Cleanup();
	
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
