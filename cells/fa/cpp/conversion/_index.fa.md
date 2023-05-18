---
title:  Microsoft تبدیل فایل اکسل از طریق C++
description: اکسل XLS، XLSX، ODS، CSV را به PDF، XPS، HTML، HTML، JPEG، JPEG، JPEG، ODS و سایر فرمت های کد 438 و سایر فرمت های PDF تبدیل کنید.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> تبدیل سند اکسل از طریق C++" h2="Microsoft<sup>&reg;</sup> فایل های Excel را به صورت صفحه گسترده، وب، تصویر و فرمت های طرح بندی ثابت ذخیره کنید" >}}

{{% blocks/products/pf/feature-page-summary %}}
 برای هر برنامه یا راه حل مبدل صفحه گسترده،**C++ کتابخانه اکسل**فرآیندهای کدنویسی، اتوماسیون و تبدیل را در حین مدیریت چندین فایل از جمله XLSX، XLS، XLSM، XLSB، XLTX، XLTM، XLTM، XLSX، XLSX، XLSX، XLSX، XLSX، XLSX امکان *تبدیل اکسل به PDF**، XPS، HTML، MHTML، ساده متن و تصاویر پرطرفدار مانند JPG، TIFF، PNG، BMP و SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="تبدیل بین Microsoft فرمت های اکسل" %}}
 تبدیل فرمت صفحه گسترده فقط به بارگیری یک صفحه گسترده با یک نمونه از نیاز دارد[ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) اشاره گر و ذخیره مجدد در فرمت دلخواه با استفاده از[صرفه جویی](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) روش از[کلاس IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ کد مثال برای تبدیل فرمت فایل اکسل" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="با تنظیمات سطح انطباق، فرمت های اکسل را به PDF تبدیل کنید" %}}
 C++ Excel Automation API از تبدیل Workbookها به PDF و همچنین پشتیبانی از تنظیم سطح انطباق و تاریخ ایجاد پشتیبانی می کند. توسعه دهندگان می توانند استفاده کنند[IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) همراه با[Aspose::Cells:: رندر](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering)برای تنظیم انطباق PDF. برای تبدیل، API روش ذخیره با داشتن PdfSaveOptions به عنوان پارامتر و مسیر فایل خروجی مشخص شده است.
{{% blocks/products/pf/feature-page-code h3="C++ نمونه کد برای تبدیل اکسل به PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="اکسل را در تصاویر ذخیره کنید" %}}
**C++ تجزیه کننده اکسل** قابلیت صادرات داده ها به صورت تصویر را دارد. هر کاربرگ را می توان به فرمت های تصویری مختلف از جمله BMP، JPEG، PNG و GIF تبدیل کرد که توسط[Rendering::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . برای هرچی**تبدیل اکسل به تصاویر** مورد، مورد مربوطه را از لینک ها انتخاب کنید.
{{% blocks/products/pf/feature-page-code h3="C++ کد برای تبدیل اکسل به تصویر" %}}

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
