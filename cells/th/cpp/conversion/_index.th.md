---
title: การแปลงไฟล์ Microsoft Excel ผ่าน C++ 

description: แปลง Excel XLS, XLSX, ODS, CSV เป็น PDF, XPS, HTML, JPEG และรูปแบบอื่นๆ ด้วยโค้ด C++ เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงเอกสาร Excel ผ่าน C++" h2="บันทึก Microsoft<sup>&reg;</sup> ไฟล์ Excel เป็นสเปรดชีต เว็บ รูปภาพ และรูปแบบเค้าโครงคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
สำหรับแอปพลิเคชันหรือโซลูชันตัวแปลงสเปรดชีต **C++ ไลบรารี Excel** ช่วยเพิ่มความเร็วในกระบวนการเข้ารหัส การทำงานอัตโนมัติ และการแปลงในขณะที่จัดการไฟล์หลายไฟล์ รวมถึง XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS นอกจากนี้ยังช่วยให้ **แปลง Excel เป็น PDF**, XPS, HTML, MHTML, ข้อความธรรมดา และรูปภาพยอดนิยม เช่น JPG, TIFF, PNG, BMP และ SVG
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="การแปลงระหว่างรูปแบบ Microsoft Excel" %}}
การแปลงรูปแบบสเปรดชีตระหว่างกัน จำเป็นต้องโหลดสเปรดชีตที่มีอินสแตนซ์ของ . เท่านั้น [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ตัวชี้และบันทึกกลับในรูปแบบที่ต้องการโดยใช้ [บันทึก](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) วิธีการของ [คลาส IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ ตัวอย่างโค้ดสำหรับการแปลงรูปแบบไฟล์ Excel" %}}

```cs

// โหลดรูปแบบ excel ต้นทาง
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// บันทึกในรูปแบบเอาต์พุตที่ต้องการ
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="แปลงรูปแบบ Excel เป็น PDF ด้วยการตั้งค่าระดับการปฏิบัติตามข้อกำหนด" %}}
C++ Excel Automation API รองรับการแปลงสมุดงานเป็น PDF ตลอดจนสนับสนุนการตั้งค่าระดับการปฏิบัติตามข้อกำหนดและวันที่สร้าง นักพัฒนาสามารถใช้ [IPdfSaveOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) พร้อมด้วย [Aspose::Cells::กำลังแสดงผล](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) เพื่อตั้งค่าการปฏิบัติตาม PDF สำหรับการแปลง API วิธีบันทึกที่มี PdfSaveOptions เป็นพารามิเตอร์และเส้นทางไฟล์เอาต์พุตที่ระบุ 
{{% blocks/products/pf/feature-page-code h3="C++ โค้ดตัวอย่างสำหรับการแปลง Excel เป็น PDF" %}}

```cs
// โหลดไฟล์ตัวอย่าง Excel
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// สร้างวัตถุตัวเลือกบันทึก pdf
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// ตั้งค่าการปฏิบัติตาม PDF/A-1b
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// หรือ PdfCompliance_PdfA1a 
// สำหรับ PDF ปกติจะเป็น PdfCompliance_None

// บันทึกเอกสาร Excel ในรูปแบบ PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="บันทึก Excel เป็นรูปภาพ" %}}
**C++ Excel Parser** มีความสามารถในการส่งออกข้อมูลในรูปของรูปภาพ แผ่นงานแต่ละแผ่นสามารถแปลงเป็นรูปแบบภาพต่างๆ รวมทั้ง BMP, JPEG, PNG และ GIF ที่กำหนดโดย [การแสดงผล::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). สำหรับกรณี **แปลง Excel เป็นรูปภาพ** ให้เลือกกรณีที่เกี่ยวข้องจากลิงก์
{{% blocks/products/pf/feature-page-code h3="C++ โค้ดสำหรับ Excel เป็นการแปลงรูปภาพ" %}}

```cs
// เส้นทางไดเรกทอรีผลลัพธ์
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// โหลด XLSX
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// เข้าถึงแผ่นงานแรก
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// สร้างภาพหรือวัตถุตัวเลือกการพิมพ์
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// ระบุรูปแบบภาพ รหัสด้านล่างสำหรับ JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// สำหรับรูปภาพอื่นๆ เช่น GIF, BMP และ PNG สามารถใช้ GetGif(), GetBmp() และ GetPng() ตามลำดับ 

// ระบุความละเอียดแนวนอนและแนวตั้ง
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// แสดงผลแผ่นงานตามภาพที่ระบุหรือตัวเลือกการพิมพ์
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// รับจำนวนหน้า
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// สร้างวัตถุตัวสร้างสตริงสำหรับการต่อสายอักขระ
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// แสดงผลแต่ละหน้าเป็นภาพ jpeg ทีละภาพ
for (int i = 0; i < pageCount; i++){
	// ล้างตัวสร้างสตริงและสร้างพา ธ อิมเมจเอาต์พุตด้วยการต่อสตริง
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// รับเส้นทางภาพที่ส่งออก
	StringPtr outputJPEG = sb->ToString();
	// แปลงแผ่นงานเป็นรูปภาพ
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
