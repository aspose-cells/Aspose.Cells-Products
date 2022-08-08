---
title: 通過 .NET 在 Excel 中插入註釋
url: /zh-hant/net/comment/
description: C# 源代碼，說明如何使用 .NET 庫將註釋插入 Microsoft Excel 文件。 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通過 .NET 插入 Excel 評論" h2="在基於 .NET 的應用程序中使用服務器端 API 創建 Excel 文檔並插入註釋。" >}}
{{% blocks/products/pf/feature-page-summary %}}

您可以向單元格添加註釋。當單元格有註釋時，單元格的角落會出現一個指示符。將光標懸停在單元格上時會顯示註釋。這些註釋可用於討論、特殊說明或文檔內容的標記。 [.NET Excel 庫](/cells/net/) 支持在 Excel 文件中插入註釋。為此，API 提供了一個 [評論](https://reference.aspose.com/cells/net/aspose.cells/comment) 評論構建塊的類。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="在 Excel 文件中插入註釋" %}}

使用 Excel API 插入註釋很簡單。過程是，創造 [工作簿類](https://reference.aspose.com/cells/net/aspose.cells/workbook) 對象並通過提供其索引來選擇第一個工作表或相關工作表。使用插入所需的單元格數據 [PutValue 方法](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index).使用向工作表添加註釋 [評論集合](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)的 [添加方法](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# 在 Excel 中插入註釋的代碼" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
