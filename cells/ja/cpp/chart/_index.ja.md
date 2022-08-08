---
title: Excelチャートを作成し、C++を介して画像に変換します
url: /ja/cpp/chart/
description: C++ライブラリを使用してMicrosoftExcelでチャートまたは図を描画および変換するためのC++ソースコード
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </ sup> Excelチャートを作成し、C++を介して画像に変換する" h2="Excelドキュメントのグラフを画像に変換し、C++ベースのアプリケーション内で円グラフ、ピラミッドグラフ、線グラフ、バブルグラフなどのグラフを作成します。" >}}

{{% blocks/products/pf/feature-page-summary %}}

Excelチャートを使用すると、全体像を把握し、データを簡単に分析して正しい意思決定を行うことができます。 [C++Excelライブラリ](/cells/cpp/) によってリストされたさまざまなチャートの作成をサポートします [列挙型Aspose::Cells :: Charts :: ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) エリア、バー、パイ、ピラミッド、ラインチャート、バブルチャートを含みます。さらに、チャートを画像に変換するために、APIは [ToImage mehtod](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) 必要な画像形式に変換します。

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excelチャートを作成する" %}}

Excelチャートを作成するプロセスは、のインスタンスを作成することです [IWorkbookクラス](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 希望するものを選択します [ワークシート](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43)。を使用してグラフを追加します [メソッドを追加](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) チャートタイプを含む関連パラメータを使用します。インデックスを介してチャートにアクセスし、 [追加](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) チャートのデータソース。

{{% blocks/products/pf/feature-page-code h3="C++Excelグラフを作成するためのコード" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="チャートを画像に変換する" %}}


チャートの変換プロセスは、最初に上記のコードを使用して関連するタイプのチャートを作成するか、関連するシートからアクセスします。画像の出力保存パスを定義し、変換にToImageメソッドを使用します。

 
{{% blocks/products/pf/feature-page-code h3="C++Excelチャートを変換するコード" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}