---
title:  ป้องกันและล็อค XLSB เอกสาร via .NET
weight: 5920
description: ซอร์สโค้ด C# เพื่อล็อคไฟล์ XLSB โดยใช้รหัสผ่านบน .NET Framework, .NET Core, Mono หรือแพลตฟอร์ม Xamarin
keywords: [C# Aspose.Cells., c# Lock XLSB files., c# How to Protect and lock XLSB document., c# Protect XLSB files., Encrypt XLSB Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="เข้ารหัสไฟล์ XLSB ผ่าน C#" h2="สเปรดชีต Excel ที่ป้องกันด้วยรหัสผ่านรวมถึงรูปแบบ XLSB โดยใช้ไลบรารี .NET" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีป้องกันไฟล์ XLSB โดยใช้ C#" %}}

 เพื่อป้องกันไฟล์ XLSB เราจะใช้
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API ซึ่งเป็นระบบป้องกันเอกสารที่มีคุณสมบัติหลากหลาย ทรงพลัง และใช้งานง่าย API สำหรับแพลตฟอร์ม C# เปิด
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 ผู้จัดการแพ็คเกจ ค้นหา
 **Aspose.Cells** 
 และติดตั้ง คุณอาจใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ปกป้อง XLSB ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

 คุณต้องการ
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 อ้างอิงในโครงการของคุณเพื่อดำเนินการเวิร์กโฟลว์ต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

1.  สร้างอินสแตนซ์คลาสสมุดงานด้วยเส้นทางไปยังไฟล์ XLSB
1.  รับค่าเริ่มต้นหรือแผ่นงานใดๆ เพื่อเพิ่มการป้องกัน
1.  ป้องกันแผ่นงานด้วยวิธี Worksheet.Protect
1.  ปกป้องสมุดงานด้วยวิธี Workbook.Protect
1.  บันทึกผลลัพธ์ในรูปแบบ XLSB

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET รองรับระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono หรือแพลตฟอร์ม Xamarin
-  สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
-  เพิ่มการอ้างอิงถึง Aspose.Cells for .NET DLL ในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="" %}}

```cs

// load the XLSB Excel file 
var book = new Aspose.Cells.Workbook("unlocked.xlsb");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.xlsb");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for .NET API" %}}

 Aspose.Cells API สามารถใช้สร้าง แก้ไข แปลง และเรนเดอร์รูปแบบ Excel Microsoft เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็น API แบบสแตนด์อโลน และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="แอพปกป้องฟรี XLSB" sectionDescription=" ตรวจสอบการสาธิตสดของเราไปที่[เข้ารหัสไฟล์ XLSB](https://products.aspose.app/cells/protect/xlsb) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนหรือคอมไพล์โค้ด" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ XLSB แล้วกดปุ่ม \"ปลดล็อค\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" ดาวน์โหลดไฟล์ผลลัพธ์ XLSB จากลิงก์" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
รูปแบบไฟล์ XLSB ระบุรูปแบบไฟล์ไบนารีของ Excel ซึ่งเป็นคอลเลกชันของระเบียนและโครงสร้างที่ระบุเนื้อหาสมุดงาน Excel เนื้อหาอาจรวมถึงตารางตัวเลข ข้อความ หรือทั้งตัวเลขและข้อความ สูตร การเชื่อมต่อข้อมูลภายนอก แผนภูมิ และรูปภาพที่ไม่มีโครงสร้างหรือกึ่งโครงสร้าง ต่างจาก XLSX (ซึ่งยึดตามรูปแบบไฟล์ Open XML) XLSB แสดงถึงไฟล์เวิร์กบุ๊ก Excel ไบนารี ไฟล์ XLSB สามารถอ่านและเขียนได้รวดเร็วยิ่งขึ้น ซึ่งมีประโยชน์สำหรับการทำงานกับไฟล์ขนาดใหญ่ XLSB ไม่ค่อยได้ใช้เพื่อจัดเก็บสมุดงาน เนื่องจาก XLSX (และก่อนหน้านี้ XLS) เป็นรูปแบบไฟล์ที่ผู้ใช้เลือกบ่อยที่สุดสำหรับการบันทึกสมุดงาน สามารถเปิดได้ภายใน Microsoft Office 2007 ขึ้นไป

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการป้องกันอื่นๆ ที่รองรับ" subTitle="การใช้ C# ทำให้สามารถป้องกันรูปแบบอื่น ๆ ได้อย่างง่ายดายรวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
