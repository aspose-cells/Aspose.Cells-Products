---
title: แปลง HTML เป็น JPEG ผ่าน C++ แอปพลิเคชัน 
weight: 7270
url: /th/cpp/conversion/html-to-jpeg/ 
description: ตัวอย่างโค้ดการแปลง C++ สำหรับเอกสาร HTML เป็นรูปแบบ JPEG โปรแกรมเมอร์สามารถใช้ซอร์สโค้ดนี้สำหรับการแปลง HTML เป็นชุดงานเป็น JPEG ภายในแอปพลิเคชัน C++ ใดๆ
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง HTML เป็น JPEG ผ่าน C++" h2="การแปลง HTML เป็น JPEG ประสิทธิภาพสูงโดยใช้ไลบรารี C++ โดยไม่ต้องติดตั้ง Microsoft Excel, OpenOffice หรือ Adobe Acrobat" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง HTML เป็น JPEG โดยใช้ C++" %}}

 ในการแปลง HTML เป็น JPEG เราจะใช้
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง HTML เป็น JPEG ผ่าน C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ นักพัฒนาซอฟต์แวร์สามารถแปลงไฟล์ HTML เป็น JPEG ได้ง่ายๆ โดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ HTML โดยใช้ Factory::CreateIWorkbook1. เลือกแผ่นงานแรก1. ตั้งค่าตัวเลือก (JPEG)1. วนซ้ำในแต่ละหน้าของชีตและเรนเดอร์1. เปิดไฟล์ JPEG ในโปรแกรมที่เข้ากันได้
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ดตัวอย่างการแปลง C++ ตรวจสอบว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต- Aspose.Cells สำหรับ C++ DLL ที่อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="HTML เป็น JPEG C++ รหัสแหล่งที่มาของการแปลง" offSpacer="" %}}

```cs
// เส้นทางไดเรกทอรีผลลัพธ์
StringPtr outDir = new String("OutputDirectoryPath");

// โหลด HTML
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.html");

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

{{< blocks/products/pf/agp/demobox sectionTitle="การสาธิตการแปลง HTML เป็น JPEG สด" sectionDescription="[แปลง HTML เป็น JPEG](https://products.aspose.app/cells/conversion/html-to-jpeg) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ HTML ของคุณ ไฟล์นั้นจะถูกแปลงเป็น JPEG ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="C++ ไลบรารีการจัดการไฟล์ Excel" %}}

 สามารถใช้ Excel API เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language) เป็นส่วนขยายสำหรับหน้าเว็บที่สร้างขึ้นสำหรับแสดงในเบราว์เซอร์ HTML เป็นที่รู้จักในฐานะภาษาของเว็บ โดยมีการพัฒนาข้อกำหนดของข้อกำหนดข้อมูลใหม่เพื่อแสดงเป็นส่วนหนึ่งของหน้าเว็บ ตัวแปรล่าสุดเรียกว่า HTML 5 ซึ่งให้ความยืดหยุ่นอย่างมากในการทำงานกับภาษา หน้า HTML จะได้รับจากเซิร์ฟเวอร์ซึ่งโฮสต์เหล่านี้หรือสามารถโหลดจากระบบภายในได้เช่นกัน หน้า HTML แต่ละหน้าประกอบด้วยองค์ประกอบ HTML เช่น แบบฟอร์ม ข้อความ รูปภาพ แอนิเมชั่น ลิงก์ ฯลฯ องค์ประกอบเหล่านี้แสดงโดยแท็ก เช่น img, a, p และอื่นๆ อีกหลายอย่างซึ่งแต่ละแท็กมีจุดเริ่มต้นและจุดสิ้นสุด นอกจากนี้ยังสามารถฝังแอปพลิเคชันที่เขียนด้วยภาษาสคริปต์ เช่น JavaScript และสไตล์ชีต (CSS) สำหรับการแสดงเค้าโครงโดยรวม


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

JPEG เป็นรูปแบบรูปภาพประเภทหนึ่งที่บันทึกโดยใช้วิธีการบีบอัดแบบสูญเสียข้อมูล ภาพที่ส่งออกซึ่งเป็นผลมาจากการบีบอัด เป็นการแลกเปลี่ยนระหว่างขนาดพื้นที่จัดเก็บและคุณภาพของภาพ ผู้ใช้สามารถปรับระดับการบีบอัดเพื่อให้ได้ระดับคุณภาพที่ต้องการ ในขณะเดียวกันก็ลดขนาดการจัดเก็บลง คุณภาพของรูปภาพจะได้รับผลกระทบเล็กน้อยหากใช้การบีบอัด 10:1 กับรูปภาพ ยิ่งค่าการบีบอัดสูง คุณภาพของภาพก็จะยิ่งลดลง รูปแบบไฟล์ภาพ JPEG ได้มาตรฐานโดย Joint Photographic Experts Group และด้วยเหตุนี้จึงเรียกว่า JPEG รูปแบบนี้เป็นทางเลือกในการจัดเก็บและส่งภาพถ่ายทางเว็บ ขณะนี้ระบบปฏิบัติการเกือบทั้งหมดมีโปรแกรมดูที่รองรับการแสดงภาพ JPEG ซึ่งมักจะจัดเก็บด้วยนามสกุล JPG เช่นกัน แม้แต่เว็บเบราว์เซอร์ก็สนับสนุนการแสดงภาพ JPEG


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง HTML เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-bmp/" name="HTML เป็น BMP" description="ภาพบิตแมป" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-csv/" name="HTML เป็น CSV" description="ค่าที่คั่นด้วยจุลภาค" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-dif/" name="HTML TO DIF" description="รูปแบบการแลกเปลี่ยนข้อมูล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-emf/" name="HTML เป็น EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-gif/" name="HTML เป็น GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-mhtml/" name="HTML เป็น MHTML" description="รูปแบบการเก็บถาวรของหน้าเว็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-ods/" name="HTML เป็น ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-pdf/" name="HTML เป็น PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-png/" name="HTML เป็น PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-svg/" name="HTML เป็น SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tiff/" name="HTML เป็น TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tsv/" name="HTML เป็น TSV" description="ค่าที่คั่นด้วยแท็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xls/" name="HTML เป็น XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsb/" name="HTML เป็น XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsm/" name="HTML เป็น XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsx/" name="HTML เป็น XLSX" description="ไฟล์ OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltm/" name="HTML เป็น XLTM" description="เทมเพลตที่เปิดใช้งาน Excel Macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltx/" name="HTML เป็น XLTX" description="เทมเพลต Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xps/" name="HTML เป็น XPS" description="ข้อมูลจำเพาะของกระดาษ XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}