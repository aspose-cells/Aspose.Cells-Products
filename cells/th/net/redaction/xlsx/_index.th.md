---
title:  ค้นหาและแทนที่ข้อความใน XLSX เอกสาร via .NET
weight: 2370
description: ซอร์สโค้ด C# เพื่อตรวจทานข้อมูลที่ละเอียดอ่อนในไฟล์ XLSX บน .NET Framework, .NET Core, Mono หรือแพลตฟอร์ม Xamarin
keywords: [C# Aspose.Cells., c# Search and replace text in XLSX file., c# redact XLSX file., c# edit XLSX file., c# XLSX file redaction., c# Search and replace string in XLSX file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แก้ไข XLSX รูปแบบใน C#" h2="ข้อมูลการแก้ไขที่ละเอียดอ่อนของเอกสาร XLSX แบบเนทีฟและประสิทธิภาพสูงโดยใช้ API ฝั่งเซิร์ฟเวอร์ Aspose.Cells for .NET โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Adobe PDF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแก้ไขไฟล์ XLSX โดยใช้ C#" %}}

 เพื่อทำการปกปิดไฟล์ XLSX เราจะใช้[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API ซึ่งเป็นโปรแกรมจัดการเอกสารที่มีคุณสมบัติหลากหลาย ทรงพลัง และใช้งานง่าย API สำหรับแพลตฟอร์ม C# เปิด[NuGet](https://www.nuget.org/packages/aspose.cells) ผู้จัดการแพ็คเกจ ค้นหา**Aspose.Cells** และติดตั้ง คุณอาจใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการทำซ้ำไฟล์ XLSX ใน C#" %}}

{{% blocks/products/pf/agp/text %}}

 การค้นหาเอกสารขั้นพื้นฐานและแทนที่ข้อความในเนื้อหา ความคิดเห็น หรือข้อมูลเมตาด้วย[Aspose.Cells for .NET](https://products.aspose.com/cells/net) API สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

+โหลดไฟล์XLSX.
+ เลือกแผ่นงาน
+ สร้างวัตถุ FindOptions
ตั้งค่าตัวเลือกการค้นหา
+ วนซ้ำแต่ละเซลล์แล้วใช้วิธีค้นหา
+ บันทึกสมุดงาน

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 API ของเราได้รับการสนับสนุนบนแพลตฟอร์มและระบบปฏิบัติการหลักทั้งหมด ก่อนที่จะรันโค้ดด้านล่าง โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นต่อไปนี้ในระบบของคุณ

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono หรือแพลตฟอร์ม Xamarin
-  สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
-  เพิ่มการอ้างอิงถึง Aspose.Cells for .NET DLL ในโครงการของคุณ - ติดตั้งจาก NuGet โดยใช้ปุ่มดาวน์โหลดด้านบน

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ตรวจทานไฟล์ XLSX - C#" offSpacer="" %}}

```cs
Workbook wb = new Workbook("e:\test2\Input.xlsx");
Worksheet sheet = wb.Worksheets[0];
FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.Contains;
opts.RegexKey = true;
Aspose.Cells.Cell cell = null;
do
{   //find only whole word and not part of any word.  
    cell = sheet.Cells.Find("\bKIM\b", cell, opts);
    if (cell != null)
    {
        string celltext = cell.Value.ToString();
        celltext = celltext.Replace("KIM", "^^^^^^^^^^");
        cell.PutValue(celltext);
    }
}
while (cell != null);

wb.Save("e:\test2\out1.xlsx");

// Find/Replace in whole workbook.

Workbook wb = new Workbook("e:\test2\Input.xlsx");
wb.Replace("\bKIM\b", "^^^^^^^^", new ReplaceOptions() { RegexKey = true });  
wb.Save("e:\test2\output.xlsx");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for .NET API" %}}

 Aspose.Cells API สามารถใช้สร้าง แก้ไข แปลง และเรนเดอร์รูปแบบ Excel Microsoft เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็น API แบบสแตนด์อโลน และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ออนไลน์ XLSX Redaction สาธิตสด" sectionDescription=" ค้นหาและแทนที่ข้อความในเนื้อหา ความคิดเห็น หรือข้อมูลเมตาในเอกสาร XLSX ทันทีโดยไปที่[เว็บไซต์สาธิตสด](https://products.aspose.app/cells/redaction)- การสาธิตสดมีข้อดีดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่ต้องดาวน์ Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัพโหลดไฟล์ XLSX ของคุณ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" มันจะถูกแก้ไขทันที" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX เป็นรูปแบบที่รู้จักกันดีสำหรับเอกสาร Excel Microsoft ที่นำมาใช้โดย Microsoft พร้อมกับการเปิดตัว Microsoft Office 2007 ตามโครงสร้างที่จัดตาม Open Packaging Conventions ดังที่ระบุไว้ในส่วนที่ 2 ของมาตรฐาน OOXML ECMA-376 รูปแบบใหม่คือ แพ็คเกจ zip ที่มีไฟล์ XML จำนวนหนึ่ง สามารถตรวจสอบโครงสร้างและไฟล์พื้นฐานได้โดยการแตกไฟล์ .xlsx

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการเขียนทับอื่นๆ ที่รองรับ" subTitle="การใช้ C# ทำให้สามารถแก้ไขรูปแบบต่างๆ ได้อย่างง่ายดาย รวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
