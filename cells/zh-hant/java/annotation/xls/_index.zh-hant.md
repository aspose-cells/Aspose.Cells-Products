---
title: 新增或刪除 XLS 註 via Java
weight: 10040
description: Java 用於刪除 JSP/JSF 應用程式和桌面應用程式的 Java 執行時間環境上的 XLS 格式註解的範例程式碼。
keywords: [Java Aspose.Cells., add xls annotation., insert xls annotation., access xls annotation., remove xls annotation., delete xls annotation., add annotation in xls., insert annotation in xls., access annotation in xls., remove annotation in xls., delete annotation in xls]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="新增或刪除註釋 XLS via Java" h2="建立您自己的 Java 應用程序，以使用伺服器端 API 操作文件檔案中的評論和作者。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 註 XLS 文件" %}}

為了註 XLS 文件，我們將使用
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API這是一個功能豐富、功能強大且易於使用的註解API for Java平台。您可以直接從以下位置下載其最新版本
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

{{% blocks/products/pf/agp/feature-section-col title="從 XLS via Java 新增或刪除註釋的步驟" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. 使用Workbook類別載入XLS文件
1. 選擇相關工作表
1. 透過 CommentCollection 獲取所有評論
1. 使用 Cell Id 呼叫 RemoveAt 將其刪除
1. 儲存呼叫RemoveAt方法前後的工作簿進行比較

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Java 支援所有主要平台和作業系統。請確保您具備以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 應用程式和桌面應用程式運行時環境的相容作業系統。
- 直接從 Maven 取得最新版本的 Aspose.Cells for Java。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="刪除 XLS - Java 中的註釋" offSpacer="" %}}

```cs
// Instantiating a Workbook object
Workbook workbook = new Workbook(dataDir + "ThreadedCommentsSample.xls");

//Access first worksheet
Worksheet worksheet = workbook.getWorksheets().get(0);

CommentCollection comments = worksheet.getComments();
ThreadedCommentCollection threadedComments = worksheet.getComments().getThreadedComments("I4");
ThreadedCommentAuthor author = threadedComments.get(0).getAuthor();
      
comments.removeAt("I4");
      
ThreadedCommentAuthorCollection authors = workbook.getWorksheets().getThreadedCommentAuthors();

authors.removeAt(authors.indexOf(author));
workbook.save(dataDir + "ThreadedCommentsSample_Out.xls");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="關於 Aspose.Cells for Java API" %}}

 Aspose.Cells API 可用於建立、編輯、轉換和渲染 Microsoft Excel 格式為不同的格式。此外，它還可用於軟體應用程式中的全面圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何像 Microsoft 或 OpenOffice 這樣的軟體。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="透過線上應用程式刪除 XLS 的註釋" sectionDescription="立即刪除 XLS 文件註釋，存取我們的[現場示範網站](https://products.aspose.app/cells/annotation)。現場演示有以下好處" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="無需下載或設定任何東西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="無需編寫任何程式碼" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上傳您的 XLS 檔案並點擊「刪除」按鈕" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="立即獲取結果文件的下載鏈接" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
副檔名為 XLS 的檔案代表 Excel 二進位檔案格式。此類文件可以由 Microsoft Excel 以及其他類似的電子表格程式（例如 OpenOffice Calc 或 Apple Numbers）建立。Excel 儲存的檔案稱為工作簿，其中每個工作簿可以有一個或多個工作表。資料以工作表中的表格格式儲存並顯示給用戶，可以涵蓋數值、文字資料、公式、外部資料連接、圖像和圖表。 Microsoft Excel 等應用程式可讓您將工作簿資料匯出為多種不同的格式，包括 PDF、CSV、XLSX、TXT、HTML、XPS 等。隨著 Microsoft Excel 2007 的發布，XLS 文件格式被更開放和結構化的格式 XLSX 所取代。最新版本仍然支援創建和讀取 XLS 文件，儘管 XLSX 是現在使用的首選。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支援的註釋格式" subTitle="使用 Java，人們可以輕鬆註釋其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/annotation/ods/" name="ODS" description="OpenDocument 電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/annotation/xlsb/" name="XLSB" description="二進位 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/annotation/xlsm/" name="XLSM" description="試算表文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/annotation/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
