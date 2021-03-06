---
title: แปลง XLTX เป็น TABDELIMITED ผ่าน Java 
url: /th/java/conversion/xltx-to-tabdelimited/ 
description: ตัวอย่างโค้ดการแปลง Java สำหรับรูปแบบ XLTX เป็นไฟล์ TABDELIMITED โปรแกรมเมอร์สามารถใช้โค้ดตัวอย่างนี้เพื่อส่งออกสเปรดชีต Excel & OpenOffice ไปยัง TABDELIMITED ภายในแอปพลิเคชันบนเว็บหรือเดสก์ท็อป Java
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง XLTX เป็น TABDELIMITED ผ่าน Java" h2="การแปลง XLTX เป็น TABDELIMITED Java เพื่อแปลงหน้าเดียวหรือหลายหน้าเป็น TABDELIMITED โดยใช้ไลบรารี Java ในสถานที่" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TABDELIMITED" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง XLTX เป็น TABDELIMITED โดยใช้ Java" %}}

 ในการแสดง XLTX เป็น TABDELIMITED เราจะใช้
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง XLTX เป็น TABDELIMITED ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java นักพัฒนาซอฟต์แวร์สามารถแปลงไฟล์ XLTX เป็น TABDELIMITED ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ XLTX ด้วยอินสแตนซ์ของ Workbook class1. วิธีการโทร Workbook.save1. ส่งเส้นทางเอาต์พุตด้วยส่วนขยาย TABDELIMITED & SaveFormat เป็นพารามิเตอร์1. ตรวจสอบพาธที่ระบุสำหรับไฟล์ผลลัพธ์ TABDELIMITED

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้ซอร์สโค้ดของการแปลง Java ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป- รับเวอร์ชันล่าสุดของ Aspose.Cells for Java โดยตรงจาก Maven
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTX เป็น TABDELIMITED Java ซอร์สโค้ดการแปลง" offSpacer="" %}}

```cs
// โหลดไฟล์ XLTX ในอินสแตนซ์ของ Workbook
Workbook book = new Workbook("template.xltx");
// บันทึก XLTX เป็น TABDELIMITED
book.save("output.tabdelimited", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLTX เป็น TABDELIMITED สาธิตการแปลงสด" sectionDescription="[แปลง XLTX เป็น TABDELIMITED](https://products.aspose.app/cells/conversion/xltx-to-tabdelimited) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ XLTX ไฟล์จะถูกแปลงเป็น TABDELIMITED ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="Java ไลบรารีการจัดการสเปรดชีต" %}}

 สามารถใช้ Excel API เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTX" readMoreLink="https://docs.fileformat.com/spreadsheet/xltx/" >}}

ไฟล์ที่มีนามสกุล XLTX แสดงถึงไฟล์เทมเพลต Microsoft Excel ที่อิงตามข้อกำหนดรูปแบบไฟล์ Office OpenXML ใช้เพื่อสร้างไฟล์เทมเพลตมาตรฐานที่สามารถใช้สร้างไฟล์ XLSX ที่แสดงการตั้งค่าเดียวกันกับที่ระบุในไฟล์ XLTX

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง XLTX เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-bmp/" name="XLTX เป็น BMP" description="ภาพบิตแมป" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-csv/" name="XLTX เป็น CSV" description="ค่าที่คั่นด้วยจุลภาค" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-dif/" name="XLTX เป็น DIF" description="รูปแบบการแลกเปลี่ยนข้อมูล" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-emf/" name="XLTX เป็น EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-gif/" name="XLTX ถึง GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-html/" name="XLTX เป็น HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-jpeg/" name="XLTX เป็น JPEG" description="ภาพ JPEG" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-mhtml/" name="XLTX เป็น MHTML" description="รูปแบบการเก็บถาวรของหน้าเว็บ" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-ods/" name="XLTX เป็น ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-pdf/" name="XLTX เป็น PDF" description="รูปแบบเอกสารพกพา" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-png/" name="XLTX เป็น PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-svg/" name="XLTX เป็น SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-tiff/" name="XLTX ถึง TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-tsv/" name="XLTX เป็น TSV" description="ค่าที่คั่นด้วยแท็บ" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-txt/" name="XLTX เป็น TXT" description="เอกสารข้อความ" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlm/" name="XLTX ถึง XLM" description="ไฟล์มาโคร Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xls/" name="XLTX ถึง XLS" description="รูปแบบไบนารีของ Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlsb/" name="XLTX ถึง XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlsx/" name="XLTX ถึง XLSX" description="ไฟล์ OOXML Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlt/" name="XLTX เป็น XLT" description="แม่แบบ Microsoft Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xltm/" name="XLTX ถึง XLTM" description="เทมเพลตที่เปิดใช้งาน Excel Macro" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xps/" name="XLTX เป็น XPS" description="ข้อมูลจำเพาะของกระดาษ XML" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-json/" name="XLTX เป็น JSON" description="สัญกรณ์วัตถุ JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}