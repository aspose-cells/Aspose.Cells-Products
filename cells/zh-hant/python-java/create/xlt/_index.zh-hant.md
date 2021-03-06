---
title: 通過 Python 創建 MS Excel XLT 文件 
url: /zh-hant/python-java/create-xlt/ 
description: Python 用於生成 XLT 文檔的示例代碼。使用此代碼在 Python 應用程序中創建 MS Excel XLT 文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 Python 創建 XLT 文檔" h2="使用 Python API 以編程方式創建本機和高性能 MS Excel XLT 電子表格。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/python" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 在運行的應用程序中動態生成 MS Excel XLT 文件很容易。為了在不需要 MS Office 的情況下從頭開始創建 XLT 文檔，我們將使用
 [Aspose.Cells 代表 Python](https://pypi.org/project/aspose-cells) 
 API，它為使用 Python 平台的電子表格創建、操作和轉換提供不同的功能。開發人員可以輕鬆增強用於編寫數據、生成圖表或圖形以及在電子表格中創建表格的代碼。
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="如何通過 Python 創建 XLT" %}}

{{% blocks/products/pf/agp/text %}}

 開發人員只需幾行代碼即可在運行不同的報告應用程序中輕鬆創建、加載、修改和轉換 MS Excel XLT 電子表格以進行數據處理。

{{% /blocks/products/pf/agp/text %}}

1. 在您的代碼文件中導入 asposecells。1. 創建工作簿類實例。1. 訪問工作簿的第一個工作表。1. 獲取工作表的所需單元格並將值輸入到單元格中。1. 使用 Save 方法將工作簿保存為 XLT 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 Python 通過 Java 的 Aspose.Cells 是獨立於平台的 API 並且可以在任何平台（Windows、Linux 和 MacOS）上使用，只需確保系統具有 Java 1.8 或更高版本， [Python](https://www.python.org/downloads/) 3.5 或更高。 

{{% /blocks/products/pf/agp/text %}}

- 安裝 Java 並將其添加到 PATH 環境變量，例如： <code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.- 通過 Java 為 Python 安裝 Aspose.Cells <a href="https://pypi.org/project/aspose-cells/">皮皮</a>，使用命令為： <code>$ pip install aspose-cells</code>.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="以下源代碼顯示瞭如何使用 Python 創建 MS Excel XLT 文件。" offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

// 創建工作簿對象。
workbook = Workbook(FileFormatType.XLT)

// 訪問工作簿的第一個工作表。
worksheet = workbook.getWorksheets().get(0)

// 獲取工作表的所需單元格並將值輸入到單元格中。
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// 將工作簿另存為 XLT 文件。
workbook.save("output.xlt")

jpype.shutdownJVM()


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 一個 Excel 電子表格編程庫，能夠構建跨平台應用程序，能夠生成、修改、轉換、呈現和打印 MS Excel XLT 文件。 Python API 不僅可以在電子表格格式之間進行轉換，還可以將 Excel 文件呈現為圖像、PDF、HTML、ODS 等，從而使其成為以行業標準格式交換文檔的完美選擇。

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
帶有 .xlt 擴展名的文件是使用 Microsoft Excel 創建的模板文件，這是一個電子表格應用程序，是 Microsoft Office 套件的一部分。 Microsoft Office 97-2003 支持創建新的 XLT 文件以及打開這些文件。最新版本的 Excel 仍然能夠打開這種舊格式的模板文件。這樣的模板文件用於快速創建具有默認數據和設置（例如頁面格式、字體大小、邊距、圖表等）的新 Excel 文件，這些文件可以進一步保存為新的 .xls 文件。
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}   

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的電子表格生成" subTitle="您還可以創建其他 Microsoft Excel 格式，包括下面列出的幾種格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xls/" name="XLS" description="Microsoft Excel 電子表格（舊版）" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsx/" name="XLSX" description="打開 XML 工作簿" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsb/" name="XLSB" description="Excel 二進制工作簿" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsm/" name="XLSM" description="啟用宏的電子表格" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlt/" name="XLT" description="Excel 97 - 2003 模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltx/" name="XLTX" description="Excel 模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltm/" name="XLTM" description="Excel 啟用宏的模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-csv/" name="CSV" description="逗號分隔值" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-tsv/" name="矽通孔" description="製表符分隔值" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-ods/" name="消耗臭氧層物質" description="OpenDocument 電子表格" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
