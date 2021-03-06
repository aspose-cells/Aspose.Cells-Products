---
title: 通過 Java 將 MHTML 轉換為 HTML 
weight: 1760
url: /zh-hant/java/conversion/mhtml-to-html/ 
description: MHTML 格式到 HTML 文件的示例 Java 轉換代碼。程序員可以使用此示例代碼在任何基於 Web 或桌面 Java 的應用程序中將 Excel 和 OpenOffice 電子表格導出為 HTML。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 Java 將 MHTML 轉換為 HTML" h2="MHTML 到 HTML Java 轉換以使用內部部署 Java 庫將單個或多個頁面轉換為 HTML。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 將 MHTML 轉換為 HTML" %}}

 為了將 MHTML 呈現為 HTML，我們將使用
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

{{% blocks/products/pf/agp/feature-section-col title="通過 Java 將 MHTML 轉換為 HTML 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 Java 開發人員只需幾行代碼即可輕鬆地將 MHTML 文件轉換為 HTML。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Workbook 類的實例加載 MHTML 文件1. 調用 Workbook.save 方法1. 將帶有 HTML 擴展名和 SaveFormat 的輸出路徑作為參數傳遞1. 檢查生成的 HTML 文件的指定路徑
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 Java 轉換源代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 應用程序和桌面應用程序運行時環境的兼容操作系統。- 直接從 Maven 獲取最新版本的 Aspose.Cells for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="MHTML 到 HTML Java 轉換源代碼" offSpacer="" %}}

```cs
// 在 Workbook 實例中加載 MHTML 文件
Workbook book = new Workbook("template.mhtml");
// 將 MHTML 保存為 HTML
book.save("output.html", SaveFormat.AUTO);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="MHTML 到 HTML 轉換現場演示" sectionDescription="[將 MHTML 轉換為 HTML](https://products.aspose.app/cells/conversion/mhtml-to-html) 立即訪問我們的現場演示網站。現場演示具有以下好處" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳您的 MHTML 文件，它就會立即轉換為 HTML。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您將獲得下載鏈接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 電子表格操作庫" %}}

 Excel API 可用於創建、編輯、轉換 Microsoft Excel 格式並將其呈現為不同的格式。此外，它還可用於軟件應用程序中的綜合圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何軟件，例如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

具有 MHTML 擴展名的文件代表一種網頁存檔格式，可以由許多不同的應用程序創建。該格式被稱為存檔格式，因為它將 Web HTML 代碼和相關資源保存在單個文件中。這些資源包括鏈接到網頁的任何內容，例如圖像、小程序、動畫、音頻文件等。 MHTML 文件可以在各種應用程序中打開，例如 Internet Explorer 和 Microsoft Word。 Microsoft Windows 使用 MHTML 文件格式記錄在 Windows 上使用任何引發問題的應用程序期間觀察到的問題場景。 MHTML 文件格式對頁面內容進行編碼，類似於 message/rfc822 中定義的規範，這是純文本電子郵件相關規範。格式的實際規範在 RFC 2557 中有詳細說明。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML（超文本標記語言）是為在瀏覽器中顯示而創建的網頁的擴展。 HTML 被稱為網絡語言，隨著新信息要求的要求而發展，要求將其顯示為網頁的一部分。最新的變體被稱為 HTML 5，它為使用該語言提供了很大的靈活性。 HTML 頁面要么從託管這些頁面的服務器接收，要么也可以從本地系統加載。每個 HTML 頁面都由 HTML 元素組成，例如表單、文本、圖像、動畫、鏈接等。這些元素由諸如 img、a、p 和其他幾個標籤表示，其中每個標籤都有開始和結束。它還可以嵌入以 JavaScript 和样式表 (CSS) 等腳本語言編寫的應用程序，以實現整體佈局表示。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="您還可以將 MHTML 轉換為許多其他文件格式，包括下面列出的幾種。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-bmp/" name="MHTML轉BMP" description="位圖圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-csv/" name="MHTML 轉 CSV" description="逗號分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-dif/" name="MHTML轉DIF" description="數據交換格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-emf/" name="MHTML 到 EMF" description="增強的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-gif/" name="MHTML轉GIF" description="圖形交換格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-jpeg/" name="MHTML轉JPEG" description="JPEG圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-ods/" name="MHTML 到 ODS" description="OpenDocument 電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-pdf/" name="MHTML轉PDF" description="便攜式文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-png/" name="MHTML轉PNG" description="便攜式網絡圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-svg/" name="MHTML 轉 SVG" description="可縮放矢量圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-tiff/" name="MHTML 轉 TIFF" description="標記圖像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-tsv/" name="MHTML 轉 TSV" description="製表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-txt/" name="MHTML轉TXT" description="文本文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlm/" name="MHTML 轉 XLM" description="Excel 宏文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xls/" name="MHTML 到 XLS" description="Excel 二進制格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlsb/" name="MHTML 轉 XLSB" description="二進制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlsx/" name="MHTML 到 XLSX" description="OOXML Excel 文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlt/" name="MHTML 到 XLT" description="微軟 Excel 模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xltm/" name="MHTML 到 XLTM" description="Excel 啟用宏的模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xltx/" name="MHTML 到 XLTX" description="Office OpenXML Excel 模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xps/" name="MHTML 轉 XPS" description="XML 紙張規格" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-json/" name="MHTML 轉 JSON" description="JavaScript 對象表示法" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}