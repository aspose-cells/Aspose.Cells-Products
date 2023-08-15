---
title: 通過 C++ 創建 Excel 圖表並轉換為圖像
description: C++ 使用 C++ 庫在 Microsoft Excel 中繪製和轉換圖表或圖表的源代碼
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="創建 Microsoft<sup>&reg;</sup> Excel 圖表並通過 C++ 轉換為圖像" h2="將 Excel 文檔圖表轉換為圖像，並在基於 C++ 的應用程序中創建圖表，包括餅圖、金字塔圖、折線圖和氣泡圖。" >}}

{{% blocks/products/pf/feature-page-summary %}}

使用 Excel 圖表，人們可以了解更大的情況並輕鬆分析數據以做出正確的決策。[C++ Excel 庫](/cells/zh-hant/cpp/)支持創建列出的不同圖表[枚舉Aspose::Cells::圖表::圖表類型
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70)包括面積圖、條形圖、餅圖、金字塔圖、折線圖和氣泡圖。此外，為了將圖表轉換為圖像，API 提供了[圖像轉換方法](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb)轉換為所需的圖像格式。

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="創建 Excel 圖表" %}}

創建Excel圖表的過程是，創建一個實例[I作業簿類](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)並選擇所需的[工作表](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43)。使用添加圖表[添加方法](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068)以及相關參數，包括圖表類型。通過索引訪問圖表[添加](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f)圖表的數據源。

{{% blocks/products/pf/feature-page-code h3="C++ 創建 Excel 圖表的代碼" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="將圖表轉換為圖像" %}}


對於轉換圖表的過程是，首先使用上面的代碼創建相關類型的圖表或從相關工作表訪問它。定義圖像的輸出保存路徑，並使用ToImage方法進行轉換。

 
{{% blocks/products/pf/feature-page-code h3="C++ 轉換Excel圖表的代碼" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
