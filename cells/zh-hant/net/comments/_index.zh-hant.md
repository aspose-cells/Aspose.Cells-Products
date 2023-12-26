---
title: 在 Excel 中插入註 via .NET
description:  C# 原始程式碼，如何使用 .NET 函式庫將註解插入到 Microsoft Excel 檔案中。
keywords: [C# Aspose.Cells., add excel comments., insert excel comments., access excel comments., remove excel comments., delete excel comments., add comments in excel., insert comments in excel., access comments in excel., remove comments in excel., delete comments in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 註解插入 via .NET" h2="在基於 .NET 的應用程式中使用伺服器端 API 建立 Excel 文件並插入註解。" >}}
{{% blocks/products/pf/feature-page-summary %}}

您可以為儲存格新增註解。當儲存格有註解時，儲存格的角落會出現一個指示符。當您將遊標停留在儲存格上時，會出現註解。這些註釋可用於討論、特殊說明或文件內容的標記。[.NET Excel 庫](/cells/zh-hant/net/)支援在Excel檔案中插入註解。為此，API提供了一個[評論](https://reference.aspose.com/cells/net/aspose.cells/comment)評論構建塊的類別。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="在 Excel 文件中插入註釋" %}}

使用 Excel API 插入註解很簡單。流程是，創建[作業本類](https://reference.aspose.com/cells/net/aspose.cells/workbook)物件並透過提供其索引來選擇第一個工作表或相關工作表。使用插入所需的儲存格數據[價值法](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index)。使用以下命令為工作表新增註釋[評論收藏](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)的[添加方法](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# 在 Excel 中插入註解的程式碼" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
