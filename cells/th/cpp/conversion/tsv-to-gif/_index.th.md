---
title: แปลง TSV เป็น GIF ผ่าน C++ แอปพลิเคชัน 
weight: 9540
url: /th/cpp/conversion/tsv-to-gif/ 
description: ตัวอย่างรหัสการแปลง C++ สำหรับเอกสาร TSV เป็นรูปแบบ GIF โปรแกรมเมอร์สามารถใช้ซอร์สโค้ดนี้สำหรับการแปลงแบตช์ TSV เป็น GIF ภายในแอปพลิเคชัน C++ ใดก็ได้
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง TSV เป็น GIF ผ่าน C++" h2="การแปลง TSV เป็น GIF ประสิทธิภาพสูงโดยใช้ไลบรารี C++ โดยไม่ต้องติดตั้ง Microsoft Excel, OpenOffice หรือ Adobe Acrobat" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง TSV เป็น GIF โดยใช้ C++" %}}

 ในการแปลง TSV เป็น GIF เราจะใช้
 [Aspose.Cells สำหรับ C++](https://products.aspose.com/cells/cpp) 
 API ซึ่งเป็นการจัดการและแปลงเอกสารที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย API สำหรับแพลตฟอร์ม C++ คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงแค่เปิด
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 package manager ค้นหา
 Aspose.Cells.Cpp 
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง TSV เป็น GIF ผ่าน C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ นักพัฒนาซอฟต์แวร์สามารถแปลงไฟล์ TSV เป็น GIF ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ TSV โดยใช้ Factory::CreateIWorkbook1. เลือกแผ่นงานแรก1. ตั้งค่าตัวเลือก (GIF)1. วนซ้ำในแต่ละหน้าของชีตและเรนเดอร์1. เปิดไฟล์ GIF ในโปรแกรมที่เข้ากันได้
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ดตัวอย่างการแปลง C++ ตรวจสอบว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต- Aspose.Cells สำหรับ C++ DLL ที่อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSV เป็น GIF C++ ซอร์สโค้ดการแปลง" offSpacer="" %}}

```cs
// เส้นทางไดเรกทอรีผลลัพธ์
StringPtr outDir = new String("OutputDirectoryPath");

// โหลด TSV
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.tsv");

// เข้าถึงแผ่นงานแรก
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// สร้างภาพหรือวัตถุตัวเลือกการพิมพ์
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// ระบุรูปแบบภาพ
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetGif());

// ระบุความละเอียดแนวนอนและแนวตั้ง
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// แสดงผลแผ่นงานตามภาพที่ระบุหรือตัวเลือกการพิมพ์
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// รับจำนวนหน้า
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// สร้างวัตถุตัวสร้างสตริงสำหรับการต่อสายอักขระ
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// แสดงผลแต่ละหน้าเป็นภาพ gif ทีละภาพ
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageGIF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".gif"));

	// รับเส้นทางภาพที่ส่งออก
	StringPtr outputGIF = sb->ToString();

	// แปลงแผ่นงานเป็นภาพ gif
	sr->ToImage(i, outputGIF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="การสาธิตสดการแปลง TSV เป็น GIF" sectionDescription="[แปลง TSV เป็น GIF](https://products.aspose.app/cells/conversion/tsv-to-gif) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ TSV ของคุณ ไฟล์นั้นจะถูกแปลงเป็น GIF ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="C++ ไลบรารีการจัดการไฟล์ Excel" %}}

 สามารถใช้ Excel API เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

รูปแบบไฟล์ Tab-Separated Values (TSV) แสดงถึงข้อมูลที่คั่นด้วยแท็บในรูปแบบข้อความธรรมดา รูปแบบไฟล์คล้ายกับ CSV ใช้สำหรับจัดระเบียบข้อมูลในลักษณะที่มีโครงสร้างเพื่อนำเข้าและส่งออกระหว่างแอปพลิเคชันต่างๆ รูปแบบนี้ใช้สำหรับการนำเข้า/ส่งออกและแลกเปลี่ยนข้อมูลในแอปพลิเคชันสเปรดชีตและฐานข้อมูลเป็นหลัก แต่ละเร็กคอร์ดในไฟล์ TSV จะอยู่ในไฟล์ข้อความบรรทัดเดียว โดยที่แต่ละค่าฟิลด์จะถูกคั่นด้วยอักขระแท็บ ประเภทสื่อสำหรับรูปแบบไฟล์ TSV คือค่าที่คั่นด้วยข้อความ/แท็บ


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

รูปแบบ GIF หรือ Graphical Interchange เป็นประเภทของรูปภาพที่มีการบีบอัดสูง Unisys เป็นเจ้าของ GIF ใช้อัลกอริธึมการบีบอัด LZW ที่ไม่ลดคุณภาพของภาพ สำหรับแต่ละภาพ โดยทั่วไปแล้ว GIF อนุญาตให้ใช้ได้ถึง 8 บิตต่อพิกเซล และอนุญาตให้ใช้สีได้ถึง 256 สีทั่วทั้งภาพ ตรงกันข้ามกับภาพ JPEG ซึ่งสามารถแสดงสีได้มากถึง 16 ล้านสีและสัมผัสได้ถึงขีดจำกัดของสายตามนุษย์ ย้อนกลับไปเมื่ออินเทอร์เน็ตปรากฏขึ้น GIF ยังคงเป็นตัวเลือกที่ดีที่สุด เนื่องจากต้องใช้แบนด์วิดท์ต่ำและเข้ากันได้กับกราฟิกที่ใช้พื้นที่สีทึบ GIF แบบเคลื่อนไหวจะรวมรูปภาพหรือเฟรมจำนวนมากเป็นไฟล์เดียว และแสดงตามลำดับเพื่อสร้างคลิปภาพเคลื่อนไหวหรือวิดีโอสั้น ข้อจำกัดด้านสีสูงสุด 256 สำหรับแต่ละเฟรม และมีแนวโน้มว่าจะเหมาะสมน้อยที่สุดสำหรับการสร้างภาพอื่นๆ และภาพถ่ายที่มีการไล่ระดับสี


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง TSV เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-bmp/" name="TSV เป็น BMP" description="ภาพบิตแมป" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-csv/" name="TSV เป็น CSV" description="ค่าที่คั่นด้วยจุลภาค" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-dif/" name="TSV ถึง DIF" description="รูปแบบการแลกเปลี่ยนข้อมูล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-emf/" name="TSV ถึง EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-html/" name="TSV เป็น HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-jpeg/" name="TSV TO JPEG" description="ภาพ JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-mhtml/" name="TSV เป็น MHTML" description="รูปแบบการเก็บถาวรของหน้าเว็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-ods/" name="TSV ถึง ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-pdf/" name="TSV เป็น PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-png/" name="TSV เป็น PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-svg/" name="TSV ถึง SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-tiff/" name="TSV ถึง TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xls/" name="TSV ถึง XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsb/" name="TSV เป็น XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsm/" name="TSV ถึง XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsx/" name="TSV TO XLSX" description="ไฟล์ OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltm/" name="TSV TO XLTM" description="เทมเพลตที่เปิดใช้งาน Excel Macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltx/" name="TSV TO XLTX" description="เทมเพลต Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xps/" name="TSV เป็น XPS" description="ข้อมูลจำเพาะของกระดาษ XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}