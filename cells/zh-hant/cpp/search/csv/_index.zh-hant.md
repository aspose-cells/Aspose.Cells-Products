---
title: 在不通過 C++ 打開的情況下搜索 CSV 文檔 
weight: 5540
url: /zh-hant/cpp/search/csv/ 
description: C++ 示例代碼，用於在 CSV 文件中搜索具有模式的單詞，C++ Windows 32 位、Windows 64 位和 Linux 64 位運行時環境。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="在 C++ 中搜索 CSV 格式" h2="使用用於 C++ API 的服務器端 Aspose.Cells 進行本機和高性能 CSV 文檔搜索，無需使用 Microsoft 或 Adobe PDF 等任何軟件。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 搜索 CSV 文件" %}}

 為了搜索 CSV 文件，我們將使用
 [Aspose.Cells 代表 C++](https://products.aspose.com/cells/cpp) 
 API 是一個功能豐富、功能強大且易於使用的文檔搜索 API C++ 平台。可以直接下載最新版本，直接打開
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 包管理器，搜索
 **Aspose.Cells.Cpp** 
 並安裝。您也可以從包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="在 C++ 中搜索 CSV 文件的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 使用 Aspose.Cells API 的基本文檔搜索只需幾行代碼即可完成。

{{% /blocks/products/pf/agp/text %}}

+ 通過實例化 IWorkbook 類來加載 CSV 文件。
實例化 IReplaceOptions 類。
+ 設置所需的模式，如 SetCaseSensitive(bool value)、SetMatchEntireCellContents(bool value)。
+ 使用 IWorkbook->Replace(..) 方法和相關選項。
+ 使用 IWorkbook->Save(.) 方法保存 CSV 文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ 支持所有主要平台和操作系統。請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 C++ 運行時環境的兼容操作系統，適用於 Windows 32 位、Windows 64 位和 Linux 64 位。- Aspose.Cells 用於您的項目中引用的 C++ 個 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="搜索 CSV 文件 - C++" offSpacer="" %}}

```cs

// 源目錄路徑。
StringPtr srcDir = new String("SourcePath\\");

// 輸出目錄路徑。
StringPtr outDir = new String("OutputPath\\");

// 加載 CSV 文件
intrusive_ptr<IWorkbook>  wkb = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sourceFile.csv")));

// 創建 IReplaceOptions 類的實例
intrusive_ptr<IReplaceOptions> replaceOptions = Factory::CreateIReplaceOptions();

// 設置區分大小寫選項
replaceOptions->SetCaseSensitive(false);

// 設置文本匹配選項
replaceOptions->SetMatchEntireCellContents(false);

// 替換文本
wkb->Replace(new String("Text to find"), new String("Text replacement"), replaceOptions);

// 另存為 CSV 文件
wkb->Save(outDir->StringAppend(new String("outputFile.csv")));  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="關於 Aspose.Cells 的 C++ API" %}}

 Aspose.Cells API 可用於創建、編輯、轉換 Microsoft Excel 格式並將其呈現為不同的格式。此外，它還可用於軟件應用程序中的綜合圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何軟件，如 Microsoft 或 OpenOffice。  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="在線 CSV 搜索現場演示" sectionDescription="立即訪問我們的 CSV 文檔中搜索文本、單詞、短語 [現場演示網站](https://products.aspose.app/cells/search).現場演示有以下好處" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上傳您的 CSV 文件。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 搜索結果立即出現。" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV " readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}
具有 CSV（逗號分隔值）擴展名的文件表示純文本文件，其中包含具有逗號分隔值的數據記錄。 CSV 文件中的每一行都是文件中包含的記錄集中的一條新記錄。當數據從一個存儲系統傳輸到另一個存儲系統時，會生成此類文件。由於所有應用程序都可以識別以逗號分隔的記錄，因此將此類數據文件導入數據庫非常方便。幾乎所有電子表格應用程序（例如 Microsoft Excel 或 OpenOffice Calc）都可以輕鬆導入 CSV。從這些文件導入的數據排列在電子表格的單元格中，以便向用戶表示。 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的搜索文檔" subTitle="使用 C++，還可以搜索其他文件，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="消耗臭氧層物質" description="OpenDocument 電子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="矽通孔" description="製表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="文本文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Excel 二進制格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="二進制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="電子表格文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}