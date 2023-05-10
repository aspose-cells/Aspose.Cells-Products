---
title: 通過 C# 生成 Excel 文件
description: 使用 C# 代碼從模板表生成 Microsoft Excel 電子表格
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 基於 Excel 模板的文件創建 via .NET" h2="基於基於 .NET 的應用程序中的預定義模板生成 Excel 文件報告" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel 庫](/cells/zh-hant/net/)支持生成基於模板的 Excel 文件，用於批量報告生成。模板是預先設計的格式，用於創建相同模式的報告。 .NET 代碼創建了一個新的excel文件，與填充了數據的模板文件一樣。支持的文件格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="基於預先設計的 Excel 模板創建報告" %}}

使用 .NET Assembly API 可以很容易地自動化創建相同模式文件的過程。有不同的方法[導入數據](https://docs.aspose.com/cells/net/import-data-into-worksheet/#importing-data-from-json)並生成Excel文件。 API提供了[WorkbookDesigner 類](https://reference.aspose.com/cells/net/aspose.cells/workbookdesigner)代表設計師工作表。創建它的對象並用它來打開模板文件。設置數據源，可以是DataTable、Array、Json文件等。處理它以導入數據並以所需格式保存包含數據的文件。程序員可以通過下面列出的鏈接將數據組合成其他文件格式的報告。



{{% blocks/products/pf/feature-page-code h3="C# 生成 Excel 報告的代碼" %}}

{{< gist "aspose-com-gists" "5c193070f1b6acdc3eed001f52eadbc2" "generate-excel-reports.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Generate" afterslug="Reports" >}}
