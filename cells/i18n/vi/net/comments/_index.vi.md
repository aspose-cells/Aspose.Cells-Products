---
title: Chèn nhận xét trong Excel qua .NET
url: /vi/net/comment/
description: C# mã nguồn cách chèn nhận xét vào tệp Microsoft Excel bằng cách sử dụng .NET Thư viện. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chèn nhận xét Microsoft <sup> & reg; </sup> Excel qua .NET" h2="Tạo tài liệu Excel và chèn nhận xét bằng cách sử dụng API phía máy chủ trong các ứng dụng dựa trên .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

Bạn có thể thêm nhận xét vào ô. Khi một ô có nhận xét, một chỉ báo sẽ xuất hiện ở góc của ô đó. Nhận xét xuất hiện khi bạn di con trỏ qua một ô. Những nhận xét này có thể được sử dụng để thảo luận, hướng dẫn đặc biệt hoặc đánh dấu nội dung tài liệu. [.NET Thư viện Excel](/cells/net/) hỗ trợ chèn nhận xét trong tệp Excel. Đối với điều này, API cung cấp [Nhận xét](https://apireference.aspose.com/cells/net/aspose.cells/comment) lớp cho ý kiến khối xây dựng.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chèn nhận xét vào tệp Excel" %}}

Chèn nhận xét bằng Excel API rất đơn giản. Quy trình là, Tạo [Lớp sổ làm việc](https://apireference.aspose.com/cells/net/aspose.cells/workbook) và chọn trang tính đầu tiên hoặc trang tính có liên quan bằng cách cung cấp chỉ mục của nó. Chèn dữ liệu ô bắt buộc bằng cách sử dụng [Phương thức PutValue](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Thêm nhận xét vào trang tính bằng cách sử dụng [Bình luận](https://apireference.aspose.com/cells/net/aspose.cells/commentcollection)'S [Thêm phương pháp](https://apireference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Mã để Chèn Nhận xét trong Excel" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
