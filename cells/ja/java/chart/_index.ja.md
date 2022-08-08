---
title: Excelチャートを作成し、Javaを介して画像に変換します
url: /ja/java/chart/
description: Javaライブラリを使用してMicrosoftExcelでチャートまたは図を描画および変換するためのJavaソースコード。 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft <sup>＆reg; </sup>JavaによるExcelファイルチャートの変換と作成" h2="Excelドキュメントチャートを画像に変換し、Javaベースのアプリケーション内でサーバー側APIを使用してさまざまなチャートを作成します。" >}}


{{% blocks/products/pf/feature-page-summary %}}

チャートを介してデータを分析すると、全体像がわかり、より明確な洞察でより多くの情報に基づいた意思決定を行うことが容易になります。 [JavaExcelライブラリ](/cells/java/) によってリストされたさまざまなチャート作成の描画をサポートします [ChartType](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) 円グラフ、ピラミッド、線グラフ、バブルグラフを含みます。さらに、チャートを画像に変換します。 APIは [チャートクラス](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) 単一のExcelチャートを表すため。

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excelチャートを画像に変換する" %}}

チャートをJPG、PNG、TIFF、BMPなどを含む画像に変換するプロセスは、 [ワークブック](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) クラスでExcelファイルをロードするには、関連するクラスを選択します [ワークシート](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) チャートを含めるか、各ワークシートの各チャートを繰り返します。定義 [ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) を使用してチャートの出力画像をレンダリングします [Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)）。


{{% blocks/products/pf/feature-page-code h3="JavaExcelチャートを画像に変換するコード" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Excelファイル内にチャートを作成する" %}}

APIは、さまざまな種類のグラフに対してAxis、Chart、ChartArea、ChartDataTable、ChartFrame、ChartPoint、ChartPointCollection、ChartCollectionなどのさまざまなクラスのセットを提供するため、ExcelAPIを使用してグラフを作成するのは簡単です。プロセスは、ワークブッククラスオブジェクトを作成し、インデックスを指定して最初のワークシートまたは関連するシートを選択します。チャートのデータソースとして、を使用してワークシートセルに値を挿入します [setValue](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) 方法。 ChartCollectionコレクションを使用する [メソッドを追加](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)）チャートを追加するには、ChartType列挙でチャートのタイプを定義します。インデックスを渡して、ChartCollectionコレクションから新しいChartオブジェクトにアクセスします。使用 [SeriesCollection](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) チャートのデータソースを指定するチャートオブジェクト。

{{% blocks/products/pf/feature-page-code h3="JavaExcelグラフを作成するためのコード" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}