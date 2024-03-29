---
title:  แก้ไขหรือดู ODS ข้อมูลเมตาของไฟล์ via Java
weight: 2080
description: โค้ดตัวอย่าง Java เพื่อแก้ไขหรือดูข้อมูลเมตาของรูปแบบ ODS บน Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
keywords: [Java Aspose.Cells., Java view ods metadata., Java add ods metadata., Java insert ods metadata., Java edit ods metadata., Java remove ods metadata., Java extract ods metadata., Java modify ods metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แยก ODS ข้อมูลเมตา via Java" h2="สร้างแอป Java ของคุณเองเพื่อเพิ่ม แก้ไข ลบ หรือแยกข้อมูลเมตาจากไฟล์ ODS โดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="วิธีแยกข้อมูลเมตา ODS โดยใช้ Java" %}}

 เพื่อที่จะรับข้อมูลเมตาของไฟล์ ODS เราจะใช้
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API ซึ่งเป็นแพลตฟอร์มเมทาดาทา API for Java ที่มีคุณสมบัติหลากหลาย ทรงพลัง และใช้งานง่าย คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนการแยก Metadata ของ ODS via Java" %}}

{{% blocks/products/pf/agp/text %}}

 เข้าถึงข้อมูลที่เป็นประโยชน์ที่จัดเก็บไว้ในไฟล์ ODS รวมถึงเวลาที่ได้รับ ประมวลผล การประทับเวลา และอื่นๆ

{{% /blocks/products/pf/agp/text %}}

+ โหลดไฟล์ ODS ภายใน WorkbookMetadata
+ สร้างวัตถุ MetadataOptions พร้อมตัวเลือกที่เกี่ยวข้อง
+ ตั้งค่าคุณสมบัติที่เกี่ยวข้อง
+ บันทึกข้อมูลเมตาดาต้า ODS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java รองรับแพลตฟอร์มและระบบปฏิบัติการหลักๆ ทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
-  รับเวอร์ชั่นล่าสุด Aspose.Cells for Java ส่งตรงจาก
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="แยกข้อมูลเมตาของ ODS - Java" offSpacer="" %}}

```cs

// Open Workbook metadata
MetadataOptions options = new MetadataOptions(MetadataType.DOCUMENT_PROPERTIES);
WorkbookMetadata meta = new WorkbookMetadata("Sample1.ods", options);

// Set some properties
meta.getCustomDocumentProperties().add("test", "test");

// Save the metadata info
meta.save("Sample1.out.ods");

// Open the workbook
Workbook w = new Workbook("Sample1.out.ods");

// Read document property
System.out.println(w.getCustomDocumentProperties().get("test"));  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for Java API" %}}

 Aspose.Cells API สามารถใช้สร้าง แก้ไข แปลง และเรนเดอร์รูปแบบ Excel Microsoft เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็น API แบบสแตนด์อโลน และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="แยกข้อมูลเมตาของ ODS ผ่านแอปออนไลน์" sectionDescription=" ดูและแก้ไขข้อมูลเมตาเป็นเอกสาร ODS โดยใช้ของเรา[การสาธิตสด](https://products.aspose.app/cells/metadata) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ ODS ของคุณ & แก้ไขคุณสมบัติเอกสาร" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" รับลิงค์ดาวน์โหลดไฟล์ผลลัพธ์ทันที" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
ไฟล์ที่มีนามสกุล ODS ย่อมาจากรูปแบบเอกสาร OpenDocument Spreadsheet ที่ผู้ใช้สามารถแก้ไขได้ ข้อมูลจะถูกเก็บไว้ในไฟล์ ODF เป็นแถวและคอลัมน์ มันเป็นรูปแบบที่ใช้ XML และเป็นหนึ่งในประเภทย่อยหลายประเภทในตระกูล Open Document Formats (ODF) รูปแบบนี้ระบุเป็นส่วนหนึ่งของข้อกำหนด ODF 1.2 ที่เผยแพร่และดูแลโดย OASIS แอปพลิเคชั่นจำนวนหนึ่งบน Windows รวมถึงระบบปฏิบัติการอื่นสามารถเปิดไฟล์ ODS เพื่อแก้ไขและจัดการรวมถึง Microsoft Excel, NeoOffice และ LibreOffice ไฟล์ ODS ยังสามารถแปลงเป็นรูปแบบสเปรดชีตอื่นๆ ได้ เช่นเดียวกับ XLS, XLSX และอื่นๆ โดยใช้แอปพลิเคชันต่างๆ

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบข้อมูลเมตาอื่น ๆ ที่รองรับ" subTitle="การใช้ Java เราสามารถจัดการข้อมูลเมตาของรูปแบบอื่น ๆ ได้มากมายรวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
