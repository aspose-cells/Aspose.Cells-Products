---
title: ดูหรือแก้ไขข้อมูลเมตาของไฟล์ ODS ผ่าน .NET 
weight: 320
url: /th/net/metadata/ods/ 
description: C# ซอร์สโค้ดสำหรับแก้ไขหรือดูข้อมูลเมตาของรูปแบบ ODS บน .NET Framework, .NET Core, Mono หรือ Xamarin Platforms
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แยกข้อมูลเมตา ODS ผ่าน .NET" h2="สร้างแอป .NET ของคุณเองเพื่อเพิ่ม แก้ไข ลบ หรือแยกข้อมูลเมตาจากไฟล์ ODS โดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแยกข้อมูลเมตา ODS โดยใช้ C#" %}}

 เพื่อแยกข้อมูลเมตา ODS เราจะใช้
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API ซึ่งเป็นข้อมูลเมตาของเอกสารที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย API สำหรับแพลตฟอร์ม C# เปิด
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 package manager ค้นหา
 **Aspose.Cells** 
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการดึงข้อมูลเมตาของ ODS ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

 เข้าถึงข้อมูลที่เป็นประโยชน์ซึ่งจัดเก็บไว้ในไฟล์ ODS รวมถึงเวลาที่ได้รับไฟล์ ODS ประมวลผล ประทับเวลา และอื่นๆ

{{% /blocks/products/pf/agp/text %}}

+ โหลด ODS ด้วยอินสแตนซ์ของสมุดงาน
+ รับคอลเลกชัน BuiltInDocumentProperties ของวัตถุสมุดงาน
+ วนซ้ำในคอลเล็กชัน
+ แสดงชื่อคุณสมบัติ ประเภท & มูลค่า

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET ได้รับการสนับสนุนในระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono หรือ Xamarin Platforms- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio- Aspose.Cells for .NET อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="แยกข้อมูลเมตาของ ODS - C#" offSpacer="" %}}

```cs

// โหลด ODS ด้วยอินสแตนซ์ของ Workbook
var book = new Aspose.Cells.Workbook("template.ods");
// วนซ้ำบนคอลเลกชัน BuiltInDocumentProperties
foreach (Aspose.Cells.Properties.DocumentProperty property in book.Worksheets.BuiltInDocumentProperties)
{
    Console.WriteLine($"\tType:\t{property.Type}");

    // คุณสมบัติบางอย่างอาจเก็บค่าได้หลายค่า
    if (property.Value is Array)
    {
        foreach (object value in property.Value as Array)
            Console.WriteLine($"\tValue:\t\"{value}\"");
    }
    else
    {
        Console.WriteLine($"\tValue:\t\"{property.Value}\"");
    }
}  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for .NET API" %}}

 Aspose.Cells API สามารถใช้เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ดึงข้อมูลเมตาของ ODS ผ่านแอปออนไลน์" sectionDescription="ดูและแก้ไขข้อมูลเมตาไปยังเอกสาร ODS โดยใช้ .ของเรา [การสาธิตสด](https://products.aspose.app/cells/metadata) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ ODS ของคุณและแก้ไขคุณสมบัติของเอกสาร" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" รับลิงค์ดาวน์โหลดทันทีสำหรับไฟล์ผลลัพธ์" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
ไฟล์ที่มีนามสกุล ODS ย่อมาจากรูปแบบเอกสารสเปรดชีต OpenDocument ที่ผู้ใช้แก้ไขได้ ข้อมูลถูกเก็บไว้ในไฟล์ ODF เป็นแถวและคอลัมน์ เป็นรูปแบบ XML และเป็นหนึ่งในหลายประเภทย่อยในตระกูล Open Document Formats (ODF) รูปแบบถูกระบุเป็นส่วนหนึ่งของข้อกำหนด ODF 1.2 ที่เผยแพร่และดูแลโดย OASIS แอปพลิเคชั่นจำนวนมากบน Windows รวมถึงระบบปฏิบัติการอื่น ๆ สามารถเปิดไฟล์ ODS เพื่อแก้ไขและจัดการรวมถึง Microsoft Excel, NeoOffice และ LibreOffice ไฟล์ ODS ยังสามารถแปลงเป็นรูปแบบสเปรดชีตอื่น ๆ เช่น XLS, XLSX และอื่น ๆ โดยใช้แอปพลิเคชันต่างๆ

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบข้อมูลเมตาที่รองรับอื่นๆ" subTitle="เมื่อใช้ C# เรายังสามารถจัดการข้อมูลเมตาของรูปแบบอื่นๆ ได้มากมาย รวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}