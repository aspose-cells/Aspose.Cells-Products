---
title: 透過 C++ 管理 Excel 文件元數據
description: 使用 C++ 庫檢視、新增、編輯、刪除或擷取 Excel 檔案元數據
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="透過 C++ 管理 Microsoft<sup>&reg;</sup> Excel 文件元數據" h2="在 C++ 應用程式中檢視、插入、更新、刪除或提取自訂和內建 Excel 文件屬性。" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Excel 中的元資料 - 如何檢視、插入和刪除 Excel 檔案元資料。[C++ Excel 庫](/cells/zh-hant/cpp/)透過支援內建/系統定義的屬性（例如作者姓名、標題、文件統計資料等），有時需要檢查最後文件何時被修改或儲存以及自訂/使用者定義的屬性，以簡單的方式提供便利名稱/值對。為了自動化該過程，庫支援建立和維護大型元資料 Excel 檔案。[練習冊](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class 會依路徑、串流和特殊 FileFormatType 開啟工作簿。因此，請使用適當的方法載入文件以進行進一步處理。下面列出的可能性很少，開發人員可以根據應用程式需求輕鬆增強他們的程式碼。
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="讀取和更新內建屬性" %}}

為了自動化內建屬性，API 提供了[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/)傳回 DocumentProperties 集合的方法，該集合表示電子表格的所有內建文件屬性。存取所有內建屬性後，使用相關方法如 GetTitle()、GetSubject() 等存取相關屬性。為了更新屬性，API 提供了 SetTitle、SetSubject、SetAuthor、SetComments 等方法。檢視[內建文件屬性集合](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/)用於所需的功能。

{{% blocks/products/pf/feature-page-code h3="C++ 讀取系統定義屬性的程式碼" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ 更新內建屬性的程式碼" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="查看和新增自訂屬性" %}}

為了處理自訂屬性，API 提供[工作簿::取得自訂文件屬性](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/)傳回電子表格的所有自訂文件屬性集合。首先透過此方法存取自訂屬性，開發人員可以使用相關方法新增屬性，如 AddIDocumentProperty、AddLinkToContentProperty 以及類似地使用 UpdateLinkedPropertyValue、UpdateLinkedRange 來更新分別連結到內容和連結範圍的自訂文件屬性值。開發者可以使用相關方法[自訂文件屬性的集合](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ 查看自訂屬性的程式碼" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ 在 Excel 檔案中新增元資料的程式碼" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
