---
title: 通過 .NET 創建 Excel 圖表並將其轉換為圖像
url: /zh-hant/net/chart/
description: C# 使用 .NET 庫在 Microsoft Excel 中繪製和轉換圖表或圖表的源代碼。 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通過 .NET 創建和轉換 Excel 文件圖表" h2="在基於 .NET 的應用程序中使用服務器端 API 創建 Excel 文檔圖表並轉換為圖像。" >}}
{{% blocks/products/pf/feature-page-summary %}}
繪製圖表是一種以圖形方式顯示數據以便於分析的藝術。 [.NET Excel 庫](/cells/net/) 支持在 Excel 文件中繪製圖表。 API 支持中列出的不同圖表創建 [ChartType 枚舉](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) 包括餅圖、金字塔圖、折線圖和氣泡圖。此外，它還將圖表轉換為圖像。 API 提供了一個 [圖表類](https://apireference.aspose.com/cells/net/aspose.cells.charts) 用於圖表構建塊。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="在 Excel 文件中創建圖表" %}}

使用 Excel API 創建圖表很簡單。過程是，創造 [工作簿類](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 對象並通過提供其索引來選擇第一個工作表或相關工作表。使用插入所需的單元格數據 [PutValue 方法](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index).使用 Charts 集合將圖表添加到工作表 [添加方法](https://apireference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add).指定 [圖表類型](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) 來自 ChartType 枚舉。
{{% blocks/products/pf/feature-page-code h3="C# 創建 Excel 圖表的代碼" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="將 Excel 圖表轉換為圖像" %}}

將圖表轉換為圖像的過程是，使用 Workbook 類加載 Excel 文件，選擇包含圖表的相關工作集並調用 [ToImage 方法](https://apireference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) 用於轉換。

{{% blocks/products/pf/feature-page-code h3="C# 將 Excel 圖表轉換為圖像的代碼" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}