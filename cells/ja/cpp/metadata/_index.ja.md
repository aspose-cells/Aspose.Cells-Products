---
title: C++を介してExcelファイルメタデータを管理する
url: /ja/cpp/metadata/
description: C++ライブラリを使用してExcelファイルのメタデータを表示、追加、編集、削除、または抽出する
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C++を介してMicrosoft<sup>＆reg; </sup>Excelドキュメントメタデータを管理する" h2="C++アプリケーション内のカスタムおよび組み込みのExcelドキュメントプロパティを表示、挿入、更新、削除、または抽出します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
Excelのメタデータ-Excelファイルのメタデータを表示、挿入、および削除する方法。 [C++Excelライブラリ](/cells/cpp/) faclitatesは、作成者名、タイトル、ドキュメント統計などの組み込み/システム定義のプロパティをサポートすることで簡単にできます。たとえば、ファイルが最後に変更または保存されたときに、カスタム/ユーザー定義のプロパティとともに次の形式でファイルが変更または保存されるかどうかを確認する必要があります。名前と値のペア。プロセスを自動化するために、ライブラリは大きなメタデータExcelファイルの作成と保守をサポートしています。 [CreateIWorkbookメソッド](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) の [ファクトリークラス](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) パス、ストリーム、および特別なFileFormatTypeでワークブックを開きます。したがって、さらに処理するために、適切な方法でファイルをロードします。以下にリストされている可能性のいくつかと開発者は、アプリケーションの要件に応じてコードを簡単に拡張できます。 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="組み込みプロパティの読み取りと更新" %}}

組み込みのプロパティを自動化するために、APIは [GetIBuiltInDocumentProperties（）](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) スプレッドシートのすべての組み込みドキュメントプロパティを表すDocumentPropertiesコレクションを返すメソッド。すべての組み込みプロパティにアクセスした後、GetTitle（）、GetSubject（）などの関連メソッドを使用して関連プロパティにアクセスします。プロパティを更新するために、APIはSetTitle、SetSubject、SetAuthor、SetCommentsなどのメソッドを提供します。 [組み込みのドキュメントプロパティコレクション](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) 必要な機能のために。

{{% blocks/products/pf/feature-page-code h3="C++システム定義のプロパティを読み取るためのコード" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ビルトインプロパティを更新するコード" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="カスタム定義のプロパティの表示と追加" %}}

カスタムプロパティを処理するために、APIは [IWorkbookMetadata :: GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) これは、スプレッドシートのすべてのカスタムドキュメントプロパティコレクションを返します。最初にこのメソッドを介してカスタムプロパティにアクセスし、開発者は関連するメソッドを使用してAddIDocumentProperty、AddLinkToContentPropertyなどのプロパティを追加し、同様にUpdateLinkedPropertyValue、UpdateLinkedRangeを使用して、コンテンツとリンク範囲にそれぞれリンクするカスタムドキュメントプロパティ値を更新できます。開発者はから関連する方法を使用できます [カスタムドキュメントプロパティのコレクション](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection)。

{{% blocks/products/pf/feature-page-code h3="C++カスタムプロパティを表示するコード" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++Excelファイルにメタデータを追加するためのコード" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}