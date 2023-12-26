---
title: 將 Excel 電子表格拆分為 Java 中的工作表
description: Java 原始程式碼，說明如何使用 Java Excel 庫將 Microsoft Excel 文件拆分為多個文檔
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel 檔案分割 via Java" h2="在基於 Java 的應用程式中將 Excel 電子表格拆分為工作表" >}}
{{% blocks/products/pf/feature-page-summary %}}
有多種場景，當需要拆分 Excel 文件（例如包含學生資料的電子表格）並為每個學生分配單個工作表時。並且需要將每個學生的工作表拆分為一個單獨的文件。要自動化它 via Java 應用程序，[Java Excel API](/cells/zh-hant/java/)是否可以依工作表拆分 Excel 文件。支援的格式包括 XLS、XLSX、XLSB、XLSM、ODS。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 文檔拆分為多個文件" %}}

將 Excel 檔案拆分為工作表的最簡單方法是存取所有工作表，遍歷每個工作表並以所需格式一張一張儲存。為了載入工作表，API 提供[練習冊](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)班級。[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count)方法取得總頁數。迭代每個工作表並使用[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get)用於存取特定工作表。使用下列命令將選取的工作表資料移至新建立的 Workbook 類別物件中[複製方法](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)）。最後保存成需要的格式。

{{% blocks/products/pf/feature-page-code h3="Java 分割Excel檔案的程式碼" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="將 Excel 工作表分割為多個窗格" %}}

API也提供了將Excel工作表分割為不同窗格的功能。過程是，使用 Workbook 類別載入檔案。透過提供其索引來選擇第一個工作表或任何所需的工作表。呼叫具有相關單元格索引作為參數的setActiveCell。最後透過呼叫 split() 方法將工作表視窗分割為不同的窗格。

{{% blocks/products/pf/feature-page-code h3="Java 將 Excel 工作表分割為窗格視圖的程式碼" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
