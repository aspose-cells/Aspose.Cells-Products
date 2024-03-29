---
title:  แยกไฟล์ ODS via Java
weight: 1950
description: โค้ดตัวอย่าง Java เพื่อแยกเอกสาร ODS บน Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
keywords: [Java Aspose.Cells., Java split ods files., Java how to split ods files into multiple files., Java ods splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แยกไฟล์ ODS via Java" h2="ODS แยกด้วยความช่วยเหลือของไลบรารีฝั่งเซิร์ฟเวอร์ Java" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="วิธีแยกไฟล์ ODS โดยใช้ Java" %}}

 ในการแยกไฟล์ ODS เราจะใช้
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API ซึ่งเป็นแพลตฟอร์มตัวแยกสัญญาณที่มีคุณสมบัติหลากหลาย ทรงพลัง และใช้งานง่าย API for Java คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 และติดตั้งภายในโปรเจ็กต์ที่ใช้ Maven ของคุณโดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml

{{% blocks/products/pf/agp/code-block title="พื้นที่เก็บข้อมูล" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การพึ่งพาอาศัยกัน" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนสำหรับการแยกไฟล์ ODS ใน Java" %}}

{{% blocks/products/pf/agp/text %}}

 ตัวแยกสัญญาณพื้นฐานด้วย
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

+ โหลดไฟล์ ODS โดยใช้คลาส Workbook
+ วนซ้ำแต่ละแผ่น
+ สร้างวัตถุคลาสสมุดงานใหม่
คัดลอกแผ่นงานที่เลือกไปยังวัตถุใหม่
+ เรียกวิธีการบันทึกด้วยเส้นทางไฟล์ ODS ใหม่

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java รองรับแพลตฟอร์มและระบบปฏิบัติการหลักๆ ทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
-  รับเวอร์ชั่นล่าสุด Aspose.Cells for Java ส่งตรงจาก
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="แยกไฟล์ ODS - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-ods-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for Java API" %}}

 Aspose.Cells API สามารถใช้สร้าง แก้ไข แปลง และเรนเดอร์รูปแบบ Excel Microsoft เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็น API แบบสแตนด์อโลน และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ออนไลน์ ODS Splitter สาธิตสด" sectionDescription=" แยกเอกสาร ODS ทันทีโดยไปที่ของเรา[เว็บไซต์สาธิตสด](https://products.aspose.app/cells/splitter). การสาธิตสดมีข้อดีดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่ต้องดาวน์ Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="เพียงอัพโหลดไฟล์ ODS ของคุณ มันก็จะแตกไฟล์ทันที" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
ไฟล์ที่มีนามสกุล ODS ย่อมาจากรูปแบบเอกสาร OpenDocument Spreadsheet ที่ผู้ใช้สามารถแก้ไขได้ ข้อมูลจะถูกเก็บไว้ในไฟล์ ODF เป็นแถวและคอลัมน์ มันเป็นรูปแบบที่ใช้ XML และเป็นหนึ่งในประเภทย่อยหลายประเภทในตระกูล Open Document Formats (ODF) รูปแบบนี้ระบุเป็นส่วนหนึ่งของข้อกำหนด ODF 1.2 ที่เผยแพร่และดูแลโดย OASIS แอปพลิเคชั่นจำนวนหนึ่งบน Windows รวมถึงระบบปฏิบัติการอื่นสามารถเปิดไฟล์ ODS เพื่อแก้ไขและจัดการรวมถึง Microsoft Excel, NeoOffice และ LibreOffice ไฟล์ ODS ยังสามารถแปลงเป็นรูปแบบสเปรดชีตอื่นๆ ได้ เช่นเดียวกับ XLS, XLSX และอื่นๆ โดยใช้แอปพลิเคชันต่างๆ

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการแยกอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ Java เรายังสามารถแยกไฟล์ขนาดใหญ่ออกเป็นส่วนๆ ของไฟล์รูปแบบอื่นๆ มากมาย รวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/splitter/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/splitter/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/splitter/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/splitter/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
