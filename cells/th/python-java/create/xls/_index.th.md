---
title: สร้าง XLS - สร้างไฟล์ XLS ใน Python
description: Aspose เอ็กเซล. Python เอ็กเซล. Python สร้างไฟล์ XLS อย่างรวดเร็วและง่ายดายด้วย Aspose.Cells สร้างไฟล์ XLS โดยใช้ Python Excel Library สร้าง XLS ในไลบรารี Excel Python Python XLS คนสร้าง.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create XLS file., Generate XLS file in Python Excel Library., Create XLS file using Python Excel Library., Write data to XLS file via Python Excel Library., Create a XLS file in Python Excel Library., Python Generate a XLS file., Python XLS Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="สร้างไฟล์ XLS ในไลบรารี Excel Python" h2="ไลบรารี Excel Python ความเร็วสูงสำหรับการสร้างไฟล์ XLS นี่คือโซลูชันซอฟต์แวร์ระดับมืออาชีพสำหรับการนำเข้าและส่งออก XLSX, PDF และรูปแบบอื่นๆ อีกมากมายโดยใช้ Python" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="สร้างไฟล์ XLS โดยใช้ไลบรารี Excel Python" %}}

 จะสร้างไฟล์ XLS ได้อย่างไร? ด้วยไลบรารี Excel Aspose.Cells for Python via Java คุณสามารถสร้างไฟล์ XLS โดยทางโปรแกรมได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด[Aspose.Cells for Python](https://pypi.org/project/aspose-cells)สามารถสร้างแอปพลิเคชันข้ามแพลตฟอร์มด้วยความสามารถในการสร้าง แก้ไข แปลง เรนเดอร์ และพิมพ์ไฟล์ Excel ทั้งหมด Python Excel API ไม่เพียงแต่แปลงระหว่างรูปแบบสเปรดชีตเท่านั้น แต่ยังสามารถเรนเดอร์ไฟล์ Excel เป็นรูปภาพ, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT และอื่นๆ อีกมากมาย จึงเป็นตัวเลือกที่สมบูรณ์แบบในการแลกเปลี่ยนเอกสารในรูปแบบมาตรฐานอุตสาหกรรม

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="วิธีสร้าง XLS ในไลบรารี Excel Python" %}}

{{% blocks/products/pf/agp/text %}}

 เป็นเรื่องง่ายสำหรับนักพัฒนาในการสร้าง โหลด แก้ไข และแปลงไฟล์ XLS ภายในการเรียกใช้แอปพลิเคชันการรายงานต่างๆ สำหรับการประมวลผลข้อมูลโดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1.  นำเข้า asposecells ในไฟล์โค้ดของคุณ
1.  สร้างอินสแตนซ์คลาสสมุดงาน
1.  เข้าถึงแผ่นงานแรกของสมุดงาน
1. รับเซลล์ที่ต้องการของแผ่นงานและป้อนค่าลงในเซลล์
1.  ใช้วิธีการบันทึกเพื่อบันทึกสมุดงานเป็นไฟล์ XLS

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่างแสดงวิธีสร้างไฟล์ XLS ในไลบรารี Excel Python" offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

# Create Workbook object.
workbook = Workbook(FileFormatType.XLS)

# Access the first worksheet of the workbook.
worksheet = workbook.getWorksheets().get(0)

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

# Save the workbook as XLS file.
workbook.save("output.xls")

jpype.shutdownJVM()

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python ไลบรารี Excel เพื่อสร้างไฟล์ XLS" %}}

{{% blocks/products/pf/agp/text %}}

มีสามตัวเลือกในการติดตั้ง "Aspose.Cells for Python via Java" ลงในระบบของคุณ โปรดเลือกรายการที่ตรงกับความต้องการของคุณและปฏิบัติตามคำแนะนำทีละขั้นตอน:

{{% /blocks/products/pf/agp/text %}}

1.  ติดตั้ง Aspose.Cells for Python via Java ใน Windows ดู[เอกสารประกอบ](https://docs.aspose.com/cells/python-java/getting-started/#windows)
1.  ติดตั้ง Aspose.Cells for Python via Java ใน Linux ดู[เอกสารประกอบ](https://docs.aspose.com/cells/python-java/getting-started/#linux)
1.  ติดตั้ง Aspose.Cells for Python via Java ใน macOS ดู[เอกสารประกอบ](https://docs.aspose.com/cells/python-java/getting-started/#macos)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Python via Java เป็นอิสระจากแพลตฟอร์ม API และสามารถใช้ได้กับทุกแพลตฟอร์ม (Windows, Linux และ MacOS) เพียงตรวจสอบให้แน่ใจว่าระบบมี Java 1.8 หรือสูงกว่า[Python](https://www.python.org/downloads/) 3.5 หรือสูงกว่า

{{% /blocks/products/pf/agp/text %}}

-  ติดตั้ง Java และเพิ่มลงในตัวแปรสภาพแวดล้อม PATH เช่น:<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  ติดตั้ง Aspose.Cells for Python via Java จาก<a href="https://pypi.org/project/aspose-cells/">pypi</a> ให้ใช้คำสั่งดังนี้:<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}ไฟล์ที่มีนามสกุล XLS แสดงถึงรูปแบบไฟล์ Excel Binary ไฟล์ดังกล่าวสามารถสร้างได้โดย Microsoft Excel รวมถึงโปรแกรมสเปรดชีตอื่นที่คล้ายคลึงกัน เช่น OpenOffice Calc หรือ Apple Numbers ไฟล์ที่บันทึกโดย Excel เรียกว่าสมุดงาน โดยแต่ละสมุดงานสามารถมีแผ่นงานได้หนึ่งแผ่นขึ้นไป ข้อมูลจะถูกจัดเก็บและแสดงต่อผู้ใช้ในรูปแบบตารางในเวิร์กชีตและสามารถขยายค่าตัวเลข ข้อมูลข้อความ สูตร การเชื่อมต่อข้อมูลภายนอก รูปภาพ และแผนภูมิได้ แอปพลิเคชันเช่น Microsoft Excel ช่วยให้คุณสามารถส่งออกข้อมูลเวิร์กบุ๊กเป็นรูปแบบต่างๆ ได้หลากหลาย รวมถึง PDF, CSV, XLSX, TXT, HTML, XPS และอื่นๆ อีกมากมาย รูปแบบไฟล์ XLS ถูกแทนที่ด้วยรูปแบบที่เปิดกว้างและมีโครงสร้างมากขึ้น คือ XLSX ด้วยการเปิดตัว Microsoft Excel 2007 เวอร์ชันล่าสุดยังคงให้การสนับสนุนสำหรับการสร้างและการอ่านไฟล์ XLS แม้ว่า XLSX จะเป็นตัวเลือกแรกสำหรับการใช้งานในขณะนี้{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การสร้างสเปรดชีตอื่นๆ ที่รองรับ" subTitle="คุณยังสามารถสร้างรูปแบบ Excel Microsoft อื่นๆ ได้ รวมถึงบางรูปแบบที่แสดงด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xls/" name="XLS" description="Microsoft สเปรดชีต Excel (ดั้งเดิม)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsx/" name="XLSX" description="เปิดสมุดงาน XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsb/" name="XLSB" description="สมุดงาน Excel ไบนารี" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsm/" name="XLSM" description="สเปรดชีตที่เปิดใช้งานมาโคร" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlt/" name="XLT" description="เทมเพลต Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltx/" name="XLTX" description="เทมเพลต Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltm/" name="XLTM" description="เทมเพลตที่เปิดใช้งานแมโคร Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/csv/" name="CSV" description="ค่าที่คั่นด้วยเครื่องหมายจุลภาค" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/tsv/" name="TSV" description="แท็บค่าที่แยกจากกัน" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/ods/" name="ODS" description="สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/pdf/" name="PDF" description="รูปแบบเอกสารแบบพกพา" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/html/" name="HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
