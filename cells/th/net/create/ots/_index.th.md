---
title: สร้าง OTS - สร้างไฟล์ OTS ใน C#
description:  Aspose เอ็กเซล. C# สร้างไฟล์ OTS อย่างรวดเร็วและง่ายดายด้วย Aspose.Cells สร้างไฟล์ OTS โดยใช้ C# สร้าง OTS ใน C# C# OTS Creater
keywords: [Aspose Excel., C# Aspose.Cells., C# Create OTS file., Generate OTS file in C#., Create OTS file using C#., Write data to OTS file via C#., Create a OTS file in C#., C# Generate a OTS file., C# OTS Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="สร้างไฟล์ OTS ใน C#" h2="ไลบรารี่ C# ความเร็วสูงสำหรับการสร้าง OTS นี่คือโซลูชันซอฟต์แวร์ระดับมืออาชีพสำหรับการนำเข้าและส่งออก XLSX, PDF และรูปแบบอื่นๆ อีกมากมายบน .NET Framework, .NET Core หรือ Mono Platforms" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OTS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="สร้างไฟล์ OTS โดยใช้ C#" %}}
 จะสร้างไฟล์ OTS ได้อย่างไร? ด้วยไลบรารี Aspose.Cells for .NET คุณสามารถสร้างไฟล์ OTS โดยทางโปรแกรมได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด[Aspose.Cells for .NET](https://products.aspose.com/cells/net)สามารถสร้างแอปพลิเคชันข้ามแพลตฟอร์มด้วยความสามารถในการสร้าง แก้ไข แปลง เรนเดอร์ และพิมพ์ไฟล์ Excel ทั้งหมด .NET Excel API ไม่เพียงแต่แปลงระหว่างรูปแบบสเปรดชีตเท่านั้น แต่ยังสามารถเรนเดอร์ไฟล์ Excel เป็นรูปภาพ, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT และอื่นๆ อีกมากมาย จึงเป็นตัวเลือกที่สมบูรณ์แบบในการแลกเปลี่ยนเอกสารในรูปแบบมาตรฐานอุตสาหกรรม เปิด[NuGet](https://www.nuget.org/packages/aspose.cells) ตัวจัดการแพ็คเกจค้นหา Aspose.Cells และติดตั้ง คุณอาจใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="คำสั่งคอนโซลตัวจัดการแพ็คเกจ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}
 
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="วิธีสร้าง OTS ใน C#" %}}

{{% blocks/products/pf/agp/text %}}

เป็นเรื่องง่ายสำหรับนักพัฒนาในการสร้าง โหลด แก้ไข และแปลงไฟล์ OTS ภายในการเรียกใช้แอปพลิเคชันการรายงานต่างๆ สำหรับการประมวลผลข้อมูลโดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1.  รวมเนมสเปซในไฟล์ชั้นเรียนของคุณ
1.  สร้างอินสแตนซ์คลาสสมุดงาน
1.  เข้าถึงแผ่นงานแรกของสมุดงาน
1.  รับเซลล์ที่ต้องการของแผ่นงานและป้อนค่าลงในเซลล์
1.  ใช้วิธีการบันทึกเพื่อบันทึกสมุดงานเป็นไฟล์ OTS

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่างแสดงวิธีสร้างไฟล์ OTS ใน C#" offSpacer="" %}}

```cs

// Create Workbook class instance.
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet sht = wkb.Worksheets[0];

// Get the desired cell(s) of the worksheet.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// input the value into the cell(s).
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Save the Workbook as .ots file.
wkb.Save("created_one.ots");

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="C# ไลบรารี่ เพื่อสร้างไฟล์ OTS" %}}

{{% blocks/products/pf/agp/text %}}

มีสองทางเลือกอื่นในการติดตั้ง "Aspose.Cells for .NET" ลงในระบบของคุณ โปรดเลือกรายการที่ตรงกับความต้องการของคุณและปฏิบัติตามคำแนะนำทีละขั้นตอน:

{{% /blocks/products/pf/agp/text %}}

1.  ติดตั้งก[NuGet แพ็คเกจ](https://www.nuget.org/packages/Aspose.Cells/) . ดู[เอกสารประกอบ](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  ติดตั้งไลบรารี่โดยใช้[คอนโซลตัวจัดการแพ็คเกจ](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) ภายใน Visual Studio IDE

{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนที่จะรันโค้ดตัวอย่างการแปลง .NET ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows หรือระบบปฏิบัติการที่รองรับกับ .NET, .NET Core, Windows Azure หรือ Mono Platforms
-  สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
-  เพิ่มการอ้างอิงถึง Aspose.Cells for .NET DLL ในโครงการของคุณ

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OTS" readMoreLink="https://docs.fileformat.com/spreadsheet/ots/" >}}ไฟล์ที่มีนามสกุล .ots คือไฟล์เทมเพลต OpenDocument Spreadsheet ที่สร้างขึ้นด้วยแอปพลิเคชันซอฟต์แวร์ Calc ที่รวมอยู่ใน Apache OpenOffice ซอฟต์แวร์แอปพลิเคชัน Calc คล้ายกับ Excel ที่มีอยู่ใน Microsoft Office รูปแบบไฟล์ OTS ใช้เพื่อสร้างเทมเพลตที่มีการตั้งค่าที่กำหนดไว้ล่วงหน้าที่เกี่ยวข้องกับสไตล์ แบบอักษร ข้อมูล เค้าโครงสเปรดชีต และการจัดรูปแบบ ไฟล์ OTF มีแอปพลิเคชันประเภท mime/vnd.oasis.opendocument.spreadsheet-template ไฟล์เทมเพลตเหล่านี้สามารถใช้เป็นจุดเริ่มต้นในการสร้างและบันทึกไฟล์ข้อมูลจริงที่บันทึกในรูปแบบไฟล์ ODS ไฟล์ OTS สามารถใช้กับแอปพลิเคชันเช่น OpenOffice และ LibreOffice{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การสร้างสเปรดชีตอื่นๆ ที่รองรับ" subTitle="คุณยังสามารถสร้างรูปแบบ Excel Microsoft อื่นๆ ได้ รวมถึงบางรูปแบบที่แสดงด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xls/" name="XLS" description="Microsoft สเปรดชีต Excel (ดั้งเดิม)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsx/" name="XLSX" description="เปิดสมุดงาน XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsb/" name="XLSB" description="สมุดงาน Excel ไบนารี" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsm/" name="XLSM" description="สเปรดชีตที่เปิดใช้งานมาโคร" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlt/" name="XLT" description="เทมเพลต Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltx/" name="XLTX" description="เทมเพลต Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltm/" name="XLTM" description="เทมเพลตที่เปิดใช้งานแมโคร Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/csv/" name="CSV" description="ค่าที่คั่นด้วยเครื่องหมายจุลภาค" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/tsv/" name="TSV" description="แท็บค่าที่แยกจากกัน" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/ods/" name="ODS" description="สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/pdf/" name="PDF" description="รูปแบบเอกสารแบบพกพา" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/html/" name="HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
