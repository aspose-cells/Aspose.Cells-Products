---
title: Chèn comment trong Excel via .NET
description:  C# mã nguồn cách chèn nhận xét vào Microsoft tệp Excel bằng Thư viện .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Chèn nhận xét Excel via .NET" h2="Tạo tài liệu Excel và chèn nhận xét bằng API phía máy chủ trong các ứng dụng dựa trên .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

 Bạn có thể thêm nhận xét vào các ô. Khi một ô có nhận xét, một chỉ báo sẽ xuất hiện ở góc của ô. Nhận xét xuất hiện khi bạn di chuột qua một ô. Những nhận xét này có thể được sử dụng để thảo luận, hướng dẫn đặc biệt hoặc đánh dấu nội dung tài liệu.[.NET Thư Viện Excel](/cells/vi/net/)hỗ trợ chèn nhận xét vào tệp Excel. Đối với điều này, API cung cấp[Bình luận](https://reference.aspose.com/cells/net/aspose.cells/comment) lớp cho ý kiến xây dựng khối.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chèn comment vào File Excel" %}}

 Chèn nhận xét bằng Excel API rất đơn giản. Quy trình là, Tạo[lớp sách bài tập](https://reference.aspose.com/cells/net/aspose.cells/workbook) đối tượng và chọn trang tính đầu tiên hoặc trang tính có liên quan bằng cách cung cấp chỉ mục của nó. Chèn dữ liệu ô cần thiết bằng cách sử dụng[Phương thức PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Thêm nhận xét vào trang tính bằng cách sử dụng[Bình luậnBộ sưu tập](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 'S[thêm phương pháp](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Mã để Chèn Nhận xét trong Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
