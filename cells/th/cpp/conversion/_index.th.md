---
title:  Microsoft แปลงไฟล์ Excel ผ่านทาง C++
description: Aspose.Cells for C++ ห้องสมุด. แปลง EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG และรูปแบบอื่นๆ ด้วยโค้ด C++ เพียงไม่กี่บรรทัด
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> แปลงเอกสาร Excel ผ่านทาง C++" h2="บันทึกไฟล์ Excel Microsoft<sup>&reg;</sup> เป็นไฟล์สเปรดชีต เว็บ รูปภาพ และรูปแบบคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
 สำหรับแอปพลิเคชันหรือโซลูชันตัวแปลงสเปรดชีต**C++ เอ็กเซล ไลบรารี่** เพิ่มความเร็วให้กับกระบวนการเขียนโค้ด ระบบอัตโนมัติ และการแปลงในขณะที่จัดการไฟล์หลายไฟล์ รวมถึง XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS นอกจากนี้ยังช่วยให้ *แปลง Excel เป็น PDF**, XPS, HTML, MHTML, ธรรมดา ข้อความและรูปภาพยอดนิยม เช่น JPG, TIFF, PNG, BMP และ SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การแปลงรูปแบบ Excel Microsoft ระหว่างกัน" %}}
 การแปลงระหว่างรูปแบบสเปรดชีตต้องการเพียงการโหลดสเปรดชีตโดยใช้[สมุดงาน](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) และบันทึกใหม่ในรูปแบบที่ต้องการโดยใช้[บันทึก](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) วิธีการของ[สมุดงาน](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) ระดับ.
{{% blocks/products/pf/feature-page-code h3="C++ ตัวอย่างโค้ดสำหรับการแปลงรูปแบบไฟล์ Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="แปลงรูปแบบ Excel เป็น PDF ด้วยการตั้งค่าระดับการปฏิบัติตามข้อกำหนด" %}}
C++ Excel Automation API รองรับการแปลงเวิร์กบุ๊กเป็น PDF รวมถึงรองรับการตั้งค่าระดับการปฏิบัติตามข้อกำหนดและวันที่สร้าง นักพัฒนาสามารถใช้งานได้[ตัวเลือก PdfSave](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) พร้อมด้วย[Aspose::Cells::กำลังเรนเดอร์](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) เพื่อตั้งค่าการปฏิบัติตาม PDF สำหรับการแปลง API วิธีการบันทึกที่มี PdfSaveOptions เป็นพารามิเตอร์และเส้นทางไฟล์เอาต์พุตที่ระบุ
{{% blocks/products/pf/feature-page-code h3="โค้ดตัวอย่าง C++ สำหรับการแปลง Excel เป็น PDF" %}}

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

{{% blocks/products/pf/feature-page-section h2="บันทึก Excel ลงในรูปภาพ" %}}
**C++ เอกเซลพาร์เซอร์** มีความสามารถในการส่งออกข้อมูลในรูปแบบรูปภาพ แต่ละเวิร์กชีตสามารถแปลงเป็นรูปแบบรูปภาพที่แตกต่างกัน ได้แก่ BMP, JPEG, PNG และ GIF ซึ่งกำหนดโดย[การแสดงผล::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . สำหรับอย่างใดอย่างหนึ่ง**แปลง Excel เป็นรูปภาพ** กรณี ให้เลือกกรณีที่เกี่ยวข้องจากลิงก์
{{% blocks/products/pf/feature-page-code h3="C++ รหัสสำหรับการแปลง Excel เป็นรูปภาพ" %}}

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
