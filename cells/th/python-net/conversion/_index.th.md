---
title: Microsoft การแปลงไฟล์ Excel โดยใช้ Python via NET
description: แปลง Excel XLS, XLSX, ODS, CSV เป็น PDF, XPS, HTML, JPEG, HTML และรูปแบบยอดนิยมอื่น ๆ อีกมากมายด้วยรหัส Python เพียงไม่กี่บรรทัด .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> การแปลงรูปแบบ Excel ผ่าน Python" h2="นำเข้าและส่งออกไฟล์ Excel เป็นรูปแบบสเปรดชีต เว็บ รูปภาพ และเค้าโครงคงที่" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel Library เร่งความเร็วการเขียนโปรแกรมสเปรดชีตและกระบวนการแปลงในขณะที่รองรับรูปแบบยอดนิยม ได้แก่ XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 076193 481 นอกจากนี้ยังอนุญาตให้ส่งออกไฟล์ Excel ไปที่ PDF, XPS, HTML, MHTML, Plain รูปแบบข้อความและรูปภาพยอดนิยม เช่น TIFF, JPG, PNG, BMP และ SVG
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น XLSX, ODS, SXC & FODS" %}}
 การแปลงรูปแบบสเปรดชีตระหว่างกันจำเป็นต้องโหลดสเปรดชีตที่มีอินสแตนซ์ของ[สมุดงาน](https://reference.aspose.com/cells/python-net/aspose.cells/workbook/) และบันทึกกลับในรูปแบบที่ต้องการพร้อมเลือกค่าที่เหมาะสมจาก[บันทึกรูปแบบ](https://reference.aspose.com/cells/python-net/aspose.cells/saveformat/) การแจงนับ
{{% blocks/products/pf/feature-page-code h3="Python รหัสสำหรับการแปลงรูปแบบไฟล์ Excel" %}}

```cs
// load the template file
workbook = Workbook("Book1.xls")
  
// save as XLSX, ODS, SXC & FODS formats
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.sxc", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น PDF, XPS, HTML & MD" %}}
 มีคลาสเฉพาะสำหรับควบคุมกระบวนการแปลงสำหรับรูปแบบเอาต์พุตเฉพาะ เช่น[PdfSaveตัวเลือก](https://reference.aspose.com/cells/python-net/aspose.cells/pdfsaveoptions/) เพื่อส่งออกไฟล์ Excel เป็น PDF[ตัวเลือก XpsSave](https://reference.aspose.com/cells/python-net/aspose.cells/xpssaveoptions/) สำหรับการแปลง Excel เป็น XPS[ตัวเลือก HtmlSave](https://reference.aspose.com/cells/python-net/aspose.cells/htmlsaveoptions/) เพื่อแสดง Excel เป็น HTML และ[MarkdownSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/markdownsaveoptions/) สำหรับการแปลง Excel เป็น Markdown
{{% blocks/products/pf/feature-page-code h3="Python รหัสสำหรับ Excel ถึง PDF และรูปแบบเว็บ" %}}

```cs
// load template Excel file from disc
book = Workbook("template.xlsx")

// save Excel in PDF_A_1_B format
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// save Excel in XPS with 1 page per worksheet
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// save Excel in HTML with images as Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// save Excel in Markdown (MD) while retaining cell formatting
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง JSON เป็น Excel และ Excel เป็น JSON" %}}
นักพัฒนา Python สามารถโหลดและแปลงไฟล์ JSON เป็น Excel ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด ในทำนองเดียวกัน ข้อมูล Excel สามารถส่งออกไปยังข้อมูล JSON
{{% blocks/products/pf/feature-page-code h3="รหัส Python สำหรับการแปลง JSON เป็น Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python รหัสสำหรับการแปลง Excel เป็น JSON" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="แปลงแผ่นงาน Excel เป็น JPG, BMP, PNG & GIF" %}}
 แต่ละแผ่นงานของไฟล์ Excel สามารถแปลงเป็นรูปแบบภาพต่างๆ โทร[ImageOrPrintOptions](https://reference.aspose.com/cells/python-net/aspose.cells.rendering/imageorprintoptions/) .setImageFormat เพื่อกำหนดรูปแบบภาพ
{{% blocks/products/pf/feature-page-code h3="Python รหัสสำหรับการแปลง Excel เป็นรูปภาพ" %}}
```cs
// load template spreadsheet
workbook = Workbook("template.xlsx")
// create & set an instance of ImageOrPrintOptions
options = ImageOrPrintOptions()
// set output image format
options.setImageFormat(ImageFormat.getPng())
// create SheetRender for first worksheet in the collection
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// render worksheet to image
sr.toImage(0, "output.jpg")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="แปลง Excel เป็น Word & PowerPoint" %}}
 เป็นไปได้ที่จะโหลดสเปรดชีตและแปลงเป็นไฟล์ Word DOCX & PowerPoint PPTX ขณะใช้งาน[ตัวเลือก DocxSave](https://reference.aspose.com/cells/python-net/aspose.cells/docxsaveoptions/) & [ตัวเลือก PptxSave](https://reference.aspose.com/cells/python-net/aspose.cells/pptxsaveoptions/) ชั้นเรียนที่แสดงด้านล่าง
{{% blocks/products/pf/feature-page-code h3="รหัส Python สำหรับการแปลง Excel เป็น Word & PowerPoint" %}}
```cs
// load the template file
workbook = Workbook("template.xlsx")

// save spreadsheet as DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// save spreadsheet as PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx" >}}
