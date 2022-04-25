---
title: Hợp nhất Tệp Excel API .NET C#
url: /vi/net/merger/
description: Nối các tệp bảng tính Excel và OpenOffice chỉ bằng vài dòng mã C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg; </sup> Hợp nhất Tệp Excel qua .NET" h2="Kết hợp 2 hoặc nhiều tệp Excel trong một bảng tính bằng cách sử dụng mã C#" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Thư viện Excel](/cells/net/) cung cấp nhiều cách để kết hợp sổ làm việc với nhiều loại nội dung khác nhau như công thức, dữ liệu, hình ảnh, biểu đồ, v.v. vào một tệp bảng tính duy nhất. Các định dạng tệp được hỗ trợ bao gồm XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV và hơn thế nữa.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kết hợp Tệp Excel với Hình ảnh và Biểu đồ" %}}
Cách đơn giản nhất để kết hợp 2 tệp Excel có hình ảnh và biểu đồ là gọi [Workbook.Combine](https://apireference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) phương pháp. Nó cho phép hợp nhất các tệp Excel cùng loại thành một bảng tính duy nhất.
{{% blocks/products/pf/feature-page-code h3="C# Mã để Kết hợp Tệp Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất nhiều tệp Excel" %}}
[CellsHelper.MergeFiles](https://apireference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) phương pháp hỗ trợ hợp nhất dữ liệu, kiểu và công thức của tệp Excel vào một bảng tính mới có cùng định dạng. Đó là một cách hiệu quả để hợp nhất một số tệp trong khi sử dụng bộ nhớ đệm. 
{{% blocks/products/pf/feature-page-code h3="C# Mã để Hợp nhất Một số Tệp Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Hợp nhất các tệp Excel bằng cách sao chép trang tính" %}}
[Worksheet.Copy](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) có thể được sử dụng để sao chép dữ liệu và định dạng từ một trang tính nguồn sang một trang tính khác trong hoặc giữa các sổ làm việc. Phương thức này lấy đối tượng trang tính nguồn làm tham số.
{{% blocks/products/pf/feature-page-code h3="C# Mã để sao chép trang tính qua tệp Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}