---
title: Excel 圖表建立和影像轉換 via .NET
description:  C# 使用 .NET 庫在 Microsoft Excel 中繪製和轉換圖表或圖表的原始程式碼。
keywords: [C# Aspose.Cells., c# Convert chart to image., c# Save chart to image., c# chart to image., create charts in c#., insert charts in c#., manage charts in c#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 檔案圖表建立與轉換 via .NET" h2="在基於 .NET 的應用程式中使用伺服器端 API 建立 Excel 文件圖表並轉換為影像。" >}}
{{% blocks/products/pf/feature-page-summary %}}
繪製圖表是一門以圖形方式顯示數據以便於分析的藝術。[.NET Excel 庫](/cells/zh-hant/net/)支援在Excel檔案中繪製圖表。 API 支援中列出的不同圖表創建[圖表類型枚舉](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)包括圓餅圖、金字塔圖、折線圖和氣泡圖。此外，它還將圖表轉換為圖像。 API 提供[圖表類](https://reference.aspose.com/cells/net/aspose.cells.charts)用於圖表構建塊。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="在 Excel 檔案中建立圖表" %}}

使用 Excel API 建立圖表很簡單。流程是，創建[作業本類](https://reference.aspose.com/cells/net/aspose.cells/workbook)物件並透過提供其索引來選擇第一個工作表或相關工作表。使用插入所需的儲存格數據[價值法](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index)。使用 Charts 集合將圖表新增至工作表[添加方法](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add)。指定[圖表類型](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)來自 ChartType 枚舉。
{{% blocks/products/pf/feature-page-code h3="C# 建立 Excel 圖表的程式碼" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="將 Excel 圖表轉換為影像" %}}

將圖表轉換為圖像的過程是，使用 Workbook 類別載入 Excel 文件，選擇包含圖表的相關工作集並調用[影像方法](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7)用於轉換。

{{% blocks/products/pf/feature-page-code h3="C# 將Excel圖表轉換為圖像的程式碼" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
