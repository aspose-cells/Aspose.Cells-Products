---
title: 通過 Java 創建 Excel 文件
url: /zh-hant/java/assembly/
description: 使用 Java 電子表格庫從模板工作表生成 Microsoft Excel 電子表格
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> 通過 Java 創建基於 Excel 模板的報告" h2="根據基於 Java 的應用程序中的預定義模板生成批量 Excel 文件報告。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel 庫](/cells/java/) 支持生成基於模板的 Excel 文件以生成批量報告。大多數情況下都需要它，例如創建費用挑戰、結果卡和患者記錄等。模板是預定義的模式。 Java 下面的代碼會生成與已填充數據的模板文檔相同的批量 excel 文件。支持的文件格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="基於預先設計的 Excel 模板創建報告" %}}

使用 JavaAssembly API，開發人員可以通過包含以下代碼片段輕鬆編寫批量報告生成代碼。 API 提供 [導入數據](https://docs.aspose.com/cells/java/import-and-export-data/) 來自不同來源的功能並根據該數據創建 Excel 文檔。對於基於模板的模式，API 提供了一個 [WorkbookDesigner 類](https://apireference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner) 表示設計器工作表。過程是，創建它的對象並用它來打開模板文件。設置數據源，可以是 Array、DataTable、Json 等。處理它以導入數據並以所需格式保存文件。程序員可以將數據組裝成其他文件格式的報告，包括 XLS、XLSX、XLSB、XLSM、ODS，如下所列鏈接。



{{% blocks/products/pf/feature-page-code h3="Java 創建 Excel 報告的代碼" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}