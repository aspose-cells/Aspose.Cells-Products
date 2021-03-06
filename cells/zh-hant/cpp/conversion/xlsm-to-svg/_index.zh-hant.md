---
title: 通過 C++ 應用程序將 XLSM 轉換為 SVG 
url: /zh-hant/cpp/conversion/xlsm-to-svg/ 
description: 將 XLSM 文檔轉換為 SVG 格式的示例 C++。程序員可以使用此源代碼在任何 C++ 應用程序中進行批量 XLSM 到 SVG 的轉換。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 C++ 將 XLSM 轉換為 SVG" h2="使用 C++ 庫的高性能 XLSM 到 SVG 轉換，無需安裝 Microsoft Excel、OpenOffice 或 Adobe Acrobat。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 將 XLSM 轉換為 SVG" %}}

 為了將 XLSM 轉換為 SVG，我們將使用
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

{{% blocks/products/pf/agp/feature-section-col title="通過 C++ 將 XLSM 轉換為 SVG 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 開發人員只需幾行代碼即可輕鬆地將 XLSM 文件轉換為 SVG。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Factory::CreateIWorkbook 加載 XLSM 文件。1. 選擇第一個工作表。1. 設置 (SVG) 選項。1. 遍歷工作表的每一頁並進行渲染。1. 在兼容程序中打開 SVG 文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 C++ 轉換示例代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 C++ 運行時環境的兼容操作系統，適用於 Windows 32 位、Windows 64 位和 Linux 64 位。- Aspose.Cells 用於您的項目中引用的 C++ 個 DLL。
- Microsoft Windows 或具有 C++ 運行時環境的兼容操作系統，適用於 Windows 32 位、Windows 64 位和 Linux 64 位。- Aspose.Cells 用於您的項目中引用的 C++ 個 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSM 到 SVG C++ 轉換源代碼" offSpacer="" %}}

```cs
// 輸出目錄路徑。
StringPtr outDir = new String("OutputDirectoryPath");

// 加載 XLSM。
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.xlsm");

// 訪問第一個工作表。
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// 創建圖像或打印選項對象。
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// 指定圖像格式。
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetSvg());

// 指定水平和垂直分辨率
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// 根據指定的圖像或打印選項渲染工作表。
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// 獲取頁數。
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// 為字符串連接創建字符串構建器對象。
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// 將每個頁面一張一張地渲染為 svg 圖像。
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageSVG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".svg"));

	// 獲取輸出圖像路徑。
	StringPtr outputSVG = sb->ToString();

	// 將工作表轉換為 svg 圖像。
	sr->ToImage(i, outputSVG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLSM 到 SVG 轉換現場演示" sectionDescription="[將 XLSM 轉換為 SVG](https://products.aspose.app/cells/conversion/xlsm-to-svg) 立即訪問我們的現場演示網站。現場演示具有以下好處" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳您的 XLSM 文件，它就會立即轉換為 SVG。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您將獲得下載鏈接。" >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel 文件操作庫" %}}

 Excel API 可用於創建、編輯、轉換 Microsoft Excel 格式並將其呈現為不同的格式。此外，它還可用於軟件應用程序中的綜合圖表、可擴展報告和可靠計算。 Aspose.Cells 是一個獨立的 API，它不需要任何軟件，例如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}

帶有 XLSM 擴展名的文件是一種支持宏的電子表格文件。從應用程序的角度來看，宏是一組用於自動化流程的指令。宏用於記錄重複執行的步驟，並有助於通過再次運行宏來執行操作。使用 Visual Basic 編輯器從 Excel 工作簿中使用 Microsoft 的 Visual Basic for Applications (VBA) 對宏進行編程，並且可以直接從那裡運行/調試。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/page-description-language/svg/" >}}

SVG 文件是可縮放矢量圖形文件，它使用基於 XML 的文本格式來描述圖像的外觀。 Scalable 這個詞指的是 SVG 可以縮放到不同的大小而不會損失任何質量。此類文件的基於文本的描述使它們獨立於分辨率。它是用於構建網站和打印圖形以實現可擴展性的最常用格式之一。該格式只能用於二維圖形。 SVG 文件可以在幾乎所有現代瀏覽器中查看/打開，包括 Chrome、Internet Explorer、Firefox 和 Safari。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}