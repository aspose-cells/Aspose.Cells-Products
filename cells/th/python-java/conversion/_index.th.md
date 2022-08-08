---
title: การแปลงไฟล์ Microsoft Excel ผ่าน Python 
url: /th/python/conversion/
description: แปลง Excel XLS, XLSX, ODS, CSV เป็น PDF, XPS, HTML, JPEG, HTML และรูปแบบยอดนิยมอื่นๆ ด้วยโค้ด Python เพียงไม่กี่บรรทัด
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงรูปแบบ Excel ผ่าน Python" h2="นำเข้าและส่งออกไฟล์ Excel เป็นสเปรดชีต เว็บ รูปภาพ และรูปแบบเค้าโครงคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python ไลบรารี Excel ช่วยเพิ่มความเร็วในการเขียนโปรแกรมสเปรดชีตและกระบวนการแปลง ในขณะที่สนับสนุนรูปแบบยอดนิยม เช่น XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS นอกจากนี้ยังอนุญาตให้ส่งออกไฟล์ Excel เป็น PDF, XPS, HTML, MHTML, ข้อความธรรมดา และรูปแบบรูปภาพยอดนิยม เช่น TIFF, JPG, PNG, BMP และ SVG
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น XLSX, ODS, SXC & FODS" %}}
การแปลงรูปแบบสเปรดชีตระหว่างกัน จำเป็นต้องโหลดสเปรดชีตที่มีอินสแตนซ์ของ . เท่านั้น [สมุดงาน](https://reference.aspose.com/cells/python/asposecells.api/Workbook) และบันทึกในรูปแบบที่ต้องการในขณะที่เลือกค่าที่เหมาะสมจาก [บันทึกรูปแบบ](https://reference.aspose.com/cells/python/asposecells.api/saveformat) การแจงนับ
{{% blocks/products/pf/feature-page-code h3="Python โค้ดสำหรับการแปลงรูปแบบไฟล์ Excel" %}}

```cs
// โหลดไฟล์เทมเพลต
workbook = Workbook("Book1.xls")
  
// บันทึกเป็นรูปแบบ XLSX, ODS, SXC & FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น PDF, XPS, HTML & MD" %}}
มีคลาสเฉพาะเพื่อควบคุมกระบวนการแปลงสำหรับรูปแบบเอาต์พุตเฉพาะเช่น [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) เพื่อส่งออกไฟล์ Excel เป็น PDF [XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) สำหรับการแปลง Excel เป็น XPS [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) เพื่อแสดง Excel เป็น HTML และ [MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) สำหรับการแปลง Excel เป็น Markdown 
{{% blocks/products/pf/feature-page-code h3="Python โค้ดสำหรับ Excel เป็น PDF และรูปแบบเว็บ" %}}

```cs
// โหลดเทมเพลตไฟล์ Excel จาก disc
book = Workbook("template.xlsx")

// บันทึก Excel ในรูปแบบ PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// บันทึก Excel ใน XPS ด้วย 1 หน้าต่อแผ่นงาน
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// บันทึก Excel เป็น HTML พร้อมรูปภาพเป็น Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// บันทึก Excel ใน Markdown (MD) ในขณะที่ยังคงการจัดรูปแบบเซลล์ไว้
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง JSON เป็น Excel & Excel เป็น JSON" %}}
Python นักพัฒนาสามารถโหลดและแปลงไฟล์ JSON เป็น Excel ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด ในทำนองเดียวกัน ข้อมูล Excel ก็สามารถส่งออกไปยังข้อมูล JSON ได้
{{% blocks/products/pf/feature-page-code h3="Python โค้ดสำหรับการแปลง JSON เป็น Excel" %}}
```cs
//โหลดไฟล์ json ต้นทางของคุณ
workbook = Workbook("Data.json")
//บันทึกไฟล์เป็นรูปแบบ xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python โค้ดสำหรับการแปลง Excel เป็น JSON" %}}
```cs
//โหลดไฟล์ xlsx ต้นทางของคุณ
workbook = Workbook("input.xlsx")
//บันทึกไฟล์เป็นรูปแบบ json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="แปลงแผ่นงาน Excel เป็น JPG, BMP, PNG & GIF" %}}
แต่ละแผ่นงานของไฟล์ Excel สามารถแปลงเป็นรูปแบบภาพต่างๆ ได้ call [ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat เพื่อกำหนดรูปแบบภาพ 
{{% blocks/products/pf/feature-page-code h3="Python โค้ดสำหรับ Excel เป็นการแปลงรูปภาพ" %}}
```cs
// โหลดสเปรดชีตเทมเพลต
workbook = Workbook("template.xlsx")
// สร้างและตั้งค่าอินสแตนซ์ของ ImageOrPrintOptions
options = ImageOrPrintOptions()
// กำหนดรูปแบบภาพที่ส่งออก
options.setImageFormat(ImageFormat.getPng())
// สร้าง SheetRender สำหรับแผ่นงานแรกในคอลเล็กชัน
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// เรนเดอร์แผ่นงานเป็นรูปภาพ
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น Word & PowerPoint" %}}
สามารถโหลดสเปรดชีตใดก็ได้และแปลงเป็นไฟล์ Word DOCX และ PowerPoint PPTX ขณะใช้งาน [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) ชั้นเรียนดังที่แสดงด้านล่าง
{{% blocks/products/pf/feature-page-code h3="โค้ด Python สำหรับการแปลง Excel เป็น Word & PowerPoint" %}}
```cs
// โหลดไฟล์เทมเพลต
workbook = Workbook("template.xlsx")

// บันทึกสเปรดชีตเป็น DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// บันทึกสเปรดชีตเป็น PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}