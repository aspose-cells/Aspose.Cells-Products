---
title: 將 SVG 影像/圖示插入 Excel via .NET
weight: 110
description: C# 原始程式碼，用於將 SVG 映像/圖示插入 .NET Framework、.NET Core、Mono 或 Xamarin 平台上的 Excel。
keywords: [C# Aspose.Cells., c# add SVG images/Icons into Excel., c# insert SVG images/Icons into Excel., c# create SVG images/Icons in Excel]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="將 SVG 影像/圖示插入 Excel via .NET" h2="使用 Aspose.Cells\' API 插入 SVG 圖像/圖標，無需任何軟體，如 Microsoft 或 Open Office、Adobe PDF 等。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content %}}

您不想看到影像在任何裝置上被拉伸和壓縮？

您不希望放大時影像變得模糊嗎？

您不希望影像在高解析度下失真嗎？

也許SVG是一個不錯的選擇。SVG圖像在任何縮放等級下看起來都很棒，而且它們與解析度無關。由於svg影像的高保真度，它在Excel用戶中非常受歡迎。

使用Excel時，您可能會遇到以下問題：

+ 目標Excel檔案不能直接手動操作，需要程式來處理。
+ 將大量 svg 影像插入同一個 Excel 檔案。
+ 將 svg 影像插入大量不同的 Excel 檔案。

為了解決這些問題，我們建議您使用[Aspose.Cells](https://products.aspose.com/cells/)庫。它包含許多處理excel文件的常用接口，是一個非常有用的工具。

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="如何使用 Microsoft Excel 將 SVG 圖像/圖示插入 Excel 文件" %}}

![](/cells/zh-hant/net/icons/insert-icons-to-excel/sample.png)

Microsoft Excel為我們提供了三種插入svg的方式：

+  **插入本地SVG圖像/圖標**

您只需將 SVG 檔案拖放到文件中的特定位置即可。或者您可以從功能區選擇「*插入 -> 圖片 -> 此裝置...*」路徑。

+  **插入預設 SVG 圖像/圖標**

Microsoft Excel已經為我們提供了預設的svg圖片供我們選擇。您可以從功能區選擇「*插入 -> 圖片 -> 庫存影像...*」路徑來開啟選擇對話方塊。大多數 svg 檔案都位於 Stock Images 中的「圖示」選項下。

+  **插入來自網路的 SVG 圖像/圖標**

如果以上方法都無法滿足您的需求，您也可以透過Microsoft Excel從網路上搜尋您想要的結果。您可以透過選擇「*插入->圖片->線上圖片...*」來開啟選擇對話方塊。 「來自絲帶的路徑。

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 將 SVG 圖像/圖示插入 Excel 文件" %}}

為了將 SVG 圖像/圖示插入 Excel 文件，我們將使用
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
API 這是一個功能豐富、強大且易於使用的文件操作和分割器 API，適用於 C# 平台。打開
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
套件管理器，搜尋
 Aspose.Cells 
並安裝。您也可以從套件管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="透過 C# 將 SVG 圖像/圖示插入 Excel 檔案的步驟" %}}

{{% blocks/products/pf/agp/text %}}

您需要 aspose.cells.dll 在您自己的環境中嘗試以下工作流程。

{{% /blocks/products/pf/agp/text %}}

實例化一個 Workbook 物件。（或->載入 XLSX 檔案的完整路徑。）
+ 透過索引選擇工作表。
 + 使用[添加方法](https://reference.aspose.com/cells/net/aspose.cells.drawing/shapecollection/methods/addicons)在選定的工作表中插入圖標
以 XLSX 格式儲存工作簿。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for .NET 在所有主要作業系統上均支援。只需確保您滿足以下先決條件即可。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 .NET Framework、.NET Core、Mono 或 Xamarin 平台的相容作業系統
- 開發環境如Microsoft Visual Studio
- 在專案中新增對 Aspose.Cells for .NET DLL 的引用 - 使用上面的下載按鈕從 NuGet 安裝

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="插入 SVG 圖像/圖示 - C#" offSpacer="" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertIconsIntoWorksheet.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="關於 Aspose.Cells for .NET API" %}}

Aspose.Cells API 可用於建立、編輯、轉換和渲染 Microsoft Excel 格式為不同的格式。此外，它還可用於軟體應用程式中的全面圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何像 Microsoft 或 OpenOffice 這樣的軟體。

{{% /blocks/products/pf/agp/content %}}



<!-- aboutfile Ends -->
<!--
{{< blocks/products/pf/agp/other-supported-section title="Other Supported Splitting Formats" subTitle="Using C#, One can also split large file into chunks of many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xls/" name="XLS" description="Excel Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsb/" name="XLSB" description="Binary Excel Workbook File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsm/" name="XLSM" description="Spreadsheet File" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

-->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
