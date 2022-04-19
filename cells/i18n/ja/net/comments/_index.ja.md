---
title: .NETを介してExcelにコメントを挿入する
url: /ja/net/comment/
description: .NETライブラリを使用してMicrosoftExcelファイルにコメントを挿入する方法を示すC#ソースコード。 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>.NETを介したExcelコメントの挿入" h2=".NETベースのアプリケーションでサーバー側APIを使用して、Excelドキュメントを作成し、コメントを挿入します。" >}}
{{% blocks/products/pf/feature-page-summary %}}

セルにコメントを追加できます。セルにコメントがある場合、セルの隅にインジケーターが表示されます。セルにカーソルを合わせるとコメントが表示されます。これらのコメントは、ディスカッション、特別な指示、またはドキュメントコンテンツのマークアップに使用できます。 [.NETExcelライブラリ](/cells/net/) Excelファイルへのコメントの挿入をサポートします。このために、APIは [コメント](https://apireference.aspose.com/cells/net/aspose.cells/comment) コメントビルディングブロックのクラス。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excelファイルにコメントを挿入する" %}}

ExcelAPIを使用してコメントを挿入するのは簡単です。プロセスは、作成 [ワークブッククラス](https://apireference.aspose.com/cells/net/aspose.cells/workbook) オブジェクトを作成し、インデックスを指定して最初のワークシートまたは関連するシートを選択します。を使用して必要なセルデータを挿入します [PutValueメソッド](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index)。を使用してワークシートにコメントを追加します [CommentCollection](https://apireference.aspose.com/cells/net/aspose.cells/commentcollection)の [メソッドを追加](https://apireference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1)。

{{% blocks/products/pf/feature-page-code h3="C#Excelにコメントを挿入するコード" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
