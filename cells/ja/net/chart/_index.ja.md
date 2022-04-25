---
title: Excelチャートの作成と.NETによる画像への変換
url: /ja/net/chart/
description: .NETライブラリを使用してMicrosoftExcelでチャートまたは図を描画および変換するためのC#ソースコード。 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>.NETによるExcelファイルチャートの作成と変換" h2="Excelドキュメントチャートを作成し、.NETベースのアプリケーション内でサーバー側APIを使用して画像に変換します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
チャートの描画は、分析を容易にするためにデータをグラフィカルに表示するための技術です。 [.NETExcelライブラリ](/cells/net/) Excelファイル内のチャートの描画をサポートします。 APIは、にリストされているさまざまなグラフの作成をサポートしています [ChartType列挙](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) 円グラフ、ピラミッド、線グラフ、バブルグラフを含みます。さらに、チャートを画像に変換します。 APIは [チャートクラス](https://apireference.aspose.com/cells/net/aspose.cells.charts) チャートビルディングブロック用。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excelファイル内にチャートを作成する" %}}

ExcelAPIを使用してチャートを作成するのは簡単です。プロセスは、作成 [ワークブッククラス](https://apireference.aspose.com/cells/net/aspose.cells/workbook) オブジェクトを作成し、インデックスを指定して最初のワークシートまたは関連するシートを選択します。を使用して必要なセルデータを挿入します [PutValueメソッド](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index)。 Chartsコレクションを使用してチャートをワークシートに追加します [メソッドを追加](https://apireference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add)。指定します [ChartType](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) ChartType列挙から。
{{% blocks/products/pf/feature-page-code h3="C#Excelグラフを作成するためのコード" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Excelチャートを画像に変換する" %}}

グラフを画像に変換するプロセスは、Workbookクラスを使用してExcelファイルを読み込み、グラフを含む関連するワークシートを選択して、 [ToImageメソッド](https://apireference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) 変換用。

{{% blocks/products/pf/feature-page-code h3="C#Excelチャートを画像に変換するコード" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}