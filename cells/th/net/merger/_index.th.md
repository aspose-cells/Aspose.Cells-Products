---
title: รวมไฟล์ Excel API .NET C#
description: เชื่อมต่อไฟล์สเปรดชีต Excel และ OpenOffice ด้วยโค้ด C# เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การรวมไฟล์ Excel via .NET" h2="รวมไฟล์ Excel 2 ไฟล์ขึ้นไปไว้ในสเปรดชีตเดียวโดยใช้รหัส C#" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET เอ็กเซล ไลบรารี่](/cells/th/net/) ให้หลายวิธีในการรวมสมุดงานเข้ากับเนื้อหาประเภทต่างๆ เช่น สูตร ข้อมูล รูปภาพ แผนภูมิ และอื่นๆ ให้เป็นไฟล์สเปรดชีตเดียว รูปแบบไฟล์ที่รองรับได้แก่ XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV และอื่นๆ
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel เข้ากับรูปภาพและแผนภูมิ" %}}
 วิธีที่ง่ายที่สุดในการรวมไฟล์ Excel 2 ไฟล์ที่มีรูปภาพและแผนภูมิคือการเรียก[สมุดงานรวม](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) วิธี. อนุญาตให้รวมไฟล์ Excel ประเภทเดียวกันลงในสเปรดชีตเดียว
{{% blocks/products/pf/feature-page-code h3="C# โค้ดรวมไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel หลายไฟล์" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) วิธีการนี้รองรับการรวมข้อมูล สไตล์ และสูตรของไฟล์ Excel เข้ากับสเปรดชีตใหม่ที่มีรูปแบบเดียวกัน เป็นวิธีที่มีประสิทธิภาพในการรวมไฟล์หลายไฟล์ในขณะที่ใช้แคช
{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับรวมไฟล์ Excel หลายไฟล์" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel โดยการคัดลอกแผ่นงาน" %}}
[แผ่นงาน.คัดลอก](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index)สามารถใช้เพื่อคัดลอกข้อมูลและการจัดรูปแบบจากแผ่นงานต้นฉบับไปยังแผ่นงานอื่นภายในหรือระหว่างสมุดงาน วิธีการใช้วัตถุแผ่นงานต้นทางเป็นพารามิเตอร์
{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อคัดลอกแผ่นงานข้ามไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการรวมอื่น ๆ ที่รองรับ" subTitle="เมื่อใช้ C# เราสามารถรวมรูปแบบไฟล์อื่นๆ มากมายรวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/csv/" name="CSV" description="ค่าที่คั่นด้วยเครื่องหมายจุลภาค" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/html/" name="HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/mhtml/" name="MHTML" description="รูปแบบการเก็บถาวรหน้าเว็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/ods/" name="ODS" description="ไฟล์สเปรดชีต OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/tsv/" name="TSV" description="ค่าที่คั่นด้วยแท็บ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/txt/" name="TXT" description="เอกสารข้อความ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xls/" name="XLS" description="รูปแบบไบนารีของ Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsb/" name="XLSB" description="ไฟล์สมุดงาน Excel ไบนารี" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsm/" name="XLSM" description="ไฟล์สเปรดชีต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsx/" name="XLSX" description="ไฟล์ OOXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlt/" name="XLT" description="Microsoft เทมเพลต Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xltm/" name="XLTM" description="เทมเพลตที่เปิดใช้งาน Excel Macro" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
