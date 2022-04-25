---
title: 通過 C# 生成 Excel 文件
url: /zh-hant/net/assembly/
description: 使用 C# 代碼從模板表生成 Microsoft Excel 電子表格
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通過 .NET 創建基於 Excel 模板的文件" h2="根據基於 .NET 的應用程序中的預定義模板生成 Excel 文件報告" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 庫](/cells/net/) 支持生成基於模板的 Excel 文件以生成批量報告。模板是預先設計的格式，用於創建相同的模式報告。 .NET 代碼創建與已填充數據的模板文檔相同的新 excel 文件。支持的文件格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="基於預先設計的 Excel 模板創建報告" %}}

使用 .NETAssembly API 可以輕鬆自動創建相同的模式文件。有不同的方法可以 [導入數據](https://docs.aspose.com/cells/net/import-data-into-worksheet/#importing-data-from-json) 並生成 Excel 文件。 API 提供了一個 [WorkbookDesigner 類](https://apireference.aspose.com/cells/net/aspose.cells/workbookdesigner) 表示設計器工作表。創建它的對象並使用它來打開模板文件。設置數據源，可以是DataTable，Array，Json文件等。處理它以導入數據並以所需格式保存數據文件。程序員可以按照下面列出的鏈接將數據組裝成其他文件格式的報告。



{{% blocks/products/pf/feature-page-code h3="C# 生成 Excel 報告的代碼" %}}

{{< gist "aspose-com-gists" "5c193070f1b6acdc3eed001f52eadbc2" "generate-excel-reports.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Generate" afterslug="Reports" >}}