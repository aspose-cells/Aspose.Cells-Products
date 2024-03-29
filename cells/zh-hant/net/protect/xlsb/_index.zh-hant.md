---
title: 保護和鎖定XLSB文檔via .NET
weight: 5920
description: C# 原始碼，用於在 .NET Framework、.NET Core、Mono 或 Xamarin 平台上使用密碼鎖定 XLSB 檔案。
keywords: [C# Aspose.Cells., c# Lock XLSB files., c# How to Protect and lock XLSB document., c# Protect XLSB files., Encrypt XLSB Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="透過 C# 加密 XLSB 文件" h2="使用 .NET 庫對 Excel 電子表格進行密碼保護，包括 XLSB 格式。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 保護 XLSB 文件" %}}

為了保護 XLSB 文件，我們將使用
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
API這是一款功能豐富、強大且易於使用的文件保護API，適用於C#平台。打開
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
套件管理器，搜尋
 **Aspose.Cells** 
並安裝。您也可以從套件管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通過 C# 保護 XLSB" %}}

{{% blocks/products/pf/agp/text %}}

你需要
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
在您的專案中引用以執行以下工作流程。

{{% /blocks/products/pf/agp/text %}}

1. 使用 XLSB 檔案的路徑實例化 Workbook 類
1. 取得預設工作表或任何工作表以新增保護
1. 使用 Worksheet.Protect 方法保護工作表
1. 使用 Workbook.Protect 方法保護工作簿
1. 以 XLSB 格式儲存結果

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for .NET 在所有主要作業系統上均支援。只需確保您滿足以下先決條件即可。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 .NET Framework、.NET Core、Mono 或 Xamarin 平台的相容作業系統
- 開發環境如Microsoft Visual Studio
- 在專案中加入對 Aspose.Cells for .NET DLL 的引用

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="" %}}

```cs

// load the XLSB Excel file 
var book = new Aspose.Cells.Workbook("unlocked.xlsb");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.xlsb");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="關於 Aspose.Cells for .NET API" %}}

 Aspose.Cells API 可用於建立、編輯、轉換和渲染 Microsoft Excel 格式為不同的格式。此外，它還可用於軟體應用程式中的全面圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何像 Microsoft 或 OpenOffice 這樣的軟體。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="免費保護應用程式 XLSB" sectionDescription="查看我們的現場演示[加密XLSB文件](https://products.aspose.app/cells/protect/xlsb)具有以下好處。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="無需下載或設定任何東西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="無需編寫或編譯程式碼" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上傳 XLSB 檔案並點擊「解鎖」按鈕" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="從鏈接下載生成的 XLSB 文件" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB 檔案格式指定 Excel 二進位檔案格式，它是指定 Excel 工作簿內容的記錄和結構的集合。內容可以包括非結構化或半結構化的數字表、文字表、或數字和文字表、公式、外部資料連接、圖表和圖像。與 XLSX（基於 Open XML 檔案格式）不同，XLSB 表示二進位 Excel 工作簿檔案。 XLSB 檔案的讀取和寫入速度更快，這使得它們對於處理大檔案非常有用。 XLSB 很少用於儲存工作簿，因為 XLSX（以及之前的 XLS）是使用者選擇的最常見的用於保存工作簿的檔案格式。可用Microsoft Office 2007以上版本開啟。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支援的保護格式" subTitle="使用 C#，可以輕鬆保護其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="OpenDocument 電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xls/" name="XLS" description="Excel 二進位格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="試算表文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
