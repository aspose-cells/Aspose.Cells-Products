---
title: 透過 C# 將 XLS 轉換為位元組數組
weight: 7690
description: C# XLS 到位元組數組轉換的範例程式碼。使用此程式碼在 VB.NET、Asp.NET 或任何基於 .NET 的應用程式中將 Excel XLS 轉換為位元組數組。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="透過 C# 將 XLS 轉換為位元組數組" h2="本機和高效能 Microsoft Excel XLS 到位元組數組轉換，反之亦然，使用伺服器端 .NET API 進行電子表格資料處理。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

位元組數組有助於資料處理或儲存。您可以將 XLS 檔案轉換為位元組數組以及**位元組數組至 XLS**文件使用 C# 語言。為了將 XLS 轉換為位元組數組，我們將使用
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
API，使用 .NET 平台提供不同的文件操作和轉換功能。
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="如何透過 C# 將 XLS 轉換為位元組數組" %}}

{{% blocks/products/pf/agp/text %}}

開發人員只需幾行程式碼即可輕鬆載入 XLS 檔案並將其轉換為位元組數組，以便進行進一步的操作任務。

{{% /blocks/products/pf/agp/text %}}

1. 在類別檔案中包含命名空間
1. 使用工作簿載入輸入XLS文件
1. 初始化MemoryStream對象
1. 將流資料轉換為位元組數組
1. 根據您的要求處理數據

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

{{% blocks/products/pf/agp/text %}}

只需確保系統具有 Microsoft Windows 或與 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamar Visual Studio 平台相容的作業系統以及 Microsoft1

{{% /blocks/products/pf/agp/text %}}

- 從命令列安裝為<code>nuget install Aspose.Cells</code>或透過 Visual Studio 的套件管理器控制台<code>Install-Package Aspose.Cells</code>.
- 或者，從下列位置取得離線 MSI 安裝程式或 ZIP 檔案中的所有 DLL<a href="https://downloads.aspose.com/cells/net">下載</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此範例程式碼顯示 XLS 到位元組數組 C# 的轉換" offSpacer="" %}}

```cs
Workbook workbook = new Workbook("sourceFile.xls");

//Save the workbook in memory stream
MemoryStream ms = new MemoryStream();

workbook.Save(ms, SaveFormat.Xls);

//Read bytes from memory stream
byte[] byte_array = new byte[ms.Length];
ms.Read(byte_array, 0, byte_array.Length);

// Process the memory stream byte array data as of your requirement 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->
      
     {{% blocks/products/pf/agp/content h2="" %}}

Excel 電子表格程式庫能夠建立跨平台應用程序，能夠產生、修改、轉換、渲染和列印所有 Excel 檔案。 .NET Excel API不僅可以在電子表格格式之間進行轉換，還可以將Excel檔案（包括XLS）渲染為圖像、PDF、HTML、ODS等，從而使其成為交換行業標準的標準。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
副檔名為 XLS 的檔案代表 Excel 二進位檔案格式。此類文件可以由 Microsoft Excel 以及其他類似的電子表格程式（例如 OpenOffice Calc 或 Apple Numbers）建立。Excel 儲存的檔案稱為工作簿，其中每個工作簿可以有一個或多個工作表。資料以工作表中的表格格式儲存並顯示給用戶，可以涵蓋數值、文字資料、公式、外部資料連接、圖像和圖表。 Microsoft Excel 等應用程式可讓您將工作簿資料匯出為多種不同的格式，包括 PDF、CSV、XLSX、TXT、HTML、XPS 等。隨著 Microsoft Excel 2007 的發布，XLS 文件格式被更開放和結構化的格式 XLSX 所取代。最新版本仍然支援創建和讀取 XLS 文件，儘管 XLSX 是現在使用的首選。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

           {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支援的轉換" subTitle="您也可以將其他文件格式轉換為位元組數組，反之亦然，包括下面列出的幾種。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-byte-array/" name="XLS 轉字節數組" description="Microsoft Excel 電子表格（舊版）" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-byte-array/" name="XLSX 轉字節數組" description="開啟 XML 工作簿" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsb-to-byte-array/" name="XLSB 轉字節數組" description="Excel 二進位工作簿" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsm-to-byte-array/" name="XLSM 轉字節數組" description="啟用巨集的電子表格" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlt-to-byte-array/" name="XLT 轉字節數組" description="Excel 97 - 2003 模板" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltx-to-byte-array/" name="XLTX 轉字節數組" description="Excel模板" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltm-to-byte-array/" name="XLTM 轉字節數組" description="Excel 巨集啟用模板" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/csv-to-byte-array/" name="CSV 轉字節數組" description="逗號分隔值" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/tsv-to-byte-array/" name="TSV 轉字節數組" description="製表符分隔值" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/ods-to-byte-array/" name="ODS 轉字節數組" description="開放文件電子表格" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-pdf/" name="XLS 轉 PDF" description="便攜式文件格式" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-html/" name="XLS 轉 HTML" description="超文本標記語言" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-pdf/" name="XLSX 轉 XPS" description="Microsoft Excel OOXML Excel 文件" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-html/" name="XLSX 轉 HTML" description="OOXML Excel 文件" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-svg/" name="XLSX 轉 SVG" description="可縮放向量圖形" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-jpeg/" name="XLS 轉 JPEG" description="JPEG 圖片" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
