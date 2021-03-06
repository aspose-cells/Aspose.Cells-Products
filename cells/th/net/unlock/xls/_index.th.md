---
title: ปลดล็อกเอกสาร XLS ผ่าน .NET 
weight: 4260
url: /th/net/unlock/xls/ 
description: C# ซอร์สโค้ดเพื่อปลดล็อกไฟล์ XLS ที่ป้องกันด้วยรหัสผ่านบน .NET Framework, .NET Core, Mono หรือ Xamarin Platforms
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ปลดล็อกสเปรดชีต XLS ผ่าน C#" h2="ลบการป้องกันจาก XLS โดยใช้ไลบรารี .NET" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีปลดล็อกไฟล์ XLS โดยใช้ C#" %}}

 ในการลบไฟล์ XLS การป้องกัน เราจะใช้
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API ซึ่งเป็นการปกป้องเอกสารที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย API สำหรับแพลตฟอร์ม C# เปิด
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 package manager ค้นหา
 **Aspose.Cells** 
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ปลดล็อก XLS ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

 คุณต้องการ
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 อ้างอิงในโครงการของคุณเพื่อดำเนินการเวิร์กโฟลว์ต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

1. สร้างอินสแตนซ์คลาสเวิร์กบุ๊กด้วยพาธไปยังไฟล์ XLS ที่ได้รับการป้องกัน1. รับค่าเริ่มต้นหรือแผ่นงานใด ๆ เพื่อลบการป้องกัน1. ลบการป้องกันแผ่นงานด้วยวิธีการ Worksheet.Unprotect1. ลบการป้องกันสมุดงานด้วยวิธี Workbook.Unprotect1. บันทึกผลลัพธ์ในรูปแบบ XLS
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET ได้รับการสนับสนุนในระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono หรือ Xamarin Platforms- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio- Aspose.Cells for .NET อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="" %}}

```cs

// สร้างอินสแตนซ์วัตถุสมุดงานด้วยไฟล์ XLS ที่ได้รับการป้องกัน
var workbook = new Aspose.Cells.Workbook("protected.xls");

// เข้าถึงแผ่นงานเริ่มต้นในไฟล์ Excel
var worksheet = workbook.Worksheets[0];

// ยกเลิกการป้องกันแผ่นงานโดยไม่ต้องใช้รหัสผ่าน
worksheet.Unprotect();

// เลิกป้องกันสมุดงานด้วยรหัสผ่าน
workbook.Unprotect("password");

// บันทึกผลลัพธ์กลับในรูปแบบ XLS
workbook.Save("unprotected.xls", Aspose.Cells.SaveFormat.Auto);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for .NET API" %}}

 Aspose.Cells API สามารถใช้เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="แอปฟรีเพื่อปลดล็อก XLS" sectionDescription="ตรวจสอบการสาธิตสดของเราที่ [ปลดล็อกไฟล์ XLS](https://products.aspose.app/cells/unlock/xls) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนหรือคอมไพล์โค้ด" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ XLS แล้วกดปุ่ม \"ปลดล็อก\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" ดาวน์โหลดไฟล์ XLS ที่เป็นผลลัพธ์จากลิงค์" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
ไฟล์ที่มีนามสกุล XLS แสดงถึงรูปแบบไฟล์ไบนารีของ Excel ไฟล์ดังกล่าวสามารถสร้างได้โดย Microsoft Excel เช่นเดียวกับโปรแกรมสเปรดชีตอื่นๆ ที่คล้ายคลึงกัน เช่น OpenOffice Calc หรือ Apple Numbers ไฟล์ที่บันทึกโดย Excel เรียกว่าเวิร์กบุ๊กซึ่งแต่ละเวิร์กบุ๊กสามารถมีเวิร์กชีตได้ตั้งแต่หนึ่งแผ่นขึ้นไป ข้อมูลจะถูกจัดเก็บและแสดงต่อผู้ใช้ในรูปแบบตารางในเวิร์กชีต และสามารถขยายค่าตัวเลข ข้อมูลข้อความ สูตร การเชื่อมต่อข้อมูลภายนอก รูปภาพ และแผนภูมิ แอปพลิเคชันเช่น Microsoft Excel ช่วยให้คุณสามารถส่งออกข้อมูลเวิร์กบุ๊กเป็นรูปแบบต่างๆ ได้หลายรูปแบบ รวมทั้ง PDF, CSV, XLSX, TXT, HTML, XPS และอื่นๆ อีกมากมาย รูปแบบไฟล์ XLS ถูกแทนที่ด้วยรูปแบบที่เปิดกว้างและมีโครงสร้างมากขึ้น นั่นคือ XLSX ด้วยการเปิดตัวของ Microsoft Excel 2007 เวอร์ชันล่าสุดยังคงรองรับการสร้างและอ่านไฟล์ XLS แม้ว่า XLSX จะเป็นตัวเลือกแรกในการใช้งานในขณะนี้

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการปลดล็อกอื่น ๆ ที่รองรับ" subTitle="การใช้ C# ทำให้สามารถลบการป้องกัน/ปลดล็อกรูปแบบต่างๆ ได้อย่างง่ายดาย รวมทั้ง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}