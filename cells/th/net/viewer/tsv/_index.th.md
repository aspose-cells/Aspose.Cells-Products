---
title:  ดู TSV รูปแบบไฟล์ via .NET
weight: 3090
description: ซอร์สโค้ด C# สำหรับโหลด เรนเดอร์ และแสดงเอกสาร TSV บน .NET Framework, .NET Core, Mono หรือแพลตฟอร์ม Xamarin
keywords: [C# Aspose.Cells., c# view TSV files., c# how to render TSV document., c# load and display TSV files., TSV File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TSV โปรแกรมดูไฟล์ for .NET" h2="ดูสเปรดชีต Excel และ OpenOffice เช่น TSV โดยไม่ต้องใช้ Microsoft Excel หรือ Office Automation" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TSV" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีดูไฟล์ TSV โดยใช้ C#" %}}

 ในการดูไฟล์ TSV เราจะใช้
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API ซึ่งเป็นแพลตฟอร์ม API ที่มีคุณสมบัติหลากหลาย ทรงพลัง และใช้งานง่ายสำหรับใช้กับ Viewer ใดๆ เปิด
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 ผู้จัดการแพ็คเกจ ค้นหา
 **Aspose.Cells** 
 และติดตั้ง คุณอาจใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="คำสั่งคอนโซลตัวจัดการแพ็คเกจ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนการดู TSV ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells ช่วยให้นักพัฒนาสามารถดูไฟล์ TSV ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1.  โหลดไฟล์ TSV ในอินสแตนซ์ของสมุดงาน
1.  สร้างอินสแตนซ์ของ HtmlSaveOptions และตั้งค่าคุณสมบัติ ExportHeadings เป็นจริง
1. บันทึกไฟล์ TSV ในรูปแบบ HTML โดยใช้วิธี Workbook.Save
1.  โหลดผลลัพธ์ HTML ในเบราว์เซอร์เริ่มต้นด้วย Process.Start

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET รองรับระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono หรือแพลตฟอร์ม Xamarin
-  สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
-  เพิ่มการอ้างอิงถึง Aspose.Cells for .NET DLL ในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่าง C# เพื่อดูไฟล์ TSV" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the TSV file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.tsv");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the TSV file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for .NET API" %}}

 Aspose.Cells API สามารถใช้สร้าง แก้ไข แปลง และเรนเดอร์รูปแบบ Excel Microsoft เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็น API แบบสแตนด์อโลน และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="แอพดูฟรี TSV" sectionDescription=" ตรวจสอบการสาธิตสดของเราไปที่[โทร.TSV](https://products.aspose.app/cells/viewer/tsv) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนหรือคอมไพล์โค้ด" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ TSV แล้วกดปุ่ม \"ดู\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" ดาวน์โหลดไฟล์ TSV จากลิงก์ หากจำเป็น" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
รูปแบบไฟล์ Tab-Separated Values (TSV) แสดงถึงข้อมูลที่คั่นด้วยแท็บในรูปแบบข้อความธรรมดา รูปแบบไฟล์คล้ายกับ CSV ใช้สำหรับการจัดระเบียบข้อมูลในลักษณะที่มีโครงสร้างเพื่อนำเข้าและส่งออกระหว่างแอปพลิเคชันต่างๆ รูปแบบนี้ใช้สำหรับการนำเข้า/ส่งออกข้อมูลและการแลกเปลี่ยนข้อมูลในแอปพลิเคชันและฐานข้อมูลสเปรดชีตเป็นหลัก แต่ละเรกคอร์ดในไฟล์ TSV จะอยู่ในไฟล์ข้อความบรรทัดเดียว โดยที่ค่าฟิลด์แต่ละค่าจะถูกคั่นด้วยอักขระแท็บ ประเภทสื่อสำหรับรูปแบบไฟล์ TSV คือค่าข้อความ/แท็บที่คั่น

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบตัวแสดงอื่น ๆ ที่รองรับ" subTitle="การใช้ C# จะทำให้สามารถดูไฟล์รูปแบบอื่นๆ ได้มากมาย เช่น" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="ค่าที่คั่นด้วยเครื่องหมายจุลภาค" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="เอกสารข้อความ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlt/" name="XLT" description="Microsoft เทมเพลต Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="เทมเพลตที่เปิดใช้งาน Excel Macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="เทมเพลต Office OpenXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
