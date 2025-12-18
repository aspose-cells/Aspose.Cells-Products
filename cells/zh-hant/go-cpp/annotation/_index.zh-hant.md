---
title: 使用 Go 語言透過 C++ 新增或刪除 Excel 檔案註釋
description: 使用 Go 透過 C++ 庫新增或刪除 Excel 和 OpenOffice 電子表格的資料註釋。
keywords: [Go via C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="使用 C++ 透過 Go 管理 MicrosoftExcel 檔案註釋" h2="透過基於 C++ 的應用程式在 Go 中新增或刪除用於註釋或評論的簡單筆記。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[請聯絡 C++ Excel API](/cells/zh-hant/go-cpp/)提供對單元格層級註釋管理的支持，包括新增、存取和刪除註釋。 API 提供[評論](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/)和[評論集](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/)也[GetComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/getcomments/)用於處理各個方面的評論。支援的 Excel 格式包括 ODS、XLS、XLSX、XLSB 和 XLSM。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel 檔案資料註釋" %}}
操作工作表中的批註 - 在 MS Excel 中，工作表中的批註數量沒有限制。您可以根據實際應用需要插入任意數量的批註。插入批註的流程如下：建立批註[練習冊](https://reference.aspose.com/cells/go-cpp/aspose.cells/workbook/)使用類別物件載入現有文件並選擇要新增註解的工作表。使用 `getComments()` 取得所有註解。使用 `addcomments()` 新增註解。[添加(const char16_t* cellName)](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/add/)方法。取得單元格索引並使用[SetNote](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/setnote/)用於插入評論。此外，API 可以刪除所有評論。以下是一些方法：[ClearComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/clearcomments/)清除設計表格中的所有註解。此外，***移除***刪除指定索引或指定名稱的元素的方法。

{{% blocks/products/pf/feature-page-code h3="使用程式碼 C++ 在 Excel 檔案中新增註釋" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-comment-in-excel.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
