---
title: .NETC#を介してExcelファイルのメタデータを管理する

description: わずか数行のC#コードで、Excelファイルのメタデータを表示、追加、編集、削除、または抽出します
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NETを介してMicrosoft<sup>＆reg; </sup>Excelファイルメタデータを管理する" h2="サーバー側の.NETAPIを使用して、組み込みおよびカスタムのExcelファイルプロパティを表示、追加、更新、削除、または抽出します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) タイトル、作成者名、ドキュメント統計などのシステム定義（組み込み）プロパティ、および名前と値のペアの形式のユーザー定義（カスタム）プロパティの管理をサポートします。がある [ワークブッククラス](https://reference.aspose.com/cells/net/aspose.cells/workbook) ファイルをロードし、 [WorksheetCollection](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) ワークシートのコレクションだけでなく、 [ワークシートクラス](https://reference.aspose.com/cells/net/aspose.cells/worksheet) 単一のワークシートを表すため。これらのクラス、BuiltInDocumentProperties、CustomDocumentPropertiesに加えて、メタデータ管理のプロセスが簡単になります。 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="組み込みプロパティの管理" %}}

システム定義のプロパティを管理するために、APIは [BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties)、およびプログラマーは、組み込みのプロパティに簡単にアクセスして、その値を更新できます。アプリケーションの要件に応じて、開発者はインデックスまたはプロパティ名を使用できます。 [DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection)。 

{{% blocks/products/pf/feature-page-code h3="C#ビルトインプロパティを管理するためのコード" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="カスタム定義プロパティの管理" %}}

ユーザー定義のプロパティを管理するために、APIは [CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties)、および開発者は、すでに追加されているプロパティに簡単にアクセスしたり、新しいプロパティを追加したりできます。カスタムプロパティを追加するには、 [メソッドを追加](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) の [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) クラスはプロパティを追加し、新しいプロパティの参照をとして返します [Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) 物体。 DocumentPropertyクラスは、ドキュメントプロパティの名前、値、およびタイプを次のように取得するために使用されます。 [DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name)、 [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value)、  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) の1つを返します [プロパティタイプ](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) 列挙値。 
 
{{% blocks/products/pf/feature-page-code h3="C#Excelファイルにメタデータを追加するためのコード" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C#Excelファイルのカスタムプロパティを削除するコード" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
