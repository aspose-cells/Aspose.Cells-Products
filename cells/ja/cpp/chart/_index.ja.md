---
title: Excel グラフを作成し、C++ 経由で画像に変換
description: C++ ライブラリを使用して Excel でチャートまたは図を描画および変換するための C++ ソース コード
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel グラフを作成し、C++ 経由で画像に変換します" h2="Excel ドキュメント グラフを画像に変換し、C++ ベースのアプリケーション内で円グラフ、ピラミッド グラフ、折れ線グラフ、バブル チャートなどのグラフを作成します。" >}}

{{% blocks/products/pf/feature-page-summary %}}

 Excel グラフを使用すると、全体像を把握し、正しい意思決定を行うためにデータを簡単に分析できます。[C++ エクセルライブラリ](/cells/ja/cpp/)によってリストされたさまざまなグラフの作成をサポートします。[列挙型 Aspose::Cells::チャート::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70)面グラフ、棒グラフ、円グラフ、ピラミッド グラフ、折れ線グラフ、バブル チャートが含まれます。さらに、チャートの画像への変換については、API で提供されます。[画像メソッドへ](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb)必要な画像形式に変換します。

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel グラフの作成" %}}

Excel グラフを作成するプロセスは、[IWorkbook クラス](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)を選択し、希望の[ワークシート](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43)。次を使用してグラフを追加します[メソッドの追加](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068)グラフの種類などの関連パラメータを使用します。インデックス経由でチャートにアクセスし、[追加](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f)チャートのデータソース。

{{% blocks/products/pf/feature-page-code h3="C++ Excel グラフを作成するコード" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="チャートを画像に変換" %}}


チャートを変換するプロセスは、まず上記のコードを使用して関連するタイプのチャートを作成するか、関連するシートからアクセスします。画像の出力保存パスを定義し、変換には ToImage メソッドを使用します。

 
{{% blocks/products/pf/feature-page-code h3="C++ Excel グラフを変換するコード" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
