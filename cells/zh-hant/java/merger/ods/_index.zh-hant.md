---
title: 合併 ODS 文件 via Java
weight: 6270
description: Java 範例程式碼，用於組合 Java JSP/JSF 應用程式和桌面應用程式執行時間環境上的 ODS 文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="合併 Java 中的 ODS 格式" h2="使用伺服器端 Java API 進行本機 ODS 文件合併。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 合併 ODS 文件" %}}

為了合併 ODS 文件，我們將使用[Aspose.Cells for Java](https://products.aspose.com/cells/java)API這是一個功能豐富、功能強大且易於使用的合併API for Java平台。您可以直接從以下位置下載其最新版本[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)並透過將以下配置新增至 pom.xml 將其安裝在基於 Maven 的專案中。

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

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="合併 Java 中的 ODS 文件的步驟" %}}

{{% blocks/products/pf/agp/text %}}

基本文檔合併和連接[Aspose.Cells for Java](https://products.aspose.com/cells/java)只需幾行程式碼即可完成 API。

{{% /blocks/products/pf/agp/text %}}

使用 Workbook 類別的實例載入第一個 ODS 檔案。
+ 使用 Workbook 類別的實例載入第二個 ODS 文件。
+ 使用combine() 方法合併文件。
+ 將合併後的ODS檔案儲存在指定路徑

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Java 支援所有主要平台和作業系統。請確保您具備以下先決條件。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 或具有 Java JSP/JSF 應用程式和桌面應用程式運行時環境的相容作業系統。
- 直接從 Aspose.Cells for Java 取得最新版本
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="合併 ODS 文件 - Java" offSpacer="" %}}

```cs
// Open the first ODS file.
Workbook odsFile1 = new Workbook("chartsFileWithPath.ods");

// Define the second source book.
// Open the second ODS file.
Workbook odsFile2 = new Workbook("pictureFileWithPath.ods");

// Combining the two workbooks
odsFile1.combine(odsFile2);

// Save the target book file.
odsFile1.save("combinedFileWithPath.ods");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< blocks/products/pf/agp/demobox sectionTitle="線上 ODS 合併現場演示" sectionDescription="立即合併 ODS 文檔，存取我們的[現場示範網站](https://products.aspose.app/cells/merger)。現場演示有以下好處" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="無需下載Aspose API。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="無需編寫任何程式碼。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上傳您的 ODS 文件即可。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="它將立即合併和連接。" >}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="關於 Aspose.Cells for Java API" %}}

 Aspose.Cells API 可用於建立、編輯、轉換和渲染 Microsoft Excel 格式為不同的格式。此外，它還可用於軟體應用程式中的全面圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何像 Microsoft 或 OpenOffice 這樣的軟體。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}


        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
副檔名為 ODS 的檔案代表可由使用者編輯的 OpenDocument 電子表格文件格式。資料按行和列儲存在 ODF 檔案內。它是基於 XML 的格式，並且是開放文件格式 (ODF) 系列中的幾個子類型之一。此格式被指定為 OASIS 發布和維護的 ODF 1.2 規範的一部分。 Windows 以及其他作業系統上的許多應用程式都可以開啟 ODS 檔案進行編輯和操作，包括 Microsoft Excel、NeoOffice 和 LibreOffice。 ODS 文件還可以透過不同的應用程式轉換為其他電子表格格式，例如 XLS、XLSX 等。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支援的合併格式" subTitle="使用 Java，還可以合併許多其他文件格式，包括.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="逗號分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="網頁存檔格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="製表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="文字文檔" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Excel 二進位格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="二進位 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="試算表文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Excel 模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Excel 巨集啟用模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltx/" name="XLTX" description="Office OpenXML Excel 模板" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
