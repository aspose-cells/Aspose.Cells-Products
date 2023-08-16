---
title: Microsoft Chuyển đổi tệp Excel bằng Python via Java
description: Chuyển đổi Excel XLS, XLSX, ODS, CSV sang PDF, XPS, HTML, JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Chuyển đổi định dạng Excel qua Python" h2="Nhập và xuất các tệp Excel dưới dạng bảng tính, web, hình ảnh và định dạng bố cục cố định" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Thư viện Excel tăng tốc quá trình lập trình và chuyển đổi bảng tính đồng thời hỗ trợ các định dạng phổ biến bao gồm XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS .Còn cho phép xuất file excel sang PDF, XPS, HTML, MHTML, Plain Các định dạng văn bản và hình ảnh phổ biến như TIFF, JPG, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển Excel sang XLSX, ODS, SXC & FODS" %}}
 Chuyển đổi giữa các định dạng bảng tính chỉ yêu cầu tải một bảng tính với phiên bản[Sách bài tập](https://reference.aspose.com/cells/python/asposecells.api/Workbook) và lưu lại ở định dạng mong muốn trong khi chọn giá trị thích hợp từ[LưuĐịnh dạng](https://reference.aspose.com/cells/python/asposecells.api/saveformat) liệt kê.
{{% blocks/products/pf/feature-page-code h3="Python Mã để chuyển đổi định dạng tệp Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Chuyển Excel sang PDF, XPS, HTML & MD" %}}
 Các lớp chuyên biệt có sẵn để kiểm soát quá trình chuyển đổi cho các định dạng đầu ra cụ thể, chẳng hạn như[PdfSaveTùy chọn](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) để xuất tệp Excel dưới dạng PDF,[XpsSaveTùy chọn](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) để chuyển đổi Excel thành XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) để hiển thị Excel dưới dạng HTML và[MarkdownSaveTùy chọn](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) để chuyển đổi Excel sang Markdown.
{{% blocks/products/pf/feature-page-code h3="Python Mã cho Excel thành PDF và Định dạng Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Chuyển JSON sang Excel & Excel sang JSON" %}}
Các nhà phát triển Python có thể dễ dàng tải và chuyển đổi các tệp JSON sang Excel chỉ bằng một vài dòng mã. Tương tự, dữ liệu Excel có thể được xuất thành dữ liệu JSON.
{{% blocks/products/pf/feature-page-code h3="Python Mã cho JSON để chuyển đổi Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Mã cho Excel để chuyển đổi JSON" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi bảng tính Excel sang JPG, BMP, PNG & GIF" %}}
 Mỗi trang tính của tệp Excel có thể được chuyển đổi sang các định dạng hình ảnh khác nhau, hãy gọi[Hình ảnhHoặcInTùy chọn](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions) .setImageFormat để đặt định dạng hình ảnh.
{{% blocks/products/pf/feature-page-code h3="Python Mã để chuyển đổi Excel sang hình ảnh" %}}
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

{{% blocks/products/pf/feature-page-section h2="Chuyển Excel sang Word & PowerPoint" %}}
 Có thể tải bất kỳ bảng tính nào và chuyển đổi nó thành tệp Word DOCX & PowerPoint PPTX trong khi sử dụng[DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [Tùy chọn PptxSave](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions)các lớp như minh họa dưới đây.
{{% blocks/products/pf/feature-page-code h3="Mã Python cho Excel sang Word & PowerPoint Chuyển đổi" %}}
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

{{< blocks/products/pf/feature-page-options pairs="xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx" >}}
