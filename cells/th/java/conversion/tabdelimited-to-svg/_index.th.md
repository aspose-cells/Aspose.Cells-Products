---
title: แปลง TABDELIMITED เป็น SVG ผ่าน Java 
url: /th/java/conversion/tabdelimited-to-svg/ 
description: ตัวอย่างโค้ดการแปลง Java สำหรับรูปแบบ TABDELIMITED เป็นไฟล์ SVG โปรแกรมเมอร์สามารถใช้โค้ดตัวอย่างนี้เพื่อส่งออกสเปรดชีต Excel & OpenOffice ไปยัง SVG ภายในแอปพลิเคชันบนเว็บหรือเดสก์ท็อป Java
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง TABDELIMITED เป็น SVG ผ่าน Java" h2="การแปลง TABDELIMITED เป็น SVG Java เพื่อแปลงหน้าเดียวหรือหลายหน้าเป็น SVG โดยใช้ไลบรารีภายในองค์กร Java" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TABDELIMITED" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง TABDELIMITED เป็น SVG โดยใช้ Java" %}}

 เพื่อแสดง TABDELIMITED เป็น SVG เราจะใช้
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API ซึ่งเป็นแพลตฟอร์มการแปลง API for Java ที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 และติดตั้งภายในโปรเจ็กต์ที่ใช้ Maven โดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml

{{% blocks/products/pf/agp/code-block title="ที่เก็บ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การพึ่งพา" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง TABDELIMITED เป็น SVG ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java นักพัฒนาซอฟต์แวร์สามารถแปลงไฟล์ TABDELIMITED เป็น SVG ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ TABDELIMITED ด้วยอินสแตนซ์ของ Workbook1. เลือกค่าเริ่มต้นหรือเวิร์กชีตใดก็ได้จากคอลเล็กชัน1. สร้างและตั้งค่าวัตถุของ ImageOrPrintOptions1. สร้าง SheetRender ด้วยออบเจ็กต์ Worksheet & ImageOrPrintOptions1. เรียกวิธี SheetRender.toImage เพื่อบันทึกผลลัพธ์ในรูปแบบ SVG

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้ซอร์สโค้ดของการแปลง Java ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป- รับเวอร์ชันล่าสุดของ Aspose.Cells for Java โดยตรงจาก Maven
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TABDELIMITED ถึง SVG Java รหัสแหล่งที่มาของการแปลง" offSpacer="" %}}

```cs
// โหลดไฟล์ TABDELIMITED ที่จะแสดงผล
Workbook workbook = new Workbook("sourceFile.tabdelimited");
// เข้าถึงแผ่นงานเริ่มต้นจากคอลเลกชัน
Worksheet worksheet = workbook.getWorksheets().get(0);
// กำหนดพารามิเตอร์สำหรับภาพผลลัพธ์
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.SVG);
// แปลงเวิร์กชีตเป็นรูปภาพในรูปแบบ SVG
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.svg");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TABDELIMITED เพื่อสาธิตการแปลง SVG สด" sectionDescription="[แปลง TABDELIMITED เป็น SVG](https://products.aspose.app/cells/conversion/tabdelimited-to-svg) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ TABDELIMITED ของคุณ ไฟล์จะถูกแปลงเป็น SVG ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="Java ไลบรารีการจัดการสเปรดชีต" %}}

 สามารถใช้ Excel API เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/page-description-language/svg/" >}}

ไฟล์ SVG เป็นไฟล์กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้ซึ่งใช้รูปแบบข้อความแบบ XML เพื่ออธิบายลักษณะที่ปรากฏของรูปภาพ คำว่า Scalable หมายถึงความจริงที่ว่า SVG สามารถปรับขนาดเป็นขนาดต่างๆ ได้โดยไม่สูญเสียคุณภาพใดๆ คำอธิบายตามข้อความของไฟล์ดังกล่าวทำให้ไม่ขึ้นกับความละเอียด เป็นรูปแบบหนึ่งที่ใช้กันมากที่สุดในการสร้างเว็บไซต์และพิมพ์กราฟิกเพื่อให้ได้ความสามารถในการปรับขนาด รูปแบบสามารถใช้ได้กับกราฟิกสองมิติเท่านั้น ไฟล์ SVG สามารถดู/เปิดได้ในเบราว์เซอร์สมัยใหม่เกือบทั้งหมด รวมถึง Chrome, Internet Explorer, Firefox และ Safari

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}