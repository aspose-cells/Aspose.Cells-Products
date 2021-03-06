---
title: 通過 C++ 保護和鎖定 XLS 文檔 
weight: 8760
url: /zh-hant/cpp/protect/xls/ 
description: C++ 在 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 運行時環境中使用密碼鎖定 XLS 文件的示例代碼。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 C++ 加密 XLS 文件" h2="使用 .NET 庫對包括 XLS 格式的 Excel 電子表格進行密碼保護。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp/" installationsDocsLink="https://docs.aspose.com/cells/cpp/" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 保護 XLS 文件" %}}

 為了保護 XLS 文件，我們將使用
 [Aspose.Cells 代表 C++](https://products.aspose.com/cells/cpp) 
 API，它是一個功能豐富、功能強大且易於使用的文檔加密 API，適用於 C++ 平台。可以直接下載最新版本，直接打開
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 包管理器，搜索
 **Aspose.Cells.Cpp** 
 並安裝。您也可以從包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通過 C++ 保護 XLS 文件的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 使用 Aspose.Cells API 的文檔保護只需幾行代碼即可完成。

{{% /blocks/products/pf/agp/text %}}

1. 使用 IWorkbook 類加載 XLS 文件1. 將 Protect(..) 方法與 ProtectionType 和 Password 一起使用1. 通過 Save() 方法保存受保護的 XLS 文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ 支持所有主要平台和操作系統。請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 C++ 運行時環境的兼容操作系統，適用於 Windows 32 位、Windows 64 位和 Linux 64 位。- Aspose.Cells 用於您的項目中引用的 C++ 個 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="" %}}

```cs

// 源路徑。
StringPtr srcDir = new String("SourcePath\");

// 輸出路徑。
StringPtr outDir = new String("OutputPath\");

// 加載 XLS 文件
intrusive_ptr<IWorkbook> workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sourceFile.xls")));

// 通過指定保護類型來保護工作簿
workbook->Protect(ProtectionType::ProtectionType_All, new String("12345"));

// 保存 XLS 文件
workbook->Save(outDir->StringAppend(new String("output.xls")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="關於 Aspose.Cells 的 C++ API" %}}

 Aspose.Cells API 可用於創建、編輯、轉換 Microsoft Excel 格式並將其呈現為不同的格式。此外，它還可用於軟件應用程序中的綜合圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何軟件，如 Microsoft 或 OpenOffice。  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="保護 XLS 的免費應用程序" sectionDescription="查看我們的現場演示 [加密 XLS 文件](https://products.aspose.app/cells/protect/xls) 具有以下好處。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載或設置任何東西" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫或編譯代碼" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳 XLS 文件並點擊“解鎖”按鈕" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 從鏈接下載生成的 XLS 文件" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
帶有 XLS 擴展名的文件代表 Excel 二進製文件格式。此類文件可以由 Microsoft Excel 以及其他類似的電子表格程序（如 OpenOffice Calc 或 Apple Numbers）創建。 Excel 保存的文件稱為工作簿，其中每個工作簿可以有一個或多個工作表。數據在工作表中以表格形式存儲和顯示給用戶，可以跨越數值、文本數據、公式、外部數據連接、圖像和圖表。 Microsoft Excel 等應用程序可讓您將工作簿數據導出為多種不同格式，包括 PDF、CSV、XLSX、TXT、HTML、XPS 等。隨著 Microsoft Excel 2007 的發布，XLS 文件格式被更開放和結構化的格式 XLSX 所取代。最新版本仍然支持創建和讀取 XLS 文件，儘管 XLSX 是現在的首選。

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的保護文件" subTitle="使用 C++，可以保護其他文件，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/ods/" name="消耗臭氧層物質" description="OpenDocument 電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsb/" name="XLSB" description="二進制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsm/" name="XLSM" description="電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}