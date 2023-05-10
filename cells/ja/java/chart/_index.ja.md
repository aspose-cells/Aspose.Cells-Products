---
title: Excel グラフの作成と画像への変換 via Java
description:  Java ライブラリを使用して、Microsoft Excel でチャートまたは図を描画および変換するための Java ソース コード。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel ファイル グラフの変換と作成 via Java" h2="Excel ドキュメントのグラフを画像に変換し、Java ベースのアプリケーション内のサーバー側 API を使用してさまざまなグラフを作成します。" >}}


{{% blocks/products/pf/feature-page-summary %}}

グラフを使用してデータを分析すると、全体像が表示され、より明確な洞察を得て、より多くの情報に基づいた意思決定を行うことが簡単になります。[Java エクセルライブラリ](/cells/ja/java/)にリストされているさまざまなチャート作成の描画をサポートします。[グラフの種類](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType)円グラフ、ピラミッド グラフ、折れ線グラフ、バブル チャートが含まれます。さらに、チャートを画像に変換することもできます。 API は、[チャートクラス](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)単一の Excel グラフを表すために使用されます。

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel グラフを画像に変換" %}}

チャートを JPG、PNG、TIFF、BMP などを含む画像に変換するプロセスは、[ワークブック](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) Excel ファイルをロードするクラスを選択し、関連する[ワークシート](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet)グラフを含むか、各ワークシート内の各グラフを反復処理します。定義[画像または印刷オプション](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions)を使用してチャートの出力イメージをレンダリングします[チャートから画像へ](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Excel グラフを画像に変換するコード" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Excelファイル内にグラフを作成" %}}

Excel API を使用してグラフを作成するのは簡単です。API は、さまざまな種類のグラフに対応する Axis、Chart、ChartArea、ChartDataTable、ChartFrame、ChartPoint、ChartPointCollection、ChartCollection などのさまざまなクラスのセットを提供します。プロセスは、Workbook クラス オブジェクトを作成し、インデックスを指定して最初のワークシートまたは関連シートを選択します。グラフのデータ ソースの場合、次を使用してワークシートのセルに値を挿入します。[セット値](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)方法。 ChartCollection コレクションの使用[メソッドの追加](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) チャートを追加するには、ChartType 列挙でチャートのタイプを定義します。 ChartCollection コレクションから新しい Chart オブジェクトにアクセスするには、そのインデックスを渡します。使用[シリーズコレクション](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection)チャート オブジェクトを使用してチャートのデータ ソースを指定します。

{{% blocks/products/pf/feature-page-code h3="Java Excel グラフを作成するコード" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
