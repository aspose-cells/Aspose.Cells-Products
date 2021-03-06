---
title: แปลง CSV เป็น HTML ผ่าน Java 
weight: 6910
url: /th/java/conversion/csv-to-html/ 
description: ตัวอย่างโค้ดการแปลง Java สำหรับรูปแบบ CSV เป็นไฟล์ HTML โปรแกรมเมอร์สามารถใช้โค้ดตัวอย่างนี้เพื่อส่งออกสเปรดชีต Excel & OpenOffice เป็น HTML ภายในแอปพลิเคชันบนเว็บหรือเดสก์ท็อป Java
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง CSV เป็น HTML ผ่าน Java" h2="การแปลง CSV เป็น HTML Java เพื่อแปลงหน้าเดียวหรือหลายหน้าเป็น HTML โดยใช้ไลบรารี Java ในองค์กร" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง CSV เป็น HTML โดยใช้ Java" %}}

 ในการแสดง CSV เป็น HTML เราจะใช้
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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง CSV เป็น HTML ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java นักพัฒนาซอฟต์แวร์สามารถแปลงไฟล์ CSV เป็น HTML ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ CSV ด้วยอินสแตนซ์ของคลาสเวิร์กบุ๊ก1. วิธีการโทร Workbook.save1. ส่งเส้นทางเอาต์พุตด้วยส่วนขยาย HTML & SaveFormat เป็นพารามิเตอร์1. ตรวจสอบเส้นทางที่ระบุสำหรับไฟล์ HTML ที่เป็นผลลัพธ์
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้ซอร์สโค้ดของการแปลง Java ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป- รับเวอร์ชันล่าสุดของ Aspose.Cells for Java โดยตรงจาก Maven
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="CSV เป็น HTML Java รหัสแหล่งที่มาของการแปลง" offSpacer="" %}}

```cs
// โหลดไฟล์ CSV ในอินสแตนซ์ของ Workbook
Workbook book = new Workbook("template.csv");
// บันทึก CSV เป็น HTML
book.save("output.html", SaveFormat.AUTO);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="การสาธิตสดการแปลง CSV เป็น HTML" sectionDescription="[แปลง CSV เป็น HTML](https://products.aspose.app/cells/conversion/csv-to-html) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ CSV ของคุณ ไฟล์นั้นจะถูกแปลงเป็น HTML ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="Java ไลบรารีการจัดการสเปรดชีต" %}}

 สามารถใช้ Excel API เพื่อสร้าง แก้ไข แปลง และแสดงรูปแบบ Microsoft Excel เป็นรูปแบบต่างๆ นอกจากนี้ยังสามารถใช้สำหรับการสร้างแผนภูมิที่ครอบคลุม การรายงานที่ปรับขนาดได้ และการคำนวณที่เชื่อถือได้ภายในแอปพลิเคชันซอฟต์แวร์ Aspose.Cells เป็นแบบสแตนด์อโลน API และไม่ต้องใช้ซอฟต์แวร์ใดๆ เช่น Microsoft หรือ OpenOffice  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

ไฟล์ที่มีนามสกุล CSV (ค่าที่คั่นด้วยจุลภาค) แสดงถึงไฟล์ข้อความธรรมดาที่มีบันทึกข้อมูลด้วยค่าที่คั่นด้วยเครื่องหมายจุลภาค แต่ละบรรทัดในไฟล์ CSV เป็นระเบียนใหม่จากชุดระเบียนที่อยู่ในไฟล์ ไฟล์ดังกล่าวถูกสร้างขึ้นเมื่อมีจุดประสงค์ในการถ่ายโอนข้อมูลจากระบบจัดเก็บข้อมูลหนึ่งไปยังอีกระบบหนึ่ง เนื่องจากแอปพลิเคชันทั้งหมดสามารถรับรู้ระเบียนที่คั่นด้วยเครื่องหมายจุลภาค การนำเข้าไฟล์ข้อมูลดังกล่าวไปยังฐานข้อมูลจึงทำได้สะดวกมาก แอปพลิเคชันสเปรดชีตเกือบทั้งหมด เช่น Microsoft Excel หรือ OpenOffice Calc สามารถนำเข้า CSV ได้โดยไม่ต้องใช้ความพยายามมาก ข้อมูลที่นำเข้าจากไฟล์ดังกล่าวจะถูกจัดเรียงในเซลล์ของสเปรดชีตเพื่อนำเสนอต่อผู้ใช้


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language) เป็นส่วนขยายสำหรับหน้าเว็บที่สร้างขึ้นสำหรับแสดงในเบราว์เซอร์ HTML เป็นที่รู้จักในฐานะภาษาของเว็บ โดยมีการพัฒนาข้อกำหนดของข้อกำหนดข้อมูลใหม่เพื่อแสดงเป็นส่วนหนึ่งของหน้าเว็บ ตัวแปรล่าสุดเรียกว่า HTML 5 ซึ่งให้ความยืดหยุ่นอย่างมากในการทำงานกับภาษา หน้า HTML จะได้รับจากเซิร์ฟเวอร์ซึ่งโฮสต์เหล่านี้หรือสามารถโหลดจากระบบภายในได้เช่นกัน หน้า HTML แต่ละหน้าประกอบด้วยองค์ประกอบ HTML เช่น แบบฟอร์ม ข้อความ รูปภาพ แอนิเมชั่น ลิงก์ ฯลฯ องค์ประกอบเหล่านี้แสดงโดยแท็ก เช่น img, a, p และอื่นๆ อีกหลายอย่างซึ่งแต่ละแท็กมีจุดเริ่มต้นและจุดสิ้นสุด นอกจากนี้ยังสามารถฝังแอปพลิเคชันที่เขียนด้วยภาษาสคริปต์ เช่น JavaScript และสไตล์ชีต (CSS) สำหรับการแสดงเค้าโครงโดยรวม


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง CSV เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-bmp/" name="CSV เป็น BMP" description="ภาพบิตแมป" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-dif/" name="CSV ถึง DIF" description="รูปแบบการแลกเปลี่ยนข้อมูล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-emf/" name="CSV เป็น EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-gif/" name="CSV เป็น GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-jpeg/" name="CSV เป็น JPEG" description="ภาพ JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-mhtml/" name="CSV เป็น MHTML" description="รูปแบบการเก็บถาวรของหน้าเว็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-ods/" name="CSV เป็น ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-pdf/" name="CSV เป็น PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-png/" name="CSV เป็น PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-svg/" name="CSV เป็น SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-tiff/" name="CSV เป็น TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-tsv/" name="CSV เป็น TSV" description="ค่าที่คั่นด้วยแท็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-txt/" name="CSV เป็น TXT" description="เอกสารข้อความ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlm/" name="CSV เป็น XLM" description="ไฟล์มาโคร Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xls/" name="CSV เป็น XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlsb/" name="CSV เป็น XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlsx/" name="CSV เป็น XLSX" description="ไฟล์ OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlt/" name="CSV เป็น XLT" description="แม่แบบ Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xltm/" name="CSV เป็น XLTM" description="เทมเพลตที่เปิดใช้งาน Excel Macro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xltx/" name="CSV เป็น XLTX" description="เทมเพลต Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xps/" name="CSV เป็น XPS" description="ข้อมูลจำเพาะของกระดาษ XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-json/" name="CSV เป็น JSON" description="สัญกรณ์วัตถุ JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}