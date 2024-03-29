---
title: 在 Java 中建立散點圖
description: Aspose Excel。 Java 建立散點圖。建立散佈圖 Java。在 Java 中建立散佈圖。使用 Java 產生散佈圖。
keywords: [Aspose Excel., Java Aspose.Cells., Create Scatter Charts Java., Create Scatter Charts in Java., Generate Scatter Charts in Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="在 Java 中建立散點圖" h2="用於建立散點圖的高速 Java 庫。這是一個專業的軟體解決方案，用於匯入和匯出XLSX、PDF以及使用Java的許多其他格式。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="使用 Java 建立散點圖" %}}

如何建立散點圖？借助 Aspose.Cells for Java 庫，您可以透過幾行程式碼以程式設計方式輕鬆繪製散佈圖。[Aspose.Cells for Java](https://products.aspose.com/cells/java)能夠建立跨平台應用程序，能夠生成、修改、轉換、渲染和列印所有 Excel 檔案。 Java Excel API 不僅可以在電子表格格式之間進行轉換，還可以將 Excel 文件呈現為圖像、PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT 等，從而使其成為以行業標準格式交換文件的完美選擇。您可以直接從以下位置下載其最新版本[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)並透過將以下配置新增至 pom.xml 將其安裝在基於 Maven 的專案中。

{{% blocks/products/pf/agp/code-block title="儲存庫" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依賴性" offSpacer="true" %}}

```cs

<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="如何在Java中建立散點圖" %}}

{{% blocks/products/pf/agp/text %}}

需要以程式設計方式建立散點圖？ Java 開發人員只需幾行程式碼即可輕鬆建立散佈圖。

{{% /blocks/products/pf/agp/text %}}

1. 在類別檔案中包含命名空間
1. 創造[**練習冊**](https://reference.aspose.com/cells/java/com.aspose.cells/workbook/)類別實例。
1. 使用以下命令將一些資料添加到工作表單元格中[**Cell**](https://reference.aspose.com/cells/java/com.aspose.cells/cell/)對象的[**投入價值**](https://reference.aspose.com/cells/java/com.aspose.cells/cell/#putValue-int-)方法。
1. 添加一個[**SCATTER**](https://reference.aspose.com/cells/java/com.aspose.cells/charttype/)透過呼叫圖表到工作表[**圖表**](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection/)收藏的[**添加**](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection/#add-int-int-int-int-int-)方法，封裝在[**工作表**](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/)目的。
1. 訪問新的[**圖表**](https://reference.aspose.com/cells/java/com.aspose.cells/chart/)透過傳遞索引來取得 Charts 集合中的物件。
1. 設定圖表的資料來源[**Chart.setChartDataRange**](https://reference.aspose.com/cells/java/com.aspose.cells/chart/#setChartDataRange-java.lang.String-boolean-)方法。
1. 另存為 Excel 或 ODS 檔案。

{{% blocks/products/pf/agp/code-block title="範例程式碼展示如何在 Java 中建立散點圖。" offSpacer="" %}}

```cs

// Instantiating a Workbook object
Workbook workbook = new Workbook();
// Obtaining the reference of the first worksheet
Worksheet worksheet = workbook.getWorksheets().get(0);

// Adding sample values to cells
Cells cells = worksheet.getCells();
cells.get("A2").putValue("Category1");
cells.get("A3").putValue("Category2");
cells.get("A4").putValue("Category3");

cells.get("B1").putValue("Scatter");
cells.get("B2").putValue(324);
cells.get("B3").putValue(200);
cells.get("B4").putValue(450);

// Adding a Scatter chart to the worksheet
int chartIndex = worksheet.getCharts().add(ChartType.SCATTER, 6, 2, 20, 10);

// Accessing the instance of the newly added chart
Chart chart = worksheet.getCharts().get(chartIndex);

// Setting chart data source as the range "A1:B4"
chart.setChartDataRange("A1:B4", true);

// Save the Workbook as .xlsx file.
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Java 建立散點圖的庫" %}}
{{% blocks/products/pf/agp/text %}}

我們將 Java 包裹託管在[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)儲存庫。 「Aspose.Cells for Java」是包含字節碼的常見 JAR 檔案。請遵循[逐步說明](https://docs.aspose.com/cells/java/installation/)關於如何將其安裝到您的 Java 開發人員環境。

{{% /blocks/products/pf/agp/text %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="系統需求" %}}

{{% blocks/products/pf/agp/text %}}

在執行 Java 轉換範例原始程式碼之前，請確保滿足以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 應用程式和桌面應用程式運行時環境的相容作業系統。
- Aspose.Cells for Java 支援以下 Java 版本：J2SE 6.0 (1.6)、J2SE 7.0 (1.7) 或更高版本。
- [直接從 Maven 取得最新版本的 Aspose.Cells for Java。](https://docs.aspose.com/cells/java/installation/) 

{{% /blocks/products/pf/agp/content %}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
