---
title: Chuyển đổi Tệp Microsoft Excel qua Java 
url: /vi/java/conversion/
description: Chuyển đổi Excel XLS, XLSX, ODS, CSV sang PDF, XPS, HTML, JPEG, HTML và nhiều định dạng phổ biến khác chỉ với vài dòng mã Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg; </sup> Chuyển đổi Tệp Excel qua Java" h2="Lưu tài liệu Microsoft Excel dưới dạng bảng tính, web, hình ảnh và các định dạng bố cục cố định" >}}

{{% blocks/products/pf/feature-page-summary %}}
Đối với bất kỳ ứng dụng hoặc giải pháp ** Excel converter ** nào, Java Thư viện Excel tăng tốc quá trình lập trình và chuyển đổi bảng tính trong khi xử lý nhiều định dạng bao gồm XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Nó cũng cho phép ** chuyển đổi các tệp Excel sang PDF **, XPS, HTML, MHTML, Văn bản thuần túy và các định dạng hình ảnh phổ biến như TIFF, JPG, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi giữa các Định dạng Microsoft Excel" %}}
Việc chuyển đổi giữa các định dạng bảng tính chỉ yêu cầu tải một bảng tính có phiên bản của [Sách bài tập](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) và lưu lại ở định dạng mong muốn trong khi chọn giá trị thích hợp từ [SaveFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) sự liệt kê.
{{% blocks/products/pf/feature-page-code h3="Java Mã Ví dụ cho Chuyển đổi Định dạng Tệp Excel" %}}

```cs
// tải tệp nguồn
var wkb = new Workbook("sourceFile.xls");
// lưu dưới định dạng XLSX, ODS, SXC & FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel sang PDF, XPS, HTML & MD" %}}
Các lớp chuyên biệt có sẵn để kiểm soát quá trình chuyển đổi cho các định dạng đầu ra cụ thể như [PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) để chuyển đổi các tệp Excel thành PDF, [XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) để xuất Excel dưới dạng XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) để kết xuất Excel dưới dạng HTML và [MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) để chuyển đổi Excel sang Markdown. 
{{% blocks/products/pf/feature-page-code h3="Java Mã Mẫu cho Excel sang PDF và Định dạng Web" %}}

```cs
// tải tệp mẫu Excel từ đĩa
var bk = new Workbook("source-file.xlsx");

// chuyển đổi Excel sang PDF bằng Java
// Tạo các tùy chọn PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// lưu Excel trong XPS
bk.save("output.xps", new XpsSaveOptions());
// lưu Excel trong HTML
bk.save("output.html", new HtmlSaveOptions());
// lưu Excel trong Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// người ta có thể đặt các tùy chọn lưu có liên quan theo lựa chọn của mình trước khi lưu vào định dạng phù hợp

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi JSON sang Excel và Excel sang JSON" %}}
Dữ liệu JSON có thể được nhập vào một phiên bản của lớp Workbook với sự trợ giúp của [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) để xử lý thêm hoặc chuyển đổi đơn giản sang bất kỳ định dạng nào được hỗ trợ. Tương tự, dữ liệu Trang tính có thể được xuất dưới dạng JSON bằng cách tạo [Phạm vi](https://reference.aspose.com/cells/java/com.aspose.cells/range) hoặc các ô và gọi [exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) phương pháp.
{{% blocks/products/pf/feature-page-code h3="Java Mã cho Chuyển đổi JSON sang Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Đọc tài liệu
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Đặt JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Nhập dữ liệu JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Lưu tệp Excel
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Mã nguồn cho chuyển đổi Excel sang JSON" %}}
```cs
// tải tệp XLSX với một phiên bản của Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// Access Cells Bộ sưu tập trang tính chứa dữ liệu cần chuyển đổi
Cells cells = workbook.getWorksheets().get(0).getCells();
// tạo và đặt ExportRangeToJsonOptions cho các tùy chọn nâng cao
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// tạo một dải ô chứa dữ liệu sẽ được xuất
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// xuất phạm vi dưới dạng dữ liệu JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// ghi dữ liệu vào đĩa ở định dạng JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Lưu Trang tính Excel vào Hình ảnh" %}}
Mỗi trang tính có thể được chuyển đổi sang các định dạng hình ảnh khác nhau bao gồm JPG, BMP, PNG & GIF, được đặt bởi thuộc tính ImageType. Đối với bất kỳ trường hợp ** Chuyển Excel sang Hình ảnh ** nào, hãy chọn trường hợp liên quan từ các liên kết.
{{% blocks/products/pf/feature-page-code h3="Java Mã chuyển đổi Excel sang Hình ảnh" %}}
```cs
// tải bảng tính mẫu
var wkb = new Workbook("template.xlsx");

// Tạo một đối tượng cho ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Đặt loại hình ảnh
imgOptions.setImageType(ImageType.PNG);

// Nhận trang tính đầu tiên.
Worksheet sheet = wkb.getWorksheets().get(0);

// Tạo một đối tượng SheetRender cho trang tính đích
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Tạo hình ảnh cho trang tính
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Microsoft Excel sang Word và PowerPoint" %}}
Có thể tải bất kỳ bảng tính nào và chuyển đổi nó sang các tệp Word DOCX & PowerPoint PPTX trong khi sử dụng [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) các lớp như minh họa bên dưới.
{{% blocks/products/pf/feature-page-code h3="Java Mã chuyển đổi Excel sang Word & PowerPoint" %}}
```cs
// tải tệp mẫu
var wkb = new Workbook("template.xlsx");
// lưu bảng tính dưới dạng DOCX
wkb.save("output.docx", new DocxSaveOptions());
// lưu bảng tính dưới dạng PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}