---
title: 通過 C++ 創建 Excel 圖表並轉換為圖像
url: /zh-hant/cpp/chart/
description: C++ 使用 C++ 庫在 Microsoft Excel 中繪製和轉換圖表或圖表的源代碼
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="創建 Microsoft<sup>&reg;</sup> Excel 圖表並通過 C++ 轉換為圖像" h2="將 Excel 文檔圖表轉換為圖像，並在基於 C++ 的應用程序中創建圖表，包括餅圖、金字塔圖、折線圖和氣泡圖。" >}}

{{% blocks/products/pf/feature-page-summary %}}

使用 Excel 圖表，您可以了解全局並輕鬆分析數據以做出正確決策。 [C++ Excel 庫](/cells/cpp/) 支持創建不同的圖表 [枚舉 Aspose::Cells::Charts::ChartType
](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) 包括面積圖、條形圖、餅圖、金字塔圖、折線圖和氣泡圖。此外，為了將圖表轉換為圖像，API 提供了一個 [圖像方法](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) 成所需的圖像格式。

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="創建 Excel 圖表" %}}

創建Excel圖表的過程是，創建一個實例 [IWorkbook 類](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 並選擇所需的 [工作表](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43).使用添加圖表 [添加方法](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) 帶有相關參數，包括圖表類型。通過索引訪問圖表和 [添加](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) 圖表的數據源。

{{% blocks/products/pf/feature-page-code h3="C++ 創建 Excel 圖表的代碼" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="將圖表轉換為圖像" %}}


對於轉換圖表的過程，首先使用上述代碼創建相關類型的圖表或從相關工作表訪問它。定義圖片的輸出保存路徑，使用ToImage方法進行轉換。

 
{{% blocks/products/pf/feature-page-code h3="C++ 轉換 Excel 圖表的代碼" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}