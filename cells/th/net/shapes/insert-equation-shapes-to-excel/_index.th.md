---
title:  แทรกรูปร่างสมการลงใน Excel via .NET
weight: 360
description: C# ตัวอย่างโค้ดสำหรับเพิ่มหรือแทรกรูปร่างสมการลงใน Excel โดยใช้ .NET Library ใช้โค้ดนี้เพื่อสร้างรูปร่างสมการใน MS Excel ภายใน VB.NET, Asp.NET หรือแอปพลิเคชันที่ใช้ .NET ใดๆ
keywords: [C# Aspose.Cells., c# add equation shapes., c# insert equation shapes., c# create equation shapes]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แทรกรูปร่างสมการลงใน Excel via .NET" h2="แทรกรูปร่างสมการโดยใช้ Aspose.Cells\' API โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Open Office, Adobe PDF เป็นต้น" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแทรกรูปร่างสมการลงในไฟล์ Excel โดยใช้ C#" %}}

 เพื่อที่จะแทรกรูปร่างสมการลงในไฟล์ Excel เราจะใช้
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API ซึ่งเป็นการจัดการและแยกเอกสารที่มีคุณสมบัติหลากหลาย ทรงพลัง และใช้งานง่าย API สำหรับแพลตฟอร์ม C# เปิด
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 ผู้จัดการแพ็คเกจ ค้นหา
 Aspose.Cells 
 และติดตั้ง คุณอาจใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="สั่งการ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนการแทรกรูปทรงสมการลงในไฟล์ Excel ผ่านทาง C#" %}}

{{% blocks/products/pf/agp/text %}}

คุณต้องมี aspose.cells.dll เพื่อลองใช้เวิร์กโฟลว์ต่อไปนี้ในสภาพแวดล้อมของคุณเอง

{{% /blocks/products/pf/agp/text %}}

+ การสร้างอินสแตนซ์ของวัตถุสมุดงาน (หรือ->โหลดไฟล์ XLSX ด้วยเส้นทางแบบเต็ม)
+ เลือกแผ่นงานผ่านดัชนี
 + ใช้[เพิ่มวิธีการ](https://reference.aspose.com/cells/net/aspose.cells.drawing/shapecollection/addautoshape) เพื่อแทรกรูปร่างสมการลงในแผ่นงานที่เลือก
+ บันทึกสมุดงานในรูปแบบ XLSX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET รองรับระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono หรือแพลตฟอร์ม Xamarin
-  สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
-  เพิ่มการอ้างอิงถึง Aspose.Cells for .NET DLL ในโครงการของคุณ - ติดตั้งจาก NuGet โดยใช้ปุ่มดาวน์โหลดด้านบน

{{% /blocks/products/pf/agp/feature-section-col %}}

โค้ดตัวอย่างด้านล่างสาธิตวิธีการแทรก "คณิตศาสตร์บวก" สำหรับประเภทเพิ่มเติม โปรดดู "ภาพรวมของประเภทรูปร่างสมการ" ด้านล่าง

{{% blocks/products/pf/agp/code-block title="แทรกรูปร่างสมการ - C#" offSpacer="" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertEquationIntoWorksheet.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
 ภาพรวมของประเภทรูปร่างสมการ
   </h2>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/plus.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.MathPlus
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/minus.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.MathMinus
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/multiplication.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.Mathคูณ
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/division.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.MathDivide
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/equals.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.MathEqual
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-equation-shapes-to-excel/not_equal.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.MathNotEqual
    </p>
   </div>
  </div>
 </div>
</div>

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for .NET API" %}}

Aspose.Cells API สามารถใช้สร้าง แก้ไข แปลง และเรนเดอร์รูปแบบ Excel Microsoft เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็น API แบบสแตนด์อโลน และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice

{{% /blocks/products/pf/agp/content %}}



<!-- aboutfile Ends -->
<!--
{{< blocks/products/pf/agp/other-supported-section title="Other Supported Splitting Formats" subTitle="Using C#, One can also split large file into chunks of many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xls/" name="XLS" description="Excel Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsb/" name="XLSB" description="Binary Excel Workbook File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsm/" name="XLSM" description="Spreadsheet File" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

-->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
