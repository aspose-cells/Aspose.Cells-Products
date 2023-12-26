---
title: Excel ファイルのメタデータの管理 via Java
description: わずか数行の Java コードで Excel ファイルのメタデータを表示、追加、編集、削除、抽出できます。
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel ファイルのメタデータを管理 via Java" h2="サーバー側 Java API を使用して、カスタムおよび組み込み Excel ファイルのプロパティを表示、追加、更新、削除、または抽出します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java エクセル API](/cells/ja/java/)タイトル、作成者名、ドキュメント統計などの組み込み (システム定義) プロパティの管理と、名前と値のペアの形式でのカスタム (ユーザー定義) プロパティの管理をサポートします。がある[ワークブッククラス](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)ファイルをロードし、[ワークシートコレクション](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection)ワークシートのコレクションと同様に扱います[ワークシートクラス](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet)単一のワークシートを表すために使用されます。組み込みプロパティとカスタム プロパティにアクセスする場合、BuiltInDocumentProperties、CustomDocumentProperties を使用すると、メタデータ管理のプロセスが簡単になります。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="システム定義プロパティの管理" %}}

組み込みプロパティを管理するには、API が提供します。[組み込みドキュメントのプロパティ](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)、プログラマは簡単に組み込みプロパティにアクセスし、その値を更新できます。アプリケーションの要件に応じて、開発者は、[ドキュメントプロパティコレクション](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java システム定義のプロパティを管理するコード" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="カスタム定義のメタデータの追加と削除" %}}

カスタム プロパティの処理については、API が提供します。[カスタムドキュメントプロパティ](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties)を使用すると、開発者は既存のプロパティに簡単にアクセスできるだけでなく、新しいプロパティを追加することもできます。[メソッドの追加](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ） の[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection)クラスはプロパティを追加し、新しいプロパティの参照を[プロパティ.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty)物体。 DocumentProperty クラスは、ドキュメント プロパティの名前、値、タイプを取得するために使用されます。[ドキュメントプロパティ名](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type)次のいずれかを返します[プロパティタイプ](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType)列挙値。
 
{{% blocks/products/pf/feature-page-code h3="Java Excel ファイルにメタデータを追加するコード" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Excel ファイルのカスタム プロパティを削除するコード" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
