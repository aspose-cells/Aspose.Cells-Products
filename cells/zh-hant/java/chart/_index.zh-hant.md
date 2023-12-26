---
title: 建立 Excel 圖表並轉換為影像 via Java
description:  Java 使用 Java 庫在 Microsoft Excel 中繪製和轉換圖表或圖表的原始程式碼。
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 檔案圖表轉換與建立 via Java" h2="將 Excel 文件圖表轉換為圖像，並在基於 Java 的應用程式中使用伺服器端 API 建立各種圖表。" >}}


{{% blocks/products/pf/feature-page-summary %}}

透過圖表分析數據可以顯示更大的圖景，並且可以透過更清晰的見解輕鬆做出更明智的決策。[Java Excel 庫](/cells/zh-hant/java/)支援繪製列出的不同圖表創建[圖表類型](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType)包括圓餅圖、金字塔圖、折線圖和氣泡圖。此外，它還將圖表轉換為圖像。 API 提供[圖表類](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)用於表示單一 Excel 圖表。

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="將 Excel 圖表轉換為影像" %}}

將圖表轉換為圖像（包括 JPG、PNG、TIFF、BMP 等）的過程是，使用[練習冊](https://reference.aspose.com/java/cells/com.aspose.cells/workbook)載入Excel檔案的類，選擇相關[工作區](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet)包含圖表或迭代每個工作表中的每個圖表。定義[影像或列印選項](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions)並使用渲染圖表的輸出影像[圖表轉圖像](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java 將Excel圖表轉換為圖像的程式碼" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="在 Excel 檔案中建立圖表" %}}

使用 Excel API 建立圖表很簡單，因為 API 為不同類型的圖表提供了一組不同的類，例如 Axis、Chart、ChartArea、ChartDataTable、ChartFrame、ChartPoint、ChartPointCollection、ChartCollection 等。過程是，建立 Workbook 類別物件並透過提供其索引來選擇第一個工作表或相關工作表。對於圖表的資料來源，使用下列命令將值插入工作表儲存格[設定值](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)方法。使用 ChartCollection 集合[添加方法](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) 若要新增圖表，請使用 ChartType 枚舉定義圖表類型。透過傳遞索引從 ChartCollection 集合中存取新的 Chart 物件。使用[系列合集](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection)圖表物件來指定圖表的資料來源。

{{% blocks/products/pf/feature-page-code h3="Java 建立 Excel 圖表的程式碼" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
