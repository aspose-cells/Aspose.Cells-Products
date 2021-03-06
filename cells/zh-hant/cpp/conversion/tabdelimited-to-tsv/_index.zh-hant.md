---
title: 通過 C++ 應用程序將 TABDELIMITED 轉換為 TSV 
url: /zh-hant/cpp/conversion/tabdelimited-to-tsv/ 
description: TABDELIMITED 文檔到 TSV 格式的示例 C++ 轉換代碼。程序員可以使用此源代碼在任何 C++ 應用程序中批量將 TABDELIMITED 轉換為 TSV。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 C++ 將 TABDELIMITED 轉換為 TSV" h2="使用 C++ 庫的高性能 TABDELIMITED 到 TSV 轉換，無需安裝 Microsoft Excel、OpenOffice 或 Adobe Acrobat。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="TSV" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TABDELIMITED" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 將 TABDELIMITED 轉換為 TSV" %}}

 為了將 TABDELIMITED 轉換為 TSV，我們將使用
 [Aspose.Cells 代表 C++](https://products.aspose.com/cells/cpp) 
 API 是一個功能豐富、功能強大且易於使用的文檔操作和轉換 API C++ 平台。可以直接下載最新版本，直接打開
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 包管理器，搜索
 Aspose.Cells.Cpp 
 並安裝。您也可以從包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通過 C++ 將 TABDELIMITED 轉換為 TSV 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 開發人員只需幾行代碼即可輕鬆地將 TABDELIMITED 文件轉換為 TSV。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Factory::CreateIWorkbook 加載 TABDELIMITED 文件。1. 調用 Save() 方法。1. 使用 (TSV) 文件擴展名傳遞輸出文件路徑。1. TSV 文件將保存在指定路徑。1. 在兼容程序中打開 TSV 文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 C++ 轉換示例代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 C++ 運行時環境的兼容操作系統，適用於 Windows 32 位、Windows 64 位和 Linux 64 位。- Aspose.Cells 用於您的項目中引用的 C++ 個 DLL。
- Microsoft Windows 或具有 C++ 運行時環境的兼容操作系統，適用於 Windows 32 位、Windows 64 位和 Linux 64 位。- Aspose.Cells 用於您的項目中引用的 C++ 個 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TABDELIMITED 到 TSV C++ 轉換源代碼" offSpacer="" %}}

```cs
// 加載 TABDELIMITED。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tabdelimited");

// 以 TSV 格式保存。
wkb->Save(u"convertedFile.tsv", SaveFormat_Tsv);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TABDELIMITED 到 TSV 轉換現場演示" sectionDescription="[將 TABDELIMITED 轉換為 TSV](https://products.aspose.app/cells/conversion/tabdelimited-to-tsv) 立即訪問我們的現場演示網站。現場演示具有以下好處" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳您的 TABDELIMITED 文件，它將立即轉換為 TSV。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您將獲得下載鏈接。" >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel 文件操作庫" %}}

 Excel API 可用於創建、編輯、轉換 Microsoft Excel 格式並將其呈現為不同的格式。此外，它還可用於軟件應用程序中的綜合圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何軟件，例如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

製表符分隔值 (TSV) 文件格式表示用純文本格式的製表符分隔的數據。該文件格式類似於 CSV，用於以結構化方式組織數據，以便在不同應用程序之間導入和導出。該格式主要用於電子表格應用程序和數據庫中的數據導入/導出和交換。 TSV 文件中的每條記錄都包含在單行文本文件中，其中每個字段值由製表符分隔。 TSV 文件格式的媒體類型是文本/製表符分隔值。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}