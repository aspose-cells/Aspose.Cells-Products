---
title: 通過 C# 創建 ODS (Openoffice / Lbreoffice) 文件 
url: /zh-hant/net/create-ods/ 
description: C# 用於生成 ODS 文檔的示例代碼。使用此代碼在 VB.NET、Asp.NET 或任何基於 .NET 的應用程序中創建 ODS (Openoffice / Lbreoffice) 文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 C# 創建 ODS 文檔" h2="使用服務器端 .NET API 以編程方式創建本機和高性能 ODS（Openoffice / Lbreoffice）電子表格。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 在運行的應用程序中動態生成 ODS（Openoffice / Lbreoffice）文件很容易。為了在不需要 MS Office 的情況下從頭開始創建 ODS 文檔，我們將使用
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API，它為使用 .NET 平台的電子表格創建、操作和轉換提供不同的功能。開發人員可以輕鬆增強用於編寫數據、生成圖表或圖形以及在電子表格中創建表格的代碼。
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="如何通過 C# 創建 ODS" %}}

{{% blocks/products/pf/agp/text %}}

 開發人員只需幾行代碼即可在運行不同的報告應用程序中輕鬆創建、加載、修改和轉換 ODS（Openoffice / Lbreoffice）電子表格以進行數據處理。

{{% /blocks/products/pf/agp/text %}}

1. 在類文件中包含命名空間1. 創建工作簿類實例。1. 訪問工作簿的第一個工作表。1. 獲取工作表的所需單元格並將值輸入到單元格中。1. 使用 Save 方法將工作簿保存為 ODS 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 只需確保該系統具有 Microsoft Windows 或與 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台以及 Microsoft Visual Studio 等開發環境兼容的操作系統。 

{{% /blocks/products/pf/agp/text %}}

- 從命令行安裝為 <code>nuget install Aspose.Cells</code> 或通過 Visual Studio 的包管理器控制台 <code>Install-Package Aspose.Cells</code>.- 或者，從以下位置獲取離線 MSI 安裝程序或 ZIP 文件中的所有 DLL <a href="https://downloads.aspose.com/cells/net">下載</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="以下源代碼顯示瞭如何使用 C# 創建 ODS (Openoffice / Lbreoffice) 文件。" offSpacer="" %}}

```cs

// 創建工作簿類實例。
Workbook wkb = new Workbook();

// 訪問工作簿的第一個工作表。
Worksheet sht = wkb.Worksheets[0];

// 獲取工作表的所需單元格。
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// 將值輸入到單元格中。
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// 將工作簿另存為 .ods 文件。
wkb.Save("created_one.ods");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 一個 Excel 電子表格編程庫，能夠構建跨平台應用程序，能夠生成、修改、轉換、呈現和打印 ODS（Openoffice / Lbreoffice）文件。 .NETExcelAPI 不僅可以在電子表格格式之間進行轉換，還可以將 Excel 文件呈現為圖像、PDF、HTML、ODS 等，從而使其成為以行業標準格式交換文檔的完美選擇。

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
帶有 .ods 擴展名的文件代表用戶可編輯的 OpenDocument 電子表格文檔格式。數據在 ODF 文件中存儲為行和列。它是基於 XML 的格式，是開放文檔格式 (ODF) 系列中的幾個子類型之一。該格式被指定為 OASIS 發布和維護的 ODF 1.2 規範的一部分。 Windows 和其他操作系統上的許多應用程序可以打開 ODS 文件進行編輯和操作，包括 Microsoft Excel、NeoOffice 和 LibreOffice。 ODS 文件還可以通過不同的應用程序轉換為其他電子表格格式以及 XLS、XLSX 等。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的電子表格生成" subTitle="您還可以創建其他 Microsoft Excel 格式，包括下面列出的幾種格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xls/" name="XLS" description="Microsoft Excel 電子表格（舊版）" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsx/" name="XLSX" description="打開 XML 工作簿" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsb/" name="XLSB" description="Excel 二進制工作簿" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsm/" name="XLSM" description="啟用宏的電子表格" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlt/" name="XLT" description="Excel 97 - 2003 模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltx/" name="XLTX" description="Excel 模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltm/" name="XLTM" description="Excel 啟用宏的模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-csv/" name="CSV" description="逗號分隔值" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-tsv/" name="矽通孔" description="製表符分隔值" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-ods/" name="消耗臭氧層物質" description="OpenDocument 電子表格" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
