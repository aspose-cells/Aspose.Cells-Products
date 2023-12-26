---
title: Chia bảng tính Excel khôn ngoan trong C#
description: Mã nguồn C# giải thích cách chia file Excel Microsoft thành nhiều file trong ứng dụng Visual C#.NET
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Tách file Excel via .NET" h2="Chia tài liệu Excel đơn lẻ thành các tệp khác nhau bằng mã C# trong các ứng dụng dựa trên .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Thư viện Excel](/cells/vi/net/) có khả năng chia tài liệu Excel thành nhiều bảng tính trong các ứng dụng dựa trên .NET. Các định dạng file được hỗ trợ bao gồm XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Tách tài liệu Excel thành nhiều tệp" %}}
Cách đơn giản nhất để chia nhỏ các trang tính Excel là Truy cập tất cả các trang tính thông qua[Bảng tính](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Lặp qua từng trang và gọi[Sao chép](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) phương pháp. Cuối cùng lưu nó vào một đường dẫn cụ thể.

 + Load file Excel có đường dẫn đầy đủ bằng[Lớp sổ làm việc](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Lặp lại qua từng trang
+ Tạo đối tượng lớp Workbook mới
 + Copy sheet qua[Phương pháp sao chép](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Gọi phương thức Save() và truyền vào tên file (đường dẫn đầy đủ) có SaveFormat phù hợp.

{{% blocks/products/pf/feature-page-code h3="C# Mã để chia tệp Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Chia bảng tính Excel thành các ngăn" %}}

 Để chia cửa sổ bảng tính thành các ô, API cung cấp[Phương pháp chia tách](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) của lớp trang tính, cung cấp chế độ xem được chia nhỏ của trang tính. Để loại bỏ chế độ xem bị chia tách, API cung cấp[Phương thức RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Cuối cùng lưu nó vào một đường dẫn cụ thể.

{{% blocks/products/pf/feature-page-code h3="C# Mã để chia cửa sổ bảng tính Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Mã để loại bỏ chế độ xem Pan bị chia tách" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
