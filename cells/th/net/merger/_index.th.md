---
title: การรวมไฟล์ Excel API .NET C#
url: /th/net/merger/
description: เชื่อมไฟล์สเปรดชีต Excel และ OpenOffice ด้วยโค้ด C# เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การรวมไฟล์ Excel ผ่าน .NET" h2="รวมไฟล์ Excel 2 ไฟล์ขึ้นไปในสเปรดชีตเดียวโดยใช้ C# code" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET ไลบรารี Excel](/cells/net/) มีหลายวิธีในการรวมเวิร์กบุ๊กกับเนื้อหาประเภทต่างๆ เช่น สูตร ข้อมูล รูปภาพ แผนภูมิ และอื่นๆ ให้เป็นไฟล์สเปรดชีตไฟล์เดียว รูปแบบไฟล์ที่รองรับ ได้แก่ XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV และอื่นๆ
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel กับรูปภาพและแผนภูมิ" %}}
วิธีที่ง่ายที่สุดในการรวมไฟล์ Excel 2 ไฟล์ที่มีรูปภาพและแผนภูมิคือการเรียก [สมุดงาน รวม](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) กระบวนการ. อนุญาตให้รวมไฟล์ Excel ประเภทเดียวกันลงในสเปรดชีตเดียว
{{% blocks/products/pf/feature-page-code h3="C# โค้ดสำหรับรวมไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel หลายไฟล์" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) method รองรับการผสานข้อมูล รูปแบบ และสูตรของไฟล์ Excel เข้ากับสเปรดชีตใหม่ที่มีรูปแบบเดียวกัน เป็นวิธีที่มีประสิทธิภาพในการรวมหลายไฟล์ในขณะที่ใช้แคช 
{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อรวมไฟล์ Excel หลายไฟล์" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="รวมไฟล์ Excel โดยการคัดลอกแผ่นงาน" %}}
[ใบงาน.คัดลอก](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) สามารถใช้เพื่อคัดลอกข้อมูลและการจัดรูปแบบจากเวิร์กชีตต้นทางไปยังเวิร์กชีตอื่นภายในหรือระหว่างเวิร์กบุ๊ก เมธอดนี้ใช้ออบเจ็กต์เวิร์กชีตต้นทางเป็นพารามิเตอร์
{{% blocks/products/pf/feature-page-code h3="C# โค้ดสำหรับคัดลอกเวิร์กชีตในไฟล์ Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}