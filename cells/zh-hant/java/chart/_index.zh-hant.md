---
title: 通過 Java 創建 Excel 圖表並轉換為圖像

description: Java 使用 Java 庫在 Microsoft Excel 中繪製和轉換圖表或圖表的源代碼。 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通過 Java 轉換和創建 Excel 文件圖表" h2="將 Excel 文檔圖表轉換為圖像，並在基於 Java 的應用程序中使用服務器端 API 創建各種圖表。" >}}


{{% blocks/products/pf/feature-page-summary %}}

通過圖表分析數據可以顯示更大的圖景，並且可以通過更清晰的見解輕鬆做出更明智的決策。 [Java Excel 庫](/cells/java/) 支持繪製不同的圖表創建列出 [圖表類型](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) 包括餅圖、金字塔圖、折線圖和氣泡圖。此外，它還將圖表轉換為圖像。 API 提供了一個 [圖表類](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) 用於表示單個 Excel 圖表。

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="將 Excel 圖表轉換為圖像" %}}

將圖表轉換為 JPG、PNG、TIFF、BMP 等圖像的過程是，使用 [工作簿](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) 類加載Excel文件，選擇相關 [工作表](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) 包含圖表或遍歷每個工作表中的每個圖表。定義 [圖像或打印選項](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) 並使用渲染圖表的輸出圖像 [Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)）。


{{% blocks/products/pf/feature-page-code h3="Java 將 Excel 圖表轉換為圖像的代碼" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="在 Excel 文件中創建圖表" %}}

使用 Excel API 創建圖表很簡單，因為 API 為不同類型的圖表提供了一組不同的類，例如 Axis、Chart、ChartArea、ChartDataTable、ChartFrame、ChartPoint、ChartPointCollection、ChartCollection 等。過程是，創建工作簿類對象並通過提供其索引來選擇第一個工作表或相關工作表。對於圖表的數據源，使用 [設定值](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) 方法。使用 ChartCollection 集合的 [添加方法](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) 添加圖表，使用 ChartType 枚舉定義圖表類型。通過傳遞其索引從 ChartCollection 集合中訪問新的 Chart 對象。使用 [系列收藏](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) 圖表對象來指定圖表的數據源。

{{% blocks/products/pf/feature-page-code h3="Java 創建 Excel 圖表的代碼" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
