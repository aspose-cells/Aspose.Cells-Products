---
title: แปลง XLSM เป็น XML ผ่าน C++ แอปพลิเคชัน 
url: /th/cpp/conversion/xlsm-to-xml/ 
description: ตัวอย่างโค้ดการแปลง C++ สำหรับเอกสาร XLSM เป็นรูปแบบ XML โปรแกรมเมอร์สามารถใช้ซอร์สโค้ดนี้สำหรับการแปลง XLSM เป็น XML แบบแบตช์ภายในแอปพลิเคชัน C++ ใดๆ
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง XLSM เป็น XML ผ่าน C++" h2="การแปลง XLSM เป็น XML ประสิทธิภาพสูงโดยใช้ไลบรารี C++ โดยไม่ต้องติดตั้ง Microsoft Excel, OpenOffice หรือ Adobe Acrobat" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง XLSM เป็น XML โดยใช้ C++" %}}

 ในการแปลง XLSM เป็น XML เราจะใช้
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง XLSM เป็น XML ผ่าน C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ นักพัฒนาซอฟต์แวร์สามารถแปลงไฟล์ XLSM เป็น XML ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ XLSM โดยใช้ Factory::CreateIWorkbook1. เรียกใช้เมธอด Save()1. ส่งพาธไฟล์เอาต์พุตที่มีนามสกุลไฟล์ (XML)1. ไฟล์ XML จะถูกบันทึกในเส้นทางที่ระบุ1. เปิดไฟล์ XML ในโปรแกรมที่เข้ากันได้

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ดตัวอย่างการแปลง C++ ตรวจสอบว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต- Aspose.Cells สำหรับ C++ DLL ที่อ้างอิงในโครงการของคุณ
- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต- Aspose.Cells สำหรับ C++ DLL ที่อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSM เป็น XML C++ ซอร์สโค้ดการแปลง" offSpacer="" %}}

```cs
// โหลด XLSM
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsm");

// บันทึกในรูปแบบ XML
wkb->Save(u"convertedFile.xml", SaveFormat_Xml);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="การสาธิตสดการแปลง XLSM เป็น XML" sectionDescription="[แปลง XLSM เป็น XML](https://products.aspose.app/cells/conversion/xlsm-to-xml) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ XLSM ไฟล์นั้นจะถูกแปลงเป็น XML ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="C++ ไลบรารีการจัดการไฟล์ Excel" %}}

 สามารถใช้ Excel API เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}

ไฟล์ที่มีนามสกุล XLSM เป็นไฟล์สเปรดชีตประเภทหนึ่งที่รองรับมาโคร จากมุมมองของแอปพลิเคชัน Macro คือชุดคำสั่งที่ใช้สำหรับกระบวนการอัตโนมัติ แมโครใช้เพื่อบันทึกขั้นตอนที่ดำเนินการซ้ำ ๆ และอำนวยความสะดวกในการดำเนินการโดยการเรียกใช้แมโครอีกครั้ง แมโครได้รับการตั้งโปรแกรมด้วย Visual Basic for Applications (VBA) ของ Microsoft จากภายในสมุดงาน Excel โดยใช้ Visual Basic Editor และสามารถเรียกใช้/แก้ไขจุดบกพร่องได้โดยตรงจากที่นั่น

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" >}}

XML ย่อมาจาก Extensible Markup Language ที่คล้ายกับ HTML แต่แตกต่างกันในการใช้แท็กเพื่อกำหนดวัตถุ แนวคิดเบื้องหลังการสร้างรูปแบบไฟล์ XML คือการจัดเก็บและขนส่งข้อมูลโดยไม่ต้องพึ่งพาซอฟต์แวร์หรือเครื่องมือฮาร์ดแวร์ ความนิยมนั้นเกิดจากการที่ทั้งมนุษย์และคอมพิวเตอร์สามารถอ่านได้ ซึ่งช่วยให้สามารถสร้างโปรโตคอลข้อมูลทั่วไปในรูปแบบของอ็อบเจ็กต์ที่จะจัดเก็บและแชร์ผ่านเครือข่าย เช่น World Wide Web (WWW) "X" ใน XML ใช้สำหรับขยายได้ ซึ่งหมายความว่าสามารถขยายภาษาไปยังสัญลักษณ์จำนวนเท่าใดก็ได้ตามความต้องการของผู้ใช้ สำหรับคุณสมบัติเหล่านี้ที่รูปแบบไฟล์มาตรฐานจำนวนมากใช้งานได้ เช่น Microsoft Open XML, LibreOffice OpenDocument, XHTML และ SVG

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}