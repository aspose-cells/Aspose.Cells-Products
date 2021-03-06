---
title: แก้ไขหรือดูข้อมูลเมตาของเอกสาร XLS ผ่าน C++ 
weight: 2150
url: /th/cpp/metadata/xls/ 
description: C++ ตัวอย่างโค้ดเพื่อแก้ไขหรือดูข้อมูลเมตาของไฟล์ XLS บน C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แยกข้อมูลเมตา XLS ผ่าน C++" h2="สร้างแอป C++ ของคุณเองเพื่อเพิ่ม แก้ไข ลบ หรือแยกข้อมูลเมตาจากไฟล์ XLS โดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีรับข้อมูลเมตา XLS โดยใช้ C++" %}}

 ในการแยกข้อมูลเมตา XLS เราจะใช้
 [Aspose.Cells สำหรับ C++](https://products.aspose.com/cells/cpp) 
 API ซึ่งเป็นการดึงข้อมูลเมตาของเอกสารที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย API สำหรับแพลตฟอร์ม C++ คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงแค่เปิด
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 package manager ค้นหา
 **Aspose.Cells.Cpp** 
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการดึงข้อมูลเมตาของ XLS ผ่าน C++" %}}

{{% blocks/products/pf/agp/text %}}

 เข้าถึงข้อมูลที่เป็นประโยชน์ซึ่งจัดเก็บไว้ในไฟล์ XLS รวมถึงเวลาที่ได้รับไฟล์ XLS ประมวลผล ประทับเวลา และอื่นๆ

{{% /blocks/products/pf/agp/text %}}

+ โหลดไฟล์ XLS โดยใช้ CreateIWorkbookMetadata
+ สร้างตัวเลือกโดยใช้ CreateIMetadataOptions
+ เพิ่มคุณสมบัติใหม่โดย GetICustomDocumentProperties() และ AddIDocumentProperty
+ บันทึกเอกสาร XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells สำหรับ C++ รองรับบนแพลตฟอร์มหลักและระบบปฏิบัติการทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต- Aspose.Cells สำหรับ C++ DLL ที่อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="แยกข้อมูลเมตาของ XLS - C++" offSpacer="" %}}

```cs

intrusive_ptr<IMetadataOptions> options = Factory::CreateIMetadataOptions(MetadataType_DocumentProperties);
intrusive_ptr<IWorkbookMetadata> meta = Factory::CreateIWorkbookMetadata(new String("c:\\book1.xls"), options);
meta->GetICustomDocumentProperties()->AddIDocumentProperty(new String("test"), (StringPtr)new String("test"));
meta->Save(new String("c:\\book2.xls"));  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells สำหรับ C++ API" %}}

 Aspose.Cells API สามารถใช้เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="แยกข้อมูลเมตาของ XLS ผ่านแอปออนไลน์" sectionDescription="ดูและแก้ไขข้อมูลเมตาเป็นเอกสาร XLS โดยใช้ .ของเรา [การสาธิตสด](https://products.aspose.app/cells/metadata) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ XLS และแก้ไขคุณสมบัติของเอกสาร" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" รับลิงค์ดาวน์โหลดทันทีสำหรับไฟล์ผลลัพธ์" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
ไฟล์ที่มีนามสกุล XLS แสดงถึงรูปแบบไฟล์ไบนารีของ Excel ไฟล์ดังกล่าวสามารถสร้างได้โดย Microsoft Excel เช่นเดียวกับโปรแกรมสเปรดชีตอื่นๆ ที่คล้ายคลึงกัน เช่น OpenOffice Calc หรือ Apple Numbers ไฟล์ที่บันทึกโดย Excel เรียกว่าเวิร์กบุ๊กซึ่งแต่ละเวิร์กบุ๊กสามารถมีเวิร์กชีตได้ตั้งแต่หนึ่งแผ่นขึ้นไป ข้อมูลจะถูกจัดเก็บและแสดงต่อผู้ใช้ในรูปแบบตารางในเวิร์กชีต และสามารถขยายค่าตัวเลข ข้อมูลข้อความ สูตร การเชื่อมต่อข้อมูลภายนอก รูปภาพ และแผนภูมิ แอปพลิเคชันเช่น Microsoft Excel ช่วยให้คุณสามารถส่งออกข้อมูลเวิร์กบุ๊กเป็นรูปแบบต่างๆ ได้หลายรูปแบบ รวมทั้ง PDF, CSV, XLSX, TXT, HTML, XPS และอื่นๆ อีกมากมาย รูปแบบไฟล์ XLS ถูกแทนที่ด้วยรูปแบบที่เปิดกว้างและมีโครงสร้างมากขึ้น นั่นคือ XLSX ด้วยการเปิดตัวของ Microsoft Excel 2007 เวอร์ชันล่าสุดยังคงรองรับการสร้างและอ่านไฟล์ XLS แม้ว่า XLSX จะเป็นตัวเลือกแรกในการใช้งานในขณะนี้

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบข้อมูลเมตาที่รองรับอื่นๆ" subTitle="เมื่อใช้ C++ ผู้ใช้ยังสามารถจัดการข้อมูลเมตาของรูปแบบอื่นๆ ได้มากมาย รวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}