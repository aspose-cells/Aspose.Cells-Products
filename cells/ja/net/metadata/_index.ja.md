---
title: Excel ファイルのメタデータの管理 via .NET C#
description: わずか数行の C# コードで Excel ファイルのメタデータを表示、追加、編集、削除、抽出できます。
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel ファイルのメタデータを管理 via .NET" h2="サーバー側 .NET API を使用して、組み込みおよびカスタム Excel ファイルのプロパティを表示、追加、更新、削除、抽出します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET エクセル API](/cells/ja/net/)タイトル、作成者名、ドキュメント統計などのシステム定義 (組み込み) プロパティと、名前と値のペアの形式でのユーザー定義 (カスタム) プロパティの管理をサポートします。がある[ワークブッククラス](https://reference.aspose.com/cells/net/aspose.cells/workbook)ファイルをロードし、[ワークシートコレクション](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection)ワークシートのコレクションと同様に扱います[ワークシートクラス](https://reference.aspose.com/cells/net/aspose.cells/worksheet)単一のワークシートを表すために使用されます。これらのクラスと併せて、BuiltInDocumentProperties、CustomDocumentProperties を使用すると、メタデータ管理のプロセスが簡素化されます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="組み込みプロパティの管理" %}}

システム定義のプロパティを管理するには、API が提供します。[組み込みドキュメントのプロパティ](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties)、プログラマは簡単に組み込みプロパティにアクセスし、その値を更新できます。アプリケーションの要件に応じて、開発者は、[ドキュメントプロパティコレクション](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# 組み込みプロパティを管理するコード" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="カスタム定義プロパティの管理" %}}

ユーザー定義プロパティを管理するには、API が提供します。[カスタムドキュメントプロパティ](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) 、開発者は、新しいプロパティを追加するだけでなく、すでに追加されているプロパティに簡単にアクセスできます。カスタム プロパティを追加するには、[メソッドの追加](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index)の[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection)クラスはプロパティを追加し、新しいプロパティの参照を[プロパティ.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty)物体。 DocumentProperty クラスは、ドキュメント プロパティの名前、値、タイプを取得するために使用されます。[ドキュメントプロパティ名](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type)次のいずれかを返します[プロパティタイプ](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype)列挙値。
 
{{% blocks/products/pf/feature-page-code h3="C# Excel ファイルにメタデータを追加するコード" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Excel ファイルのカスタム プロパティを削除するコード" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
