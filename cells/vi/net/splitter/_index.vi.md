---
title: Tách trang tính Bảng tính Excel khôn ngoan trong C#

description: C# mã nguồn giải thích cách chia tệp Microsoft Excel thành nhiều tệp trong ứng dụng Trực quan C# .NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup> & reg; </sup> Tách tệp Excel qua .NET" h2="Chia một tài liệu Excel thành các tệp khác nhau bằng cách sử dụng mã C# trong các ứng dụng dựa trên .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Thư viện Excel](/cells/net/) có khả năng chia tài liệu Excel thành nhiều bảng tính trong các ứng dụng dựa trên .NET. Các định dạng tệp được hỗ trợ bao gồm XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chia tài liệu Excel thành nhiều tệp" %}}
Cách đơn giản nhất để chia trang tính tệp Excel một cách khôn ngoan là, Truy cập tất cả các trang tính qua [Trang tính](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Lặp lại từng trang tính và gọi [Sao chép](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) phương pháp. Cuối cùng lưu nó vào một đường dẫn được chỉ định. 

+ Tải tệp Excel với đường dẫn đầy đủ bằng cách sử dụng [Lớp sổ làm việc](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Lặp đi lặp lại từng trang tính
+ Tạo một đối tượng lớp Workbook mới
+ Sao chép trang tính qua [Sao chép phương pháp](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Gọi phương thức Save () và chuyển tên tệp (đường dẫn đầy đủ) có SaveFormat phù hợp.

{{% blocks/products/pf/feature-page-code h3="C# Mã để tách các tệp Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Chia bảng tính Excel thành các ngăn" %}}

Để tách cửa sổ trang tính thành các ngăn, API cung cấp [Phương pháp tách](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) của lớp trang tính, cung cấp chế độ xem được chia nhỏ của trang tính. Để xóa chế độ xem bị chia nhỏ API cung cấp [Phương thức RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Cuối cùng lưu nó vào một đường dẫn được chỉ định. 

{{% blocks/products/pf/feature-page-code h3="C# Mã để Tách Cửa sổ Trang tính Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Mã để Xóa Chế độ xem Pan bị Chia tách" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
