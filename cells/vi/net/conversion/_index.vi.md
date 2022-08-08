---
title: Chuyển đổi Tệp Microsoft Excel qua C# 
url: /vi/net/conversion/
description: Chuyển đổi Excel XLS, XLSX, ODS, CSV sang PDF, XPS, HTML, JPEG, HTML và nhiều định dạng phổ biến khác chỉ với vài dòng mã C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg; </sup> Chuyển đổi Định dạng Excel qua .NET" h2="Nhập và xuất các tệp Excel dưới dạng bảng tính, web, hình ảnh và các định dạng bố cục cố định" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Thư viện Excel tăng tốc quá trình lập trình và chuyển đổi bảng tính đồng thời hỗ trợ các định dạng phổ biến bao gồm XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Nó cũng cho phép xuất các tệp Excel sang PDF, XPS, HTML, MHTML, Văn bản thuần túy và các định dạng hình ảnh phổ biến như TIFF, JPG, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel sang XLSX, ODS, SXC & FODS" %}}
Việc chuyển đổi giữa các định dạng bảng tính chỉ yêu cầu tải một bảng tính có phiên bản của [Sách bài tập](https://reference.aspose.com/cells/net/aspose.cells/workbook) và lưu lại ở định dạng mong muốn trong khi chọn giá trị thích hợp từ [SaveFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) sự liệt kê.
{{% blocks/products/pf/feature-page-code h3="C# Mã cho Chuyển đổi Định dạng Tệp Excel" %}}

```cs
// tải tệp mẫu
var workbook = new Aspose.Cells.Workbook("template.xls");
// lưu dưới định dạng XLSX, ODS, SXC & FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel sang PDF, XPS, HTML & MD" %}}
Các lớp chuyên biệt có sẵn để kiểm soát quá trình chuyển đổi cho các định dạng đầu ra cụ thể như [PdfSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) để xuất tệp Excel dưới dạng PDF, [XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) để chuyển đổi Excel sang XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) để kết xuất Excel dưới dạng HTML và [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) để chuyển đổi Excel sang Markdown. 
{{% blocks/products/pf/feature-page-code h3="C# Mã cho Excel sang PDF và Định dạng Web" %}}

```cs
// tải tệp mẫu Excel từ đĩa
var book = new Aspose.Cells.Workbook("template.xlsx");
// lưu Excel ở định dạng PDF / A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// lưu Excel trong XPS với 1 trang trên mỗi bảng tính
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// lưu Excel trong HTML với hình ảnh dưới dạng Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// lưu Excel trong Markdown (MD) trong khi vẫn giữ nguyên định dạng ô
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi JSON sang Excel & Excel sang JSON" %}}
Dữ liệu JSON có thể được nhập vào một phiên bản của [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) lớp học với sự giúp đỡ của [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) để xử lý thêm hoặc chuyển đổi đơn giản sang bất kỳ định dạng nào được hỗ trợ. Tương tự, [Bảng tính](https://reference.aspose.com/cells/net/aspose.cells/worksheet) dữ liệu có thể được xuất dưới dạng JSON bằng cách tạo [Phạm vi](https://reference.aspose.com/cells/net/aspose.cells/range) hoặc các ô và gọi [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) phương pháp.
{{% blocks/products/pf/feature-page-code h3="C# Mã cho Chuyển đổi JSON sang Excel" %}}
```cs
// tạo một đối tượng Workbook
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// đọc dữ liệu JSON từ tệp
string jsonInput = File.ReadAllText("Data.json");
// đặt JsonLayoutOptions để coi Mảng là Bảng
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// nhập dữ liệu JSON vào trang tính bắt đầu từ ô A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// lưu tệp kết quả ở định dạng XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Mã chuyển đổi Excel sang JSON" %}}
```cs
// tải tệp XLSX với một phiên bản của Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// Access Cells Bộ sưu tập trang tính chứa dữ liệu cần chuyển đổi
var cells = workbook.Worksheets[0].Cells;
// tạo và đặt ExportRangeToJsonOptions cho các tùy chọn nâng cao
var exportOptions = new Utility.ExportRangeToJsonOptions();
// tạo một dải ô chứa dữ liệu sẽ được xuất
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// xuất phạm vi dưới dạng dữ liệu JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// ghi tệp dữ liệu vào đĩa ở định dạng JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Bảng tính Excel sang JPG, BMP, PNG & GIF" %}}
Mỗi trang tính của tệp Excel có thể được chuyển đổi sang các định dạng hình ảnh khác nhau do [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) bất động sản. Giá trị mặc định là `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Mã chuyển đổi Excel sang Hình ảnh" %}}
```cs
// tải bảng tính mẫu
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// tạo và thiết lập một phiên bản ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// đặt định dạng hình ảnh đầu ra
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// tạo SheetRender cho trang tính đầu tiên trong bộ sưu tập
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// kết xuất trang tính thành hình ảnh
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel sang Word & PowerPoint" %}}
Có thể tải bất kỳ bảng tính nào và chuyển đổi nó sang các tệp Word DOCX & PowerPoint PPTX trong khi sử dụng [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) các lớp như minh họa bên dưới.
{{% blocks/products/pf/feature-page-code h3="C# mã cho Chuyển đổi Excel sang Word & PowerPoint" %}}
```cs
// tải tệp mẫu
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// lưu bảng tính dưới dạng DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// lưu bảng tính dưới dạng PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}