---
title: Excel 文件註釋通過 C++
description: 使用 C++ 庫添加或刪除 Excel 和 OpenOffice 電子表格的數據註釋註釋。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C++ 管理 Microsoft<sup>&reg;</sup> Excel 文件註釋" h2="在基於 C++ 的應用程序中添加或刪除註釋或評論的簡單註釋。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/zh-hant/cpp/)通過添加、訪問和刪除註釋，支持在單元格級別管理註釋。 API提供[我的評論](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment)和[評論集](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection)也[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)用於處理各方面的意見。支持的 Excel 格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 文件數據註釋" %}}
操作工作表中的註釋 - MS Excel 中一張工作表的註釋數量不受限制。人們可以根據應用程序的需要插入盡可能多的內容。插入評論的過程是，創建[工作簿](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)類對象來加載現有文件並選擇要在其中添加註釋的工作表。使用 getComments() 獲取其所有評論。使用添加評論[添加](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)（侵入式_ptr< Aspose::Cells::Systems::String >單元格名稱）方法。獲取單元格索引並使用[設置註釋](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580)用於插入評論。此外，API可以刪除所有評論。其中幾個方法是[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3)清除設計器電子表格中的所有註釋。而且，[刪除於](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)（侵入式_ptr< Aspose::Cells::Systems::String > name) 方法刪除指定索引處或具有指定名稱的元素。

{{% blocks/products/pf/feature-page-code h3="C++ 在 Excel 文件中添加註釋的代碼" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
