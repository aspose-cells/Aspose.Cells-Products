---
title: แปลง XLT เป็น XPS ผ่าน C++ แอปพลิเคชัน 
url: /th/cpp/conversion/xlt-to-xps/ 
description: ตัวอย่างรหัสการแปลง C++ สำหรับเอกสาร XLT เป็นรูปแบบ XPS โปรแกรมเมอร์สามารถใช้ซอร์สโค้ดนี้สำหรับการแปลง XLT เป็น XPS แบบแบตช์ภายในแอปพลิเคชัน C++ ใดๆ
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง XLT เป็น XPS ผ่าน C++" h2="การแปลง XLT เป็น XPS ประสิทธิภาพสูงโดยใช้ไลบรารี C++ โดยไม่ต้องติดตั้ง Microsoft Excel, OpenOffice หรือ Adobe Acrobat" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XPS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง XLT เป็น XPS โดยใช้ C++" %}}

 ในการแปลง XLT เป็น XPS เราจะใช้
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง XLT เป็น XPS ผ่าน C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ นักพัฒนาซอฟต์แวร์สามารถแปลงไฟล์ XLT เป็น XPS ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ XLT โดยใช้ Factory::CreateIWorkbook1. เรียกใช้เมธอด Save()1. ส่งพาธไฟล์เอาต์พุตที่มีนามสกุลไฟล์ (XPS)1. ไฟล์ XPS จะถูกบันทึกที่พาธที่ระบุ1. เปิดไฟล์ XPS ในโปรแกรมที่เข้ากันได้

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ดตัวอย่างการแปลง C++ ตรวจสอบว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต- Aspose.Cells สำหรับ C++ DLL ที่อ้างอิงในโครงการของคุณ
- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต- Aspose.Cells สำหรับ C++ DLL ที่อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLT เป็น XPS C++ รหัสแหล่งที่มาของการแปลง" offSpacer="" %}}

```cs
// โหลด XLT
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlt");

// บันทึกในรูปแบบ XPS
wkb->Save(u"convertedFile.xps", SaveFormat_Xps);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="การสาธิตการแปลง XLT เป็น XPS สด" sectionDescription="[แปลง XLT เป็น XPS](https://products.aspose.app/cells/conversion/xlt-to-xps) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ XLT ของคุณ ไฟล์นั้นจะถูกแปลงเป็น XPS ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="C++ ไลบรารีการจัดการไฟล์ Excel" %}}

 สามารถใช้ Excel API เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}

ไฟล์ที่มีนามสกุล .XLT คือไฟล์เทมเพลตที่สร้างด้วย Microsoft Excel ซึ่งเป็นแอปพลิเคชันสเปรดชีตซึ่งเป็นส่วนหนึ่งของชุดโปรแกรม Microsoft Office Microsoft Office 97-2003 รองรับการสร้างไฟล์ XLT ใหม่และเปิดไฟล์เหล่านี้ Excel เวอร์ชันล่าสุดยังคงสามารถเปิดไฟล์เทมเพลตรูปแบบเก่านี้ได้ ไฟล์เทมเพลตดังกล่าวใช้เพื่อสร้างไฟล์ Excel ใหม่อย่างรวดเร็วด้วยข้อมูลและการตั้งค่าเริ่มต้น เช่น การจัดรูปแบบหน้า ขนาดฟอนต์ ระยะขอบ แผนภูมิ ฯลฯ ซึ่งสามารถบันทึกเพิ่มเติมเป็นไฟล์ .XLS ใหม่ได้

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XPS" readMoreLink="https://docs.fileformat.com/page-description-language/xps/" >}}

ไฟล์ XPS แสดงถึงไฟล์เค้าโครงหน้าที่อิงตามข้อกำหนด XML Paper ที่สร้างโดย Microsoft รูปแบบนี้ได้รับการพัฒนาโดย Microsoft เพื่อแทนที่รูปแบบไฟล์ EMF และคล้ายกับรูปแบบไฟล์ PDF แต่ใช้ XML ในเค้าโครง ลักษณะที่ปรากฏ และข้อมูลการพิมพ์ของเอกสาร ในความเป็นจริง มีเหตุผลมากกว่าที่จะกล่าวว่า XPS เป็นความพยายามใน PDF แต่ไม่สามารถได้รับความนิยมมากพอในฐานะที่เป็นของ PDF ด้วยเหตุผลหลายประการ Microsoft มี XPS Document Writer เป็นค่าเริ่มต้นตั้งแต่ Windows 7 เป็นต้นไปสำหรับการสร้างไฟล์ XPS ไฟล์ XPS สามารถสร้างได้โดยเลือก "Microsoft XPS Document Writer" เป็นเครื่องพิมพ์ขณะพิมพ์เอกสาร

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}