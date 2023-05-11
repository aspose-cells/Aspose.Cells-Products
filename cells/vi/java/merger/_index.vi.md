---
title: Hợp nhất các tệp Excel khác nhau thành một trong Java
description: Hợp nhất các tệp Excel bằng cách sử dụng Java thành nhiều trang tính hoặc một trang tính. Hợp nhất, kết hợp hoặc nối các tài liệu Excel thành PDF, Hình ảnh và HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Hợp nhất tệp Excel via Java" h2="Kết hợp hai hoặc nhiều tệp Excel trong một bảng tính bằng mã Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Thư Viện Excel](/cells/vi/java/) cung cấp nhiều cách để kết hợp sổ làm việc với nhiều loại nội dung khác nhau như công thức, hình ảnh, dữ liệu, biểu đồ, v.v. vào một tài liệu bảng tính duy nhất. Các định dạng tệp được hỗ trợ bao gồm XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV, v.v.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kết hợp tệp Excel với hình ảnh và biểu đồ" %}}
 Cách đơn giản nhất để kết hợp hai tệp Excel có hình ảnh và biểu đồ là gọi hàm[Sổ làm việc.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) phương pháp. Nó cho phép hợp nhất các tệp Excel cùng loại vào một bảng tính duy nhất.
{{% blocks/products/pf/feature-page-code h3="Java Mã để kết hợp các tệp Excel" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất nhiều tệp Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) phương pháp hỗ trợ hợp nhất dữ liệu, kiểu dáng và công thức của tệp Excel sang một bảng tính mới có cùng định dạng. Đó là một cách hiệu quả để hợp nhất một số tệp trong khi sử dụng bộ nhớ đệm.
{{% blocks/products/pf/feature-page-code h3="Java Mã để hợp nhất một số tệp Excel" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất các tệp Excel bằng cách sao chép trang tính" %}}
[Bảng tính.copy](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) có thể được dùng để sao chép dữ liệu và định dạng từ một trang tính nguồn sang một trang tính khác trong hoặc giữa các sổ làm việc. Phương thức lấy đối tượng trang tính nguồn làm tham số.
{{% blocks/products/pf/feature-page-code h3="Java Mã để sao chép các trang tính giữa các sổ làm việc" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng hợp nhất được hỗ trợ khác" subTitle="Sử dụng Java, Người ta cũng có thể hợp nhất nhiều định dạng tệp khác bao gồm.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Các giá trị được phân tách bằng dấu phẩy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Định dạng lưu trữ trang web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Tệp bảng tính OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Các giá trị được phân tách bằng tab" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Dữ liệu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Định dạng nhị phân Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Tệp sổ làm việc Excel nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Tệp bảng tính" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Tệp Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Mẫu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Mẫu hỗ trợ Macro Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
