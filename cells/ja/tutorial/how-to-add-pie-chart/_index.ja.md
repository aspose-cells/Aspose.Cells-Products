---
title: Aspose.Cells 経由で円グラフを追加する方法
weight: 7700
limit:
description: 円グラフを追加する方法を学びます。
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /ja/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells で円グラフを追加する方法をご覧ください。" >}}

<p>
このチュートリアルでは、Excel ファイルに円グラフを追加します。
</p>

<p>
まず、次を使用して新しいワークブックを作成します。<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells 図書館</a>そして円グラフを追加します。
</p>

<br />
{{< app/cells/tutorial >}}
//例概要: 円グラフを追加する方法については、次のコードを確認してください。
//ExStepsummary:0: 次のコードは、円グラフを追加し、系列データ範囲を設定し、カテゴリ データ範囲を設定する方法を示しています。
//ExStepImage:0:step-1.png
//ExStepsummary:1: 次のコードは、凡例をオフにする方法を示しています。
//ExStepImage:1:step-2.png
//ExStepsummary:2: 次のコードは、データ ラベルにアクセスし、カテゴリ名をオンにし、パーセント形式をオンにして、位置を設定する方法を示しています。
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
Aspose.Cellsを使用します。
Aspose.Cellsを使用しています。図面;

ワークブック workbook = new Workbook();
ワークシートsheet = workbook.Worksheets[0];
Sheet.Name = "チャートシート";
Cells セル =sheet.Cells;
セル["A1"].Value = "フルーツ";
セル["A2"].Value = "リンゴ";
セル["A3"].Value = "オレンジ";
セル["A4"].Value = "ブルーベリー";
セル["A5"].Value = "キウイ";

セル["B1"].Value = "価格";
セル["B2"].Value = 10;
セル["B3"].Value = 5;
セル["B4"].Value = 20;
セル["B5"].Value = 8;

シート.PageSetup.PrintGridlines = true;
Sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection チャート =sheet.Charts;

//円グラフを追加し、シリーズのデータ範囲を設定し、カテゴリのデータ範囲を設定します
int インデックス =sheet.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
チャート chart =sheet.Charts[index];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//例ステップ:1-
//凡例をオフにする
chart.ShowLegend = false;

//例ステップ:2-
//データラベルにアクセスし、カテゴリ名をオンにし、パーセント形式をオンにして、位置を設定します
データラベル dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.ShowPercentage = true;
dataLabels.Position = LabelPositionType.OutsideEnd;

//ExStep:0-

//拡張終了
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Aspose.Cellsの設置</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells 編集者</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}