---
title:  แก้ไขหรือดู XLSM เอกสาร Metadata ทาง C++
weight: 1300
description: โค้ดตัวอย่าง C++ เพื่อแก้ไขหรือดูข้อมูลเมตาของไฟล์ XLSM บน C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิตและ Linux 64 บิต
keywords: [C++ Aspose.Cells., C++ view xlsm metadata., C++ add xlsm metadata., C++ insert xlsm metadata., C++ edit xlsm metadata., C++ remove xlsm metadata., C++ extract xlsm metadata., C++ modify xlsm metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แยกข้อมูลเมตา XLSM ผ่าน C++" h2="สร้างแอป C++ ของคุณเองเพื่อเพิ่ม แก้ไข ลบ หรือแยกข้อมูลเมตาจากไฟล์ XLSM โดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีรับข้อมูลเมตา XLSM โดยใช้ C++" %}}

เพื่อแยกข้อมูลเมตา XLSM เราจะใช้
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API ซึ่งเป็นแพลตฟอร์มการแยกข้อมูลเมตาของเอกสารที่มีคุณสมบัติหลากหลาย ทรงพลัง และใช้งานง่าย API for C++ คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงแค่เปิดขึ้นมา
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 ผู้จัดการแพ็คเกจ ค้นหา
 **Aspose.Cells.Cpp** 
 และติดตั้ง คุณอาจใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนการแยก Metadata ของ XLSM ผ่าน C++" %}}

{{% blocks/products/pf/agp/text %}}

 เข้าถึงข้อมูลที่เป็นประโยชน์ที่จัดเก็บไว้ในไฟล์ XLSM รวมถึงเวลาที่ได้รับ ประมวลผล การประทับเวลา และอื่นๆ

{{% /blocks/products/pf/agp/text %}}

+ สร้างตัวเลือกโดยใช้ MetadataOptions
+ โหลดไฟล์ XLSM โดยใช้ WorkbookMetadata
+ เพิ่มคุณสมบัติใหม่โดย GetCustomDocumentProperties() และเพิ่ม
+บันทึกเอกสาร XLSM

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ รองรับแพลตฟอร์มและระบบปฏิบัติการหลักๆ ทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
-  เพิ่มการอ้างอิงถึง Aspose.Cells for C++ DLL ในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="แยกข้อมูลเมตาของ XLSM - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

//Load the sample excel file
MetadataOptions options(MetadataType::Document_Properties);
WorkbookMetadata meta(u"c:\\book1.xlsm", options);
//Add a new custom property
meta.GetCustomDocumentProperties().Add(u"test", u"test");
//Save the output excel file
meta.Save(u"c:\\book2.xlsm"); 

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

        {{< blocks/products/pf/agp/demobox sectionTitle="แยกข้อมูลเมตาของ XLSM ผ่านแอปออนไลน์" sectionDescription=" ดูและแก้ไขข้อมูลเมตาเป็นเอกสาร XLSM โดยใช้ของเรา[การสาธิตสด](https://products.aspose.app/cells/metadata) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ XLSM ของคุณ & แก้ไขคุณสมบัติเอกสาร" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" รับลิงค์ดาวน์โหลดไฟล์ผลลัพธ์ทันที" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
ไฟล์ที่มีนามสกุล XLSM เป็นไฟล์สเปรดชีตประเภทหนึ่งที่รองรับมาโคร จากมุมมองของแอปพลิเคชัน แมโครคือชุดคำสั่งที่ใช้สำหรับกระบวนการอัตโนมัติ แมโครใช้เพื่อบันทึกขั้นตอนที่ดำเนินการซ้ำๆ และอำนวยความสะดวกในการดำเนินการโดยการเรียกใช้แมโครอีกครั้ง แมโครได้รับการตั้งโปรแกรมด้วย Visual Basic for Applications (VBA) ของ Microsoft จากภายในสมุดงาน Excel โดยใช้ Visual Basic Editor และสามารถเรียกใช้/ดีบักได้โดยตรงจากที่นั่น

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบข้อมูลเมตาอื่น ๆ ที่รองรับ" subTitle="การใช้ C++ เราสามารถจัดการข้อมูลเมตาของรูปแบบอื่น ๆ ได้มากมายรวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
