---
title: تحويل ملف Microsoft Excel عبر C++ 
url: /ar/cpp/conversion/
description: تحويل ملفات Excel XLS و XLSX و ODS و CSV إلى PDF و XPS و HTML و JPEG وغيرها من التنسيقات باستخدام سطور قليلة فقط من C++ التعليمات البرمجية.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg؛ </sup> تحويل مستند Excel عبر C++" h2="حفظ ملفات Microsoft <sup> & reg؛ </sup> Excel كجداول بيانات وتنسيقات ويب وصورة وتنسيقات ذات تخطيط ثابت" >}}

{{% blocks/products/pf/feature-page-summary %}}
بالنسبة إلى أي تطبيق أو حل لتحويل جداول البيانات ، تعمل ** C++ Excel Library ** على تسريع عمليات الترميز والأتمتة والتحويل أثناء التعامل مع ملفات متعددة بما في ذلك XLSX و XLS و XLSM و XLSB و XLTX و XLTM و CSV و SpreadsheetML و ODS. كما يسمح ** بتحويل Excel إلى PDF ** و XPS و HTML و MHTML و Plain Text والصور الشائعة مثل JPG و TIFF و PNG و BMP و SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="التحويل البيني لتنسيقات Microsoft Excel" %}}
لا يتطلب التحويل البيني لتنسيق جدول البيانات سوى تحميل جدول بيانات بمثيل [ intrusive_ptr <Aspose :: Cells :: IWorkbook>](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) المؤشر والحفظ مرة أخرى بالتنسيق المطلوب باستخدام [يحفظ](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) طريقة [فئة IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ رمز مثال لتحويل تنسيق ملف Excel" %}}

```cs

// تحميل تنسيق اكسل المصدر.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// احفظ بتنسيق الإخراج المطلوب.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="قم بتحويل تنسيقات Excel إلى PDF باستخدام إعدادات مستوى الامتثال" %}}
يدعم C++ Excel Automation API تحويل مصنفات العمل إلى PDF بالإضافة إلى دعم إعداد مستوى الامتثال وتاريخ الإنشاء. يمكن للمطورين استخدام ملفات [IPdfSaveOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) جنبا إلى جنب مع [Aspose :: Cells :: عرض](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) لتعيين التوافق مع PDF. للتحويل ، API احفظ الطريقة التي تحتوي على PdfSaveOptions كمعامل ومسار ملف الإخراج المحدد. 
{{% blocks/products/pf/feature-page-code h3="C++ نموذج كود لتحويل Excel إلى PDF" %}}

```cs
// قم بتحميل نموذج ملف Excel.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// إنشاء كائن خيارات حفظ pdf.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// اضبط التوافق على PDF / A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// أو PdfCompliance_PdfA1a 
// بالنسبة لملف PDF العادي ، سيكون PdfCompliance_None

// احفظ مستند Excel بتنسيق PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="حفظ Excel في الصور" %}}
** C++ Excel Parser ** لديه القدرة على تصدير البيانات في شكل صور. يمكن تحويل كل ورقة عمل إلى تنسيقات صور مختلفة بما في ذلك BMP و JPEG و PNG و GIF ، التي حددها ملف [تقديم :: IImageOrPrintOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). لأي حالة ** تحويل Excel إلى صور ** ، حدد الحالة ذات الصلة من الروابط.
{{% blocks/products/pf/feature-page-code h3="C++ كود لبرنامج Excel لتحويل الصورة" %}}

```cs
// مسار دليل الإخراج.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// قم بتحميل ملف XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// الوصول إلى ورقة العمل الأولى.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// إنشاء صورة أو كائن خيارات الطباعة.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// حدد تنسيق الصورة. الكود أدناه لـ JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// بالنسبة للصور الأخرى مثل GIF و BMP و PNG ، يمكن للمرء استخدام GetGif () و GetBmp () و GetPng () على التوالي 

// حدد الدقة الأفقية والعمودية
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// تجسيد الورقة فيما يتعلق بالصورة المحددة أو خيارات الطباعة.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// احصل على عدد الصفحات.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// إنشاء كائن منشئ السلسلة لسلسلة السلاسل.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// اعرض كل صفحة على صورة بتنسيق jpeg واحدة تلو الأخرى.
for (int i = 0; i < pageCount; i++){
	// امسح أداة إنشاء السلاسل وأنشئ مسار صورة الإخراج باستخدام سلاسل السلسلة.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// احصل على مسار الصورة الناتجة.
	StringPtr outputJPEG = sb->ToString();
	// تحويل ورقة العمل إلى صورة.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}