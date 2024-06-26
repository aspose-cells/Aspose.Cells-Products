---
title: ค้นหาและแทนที่ข้อความในเอกสาร XLSM ผ่าน C++
weight: 9570
description: โค้ดตัวอย่าง C++ เพื่อตรวจทานข้อมูลที่ละเอียดอ่อนในไฟล์ XLSM บน C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
keywords: [C++ Aspose.Cells., C++ Search and replace text in XLSM file., C++ redact XLSM file., C++ edit XLSM file., C++ XLSM file redaction., C++ Search and replace string in XLSM file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แก้ไข XLSM รูปแบบใน C++" h2="ข้อมูลการแก้ไขที่ละเอียดอ่อนของเอกสาร XLSM แบบเนทีฟและประสิทธิภาพสูงโดยใช้ API ฝั่งเซิร์ฟเวอร์ Aspose.Cells for C++ โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Adobe PDF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแก้ไขไฟล์ XLSM โดยใช้ C++" %}}

 เพื่อทำการปกปิดไฟล์ XLSM เราจะใช้[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) API ซึ่งเป็นแพลตฟอร์มตรวจทานเอกสารที่มีคุณสมบัติหลากหลาย ทรงพลัง และใช้งานง่าย API for C++ คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงแค่เปิดขึ้นมา[NuGet](https://www.nuget.org/packages/aspose.cells) ผู้จัดการแพ็คเกจ ค้นหา**Aspose.Cells.Cpp** และติดตั้ง คุณอาจใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการทำซ้ำไฟล์ XLSM ใน C++" %}}

{{% blocks/products/pf/agp/text %}}

 การค้นหาเอกสารขั้นพื้นฐานและแทนที่ข้อความในเนื้อหา ความคิดเห็น หรือข้อมูลเมตาด้วย[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) API สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

+โหลดไฟล์XLSM.
+ กำหนดตัวเลือกการแทนที่
ตั้งค่าตัวเลือกความไวของตัวพิมพ์เล็กและตัวพิมพ์ใหญ่
+ ตั้งค่าตัวเลือกการจับคู่ข้อความ
+ แทนที่ข้อความโดยใช้วิธีแทนที่ (...)
+ บันทึกสมุดงาน

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ รองรับแพลตฟอร์มและระบบปฏิบัติการหลักๆ ทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
-  เพิ่มการอ้างอิงถึง Aspose.Cells for C++ DLL ในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ตรวจทานไฟล์ XLSM - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Load XLSM file
Workbook wb(u"Input.xlsm");
//Create an instance of the ReplaceOptions class
ReplaceOptions replaceOptions;
// Set text matching option
replaceOptions.SetRegexKey(true);
// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);
// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);
// Replace text
wb.Replace(u"\bKIM\b", u"^^^^^^^^", replaceOptions);
// Save as XLSM file
wb.Save("output.xlsm");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for C++ API" %}}

 Aspose.Cells API สามารถใช้สร้าง แก้ไข แปลง และเรนเดอร์รูปแบบ Excel Microsoft เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็น API แบบสแตนด์อโลน และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="ออนไลน์ XLSM Redaction สาธิตสด" sectionDescription=" ค้นหาและแทนที่ข้อความในเนื้อหา ความคิดเห็น หรือข้อมูลเมตาในเอกสาร XLSM ทันทีโดยไปที่[เว็บไซต์สาธิตสด](https://products.aspose.app/cells/redaction)- การสาธิตสดมีข้อดีดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่ต้องดาวน์ Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัพโหลดไฟล์ XLSM ของคุณ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" มันจะถูกแก้ไขทันที" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
ไฟล์ที่มีนามสกุล XLSM เป็นไฟล์สเปรดชีตประเภทหนึ่งที่รองรับมาโคร จากมุมมองของแอปพลิเคชัน แมโครคือชุดคำสั่งที่ใช้สำหรับกระบวนการอัตโนมัติ แมโครใช้เพื่อบันทึกขั้นตอนที่ดำเนินการซ้ำๆ และอำนวยความสะดวกในการดำเนินการโดยการเรียกใช้แมโครอีกครั้ง แมโครได้รับการตั้งโปรแกรมด้วย Visual Basic for Applications (VBA) ของ Microsoft จากภายในสมุดงาน Excel โดยใช้ Visual Basic Editor และสามารถเรียกใช้/ดีบักได้โดยตรงจากที่นั่น

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="เอกสารการแก้ไขอื่น ๆ ที่รองรับ" subTitle="การใช้ C++ ทำให้สามารถแก้ไขรูปแบบต่างๆ ได้อย่างง่ายดาย รวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
