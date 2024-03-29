---
title:  ค้นหาเอกสาร TSV โดยไม่ต้องเปิด via Java
weight: 4940
description: โค้ดตัวอย่าง Java เพื่อค้นหาคำที่มีรูปแบบในไฟล์ TSV บน Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
keywords: [Java Aspose.Cells., Java search words with pattern in tsv file., Java find words with pattern in tsv file., Java search string with pattern in tsv file., Java find words with pattern in tsv file., Java search words in tsv file., Java find words in tsv file., Java search string in tsv file., Java find string in tsv file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ค้นหา TSV รูปแบบใน Java" h2="การค้นหาเอกสาร TSV แบบเนทีฟและประสิทธิภาพสูงโดยใช้ API ฝั่งเซิร์ฟเวอร์ Aspose.Cells for Java โดยไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ Adobe PDF" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="วิธีค้นหาไฟล์ TSV โดยใช้ Java" %}}

 ในการค้นหาไฟล์ TSV เราจะใช้
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API ซึ่งเป็นแพลตฟอร์มค้นหา API for Java ที่มีคุณสมบัติครบครัน ทรงพลัง และใช้งานง่าย คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการค้นหาไฟล์ TSV ใน Java" %}}

{{% blocks/products/pf/agp/text %}}

 การค้นหาเอกสารพื้นฐานโดยใช้ Aspose.Cells API สามารถทำได้โดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

+ โหลดไฟล์ TSV โดยการสร้างอินสแตนซ์วัตถุ Workbook
+ เข้าถึงแผ่นงานแรกในไฟล์ TSV
+ ค้นหาเซลล์ที่มีสูตรที่ระบุ
+ ยกตัวอย่าง FindOptions
+ ค้นหาเซลล์ที่มีค่าสตริง
พิมพ์เซลล์ที่พบหลังผลการค้นหา

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java รองรับแพลตฟอร์มและระบบปฏิบัติการหลักๆ ทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
-  รับเวอร์ชั่นล่าสุด Aspose.Cells for Java ส่งตรงจาก
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ค้นหาไฟล์ TSV - Java" offSpacer="" %}}

```cs
// Instantiating a Workbook object
Workbook workbook = new Workbook(dataDir + "book1.tsv");

// Accessing the first worksheet in the TSV file
Worksheet worksheet = workbook.getWorksheets().get(0);

// Finding the cell containing the specified formula
Cells cells = worksheet.getCells();

// Instantiate FindOptions
FindOptions findOptions = new FindOptions();

// Finding the cell containing a string value that starts with Or
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// Printing the name of the cell found after searching 
System.out.println("Name of the cell containing String: " + cell.getName());  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for Java API" %}}

 Aspose.Cells API สามารถใช้สร้าง แก้ไข แปลง และเรนเดอร์รูปแบบ Excel Microsoft เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็น API แบบสแตนด์อโลน และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="ออนไลน์ TSV ค้นหาการสาธิตสด" sectionDescription=" ค้นหาข้อความ คำ วลี ภายใน TSV เอกสาร ทันที โดยเข้าไปที่ของเรา[เว็บไซต์สาธิตสด](https://products.aspose.app/cells/search). การสาธิตสดมีข้อดีดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่ต้องดาวน์ Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="เพียงอัพโหลดไฟล์ TSV ของคุณ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ผลการค้นหาปรากฏขึ้นทันที" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV " readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
รูปแบบไฟล์ Tab-Separated Values (TSV) แสดงถึงข้อมูลที่คั่นด้วยแท็บในรูปแบบข้อความธรรมดา รูปแบบไฟล์คล้ายกับ CSV ใช้สำหรับการจัดระเบียบข้อมูลในลักษณะที่มีโครงสร้างเพื่อนำเข้าและส่งออกระหว่างแอปพลิเคชันต่างๆ รูปแบบนี้ใช้สำหรับการนำเข้า/ส่งออกข้อมูลและการแลกเปลี่ยนข้อมูลในแอปพลิเคชันและฐานข้อมูลสเปรดชีตเป็นหลัก แต่ละเรกคอร์ดในไฟล์ TSV จะอยู่ในไฟล์ข้อความบรรทัดเดียว โดยที่ค่าฟิลด์แต่ละค่าจะถูกคั่นด้วยอักขระแท็บ ประเภทสื่อสำหรับรูปแบบไฟล์ TSV คือค่าข้อความ/แท็บที่คั่น

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="เอกสารการค้นหาอื่น ๆ ที่รองรับ" subTitle="เมื่อใช้ Java เราสามารถค้นหาไฟล์อื่นๆ รวมทั้ง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/csv/" name="CSV" description="ค่าที่คั่นด้วยเครื่องหมายจุลภาค" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/txt/" name="TXT" description="เอกสารข้อความ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
