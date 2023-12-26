---
title:  Microsoft Chuyển đổi tệp Excel via Java
description: Aspose.Cells for Java thư viện. Chuyển đổi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG và nhiều định dạng khác chỉ với vài dòng mã Java.
keywords: [Java Aspose.Cells., excel to pdf., excel to json., html to xps., csv to json., json to pdf., xml to excel and Convert files between various formats in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Chuyển đổi tệp Excel via Java" h2="Lưu tài liệu Excel Microsoft dưới dạng bảng tính, web, hình ảnh và bố cục cố định" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Bất cứ gì**Công cụ chuyển đổi Excel** ứng dụng hoặc giải pháp, Java Thư viện Excel tăng tốc quá trình lập trình và chuyển đổi bảng tính trong khi xử lý nhiều định dạng bao gồm XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 0761934 81. Nó cũng cho phép *chuyển đổi tập tin Excel thành PDF**, XPS, HTML, MHTML, Plain Text và các định dạng ảnh phổ biến như TIFF, JPG, PNG, BMP và SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi giữa các định dạng Excel Microsoft" %}}
 Việc chuyển đổi giữa các định dạng bảng tính chỉ yêu cầu tải một bảng tính có phiên bản của[Sách bài tập](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) và lưu lại ở định dạng mong muốn trong khi chọn giá trị thích hợp từ[Lưu định dạng](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) sự liệt kê.
{{% blocks/products/pf/feature-page-code h3="Java Mã ví dụ để chuyển đổi định dạng tệp Excel" %}}

```cs
// load the source file
var wkb = new Workbook("sourceFile.xls");
// save as XLSX, ODS, SXC & FODS formats
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Chuyển đổi Excel thành PDF, XPS, HTML & MD" %}}
 Các lớp chuyên biệt có sẵn để kiểm soát quá trình chuyển đổi cho các định dạng đầu ra cụ thể như[Tùy chọn lưu Pdf](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) để chuyển đổi file Excel thành PDF,[Tùy chọn XpsSave](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) để xuất Excel dưới dạng XPS,[Tùy chọn lưu Html](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) để hiển thị Excel dưới dạng HTML và[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) để chuyển đổi Excel sang Markdown.
{{% blocks/products/pf/feature-page-code h3="Java Mã mẫu Excel tới PDF và Định dạng Web" %}}

```cs
// load template Excel file from disc
var bk = new Workbook("source-file.xlsx");

// convert Excel to PDF using Java
// Create PDF options
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// save Excel in XPS
bk.save("output.xps", new XpsSaveOptions());
// save Excel in HTML
bk.save("output.html", new HtmlSaveOptions());
// save Excel in Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// one can set relevant save options as of his choice before saving into relevant format
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển JSON sang Excel và Excel thành JSON" %}}
 Dữ liệu JSON có thể được nhập vào một phiên bản của lớp Workbook với sự trợ giúp của[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) để xử lý thêm hoặc chuyển đổi đơn giản sang bất kỳ định dạng được hỗ trợ nào. Tương tự, dữ liệu bảng tính có thể được xuất dưới dạng JSON bằng cách tạo một[Phạm vi](https://reference.aspose.com/cells/java/com.aspose.cells/range) hoặc ô và gọi[xuấtRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) phương pháp.
{{% blocks/products/pf/feature-page-code h3="Java Mã chuyển đổi JSON sang Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Read File
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Set JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Import JSON Data
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Save Excel file
workbook.save(path + "excel-to-json.out.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Chuyển đổi mã nguồn Java Excel sang JSON" %}}
```cs
// load XLSX file with an instance of Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// access CellsCollection of the worksheet containing data to be converted
Cells cells = workbook.getWorksheets().get(0).getCells();
// create & set ExportRangeToJsonOptions for advanced options
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// export range as JSON data
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// write data to disc in JSON format
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Lưu bảng tính Excel vào hình ảnh" %}}
 Mỗi bảng tính có thể được chuyển đổi sang các định dạng hình ảnh khác nhau bao gồm JPG, BMP, PNG & GIF, được đặt bởi thuộc tính ImageType. Bất cứ gì**Chuyển đổi Excel thành hình ảnh** trường hợp, chọn trường hợp có liên quan từ các liên kết.
{{% blocks/products/pf/feature-page-code h3="Java Mã chuyển đổi Excel sang hình ảnh" %}}
```cs
// load template spreadsheet
var wkb = new Workbook("template.xlsx");

// Create an object for ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Set the image type
imgOptions.setImageType(ImageType.PNG);

// Get the first worksheet.
Worksheet sheet = wkb.getWorksheets().get(0);

// Create a SheetRender object for the target sheet
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Generate an image for the worksheet
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Chuyển Microsoft Excel sang Word và PowerPoint" %}}
Có thể tải bất kỳ bảng tính nào và chuyển đổi nó thành tệp Word DOCX & PowerPoint PPTX trong khi sử dụng[Tùy chọn lưu Docx](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [Tùy chọn lưu Pptx](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) các lớp như được minh họa dưới đây.
{{% blocks/products/pf/feature-page-code h3="Java Code chuyển Excel sang Word & chuyển đổi PowerPoint" %}}
```cs
// load the template file
var wkb = new Workbook("template.xlsx");
// save spreadsheet as DOCX
wkb.save("output.docx", new DocxSaveOptions());
// save spreadsheet as PPTX
wkb.save("output.pptx", new PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
