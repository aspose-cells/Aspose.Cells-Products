---
title: ExcelワークシートシートをC#で分割する
url: /ja/net/splitter/
description: VisualC#.NETアプリケーションでMicrosoftExcelファイルを複数のファイルに分割する方法を説明するC#ソースコード
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>.NETによるExcelファイルの分割" h2=".NETベースのアプリケーション内でC#コードを使用して、単一のExcelドキュメントを異なるファイルに分割します" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NETExcelライブラリ](/cells/net/) .NETベースのアプリケーション内でExcelドキュメントを複数のスプレッドシートに分割することができます。サポートされているファイル形式には、XLS、XLSX、XLSB、XLSM、ODSが含まれます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excelドキュメントを複数のファイルに分割" %}}
Excelファイルをシートごとに分割する最も簡単な方法は、次の方法ですべてのシートにアクセスすることです。 [ワークシート](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets)、各シートを繰り返し処理し、 [コピー](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) 方法。最後にそれを指定されたパスに保存します。 

+を使用してフルパスでExcelファイルをロードします [ワークブッククラス](https://apireference.aspose.com/cells/net/aspose.cells/workbook)。
+各シートを繰り返します
+新しいWorkbookクラスオブジェクトを作成します
+シートをコピーする [コピー方法](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Save（）メソッドを呼び出し、関連するSaveFormatを持つファイル名（フルパス）を渡します。

{{% blocks/products/pf/feature-page-code h3="C#Excelファイルを分割するためのコード" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excelワークシートをペインに分割" %}}

ワークシートウィンドウをペインに分割するために、APIは [分割法](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) ワークシートクラスの、ワークシートの分割ビューを提供します。分割されたビューを削除するには、APIが提供します [RemoveSplitメソッド](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit)。最後に、指定したパスに保存します。 

{{% blocks/products/pf/feature-page-code h3="C#Excelワークシートウィンドウを分割するコード" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C#分割パンビューを削除するコード" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
