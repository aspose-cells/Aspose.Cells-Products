---
title:  Microsoft การแปลงไฟล์ Excel ผ่าน C++
description: แปลง Excel XLS, XLSX, ODS, CSV เป็น PDF, XPS, HTML, JPEG และรูปแบบอื่นๆ ด้วยรหัส C++ เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงเอกสาร Excel ผ่าน C++" h2="บันทึก Microsoft<sup>&reg;</sup> ไฟล์ Excel เป็นรูปแบบสเปรดชีต เว็บ รูปภาพ และเค้าโครงคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
 สำหรับแอปพลิเคชันหรือโซลูชันตัวแปลงสเปรดชีตใดๆ**C++ คลังเอ็กเซล**เร่งความเร็วการเข้ารหัส ระบบอัตโนมัติ และกระบวนการแปลงในขณะที่จัดการไฟล์หลายไฟล์รวมถึง XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS นอกจากนี้ยังช่วยให้ *con เปลี่ยน Excel เป็น PDF**, XPS, HTML, MHTML, ธรรมดา ข้อความและรูปภาพยอดนิยม เช่น JPG, TIFF, PNG, BMP และ SVG
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การแปลงระหว่างรูปแบบ Excel Microsoft" %}}
 การแปลงรูปแบบสเปรดชีตระหว่างกันจำเป็นต้องโหลดสเปรดชีตที่มีอินสแตนซ์ของ[ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ตัวชี้และบันทึกกลับในรูปแบบที่ต้องการโดยใช้[บันทึก](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) วิธีการ[คลาส iWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ ตัวอย่างโค้ดการแปลงรูปแบบไฟล์ Excel" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="แปลงรูปแบบ Excel เป็น PDF ด้วยการตั้งค่าระดับการปฏิบัติตามข้อกำหนด" %}}
 C++ Excel Automation API รองรับการแปลงสมุดงานเป็น PDF รวมทั้งรองรับการตั้งค่าระดับความสอดคล้องและวันที่สร้าง นักพัฒนาสามารถใช้[ตัวเลือก IPdfSave](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) พร้อมด้วย[Aspose::Cells::เรนเดอร์](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering)เพื่อตั้งค่าการปฏิบัติตาม PDF สำหรับการแปลง API วิธีการบันทึกที่มี PdfSaveOptions เป็นพารามิเตอร์และเส้นทางไฟล์เอาต์พุตที่ระบุ
{{% blocks/products/pf/feature-page-code h3="C++ โค้ดตัวอย่างสำหรับการแปลง Excel เป็น PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="บันทึก Excel เป็นรูปภาพ" %}}
**C++ โปรแกรมแยกวิเคราะห์ Excel** มีความสามารถในการส่งออกข้อมูลในรูปแบบรูปภาพ แผ่นงานแต่ละแผ่นสามารถแปลงเป็นรูปแบบภาพต่างๆ รวมถึง BMP, JPEG, PNG และ GIF ตั้งค่าโดย[การแสดงผล::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . สำหรับใดๆ**แปลง Excel เป็นรูปภาพ** กรณี เลือกกรณีที่เกี่ยวข้องจากลิงค์
{{% blocks/products/pf/feature-page-code h3="C++ รหัสสำหรับการแปลง Excel เป็นรูปภาพ" %}}

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
