---
title: Hợp nhất các tệp Excel khác nhau thành một tệp duy nhất trong Java

description: Hợp nhất các tệp Excel bằng cách sử dụng Java thành nhiều trang tính hoặc một trang tính. Hợp nhất, kết hợp hoặc nối các tài liệu Excel sang PDF, Hình ảnh và HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg; </sup> Hợp nhất Tệp Excel qua Java" h2="Kết hợp hai hoặc nhiều tệp Excel trong một bảng tính bằng cách sử dụng mã Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Thư viện Excel](/cells/java/) cung cấp nhiều cách để kết hợp sổ làm việc với nhiều loại nội dung khác nhau như công thức, hình ảnh, dữ liệu, biểu đồ, v.v. vào một tài liệu bảng tính duy nhất. Các định dạng tệp được hỗ trợ bao gồm XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV và hơn thế nữa.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kết hợp Tệp Excel với Hình ảnh và Biểu đồ" %}}
Cách đơn giản nhất để kết hợp hai tệp Excel có hình ảnh và biểu đồ là gọi [Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) phương pháp. Nó cho phép hợp nhất các tệp Excel cùng loại thành một bảng tính duy nhất.
{{% blocks/products/pf/feature-page-code h3="Java Mã để Kết hợp Tệp Excel" %}}

```cs
// tải tệp Excel đầu tiên
var book1 = new Workbook("with-charts.xlsx");
// tải tệp Excel thứ hai vào một phiên bản riêng biệt
var book2 = new Workbook("with-images.xlsx");

// hợp nhất hai sổ làm việc
book1.combine(book2);
// lưu sổ làm việc đích 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất nhiều tệp Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) phương pháp hỗ trợ hợp nhất dữ liệu, kiểu và công thức của tệp Excel vào một bảng tính mới có cùng định dạng. Đó là một cách hiệu quả để hợp nhất một số tệp trong khi sử dụng bộ nhớ đệm. 
{{% blocks/products/pf/feature-page-code h3="Java Mã để Hợp nhất Một số Tệp Excel" %}}

```cs
// tạo một Mảng (length = 2)
String[] files = new String[2];
// chỉ định đường dẫn tệp sẽ được hợp nhất
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// hợp nhất các tệp để lưu kết quả
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất các tệp Excel bằng cách sao chép trang tính" %}}
[Worksheet.copy](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)có thể được sử dụng để sao chép dữ liệu và định dạng từ một trang tính nguồn sang một trang tính khác trong hoặc giữa các sổ làm việc. Phương thức này lấy đối tượng trang tính nguồn làm tham số.
{{% blocks/products/pf/feature-page-code h3="Java Mã để Sao chép Trang tính giữa các Sổ làm việc" %}}

```cs
// Tạo Sổ làm việc.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Tạo một Sổ làm việc khác.
Workbook excelWorkbook1 = new Workbook();

// Sao chép trang đầu tiên của cuốn sách thứ nhất vào cuốn sách thứ hai.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Lưu các tập tin.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
