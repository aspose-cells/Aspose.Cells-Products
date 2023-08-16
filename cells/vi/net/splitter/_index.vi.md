---
title: Chia bảng Excel Worksheet một cách khôn ngoan trong C#
description: C# mã nguồn giải thích cách chia Microsoft tệp Excel thành nhiều tệp trong ứng dụng Visual C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Tách tệp Excel via .NET" h2="Tách một tài liệu Excel thành các tệp khác nhau bằng mã C# trong các ứng dụng dựa trên .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Thư Viện Excel](/cells/vi/net/) có khả năng chia tài liệu Excel thành nhiều bảng tính trong các ứng dụng dựa trên .NET. Các định dạng tệp được hỗ trợ bao gồm XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Tách tài liệu Excel thành nhiều tệp" %}}
 Cách đơn giản nhất để chia trang tính tệp Excel một cách khôn ngoan là, Truy cập tất cả các trang tính qua[bảng tính](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Lặp lại qua từng trang tính và gọi[Sao chép](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) phương pháp. Cuối cùng lưu nó vào một đường dẫn cụ thể.

 + Tải file Excel đầy đủ đường dẫn bằng[lớp sách bài tập](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Lặp qua từng sheet
+ Tạo đối tượng lớp Workbook mới
 + Sao chép trang tính qua[phương pháp sao chép](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Gọi phương thức Save() và truyền tên tệp (đường dẫn đầy đủ) có SaveFormat tương ứng.

{{% blocks/products/pf/feature-page-code h3="C# Code Tách File Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Chia trang tính Excel thành các ô" %}}

 Để chia cửa sổ trang tính thành các ngăn, API cung cấp[phương pháp chia](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split)của lớp trang tính, cung cấp chế độ xem được chia nhỏ của trang tính. Để xóa chế độ xem bị chia API cung cấp[phương thức RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Cuối cùng lưu nó vào một đường dẫn xác định.

{{% blocks/products/pf/feature-page-code h3="C# Mã để chia cửa sổ bảng tính Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Mã để loại bỏ chế độ xem Pan bị tách" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
