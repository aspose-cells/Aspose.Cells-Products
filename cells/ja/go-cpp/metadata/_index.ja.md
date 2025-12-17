---
title: Go で Excel ファイルのメタデータを管理する（C++ 経由）
description: C++ ライブラリ経由で Go を使用して Excel ファイルのメタデータを表示、追加、編集、削除、または抽出します
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C++ 経由で Go 経由で Microsoft<sup>&reg;</sup> Excel ドキュメントのメタデータを管理します" h2="C++ アプリケーション内でカスタムおよび組み込みの Excel ドキュメント プロパティを表示、挿入、更新、削除、または抽出します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Excel のメタデータ - Excel ファイルのメタデータを表示、挿入、削除する方法。[C++ Excelライブラリ経由でアクセス](/cells/ja/go-cpp/)作成者名、タイトル、ドキュメント統計情報など、ファイルの最終変更日時や保存日時の確認など、必要に応じて必要となる組み込み/システム定義プロパティに加え、名前/値のペア形式のカスタム/ユーザー定義プロパティをサポートすることで、このプロセスを容易にします。このプロセスを自動化するために、ライブラリは大規模なメタデータExcelファイルの作成と管理をサポートしています。[ワークブック](https://reference.aspose.com/cells/go-cpp/workbook/)クラスは、パス、ストリーム、および特殊なFileFormatTypeによってワークブックを開きます。適切なメソッドを使用してファイルを読み込み、その後の処理に使用します。以下に挙げたいくつかの方法を利用することで、開発者はアプリケーションの要件に応じてコードを簡単に拡張できます。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="組み込みプロパティの読み取りと更新" %}}

組み込みプロパティを自動化するために、APIは[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)スプレッドシートのすべての組み込みドキュメントプロパティを表すDocumentPropertiesコレクションを返すメソッドです。すべての組み込みプロパティにアクセスした後、GetTitle()、GetSubject()などの関連メソッドを使用して関連するプロパティにアクセスします。プロパティを更新するために、APIはSetTitle、SetSubject、SetAuthor、SetCommentsなどのメソッドを提供しています。[組み込みドキュメントプロパティコレクション](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)必要な機能のために。

{{% blocks/products/pf/feature-page-code h3="C++コードを経由してシステム定義のプロパティを読み取る" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++コードを経由して組み込みプロパティを更新する" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="カスタム定義プロパティの表示と追加" %}}

カスタムプロパティの処理については、APIが提供しています。[ワークブック::GetCustomDocumentProperties](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)スプレッドシートのすべてのカスタムドキュメントプロパティコレクションを返します。まずこのメソッドでカスタムプロパティにアクセスし、開発者はAddIDocumentProperty、AddLinkToContentPropertyなどの関連メソッドを使用してプロパティを追加できます。同様にUpdateLinkedPropertyValue、UpdateLinkedRangeを使用して、それぞれコンテンツとリンク範囲にリンクするカスタムドキュメントプロパティの値を更新できます。開発者は関連メソッドを以下から使用できます。[カスタムドキュメントプロパティのコレクション](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="C++コードでカスタムプロパティを表示" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++コードを使用してExcelファイルにメタデータを追加する" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}