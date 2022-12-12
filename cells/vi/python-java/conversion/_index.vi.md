---
title: Chuyển đổi Tệp Microsoft Excel qua Python 

description: Chuyển đổi Excel XLS, XLSX, ODS, CSV sang PDF, XPS, HTML, JPEG, HTML và nhiều định dạng phổ biến khác chỉ với vài dòng mã Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg; </sup> Chuyển đổi Định dạng Excel qua Python" h2="Nhập và xuất các tệp Excel dưới dạng bảng tính, web, hình ảnh và các định dạng bố cục cố định" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Thư viện Excel tăng tốc quá trình lập trình và chuyển đổi bảng tính đồng thời hỗ trợ các định dạng phổ biến bao gồm XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Nó cũng cho phép xuất các tệp Excel sang PDF, XPS, HTML, MHTML, Văn bản thuần túy và các định dạng hình ảnh phổ biến như TIFF, JPG, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel sang XLSX, ODS, SXC & FODS" %}}
Việc chuyển đổi giữa các định dạng bảng tính chỉ yêu cầu tải một bảng tính có phiên bản của [Sách bài tập](https://reference.aspose.com/cells/python/asposecells.api/Workbook) và lưu lại ở định dạng mong muốn trong khi chọn giá trị thích hợp từ [SaveFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) sự liệt kê.
{{% blocks/products/pf/feature-page-code h3="Python Mã cho Chuyển đổi Định dạng Tệp Excel" %}}

```cs
// tải tệp mẫu
workbook = Workbook("Book1.xls")
  
// lưu dưới định dạng XLSX, ODS, SXC & FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel sang PDF, XPS, HTML & MD" %}}
Các lớp chuyên biệt có sẵn để kiểm soát quá trình chuyển đổi cho các định dạng đầu ra cụ thể như [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) để xuất tệp Excel dưới dạng PDF, [XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) để chuyển đổi Excel sang XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) để kết xuất Excel dưới dạng HTML và [MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) để chuyển đổi Excel sang Markdown. 
{{% blocks/products/pf/feature-page-code h3="Python Mã cho Excel sang PDF và Định dạng Web" %}}

```cs
// tải tệp mẫu Excel từ đĩa
book = Workbook("template.xlsx")

// lưu Excel ở định dạng PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// lưu Excel trong XPS với 1 trang trên mỗi bảng tính
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// lưu Excel trong HTML với hình ảnh dưới dạng Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// lưu Excel trong Markdown (MD) trong khi vẫn giữ nguyên định dạng ô
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi JSON sang Excel & Excel sang JSON" %}}
Python các nhà phát triển có thể dễ dàng tải và chuyển đổi các tệp JSON sang Excel chỉ trong một vài dòng mã. Tương tự, dữ liệu Excel có thể được xuất sang dữ liệu JSON.
{{% blocks/products/pf/feature-page-code h3="Python Mã cho Chuyển đổi JSON sang Excel" %}}
```cs
//Tải tệp json nguồn của bạn
workbook = Workbook("Data.json")
//lưu tệp sang định dạng xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Mã chuyển đổi Excel sang JSON" %}}
```cs
//Tải tệp xlsx nguồn của bạn
workbook = Workbook("input.xlsx")
//lưu tệp sang định dạng json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Bảng tính Excel sang JPG, BMP, PNG & GIF" %}}
Mỗi trang tính của tệp Excel có thể được chuyển đổi sang các định dạng hình ảnh khác nhau, hãy gọi [ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat để đặt định dạng hình ảnh. 
{{% blocks/products/pf/feature-page-code h3="Python Mã chuyển đổi Excel sang Hình ảnh" %}}
```cs
// tải bảng tính mẫu
workbook = Workbook("template.xlsx")
// tạo và thiết lập một phiên bản ImageOrPrintOptions
options = ImageOrPrintOptions()
// đặt định dạng hình ảnh đầu ra
options.setImageFormat(ImageFormat.getPng())
// tạo SheetRender cho trang tính đầu tiên trong bộ sưu tập
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// kết xuất trang tính thành hình ảnh
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel sang Word & PowerPoint" %}}
Có thể tải bất kỳ bảng tính nào và chuyển đổi nó sang các tệp Word DOCX & PowerPoint PPTX trong khi sử dụng [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) các lớp như minh họa bên dưới.
{{% blocks/products/pf/feature-page-code h3="Python mã cho Chuyển đổi Excel sang Word & PowerPoint" %}}
```cs
// tải tệp mẫu
workbook = Workbook("template.xlsx")

// lưu bảng tính dưới dạng DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// lưu bảng tính dưới dạng PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
