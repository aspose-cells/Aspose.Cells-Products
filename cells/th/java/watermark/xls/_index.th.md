---
title:  ลายน้ำ XLS เอกสาร via Java
weight: 2210
description: โค้ดตัวอย่าง Java เพื่อเพิ่มหรือลบลายน้ำในไฟล์ XLS บน Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
keywords: [Java Aspose.Cells., Java add watermark to xls file., Java insert watermark to xls file., Java create watermark in xls file., remove watermark from xls file using Java., Java operate watermark in xls file., Java access watermark in xls file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="เพิ่มลายน้ำข้อความไปที่ XLS via Java" h2="สร้างแอป Java ของคุณเองเพื่อใส่ลายน้ำให้กับไฟล์ XLS โดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="วิธีใส่ลายน้ำไฟล์ XLS โดยใช้ Java" %}}

 ในการใส่ลายน้ำไฟล์ XLS เราจะใช้[Aspose.Cells for Java](https://products.aspose.com/cells/java) API ซึ่งเป็นแพลตฟอร์มลายน้ำ API for Java ที่มีคุณสมบัติหลากหลาย ทรงพลัง และใช้งานง่าย คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) และติดตั้งภายในโปรเจ็กต์ที่ใช้ Maven ของคุณโดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml

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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนการเพิ่มลายน้ำที่ XLS via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  สร้างวัตถุสมุดงานใหม่
1.  เลือกแผ่นงานผ่านดัชนี
1.  สร้างรูปร่างและใช้ฟังก์ชัน addTextEffect
1.  ตั้งค่าสี ความโปร่งใส และอื่นๆ
1.  บันทึกสมุดงานในรูปแบบ XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java รองรับแพลตฟอร์มและระบบปฏิบัติการหลักๆ ทั้งหมด โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป
- รับเบอร์ล่าสุด Aspose.Cells for Java โดยตรงจาก Maven

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ใส่ลายน้ำมาที่ XLS - Java" offSpacer="" %}}

```cs

// Instantiate a new Workbook
Workbook workbook = new Workbook();

// Get the first default sheet
Worksheet sheet = workbook.getWorksheets().get(0);

// Add Watermark
Shape wordart = sheet.getShapes().addTextEffect(MsoPresetTextEffect.TEXT_EFFECT_1, "CONFIDENTIAL",
		"Arial Black", 50, false, true, 18, 8, 1, 1, 130, 800);

// Get the fill format of the word art
FillFormat wordArtFormat = wordart.getFill();

// Set the color
wordArtFormat.setOneColorGradient(Color.getRed(), 0.2, GradientStyleType.HORIZONTAL, 2);

// Set the transparency
wordArtFormat.setTransparency(0.9);

// Make the line invisible
LineFormat lineFormat = wordart.getLine();
lineFormat.setWeight(0.0);

// Save the file
workbook.save(dataDir + "AWArtWToWorksheet_out.xls");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Cells for Java API" %}}

 Aspose.Cells API สามารถใช้สร้าง แก้ไข แปลง และเรนเดอร์รูปแบบ Excel Microsoft เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็น API แบบสแตนด์อโลน และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ลายน้ำ XLS ผ่านแอพออนไลน์" sectionDescription=" เพิ่มลายน้ำให้กับเอกสาร XLS โดยเข้าไปที่ของเรา[เว็บไซต์สาธิตสด](https://products.aspose.app/cells/watermark)- การสาธิตสดมีข้อดีดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="เพียงอัปโหลดไฟล์ XLS ของคุณ ตั้งค่าลายน้ำแล้วกดปุ่ม \"เพิ่ม\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" รับลิงค์ดาวน์โหลดไฟล์ผลลัพธ์ทันที" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
ไฟล์ที่มีนามสกุล XLS แสดงถึงรูปแบบไฟล์ Excel Binary ไฟล์ดังกล่าวสามารถสร้างได้โดย Microsoft Excel รวมถึงโปรแกรมสเปรดชีตอื่นที่คล้ายคลึงกัน เช่น OpenOffice Calc หรือ Apple Numbers ไฟล์ที่บันทึกโดย Excel เรียกว่าสมุดงาน โดยแต่ละสมุดงานสามารถมีแผ่นงานได้หนึ่งแผ่นขึ้นไป ข้อมูลจะถูกจัดเก็บและแสดงต่อผู้ใช้ในรูปแบบตารางในเวิร์กชีตและสามารถขยายค่าตัวเลข ข้อมูลข้อความ สูตร การเชื่อมต่อข้อมูลภายนอก รูปภาพ และแผนภูมิได้ แอปพลิเคชันเช่น Microsoft Excel ช่วยให้คุณสามารถส่งออกข้อมูลเวิร์กบุ๊กเป็นรูปแบบต่างๆ ได้หลากหลาย รวมถึง PDF, CSV, XLSX, TXT, HTML, XPS และอื่นๆ อีกมากมาย รูปแบบไฟล์ XLS ถูกแทนที่ด้วยรูปแบบที่เปิดกว้างและมีโครงสร้างมากขึ้น คือ XLSX ด้วยการเปิดตัว Microsoft Excel 2007 เวอร์ชันล่าสุดยังคงให้การสนับสนุนสำหรับการสร้างและการอ่านไฟล์ XLS แม้ว่า XLSX จะเป็นตัวเลือกแรกสำหรับการใช้งานในขณะนี้

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบลายน้ำอื่น ๆ ที่รองรับ" subTitle="การใช้ Java ทำให้เราสามารถใส่ลายน้ำให้กับรูปแบบต่างๆ ได้อย่างง่ายดาย รวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
