---
title: 通過 C++ 管理 Excel 文件元數據
url: /zh-hant/cpp/metadata/
description: 使用 C++ 庫查看、添加、編輯、刪除或提取 Excel 文件元數據
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 C++ 管理 Microsoft<sup>&reg;</sup> Excel 文檔元數據" h2="在 C++ 應用程序中查看、插入、更新、刪除或提取自定義和內置 Excel 文檔屬性。" >}}
{{% blocks/products/pf/feature-page-summary %}}
Excel 中的元數據 - 如何查看、插入和刪除 Excel 文件元數據。 [C++ Excel 庫](/cells/cpp/) faclitates 通過支持內置/系統定義的屬性（例如作者姓名、標題、文檔統計信息等）以一種簡單的方式來檢查文件何時被修改或保存以及自定義/用戶定義的屬性形式名稱/值對。為了使過程自動化，庫支持創建和維護大型元數據 Excel 文件。 [CreateIWorkbook 方法](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) 的 [工廠類](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) 按路徑、流和特殊 FileFormatType 打開工作簿。因此，使用適當的方法加載文件以進行進一步處理。下面列出的可能性很少，開發人員可以根據應用程序需求輕鬆地增強他們的代碼。 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="讀取和更新內置屬性" %}}

為了自動化內置屬性，API 提供 [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) 返回一個 DocumentProperties 集合的方法，該集合表示電子表格的所有內置文檔屬性。訪問所有內置屬性後，使用 GetTitle()、GetSubject() 等相關方法訪問相關屬性。要更新屬性，API 提供了 SetTitle、SetSubject、SetAuthor、SetComments 等方法。查看 [內置文檔屬性集合](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) 所需的功能。

{{% blocks/products/pf/feature-page-code h3="C++ 讀取系統定義屬性的代碼" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ 更新內置屬性的代碼" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="查看和添加自定義屬性" %}}

為了處理自定義屬性，API 提供 [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) 返回電子表格的所有自定義文檔屬性集合。首先通過此方法訪問自定義屬性，開發人員可以使用相關方法添加 AddIDocumentProperty、AddLinkToContentProperty 等屬性，同樣使用 UpdateLinkedPropertyValue、UpdateLinkedRange 更新分別鏈接到內容和鏈接範圍的自定義文檔屬性值。開發者可以使用相關方法 [自定義文檔屬性的集合](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ 查看自定義屬性的代碼" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ 在 Excel 文件中添加元數據的代碼" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}