---
title: Excel グラフの作成と画像への変換 via .NET
description:  C# ライブラリを使用して、Microsoft Excel でチャートまたは図を描画および変換するための C# ソース コード。
keywords: [C# Aspose.Cells., c# Convert chart to image., c# Save chart to image., c# chart to image., create charts in c#., insert charts in c#., manage charts in c#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel ファイル グラフの作成と変換 via .NET" h2="Excel ドキュメント グラフを作成し、.NET ベースのアプリケーション内のサーバー側 API を使用して画像に変換します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
チャートの描画は、分析を容易にするためにデータをグラフィカルに表示する技術です。[.NET エクセルライブラリ](/cells/ja/net/) Excel ファイル内でのグラフの描画をサポートします。 API は、以下にリストされているさまざまなグラフの作成をサポートしています。[ChartType 列挙体](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)円グラフ、ピラミッド グラフ、折れ線グラフ、バブル チャートが含まれます。さらに、チャートを画像に変換することもできます。 API は、[チャートクラス](https://reference.aspose.com/cells/net/aspose.cells.charts)グラフの構成要素用。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excelファイル内にグラフを作成" %}}

 Excel API を使用したグラフの作成は簡単です。プロセスは、作成することです[ワークブッククラス](https://reference.aspose.com/cells/net/aspose.cells/workbook)オブジェクトを選択し、インデックスを指定して最初のワークシートまたは関連シートを選択します。次を使用して必要なセル データを挿入します。[PutValue メソッド](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index)。 Charts コレクションのを使用してワークシートにグラフを追加します。[メソッドの追加](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) 。を指定します[グラフの種類](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)ChartType 列挙から。
{{% blocks/products/pf/feature-page-code h3="C# Excel グラフを作成するコード" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Excel グラフを画像に変換" %}}

グラフを画像に変換するプロセスは、Workbook クラスを使用して Excel ファイルをロードし、グラフを含む関連ワークシートを選択して、[ToImage メソッド](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7)変換のため。

{{% blocks/products/pf/feature-page-code h3="C# Excel グラフを画像に変換するコード" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
