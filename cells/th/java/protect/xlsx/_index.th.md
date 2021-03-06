---
title: ป้องกันและล็อกเอกสาร XLSX ผ่าน Java 
weight: 1870
url: /th/java/protect/xlsx/ 
description: Java ตัวอย่างโค้ดสำหรับล็อกไฟล์ XLSX โดยใช้รหัสผ่านบน Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="เข้ารหัสไฟล์ XLSX ผ่าน Java" h2="สเปรดชีต Excel ที่ป้องกันด้วยรหัสผ่านรวมถึงรูปแบบ XLSX โดยใช้ .NET Library" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java/" installationsDocsLink="https://docs.aspose.com/cells/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="วิธีรักษาความปลอดภัยไฟล์ XLSX โดยใช้ Java" %}}

 เพื่อป้องกันไฟล์ XLSX เราจะใช้
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API ซึ่งเป็นแพลตฟอร์มการเข้ารหัส API for Java ที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 และติดตั้งภายในโปรเจ็กต์ที่ใช้ Maven โดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="ที่เก็บ" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการปกป้องไฟล์ XLSX ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

 การปกป้องเอกสารโดยใช้ Aspose.Cells API สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ XLSX โดยสร้างอินสแตนซ์ของคลาสเวิร์กบุ๊ก1. ใช้วิธีป้องกัน (..) กับ ProtectionType และ Password1. บันทึกไฟล์ XLSX ที่ได้รับการป้องกันโดย save() method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java รองรับบนแพลตฟอร์มหลักและระบบปฏิบัติการทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป- รับเวอร์ชันล่าสุดของ Aspose.Cells for Java โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="การพึ่งพา" offSpacer="" %}}

```cs

// เปิดไฟล์ XLSX
Workbook wkb = new Workbook("sourceFile.xlsx");

// ป้องกันสมุดงานโดยระบุประเภทการป้องกัน
wkb.protect(ProtectionType.ALL, "12345");

// บันทึกไฟล์ XLSX
wkb.save("lockedFile.xlsx");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for Java API" %}}

 Aspose.Cells API สามารถใช้เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="แอพฟรีเพื่อปกป้อง XLSX" sectionDescription="ตรวจสอบการสาธิตสดของเราที่ [เข้ารหัสไฟล์ XLSX](https://products.aspose.app/cells/protect/xlsx) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนหรือคอมไพล์โค้ด" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ XLSX แล้วกดปุ่ม \"ปลดล็อก\"" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ดาวน์โหลดไฟล์ XLSX ที่เป็นผลลัพธ์จากลิงค์" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX เป็นรูปแบบที่รู้จักกันดีสำหรับเอกสาร Microsoft Excel ที่เปิดตัวโดย Microsoft ด้วยการเปิดตัว Microsoft Office 2007 โดยยึดตามโครงสร้างที่จัดตาม Open Packaging Conventions ดังที่ระบุไว้ในส่วนที่ 2 ของมาตรฐาน OOXML ECMA-376 รูปแบบใหม่คือ แพ็คเกจ zip ที่มีไฟล์ XML จำนวนหนึ่ง สามารถตรวจสอบโครงสร้างและไฟล์พื้นฐานได้โดยการคลายซิปไฟล์ .xlsx

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="เอกสารคุ้มครองอื่น ๆ ที่ได้รับการสนับสนุน" subTitle="การใช้ Java สามารถป้องกันไฟล์อื่นๆ รวมทั้ง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}