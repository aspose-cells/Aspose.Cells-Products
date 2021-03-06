---
title: แปลง JSON เป็น JPEG ผ่าน C++ แอปพลิเคชัน 
url: /th/cpp/conversion/json-to-jpeg/ 
description: ตัวอย่างรหัสการแปลง C++ สำหรับเอกสาร JSON เป็นรูปแบบ JPEG โปรแกรมเมอร์สามารถใช้ซอร์สโค้ดนี้สำหรับการแปลง JSON เป็น JPEG แบบแบตช์ภายในแอปพลิเคชัน C++ ใดๆ
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง JSON เป็น JPEG ผ่าน C++" h2="การแปลง JSON เป็น JPEG ประสิทธิภาพสูงโดยใช้ไลบรารี C++ โดยไม่ต้องติดตั้ง Microsoft Excel, OpenOffice หรือ Adobe Acrobat" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JSON" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง JSON เป็น JPEG โดยใช้ C++" %}}

 ในการแปลง JSON เป็น JPEG เราจะใช้
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง JSON เป็น JPEG ผ่าน C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ นักพัฒนาซอฟต์แวร์สามารถแปลงไฟล์ JSON เป็น JPEG ได้อย่างง่ายดายโดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ JSON โดยใช้ Factory::CreateIWorkbook1. เลือกแผ่นงานแรก1. ตั้งค่าตัวเลือก (JPEG)1. วนซ้ำในแต่ละหน้าของชีตและเรนเดอร์1. เปิดไฟล์ JPEG ในโปรแกรมที่เข้ากันได้

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ดตัวอย่างการแปลง C++ ตรวจสอบว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต- Aspose.Cells สำหรับ C++ DLL ที่อ้างอิงในโครงการของคุณ
- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต- Aspose.Cells สำหรับ C++ DLL ที่อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="JSON เป็น JPEG C++ ซอร์สโค้ดการแปลง" offSpacer="" %}}

```cs
// เส้นทางไดเรกทอรีผลลัพธ์
StringPtr outDir = new String("OutputDirectoryPath");

// โหลด JSON
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.json");

// เข้าถึงแผ่นงานแรก
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// สร้างภาพหรือวัตถุตัวเลือกการพิมพ์
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// ระบุรูปแบบภาพ
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// ระบุความละเอียดแนวนอนและแนวตั้ง
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// แสดงผลแผ่นงานตามภาพที่ระบุหรือตัวเลือกการพิมพ์
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// รับจำนวนหน้า
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// สร้างวัตถุตัวสร้างสตริงสำหรับการต่อสายอักขระ
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// แสดงผลแต่ละหน้าเป็นภาพ jpeg ทีละภาพ
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));

	// รับเส้นทางภาพที่ส่งออก
	StringPtr outputJPEG = sb->ToString();

	// แปลงแผ่นงานเป็นภาพ jpeg
	sr->ToImage(i, outputJPEG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="JSON เป็น JPEG Conversion การสาธิตสด" sectionDescription="[แปลง JSON เป็น JPEG](https://products.aspose.app/cells/conversion/json-to-jpeg) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ JSON ของคุณ ไฟล์นั้นจะถูกแปลงเป็น JPEG ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="C++ ไลบรารีการจัดการไฟล์ Excel" %}}

 สามารถใช้ Excel API เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (JavaScript Object Notation) เป็นรูปแบบไฟล์มาตรฐานแบบเปิดสำหรับการแบ่งปันข้อมูลที่ใช้ข้อความที่มนุษย์สามารถอ่านได้เพื่อจัดเก็บและส่งข้อมูล ไฟล์ JSON ถูกจัดเก็บด้วยนามสกุล .json JSON ต้องการการจัดรูปแบบน้อยกว่าและเป็นทางเลือกที่ดีสำหรับ XML JSON มาจาก JavaScript แต่เป็นรูปแบบข้อมูลที่ไม่ขึ้นกับภาษา การสร้างและการแยกวิเคราะห์ JSON ได้รับการสนับสนุนโดยภาษาโปรแกรมสมัยใหม่หลายภาษา application/json เป็นประเภทสื่อที่ใช้สำหรับ JSON

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

JPEG เป็นรูปแบบรูปภาพประเภทหนึ่งที่บันทึกโดยใช้วิธีการบีบอัดแบบสูญเสียข้อมูล ภาพที่ส่งออกซึ่งเป็นผลมาจากการบีบอัด เป็นการแลกเปลี่ยนระหว่างขนาดพื้นที่จัดเก็บและคุณภาพของภาพ ผู้ใช้สามารถปรับระดับการบีบอัดเพื่อให้ได้ระดับคุณภาพที่ต้องการ ในขณะเดียวกันก็ลดขนาดการจัดเก็บลง คุณภาพของรูปภาพจะได้รับผลกระทบเล็กน้อยหากใช้การบีบอัด 10:1 กับรูปภาพ ยิ่งค่าการบีบอัดสูง คุณภาพของภาพก็จะยิ่งลดลง รูปแบบไฟล์ภาพ JPEG ได้มาตรฐานโดย Joint Photographic Experts Group และด้วยเหตุนี้จึงเรียกว่า JPEG รูปแบบนี้เป็นทางเลือกในการจัดเก็บและส่งภาพถ่ายทางเว็บ ขณะนี้ระบบปฏิบัติการเกือบทั้งหมดมีโปรแกรมดูที่รองรับการแสดงภาพ JPEG ซึ่งมักจะจัดเก็บด้วยนามสกุล JPG เช่นกัน แม้แต่เว็บเบราว์เซอร์ก็สนับสนุนการแสดงภาพ JPEG

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}