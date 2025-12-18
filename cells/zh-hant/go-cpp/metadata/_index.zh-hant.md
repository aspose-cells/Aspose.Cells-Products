---
title: 透過 C++ 使用 Go 管理 Excel 檔案元數據
description: 使用 Go 和 C++ 庫查看、新增、編輯、刪除或提取 Excel 文件元數據
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="透過 Go 管理 MicrosoftExcel 文件元數據" h2="在 C++ 應用程式中檢視、插入、更新、刪除或提取自訂和內建的 Excel 文件屬性。" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Excel 中的元資料 - 如何檢視、插入和刪除 Excel 檔案元資料。[通過 C++ Excel 庫](/cells/zh-hant/go-cpp/)該庫透過支援內建/系統定義的屬性（例如作者姓名、標題、文件統計資訊等）來簡化操作，這些屬性有時用於檢查文件的最後修改或保存時間，以及以名稱/值對形式提供的自訂/使用者定義屬性。為了實現流程自動化，該程式庫還支援建立和維護大型元資料 Excel 檔案。[練習冊](https://reference.aspose.com/cells/go-cpp/workbook/)該類別可以透過路徑、串流或特定的檔案格式類型開啟工作簿。因此，它會使用適當的方法載入文件以進行後續處理。以下列出了一些可能性，開發人員可以根據應用程式的需求輕鬆增強程式碼。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="讀取和更新內建屬性" %}}

為了實現內建屬性的自動化，API 提供了[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)此方法傳回一個 DocumentProperties 集合，該集合表示電子表格的所有內建文件屬性。存取所有內建屬性後，可以使用對應的方法（例如 GetTitle()、GetSubject() 等）存取相關屬性。要更新屬性，API 提供了諸如 SetTitle、SetSubject、SetAuthor、SetComments 等方法。看詳情[內建文件屬性集合](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)實現所需功能。

{{% blocks/products/pf/feature-page-code h3="透過代碼 C++ 讀取系統定義屬性" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="透過代碼 C++ 更新內建屬性" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="查看和新增自訂屬性" %}}

對於處理自訂屬性，API 提供[工作簿::取得自訂文件屬性](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)此方法傳回電子表格的所有自訂文件屬性集合。首先，透過此方法存取自訂屬性後，開發人員可以使用相關方法新增屬性，例如 AddIDocumentProperty 和 AddLinkToContentProperty；同樣，可以使用 UpdateLinkedPropertyValue 和 UpdateLinkedRange 分別更新連結到內容和連結範圍的自訂文件屬性值。開發人員可以使用來自以下位置的相關方法：[自訂文件屬性集合](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="透過代碼 C++ 查看自訂屬性" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="使用代碼 C++ 在 Excel 檔案中新增元數據" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}