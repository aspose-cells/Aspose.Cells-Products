---
title: ค้นหาและแทนที่ข้อความในเอกสาร XLS ผ่าน C++ 
weight: 380
url: /th/cpp/redaction/xls/ 
description: C++ ตัวอย่างโค้ดเพื่อแก้ไขข้อมูลที่ละเอียดอ่อนในไฟล์ XLS บน C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แก้ไขรูปแบบ XLS ใน C++" h2="ข้อมูลการแก้ไขที่ละเอียดอ่อนของเอกสาร XLS ดั้งเดิมและมีประสิทธิภาพสูงโดยใช้ฝั่งเซิร์ฟเวอร์ Aspose.Cells สำหรับ C++ API โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Adobe PDF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธี Redact ไฟล์ XLS โดยใช้ C++" %}}

 เพื่อแก้ไขไฟล์ XLS เราจะใช้
 [Aspose.Cells สำหรับ C++](https://products.aspose.com/cells/cpp) 
 API ซึ่งเป็นคุณลักษณะที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และง่ายต่อการใช้การแก้ไขเอกสาร API สำหรับแพลตฟอร์ม C++ คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรง เพียงแค่เปิด
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการ Redact ไฟล์ XLS ใน C++" %}}

{{% blocks/products/pf/agp/text %}}

 การค้นหาเอกสารพื้นฐานและแทนที่ข้อความในเนื้อหา ข้อคิดเห็น หรือข้อมูลเมตาด้วย
 [Aspose.Cells สำหรับ C++](https://products.aspose.com/cells/cpp) 
 API สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

+ โหลดไฟล์ XLS
+ กำหนดตัวเลือกการแทนที่
+ ตั้งค่าตัวเลือกความไวของตัวพิมพ์เล็กและตัวพิมพ์ใหญ่
+ ตั้งค่าตัวเลือกการจับคู่ข้อความ
+ แทนที่ข้อความโดยใช้วิธีการแทนที่ (...)
+ บันทึกสมุดงาน

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells สำหรับ C++ รองรับบนแพลตฟอร์มหลักและระบบปฏิบัติการทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ C++ Runtime Environment สำหรับ Windows 32 บิต, Windows 64 บิต และ Linux 64 บิต- Aspose.Cells สำหรับ C++ DLL ที่อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="แก้ไขไฟล์ XLS - C++" offSpacer="" %}}

```cs
// เส้นทางไดเรกทอรีต้นทาง
StringPtr srcDir = new String("SourceFolder\\");

// เส้นทางไดเรกทอรีผลลัพธ์
StringPtr outDir = new String("OutputFolder\\");

// โหลดไฟล์ XLS
intrusive_ptr<IWorkbook>  workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("book1.xls")));

// สร้างอินสแตนซ์ของคลาส IReplaceOptions
intrusive_ptr<IReplaceOptions> replaceOptions = Factory::CreateIReplaceOptions();

// ตั้งค่าตัวเลือกความไวของตัวพิมพ์
replaceOptions->SetCaseSensitive(false);

// ตั้งค่าตัวเลือกการจับคู่ข้อความ
replaceOptions->SetMatchEntireCellContents(false);

// แทนที่ข้อความ
workbook->Replace(new String("Text to find"), new String("Text replacement"), replaceOptions);

// บันทึกเป็นไฟล์ XLS
workbook->Save(outDir->StringAppend(new String("book1_out.xls")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells สำหรับ C++ API" %}}

 Aspose.Cells API สามารถใช้เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="การสาธิตสด Redaction XLS ออนไลน์" sectionDescription="ค้นหาและแทนที่ข้อความในเนื้อหา ความคิดเห็น หรือข้อมูลเมตาในเอกสาร XLS ได้ทันทีโดยไปที่ [เว็บไซต์สาธิตสด](https://products.aspose.app/cells/redaction). การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ XLS ของคุณ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" มันจะถูกแก้ไขทันที" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
ไฟล์ที่มีนามสกุล XLS แสดงถึงรูปแบบไฟล์ไบนารีของ Excel ไฟล์ดังกล่าวสามารถสร้างได้โดย Microsoft Excel เช่นเดียวกับโปรแกรมสเปรดชีตอื่นๆ ที่คล้ายคลึงกัน เช่น OpenOffice Calc หรือ Apple Numbers ไฟล์ที่บันทึกโดย Excel เรียกว่าเวิร์กบุ๊กซึ่งแต่ละเวิร์กบุ๊กสามารถมีเวิร์กชีตได้ตั้งแต่หนึ่งแผ่นขึ้นไป ข้อมูลจะถูกจัดเก็บและแสดงต่อผู้ใช้ในรูปแบบตารางในเวิร์กชีต และสามารถขยายค่าตัวเลข ข้อมูลข้อความ สูตร การเชื่อมต่อข้อมูลภายนอก รูปภาพ และแผนภูมิ แอปพลิเคชันเช่น Microsoft Excel ช่วยให้คุณสามารถส่งออกข้อมูลเวิร์กบุ๊กเป็นรูปแบบต่างๆ ได้หลายรูปแบบ รวมทั้ง PDF, CSV, XLSX, TXT, HTML, XPS และอื่นๆ อีกมากมาย รูปแบบไฟล์ XLS ถูกแทนที่ด้วยรูปแบบที่เปิดกว้างและมีโครงสร้างมากขึ้น นั่นคือ XLSX ด้วยการเปิดตัวของ Microsoft Excel 2007 เวอร์ชันล่าสุดยังคงรองรับการสร้างและอ่านไฟล์ XLS แม้ว่า XLSX จะเป็นตัวเลือกแรกในการใช้งานในขณะนี้ 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="เอกสารการตอบโต้อื่น ๆ ที่รองรับ" subTitle="เมื่อใช้ C++ เราสามารถแก้ไขรูปแบบต่างๆ ได้อย่างง่ายดาย รวมทั้ง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}