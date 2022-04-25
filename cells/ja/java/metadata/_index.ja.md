---
title: Javaを介してExcelファイルメタデータを管理する
url: /ja/java/metadata/
description: わずか数行のJavaコードで、Excelファイルのメタデータを表示、追加、編集、削除、または抽出します
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してMicrosoft<sup>＆reg; </sup>Excelファイルメタデータを管理する" h2="サーバー側のJavaAPIを使用して、カスタムおよび組み込みのExcelファイルプロパティを表示、追加、更新、削除、または抽出します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) タイトル、作成者名、ドキュメント統計などの組み込み（システム定義）プロパティ、および名前と値のペアの形式のカスタム（ユーザー定義）プロパティの管理をサポートします。がある [ワークブッククラス](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) ファイルをロードし、 [WorksheetCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) ワークシートのコレクションだけでなく、 [ワークシートクラス](https://apireference.aspose.com/cells/java/com.aspose.cells/Worksheet) 単一のワークシートを表すため。組み込みプロパティとカスタムプロパティにアクセスするために、BuiltInDocumentProperties、CustomDocumentPropertiesを使用すると、メタデータ管理のプロセスが簡単になります。 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="システム定義のプロパティの管理" %}}

組み込みプロパティを管理するために、APIは [BuiltInDocumentProperties](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)、およびプログラマーは、組み込みのプロパティに簡単にアクセスして、その値を更新できます。アプリケーションの要件に応じて、開発者はインデックスまたはプロパティ名を使用できます。 [DocumentPropertyCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection)。 

{{% blocks/products/pf/feature-page-code h3="Javaシステム定義のプロパティを管理するためのコード" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="カスタム定義のメタデータの追加と削除" %}}

カスタムプロパティを処理するために、APIは [CustomDocumentProperties](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties)、および開発者は、既存のプロパティに簡単にアクセスできるだけでなく、を使用して新しいプロパティを追加できます [メソッドを追加](https://apireference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)） の [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) クラスはプロパティを追加し、新しいプロパティの参照をとして返します [Properties.DocumentProperty](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) 物体。 DocumentPropertyクラスは、ドキュメントプロパティの名前、値、およびタイプを次のように取得するために使用されます。 [DocumentProperty.Name](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name)、 [DocumentProperty.Value](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value)、  [DocumentProperty.Type](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) の1つを返します [プロパティタイプ](https://apireference.aspose.com/cells/java/com.aspose.cells/PropertyType) 列挙値。 
 
{{% blocks/products/pf/feature-page-code h3="JavaExcelファイルにメタデータを追加するためのコード" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="JavaExcelファイルのカスタムプロパティを削除するコード" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
