---
title: 通過 Java 將 NUMBERS 轉換為 PNG 
url: /zh-hant/java/conversion/numbers-to-png/ 
description: NUMBERS 格式到 PNG 文件的示例 Java 轉換代碼。程序員可以使用此示例代碼在任何基於 Web 或桌面 Java 的應用程序中將 Excel 和 OpenOffice 電子表格導出為 PNG。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 Java 將 NUMBERS 轉換為 PNG" h2="NUMBERS 到 PNG Java 轉換以使用內部部署 Java 庫將單個或多個頁面轉換為 PNG。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="NUMBERS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 將 NUMBERS 轉換為 PNG" %}}

 為了將 NUMBERS 渲染為 PNG，我們將使用
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API 是一個功能豐富、功能強大且易於使用的轉換API for Java 平台。您可以直接從
 [馬文](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 並通過將以下配置添加到 pom.xml 將其安裝在基於 Maven 的項目中。

{{% blocks/products/pf/agp/code-block title="存儲庫" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依賴" offSpacer="true" %}}

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

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通過 Java 將 NUMBERS 轉換為 PNG 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 Java 開發人員只需幾行代碼即可輕鬆地將 NUMBERS 文件轉換為 PNG。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Workbook 實例加載 NUMBERS 文件1. 從集合中選擇默認或任何工作表1. 創建和設置 ImageOrPrintOptions 的對象1. 使用 Worksheet 和 ImageOrPrintOptions 對象創建 SheetRender1. 調用 SheetRender.toImage 方法將結果保存為 PNG 格式

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 Java 轉換源代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 應用程序和桌面應用程序運行時環境的兼容操作系統。- 直接從 Maven 獲取最新版本的 Aspose.Cells for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="NUMBERS 到 PNG Java 轉換源代碼" offSpacer="" %}}

```cs
// 加載要渲染的 NUMBERS 文件
Workbook workbook = new Workbook("sourceFile.numbers");
// 從集合中訪問默認工作表
Worksheet worksheet = workbook.getWorksheets().get(0);
// 定義結果圖像的參數
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.PNG);
// 將工作表轉換為 PNG 格式的圖像
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.png");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="NUMBERS 到 PNG 轉換現場演示" sectionDescription="[將 NUMBERS 轉換為 PNG](https://products.aspose.app/cells/conversion/numbers-to-png) 立即訪問我們的現場演示網站。現場演示具有以下好處" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳您的 NUMBERS 文件，它就會立即轉換為 PNG。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您將獲得下載鏈接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 電子表格操作庫" %}}

 Excel API 可用於創建、編輯、轉換 Microsoft Excel 格式並將其呈現為不同的格式。此外，它還可用於軟件應用程序中的綜合圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何軟件，例如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="NUMBERS" readMoreLink="https://docs.fileformat.com/spreadsheet/numbers/" >}}

帶有 .numbers 擴展名的文件類似於 .xlsx 文件。 Numbers 文件是使用 Apple iWork Numbers 電子表格軟件創建的。 Apple iWork Numbers 是 iWork Productivity Suite 的一個單元軟件。 iWork Productivity Suite 相當於在 Windows PC 上使用的 Microsoft Office Suite。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" >}}

PNG，便攜式網絡圖形，是指一種使用無損壓縮的光柵圖像文件格式。此文件格式是作為圖形交換格式 (GIF) 的替代品而創建的，沒有版權限制。但是，PNG 文件格式不支持動畫。 PNG文件格式支持無損圖像壓縮，使其在用戶中很受歡迎。隨著時間的推移，PNG 已經發展成為最常用的圖像文件格式之一。幾乎所有操作系統都支持打開 PNG 文件。例如，Microsoft Windows 查看器能夠打開 PNG 文件，因為操作系統默認支持作為安裝的一部分。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}