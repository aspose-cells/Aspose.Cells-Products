---
title: 透過 C++ 新增或刪除 Excel 檔案註釋
description: 使用 C++ 庫新增或刪除 Excel 和 OpenOffice 電子表格的資料註釋註釋。
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="透過 C++ 管理 Microsoft<sup>&reg;</sup> Excel 檔案註釋" h2="在基於 C++ 的應用程式中新增或刪除註釋或評論的簡單註釋。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/zh-hant/cpp/)透過新增、存取和刪除註釋，支援在儲存格層級管理註釋。 API提供[評論](https://reference.aspose.com/cells/cpp/aspose.cells/comment/)和[評論收藏](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/)也[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)用於處理各方面的意見。支援的 Excel 格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 檔案資料註釋" %}}
操作工作表中的註解 - MS Excel 中一張工作表的註解數量不受限制。人們可以根據應用程式的需要插入盡可能多的內容。插入評論的過程是，創建[練習冊](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)類別物件來載入現有文件並選擇要在其中新增註解的工作表。使用 getComments() 取得其所有評論。使用新增評論[新增(const char16_t* 單元格名稱)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/)方法。取得單元格索引並使用[設定註釋](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/)用於插入評論。此外，API可以刪除所有評論。其中幾個方法是[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/)清除設計器電子表格中的所有註解。而且，***刪除於***方法刪除指定索引處或具有指定名稱的元素。

{{% blocks/products/pf/feature-page-code h3="C++ 在 Excel 檔案中新增註解的程式碼" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
