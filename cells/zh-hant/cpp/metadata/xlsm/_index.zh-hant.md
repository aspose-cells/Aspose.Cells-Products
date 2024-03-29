---
title: 透過 C++ 編輯或檢視 XLSM 文件元數據
weight: 1300
description: 用於在 C++ 運行時環境（適用於 Windows 32 位元、Windows 64 位元和 Linux 64 位元）上編輯或檢視 XLSM 檔案元資料的 C++ 範例程式碼。
keywords: [C++ Aspose.Cells., C++ view xlsm metadata., C++ add xlsm metadata., C++ insert xlsm metadata., C++ edit xlsm metadata., C++ remove xlsm metadata., C++ extract xlsm metadata., C++ modify xlsm metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="透過 C++ 提取 XLSM 元數據" h2="建立您自己的 C++ 應用程序，以使用伺服器端 API 新增、編輯、刪除或提取 XLSM 檔案中的元資料。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 取得 XLSM 元數據" %}}

為了提取 XLSM 元數據，我們將使用
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API 這是一個功能豐富、功能強大且易於使用的文檔元資料擷取API for C++平台。您可以直接下載最新版本，打開即可
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
套件管理器，搜尋
 **Aspose.Cells.Cpp** 
並安裝。您也可以從套件管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="透過 C++ 擷取 XLSM 元資料的步驟" %}}

{{% blocks/products/pf/agp/text %}}

存取 XLSM 文件中儲存的有用信息，包括 XLSM 文件的接收時間、處理時間、時間戳等。

{{% /blocks/products/pf/agp/text %}}

+ 使用 MetadataOptions 建立選項
使用 WorkbookMetadata 載入 XLSM 文件
透過 GetCustomDocumentProperties() 和 Add 新增屬性
儲存XLSM文檔

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for C++ 支援所有主要平台和作業系統。請確保您具備以下先決條件。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 或具有 C++ 運行時環境的相容作業系統，適用於 Windows 32 位元、Windows 64 位元和 Linux 64 位元。
- 在專案中加入對 Aspose.Cells for C++ DLL 的引用。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="提取 XLSM - C++ 的元數據" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

//Load the sample excel file
MetadataOptions options(MetadataType::Document_Properties);
WorkbookMetadata meta(u"c:\\book1.xlsm", options);
//Add a new custom property
meta.GetCustomDocumentProperties().Add(u"test", u"test");
//Save the output excel file
meta.Save(u"c:\\book2.xlsm"); 

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="關於 Aspose.Cells for C++ API" %}}

 Aspose.Cells API 可用於建立、編輯、轉換和渲染 Microsoft Excel 格式為不同的格式。此外，它還可用於軟體應用程式中的全面圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何像 Microsoft 或 OpenOffice 這樣的軟體。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="透過線上應用程式提取 XLSM 的元數據" sectionDescription="使用我們的檢視和編輯 XLSM 文件的元數據[現場演示](https://products.aspose.app/cells/metadata)具有以下好處。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="無需下載或設定任何東西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="無需編寫任何程式碼" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上傳您的 XLSM 檔案並編輯文件屬性" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="立即獲取結果文件的下載鏈接" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
副檔名為 XLSM 的檔案是一種支援巨集的電子表格檔案。從應用程式的角度來看，巨集是用於自動化流程的指令集。巨集用於記錄重複執行的步驟，並透過再次執行巨集來方便執行操作。巨集是使用 Visual Basic 編輯器在 Excel 工作簿中使用 Microsoft 的 Visual Basic for Applications (VBA) 進行程式設計的，並且可以直接從那裡執行/偵錯。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支援的元資料格式" subTitle="使用C++，人們還可以操作許多其他格式的元數據，包括" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/ods/" name="ODS" description="OpenDocument 電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xls/" name="XLS" description="Excel 二進位格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="二進位 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
