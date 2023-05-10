---
title: C++ 経由で Excel ファイルのメタデータを管理
description: C++ ライブラリを使用した Excel ファイルのメタデータの表示、追加、編集、削除、抽出
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel ドキュメント メタデータを C++ 経由で管理します" h2="C++ アプリケーション内のカスタムおよび組み込みの Excel ドキュメント プロパティを表示、挿入、更新、削除、抽出します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Excel のメタデータ - Excel ファイルのメタデータを表示、挿入、削除する方法。[C++ エクセルライブラリ](/cells/ja/cpp/) faclitates は、作成者名、タイトル、ドキュメント統計などの組み込み/システム定義のプロパティをサポートすることにより、ファイルが最後に変更または保存されたときの確認などに必要な機能を、カスタム/ユーザー定義のプロパティとともに次の形式でサポートすることで簡単に実行できます。名前と値のペア。プロセスを自動化するために、ライブラリでは大規模なメタデータ Excel ファイルの作成と維持がサポートされています。[CreateIWorkbook メソッド](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)の[ファクトリークラス](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory)パス、ストリーム、および特別な FileFormatType によってワークブックを開きます。したがって、その後の処理のために適切な方法でファイルをロードしてください。以下にリストされている可能性はほとんどなく、開発者はアプリケーションの要件に応じてコードを簡単に拡張できます。
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="組み込みプロパティの読み取りと更新" %}}

組み込みプロパティを自動化するために、API は以下を提供します。[GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata)スプレッドシートのすべての組み込みドキュメント プロパティを表す DocumentProperties コレクションを返すメソッド。すべての組み込みプロパティにアクセスした後、GetTitle()、GetSubject() などの関連メソッドを使用して関連プロパティにアクセスします。プロパティを更新するには、API に SetTitle、SetSubject、SetAuthor、SetComments などのメソッドが用意されています。[組み込みドキュメントプロパティコレクション](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection)必要な機能に。

{{% blocks/products/pf/feature-page-code h3="C++ システム定義のプロパティを読み取るコード" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ 組み込みプロパティを更新するコード" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="カスタム定義プロパティの表示と追加" %}}

カスタム プロパティの処理については、API が提供します。[IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79)これは、スプレッドシートのすべてのカスタム ドキュメント プロパティ コレクションを返します。まず、このメソッドを介してカスタム プロパティにアクセスすると、開発者は関連メソッドを使用して AddIDocumentProperty、AddLinkToContentProperty などのプロパティを追加し、同様に UpdateLinkedPropertyValue、UpdateLinkedRange を使用して、それぞれコンテンツとリンク範囲にリンクするカスタム ドキュメント プロパティ値を更新できます。開発者は次の関連メソッドを使用できます。[カスタムドキュメントプロパティのコレクション](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ カスタム プロパティを表示するコード" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Excel ファイルにメタデータを追加するコード" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
