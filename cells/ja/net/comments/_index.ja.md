---
title: Excel にコメントを挿入 via .NET
description:  C# ライブラリを使用して Microsoft Excel ファイルにコメントを挿入する方法を示すソース コード。
keywords: [C# Aspose.Cells., add excel comments., insert excel comments., access excel comments., remove excel comments., delete excel comments., add comments in excel., insert comments in excel., access comments in excel., remove comments in excel., delete comments in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel コメントの挿入 via .NET" h2=".NET ベースのアプリケーションでサーバー側 API を使用して Excel ドキュメントを作成し、コメントを挿入します。" >}}
{{% blocks/products/pf/feature-page-summary %}}

セルにコメントを追加できます。セルにコメントがある場合、セルの隅にインジケーターが表示されます。セルの上にカーソルを置くとコメントが表示されます。これらのコメントは、ディスカッション、特別な指示、または文書コンテンツのマークアップに使用できます。[.NET エクセルライブラリ](/cells/ja/net/)Excel ファイルへのコメントの挿入をサポートしています。このために、API は[コメント](https://reference.aspose.com/cells/net/aspose.cells/comment)コメントビルディングブロックのクラス。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel ファイルにコメントを挿入する" %}}

Excel API を使用してコメントを挿入するのは簡単です。プロセスは、作成することです[ワークブッククラス](https://reference.aspose.com/cells/net/aspose.cells/workbook)オブジェクトを選択し、インデックスを指定して最初のワークシートまたは関連シートを選択します。次を使用して必要なセル データを挿入します。[PutValue メソッド](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index)。を使用してワークシートにコメントを追加します[コメントコレクション](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)さんの[メソッドの追加](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Excelにコメントを挿入するコード" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
