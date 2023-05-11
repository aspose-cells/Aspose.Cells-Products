---
title: โปรแกรมรวมไฟล์ Excel API .NET C#
description: เชื่อมไฟล์สเปรดชีต Excel และ OpenOffice ด้วยรหัส C# เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การรวมไฟล์ Excel via .NET" h2="รวมไฟล์ Excel 2 ไฟล์ขึ้นไปในสเปรดชีตเดียวโดยใช้รหัส C#" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET คลังเอ็กเซล](/cells/th/net/) มีหลายวิธีในการรวมสมุดงานที่มีเนื้อหาประเภทต่างๆ เช่น สูตร ข้อมูล รูปภาพ แผนภูมิ และอื่นๆ ไว้ในไฟล์สเปรดชีตเดียว รูปแบบไฟล์ที่รองรับ ได้แก่ XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV และอื่นๆ
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel เข้ากับรูปภาพและแผนภูมิ" %}}
 วิธีที่ง่ายที่สุดในการรวมไฟล์ Excel 2 ไฟล์ที่มีรูปภาพและแผนภูมิคือการเรียก[สมุดงานรวม](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) วิธี. อนุญาตให้รวมไฟล์ Excel ประเภทเดียวกันไว้ในสเปรดชีตเดียว
{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อรวมไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel หลายไฟล์" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) เมธอดรองรับการรวมข้อมูล สไตล์ และสูตรของไฟล์ Excel เข้ากับสเปรดชีตใหม่ที่มีรูปแบบเดียวกัน เป็นวิธีที่มีประสิทธิภาพในการรวมไฟล์หลายไฟล์ในขณะที่ใช้การแคช
{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อรวมไฟล์ Excel หลายไฟล์" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel โดยการคัดลอกแผ่นงาน" %}}
[ใบงาน.Copy](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index)สามารถใช้เพื่อคัดลอกข้อมูลและการจัดรูปแบบจากแผ่นงานต้นทางไปยังแผ่นงานอื่นภายในหรือระหว่างสมุดงาน วิธีการใช้วัตถุแผ่นงานต้นฉบับเป็นพารามิเตอร์
{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อคัดลอกแผ่นงานข้ามไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการผสานอื่นๆ ที่รองรับ" subTitle="เมื่อใช้ C# One ยังสามารถผสานรูปแบบไฟล์อื่นๆ ได้อีกมากมาย รวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/csv/" name="CSV" description="ค่าที่คั่นด้วยเครื่องหมายจุลภาค" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/html/" name="HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/mhtml/" name="MHTML" description="รูปแบบการเก็บถาวรของหน้าเว็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/tsv/" name="TSV" description="ค่าที่คั่นด้วยแท็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/txt/" name="TXT" description="เอกสารข้อความ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsb/" name="XLSB" description="ไฟล์สมุดงานไบนารี Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlt/" name="XLT" description="Microsoft เทมเพลต Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xltm/" name="XLTM" description="เทมเพลตที่เปิดใช้งานแมโครของ Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
