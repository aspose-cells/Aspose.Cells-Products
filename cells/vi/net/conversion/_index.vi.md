---
title:  Microsoft Chuyển đổi file Excel qua C#
description: Aspose.Cells for .NET thư viện. Chuyển đổi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG và nhiều định dạng khác chỉ với vài dòng mã C#.
keywords: [C# Aspose.Cells., excel to pdf., excel to json., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Chuyển đổi định dạng Excel via .NET" h2="Nhập và xuất các tệp Excel dưới dạng bảng tính, web, hình ảnh và bố cục cố định" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Thư viện Excel tăng tốc quá trình lập trình và chuyển đổi bảng tính đồng thời hỗ trợ các định dạng phổ biến bao gồm XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. còn cho phép xuất file Excel sang PDF, XPS, HTML, MHTML, Plain Các định dạng văn bản và hình ảnh phổ biến như TIFF, JPG, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel thành XLSX, ODS, SXC & FODS" %}}
 Việc chuyển đổi giữa các định dạng bảng tính chỉ yêu cầu tải một bảng tính có phiên bản của[Sách bài tập](https://reference.aspose.com/cells/net/aspose.cells/workbook) và lưu lại ở định dạng mong muốn trong khi chọn giá trị thích hợp từ[Lưu định dạng](https://reference.aspose.com/cells/net/aspose.cells/saveformat) sự liệt kê.
{{% blocks/products/pf/feature-page-code h3="C# Mã để chuyển đổi định dạng tệp Excel" %}}

```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xls");
// save as XLSX, ODS, SXC & FODS formats
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel thành PDF, XPS, HTML & MD" %}}
 Các lớp chuyên biệt có sẵn để kiểm soát quá trình chuyển đổi cho các định dạng đầu ra cụ thể như[Tùy chọn lưu Pdf](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) để xuất tệp Excel dưới dạng PDF,[Tùy chọn XpsSave](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) để chuyển đổi Excel sang XPS,[Tùy chọn lưu Html](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) để hiển thị Excel dưới dạng HTML và[MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) để chuyển đổi Excel sang Markdown.
{{% blocks/products/pf/feature-page-code h3="C# Mã Excel tới PDF và Định dạng Web" %}}

```cs
// load template Excel file from disc
var book = new Aspose.Cells.Workbook("template.xlsx");
// save Excel in PDF/A-1a format
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// save Excel in XPS with 1 page per worksheet
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// save Excel in HTML with images as Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// save Excel in Markdown (MD) while retaining cell formatting
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Đổi JSON sang Excel & Excel thành JSON" %}}
 Dữ liệu JSON có thể được nhập vào một phiên bản của[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) lớp với sự giúp đỡ của[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) để xử lý thêm hoặc chuyển đổi đơn giản sang bất kỳ định dạng được hỗ trợ nào. Tương tự,[Bảng tính](https://reference.aspose.com/cells/net/aspose.cells/worksheet) dữ liệu có thể được xuất dưới dạng JSON bằng cách tạo[Phạm vi](https://reference.aspose.com/cells/net/aspose.cells/range) hoặc ô và gọi[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) phương pháp.
{{% blocks/products/pf/feature-page-code h3="C# Mã chuyển đổi JSON sang Excel" %}}
```cs
// create a Workbook object
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// read JSON data from file
string jsonInput = File.ReadAllText("Data.json");
// set JsonLayoutOptions to treat Arrays as Table
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// import JSON data to worksheet starting at cell A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// save resultant file in XLSX format
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Chuyển đổi mã C# Excel sang JSON" %}}
```cs
// load XLSX file with an instance of Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// access CellsCollection of the worksheet containing data to be converted
var cells = workbook.Worksheets[0].Cells;
// create & set ExportRangeToJsonOptions for advanced options
var exportOptions = new Utility.ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// export range as JSON data
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// write data file to disc in JSON format
System.IO.File.WriteAllText("output.json", jsonData); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi bảng tính Excel sang JPG, BMP, PNG & GIF" %}}
 Mỗi bảng tính của một tệp Excel có thể được chuyển đổi sang các định dạng hình ảnh khác nhau do người dùng thiết lập.[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) tài sản. Giá trị mặc định là `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Mã chuyển đổi Excel sang hình ảnh" %}}
```cs
// load template spreadsheet
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// create & set an instance of ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// set output image format
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// create SheetRender for first worksheet in the collection
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// render worksheet to image
render.ToImage(0, "output.jpg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển Excel sang Word & PowerPoint" %}}
Có thể tải bất kỳ bảng tính nào và chuyển đổi nó thành tệp Word DOCX & PowerPoint PPTX trong khi sử dụng[Tùy chọn lưu Docx](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [Tùy chọn lưu Pptx](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) các lớp như được minh họa dưới đây.
{{% blocks/products/pf/feature-page-code h3="Mã C# chuyển Excel sang Word & chuyển đổi PowerPoint" %}}
```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// save spreadsheet as DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// save spreadsheet as PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
