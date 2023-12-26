---
title: C# で Excel ワークシートをシートごとに分割
description: Visual アプリケーションで Excel ファイルを複数のファイルに分割する方法を説明する C# ソース コード C#.NET
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel ファイルの分割 via .NET" h2=".NET ベースのアプリケーション内で C# コードを使用して、単一の Excel ドキュメントを異なるファイルに分割します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET エクセルライブラリ](/cells/ja/net/) .NET ベースのアプリケーション内で Excel ドキュメントを複数のスプレッドシートに分割できます。サポートされているファイル形式には、XLS、XLSX、XLSB、XLSM、ODS が含まれます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel ドキュメントを複数のファイルに分割する" %}}
Excel ファイルをシートごとに分割する最も簡単な方法は、次の方法ですべてのシートにアクセスすることです。[ワークシート](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) 各シートを繰り返し処理し、[コピー](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)方法。最後に指定したパスに保存します。

 + Excelファイルをフルパスでロードします。[ワークブッククラス](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ 各シートを反復処理する
新しい Workbook クラス オブジェクトを作成する
 経由でシートをコピーします[コピー方法](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Save() メソッドを呼び出し、関連する SaveFormat を持つファイル名 (フルパス) を渡します。

{{% blocks/products/pf/feature-page-code h3="C# Excel ファイルを分割するコード" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel ワークシートをペインに分割する" %}}

ワークシート ウィンドウをペインに分割するには、API が提供します。[分割方式](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split)ワークシートの分割ビューを提供するワークシート クラスの。分割ビューを削除するには、API が提供します[RemoveSplit メソッド](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit)。最後に指定したパスに保存します。

{{% blocks/products/pf/feature-page-code h3="C# Excel ワークシート ウィンドウを分割するコード" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# 分割パンビューを削除するコード" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
