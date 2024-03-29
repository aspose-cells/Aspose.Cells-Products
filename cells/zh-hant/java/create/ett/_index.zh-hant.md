---
title: 建立ETT - 在Java中建立ETT文件
description: Aspose Excel。 Java 使用 Aspose.Cells 快速輕鬆地建立 ETT 檔案。使用 Java 產生 ETT 檔案。在 Java 中建立 ETT。Java ETT 建立器。
keywords: [Aspose Excel., Java Aspose.Cells., Java Create ETT file., Generate ETT file in Java., Create ETT file using Java., Write data to ETT file via Java., Create a ETT file in Java., Java Generate a ETT file., Java ETT Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="在Java中建立ETT文件" h2="用於建立 ETT 檔案的高速 Java 庫。這是一個專業的軟體解決方案，用於匯入和匯出XLSX、PDF以及使用Java的許多其他格式。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ETT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="使用 Java 建立 ETT 文件" %}}

如何建立 ETT 檔案？使用 Aspose.Cells for Java 庫，您可以透過幾行程式碼以程式設計方式輕鬆建立 ETT 檔案。[Aspose.Cells for Java](https://products.aspose.com/cells/java)能夠建立跨平台應用程序，能夠生成、修改、轉換、渲染和列印所有 Excel 檔案。 Java Excel API 不僅可以在電子表格格式之間進行轉換，還可以將 Excel 文件呈現為圖像、PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT 等，從而使其成為以行業標準格式交換文件的完美選擇。您可以直接從以下位置下載其最新版本[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)並透過將以下配置新增至 pom.xml 將其安裝在基於 Maven 的專案中。

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



{{% blocks/products/pf/agp/content h2="如何在Java中建立ETT" %}}

{{% blocks/products/pf/agp/text %}}

開發人員只需幾行程式碼即可輕鬆在執行不同的報表應用程式中建立、載入、修改和轉換 ETT 檔案以進行資料處理。

{{% /blocks/products/pf/agp/text %}}

1. 建立一個實例[作業本類](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
1. 使用 getWorksheets.get() 方法存取相關工作表。
1. 選擇相關儲存格，使用儲存格名稱將值輸入到所需的儲存格中，例如A1、B3等。
1. 使用 save() 方法將工作簿儲存為 ETT 格式。

{{% blocks/products/pf/agp/code-block title="範例程式碼展示如何在 Java 中建立 ETT 檔案。" offSpacer="" %}}

```cs

// Create a new workbook
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet worksheet = wkb.getWorksheets().get(0);

// Add relevant content in the cell
worksheet.getCells().get("A1").putValue("ColumnA");
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Save the workbook as ETT file
wkb.save("Excel.ett"); 

// To enhance the code for further functionalities here are more functions
// getCells() and setValue for modifying the cell content
// getCharts().add() to add charts
// getPivotTables().add() for creating a Pivot Table
// getCells().get(int cell id).setFormula for adding cell level formula

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Java 庫建立ETT文件" %}}
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

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ETT" readMoreLink="https://fileinfo.com/extension/ett/" >}}ETT 檔案是由 Kingsoft Spreadsheets 建立的電子表格模板，Kingsoft Spreadsheets 是 WPS Office 套件中包含的電子表格程式。它儲存一個模板，可用作建立新金山電子表格（.ET 檔案）的起點。 ETT 檔案通常用於建立財務預算和組織資料。{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支援的電子表格生成" subTitle="您也可以建立其他 Microsoft Excel 格式，包括下面列出的幾種。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xls/" name="XLS" description="Microsoft Excel 電子表格（舊版）" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsx/" name="XLSX" description="開啟 XML 工作簿" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsb/" name="XLSB" description="Excel 二進位工作簿" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsm/" name="XLSM" description="啟用巨集的電子表格" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlt/" name="XLT" description="Excel 97 - 2003 模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xltx/" name="XLTX" description="Excel模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xltm/" name="XLTM" description="Excel 巨集啟用模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/csv/" name="CSV" description="逗號分隔值" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/tsv/" name="TSV" description="製表符分隔值" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/ods/" name="ODS" description="開放文件電子表格" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/pdf/" name="PDF" description="便攜式文件格式" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/html/" name="HTML" description="超文本標記語言" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
