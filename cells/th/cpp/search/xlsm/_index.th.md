---
title:  ค้นหาเอกสาร XLSM โดยไม่ต้องเปิดผ่าน C++
weight: 9280
description: โค้ดตัวอย่าง C++ เพื่อค้นหาคำที่มีรูปแบบในไฟล์ XLSM บน C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
keywords: [C++ Aspose.Cells., C++ search words with pattern in xlsm file., C++ find words with pattern in xlsm file., C++ search string with pattern in xlsm file., C++ find words with pattern in xlsm file., C++ search words in xlsm file., C++ find words in xlsm file., C++ search string in xlsm file., C++ find string in xlsm file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ค้นหา XLSM รูปแบบใน C++" h2="การค้นหาเอกสาร XLSM แบบเนทีฟและประสิทธิภาพสูงโดยใช้ API ฝั่งเซิร์ฟเวอร์ Aspose.Cells for C++ โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Adobe PDF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีค้นหาไฟล์ XLSM โดยใช้ C++" %}}

 ในการค้นหาไฟล์ XLSM เราจะใช้
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API แพลตฟอร์มค้นหาเอกสาร API for C++ ที่มีคุณสมบัติครบครัน ทรงพลัง และใช้งานง่าย คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงแค่เปิดขึ้นมา
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการค้นหาไฟล์ XLSM ใน C++" %}}

{{% blocks/products/pf/agp/text %}}

 การค้นหาเอกสารพื้นฐานโดยใช้ Aspose.Cells API สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

+ โหลดไฟล์ XLSM โดยสร้างอินสแตนซ์คลาส Workbook
+ สร้างอินสแตนซ์คลาสแทนที่ตัวเลือก
+ ตั้งค่ารูปแบบที่ต้องการ เช่น SetCaseSensitive(bool value), SetMatchEntireCellContents(bool value)
ใช้วิธี Workbook::Replace(...) พร้อมตัวเลือกที่เกี่ยวข้อง
+ บันทึกไฟล์ XLSM โดยใช้วิธี Workbook::Save(...)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ รองรับแพลตฟอร์มและระบบปฏิบัติการหลักๆ ทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
-  เพิ่มการอ้างอิงถึง Aspose.Cells for C++ DLL ในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ค้นหาไฟล์ XLSM - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load XLSM file
Workbook  wkb(srcDir + u"sourceFile.xlsm");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as XLSM file
wkb.Save(outDir + u"outputFile.xlsm");

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

    {{< blocks/products/pf/agp/demobox sectionTitle="ออนไลน์ XLSM ค้นหาการสาธิตสด" sectionDescription=" ค้นหาข้อความ คำ วลี ภายใน XLSM เอกสาร ทันที โดยเข้าไปที่ของเรา[เว็บไซต์สาธิตสด](https://products.aspose.app/cells/search). การสาธิตสดมีข้อดีดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่ต้องดาวน์ Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="เพียงอัพโหลดไฟล์ XLSM ของคุณ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ผลการค้นหาปรากฏขึ้นทันที" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM " readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
ไฟล์ที่มีนามสกุล XLSM เป็นไฟล์สเปรดชีตประเภทหนึ่งที่รองรับมาโคร จากมุมมองของแอปพลิเคชัน แมโครคือชุดคำสั่งที่ใช้สำหรับกระบวนการอัตโนมัติ แมโครใช้เพื่อบันทึกขั้นตอนที่ดำเนินการซ้ำๆ และอำนวยความสะดวกในการดำเนินการโดยการเรียกใช้แมโครอีกครั้ง แมโครได้รับการตั้งโปรแกรมด้วย Visual Basic for Applications (VBA) ของ Microsoft จากภายในสมุดงาน Excel โดยใช้ Visual Basic Editor และสามารถเรียกใช้/ดีบักได้โดยตรงจากที่นั่น

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="เอกสารการค้นหาอื่น ๆ ที่รองรับ" subTitle="เมื่อใช้ C++ เราสามารถค้นหาไฟล์อื่นๆ รวมทั้ง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="ค่าที่คั่นด้วยเครื่องหมายจุลภาค" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="ค่าที่คั่นด้วยแท็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="เอกสารข้อความ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
