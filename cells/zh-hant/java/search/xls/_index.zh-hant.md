---
title: 搜尋XLS文檔，無需開啟via Java
weight: 9430
description: Java 範例程式碼，用於在 JSP/JSF 應用程式和桌面應用程式的 Java 執行時間環境中搜尋 XLS 檔案中具有模式的單字。
keywords: [Java Aspose.Cells., Java search words with pattern in xls file., Java find words with pattern in xls file., Java search string with pattern in xls file., Java find words with pattern in xls file., Java search words in xls file., Java find words in xls file., Java search string in xls file., Java find string in xls file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="搜尋 XLS Java 中的格式" h2="使用伺服器端 Aspose.Cells for Java API 進行本機高效能 XLS 文件搜索，無需使用 Microsoft 或 Adobe PDF 等任何軟體。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 搜尋 XLS 文件" %}}

為了搜尋 XLS 文件，我們將使用
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API這是一個功能豐富、功能強大且易於使用的搜尋API for Java平台。您可以直接從以下位置下載其最新版本
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
並透過將以下配置新增至 pom.xml 將其安裝在基於 Maven 的專案中。

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

{{% blocks/products/pf/agp/feature-section-col title="搜尋 Java 中的 XLS 文件的步驟" %}}

{{% blocks/products/pf/agp/text %}}

只需幾行程式碼即可使用 Aspose.Cells API 完成基本文件搜尋。

{{% /blocks/products/pf/agp/text %}}

透過實例化 Workbook 物件來載入 XLS 檔案。
+ 存取 XLS 檔案中的第一個工作表。
+ 尋找包含指定公式的儲存格。
+ 實例化 FindOptions。
+ 尋找包含字串值的儲存格
列印搜尋結果後找到的儲存格

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Java 支援所有主要平台和作業系統。請確保您具備以下先決條件。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 或具有 Java JSP/JSF 應用程式和桌面應用程式運行時環境的相容作業系統。
- 直接從 Aspose.Cells for Java 取得最新版本
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="搜尋 XLS 文件 - Java" offSpacer="" %}}

```cs
// Instantiating a Workbook object
Workbook workbook = new Workbook(dataDir + "book1.xls");

// Accessing the first worksheet in the XLS file
Worksheet worksheet = workbook.getWorksheets().get(0);

// Finding the cell containing the specified formula
Cells cells = worksheet.getCells();

// Instantiate FindOptions
FindOptions findOptions = new FindOptions();

// Finding the cell containing a string value that starts with Or
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// Printing the name of the cell found after searching 
System.out.println("Name of the cell containing String: " + cell.getName());  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="關於 Aspose.Cells for Java API" %}}

 Aspose.Cells API 可用於建立、編輯、轉換和渲染 Microsoft Excel 格式為不同的格式。此外，它還可用於軟體應用程式中的全面圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何像 Microsoft 或 OpenOffice 這樣的軟體。



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="線上 XLS 搜尋現場演示" sectionDescription="立即造訪我們的 XLS 文件中搜尋文字、單字、片語[現場示範網站](https://products.aspose.app/cells/search)。現場演示有以下好處" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text="無需下載Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="無需編寫任何程式碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上傳您的 XLS 文件即可。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="搜尋結果立即出現。" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS " readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
副檔名為 XLS 的檔案代表 Excel 二進位檔案格式。此類文件可以由 Microsoft Excel 以及其他類似的電子表格程式（例如 OpenOffice Calc 或 Apple Numbers）建立。Excel 儲存的檔案稱為工作簿，其中每個工作簿可以有一個或多個工作表。資料以工作表中的表格格式儲存並顯示給用戶，可以涵蓋數值、文字資料、公式、外部資料連接、圖像和圖表。 Microsoft Excel 等應用程式可讓您將工作簿資料匯出為多種不同的格式，包括 PDF、CSV、XLSX、TXT、HTML、XPS 等。隨著 Microsoft Excel 2007 的發布，XLS 文件格式被更開放和結構化的格式 XLSX 所取代。最新版本仍然支援創建和讀取 XLS 文件，儘管 XLSX 是現在使用的首選。

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支援的搜尋文檔" subTitle="使用Java，還可以搜尋其他文件，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/csv/" name="CSV" description="逗號分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/ods/" name="ODS" description="OpenDocument 電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/tsv/" name="TSV" description="製表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/txt/" name="TXT" description="文字文檔" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsb/" name="XLSB" description="二進位 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="試算表文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
