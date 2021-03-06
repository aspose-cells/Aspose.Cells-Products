---
title: 通過 Java 將 TSV 轉換為 XML 
url: /zh-hant/java/conversion/tsv-to-xml/ 
description: TSV 格式到 XML 文件的示例 Java 轉換代碼。程序員可以使用此示例代碼在任何基於 Web 或桌面 Java 的應用程序中將 Excel 和 OpenOffice 電子表格導出為 XML。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 Java 將 TSV 轉換為 XML" h2="TSV 到 XML Java 轉換以使用內部部署 Java 庫將單個或多個頁面轉換為 XML。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 將 TSV 轉換為 XML" %}}

 為了將 TSV 呈現為 XML，我們將使用
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

{{% blocks/products/pf/agp/feature-section-col title="通過 Java 將 TSV 轉換為 XML 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 Java 開發人員只需幾行代碼即可輕鬆地將 TSV 文件轉換為 XML。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Workbook 類的實例加載 TSV 文件1. 調用 Workbook.save 方法1. 將帶有 XML 擴展名和 SaveFormat 的輸出路徑作為參數傳遞1. 檢查生成的 XML 文件的指定路徑

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 Java 轉換源代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 應用程序和桌面應用程序運行時環境的兼容操作系統。- 直接從 Maven 獲取最新版本的 Aspose.Cells for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSV 到 XML Java 轉換源代碼" offSpacer="" %}}

```cs
// 在 Workbook 的實例中加載 TSV 文件
Workbook book = new Workbook("template.tsv");
// 將 TSV 保存為 XML
book.save("output.xml", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TSV 到 XML 轉換現場演示" sectionDescription="[將 TSV 轉換為 XML](https://products.aspose.app/cells/conversion/tsv-to-xml) 立即訪問我們的現場演示網站。現場演示具有以下好處" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳您的 TSV 文件，它就會立即轉換為 XML。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您將獲得下載鏈接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 電子表格操作庫" %}}

 Excel API 可用於創建、編輯、轉換 Microsoft Excel 格式並將其呈現為不同的格式。此外，它還可用於軟件應用程序中的綜合圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何軟件，例如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

製表符分隔值 (TSV) 文件格式表示用純文本格式的製表符分隔的數據。該文件格式類似於 CSV，用於以結構化方式組織數據，以便在不同應用程序之間導入和導出。該格式主要用於電子表格應用程序和數據庫中的數據導入/導出和交換。 TSV 文件中的每條記錄都包含在單行文本文件中，其中每個字段值由製表符分隔。 TSV 文件格式的媒體類型是文本/製表符分隔值。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" >}}

XML 代表可擴展標記語言，它與 HTML 類似，但在使用標籤來定義對象方面有所不同。創建 XML 文件格式背後的整個想法是在不依賴軟件或硬件工具的情況下存儲和傳輸數據。它的流行是因為它既是人類可讀的又是機器可讀的。這使其能夠以對象的形式創建通用數據協議，以便通過網絡（如萬維網 (WWW)）存儲和共享。 XML 中的“X”表示可擴展，這意味著該語言可以根據用戶要求擴展到任意數量的符號。正是因為這些特性，許多標准文件格式都使用了它，例如 Microsoft Open XML、LibreOffice OpenDocument、XHTML 和 SVG。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="您還可以將 TSV 轉換為許多其他文件格式，包括下面列出的幾種文件格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-bmp/" name="TSV轉BMP" description="位圖圖像" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-csv/" name="TSV 轉 CSV" description="逗號分隔值" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-dif/" name="TSV轉DIF" description="數據交換格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-emf/" name="TSV 到 EMF" description="增強的元文件格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-gif/" name="TSV轉GIF" description="圖形交換格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-html/" name="TSV 轉 HTML" description="超文本標記語言" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-jpeg/" name="TSV轉JPEG" description="JPEG圖像" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-mhtml/" name="TSV轉MHTML" description="網頁存檔格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-ods/" name="TSV 到 ODS" description="OpenDocument 電子表格文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-pdf/" name="TSV轉PDF" description="便攜式文件格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-png/" name="TSV轉PNG" description="便攜式網絡圖形" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-svg/" name="TSV轉SVG" description="可縮放矢量圖形" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-tiff/" name="TSV 轉 TIFF" description="標記圖像格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-txt/" name="TSV轉TXT" description="文本文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlm/" name="TSV 轉 XLM" description="Excel 宏文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xls/" name="TSV 轉 XLS" description="Excel 二進制格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlsb/" name="TSV 轉 XLSB" description="二進制 Excel 工作簿文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlsx/" name="TSV 轉 XLSX" description="OOXML Excel 文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xlt/" name="TSV 轉 XLT" description="微軟 Excel 模板" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xltm/" name="TSV 轉 XLTM" description="Excel 啟用宏的模板" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xltx/" name="TSV 轉 XLTX" description="Office OpenXML Excel 模板" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-xps/" name="TSV 轉 XPS" description="XML 紙張規格" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/tsv-to-json/" name="TSV 轉 JSON" description="JavaScript 對象表示法" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}