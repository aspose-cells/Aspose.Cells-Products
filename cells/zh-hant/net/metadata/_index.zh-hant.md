---
title: 通過 .NET C# 管理 Excel 文件元數據
url: /zh-hant/net/metadata/
description: 只需幾行 C# 代碼即可查看、添加、編輯、刪除或提取 Excel 文件元數據
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 .NET 管理 Microsoft<sup>&reg;</sup> Excel 文件元數據" h2="使用服務器端 .NET API 查看、添加、更新、刪除或提取內置和自定義 Excel 文件屬性。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NETExcel API](/cells/net/) 支持標題、作者姓名、文檔統計等系統定義（內置）屬性以及名稱-值對形式的用戶定義（自定義）屬性的管理。有 [工作簿類](https://reference.aspose.com/cells/net/aspose.cells/workbook) 加載文件，以及 [工作表集合](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) 處理工作表的集合以及 [工作表類](https://reference.aspose.com/cells/net/aspose.cells/worksheet) 用於表示單個工作表。連同這些類，BuiltInDocumentProperties，CustomDocumentProperties 使元數據管理的過程變得簡單。 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="管理內置屬性" %}}

為了管理系統定義的屬性，API 提供 [內置文檔屬性](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties), 程序員可以輕鬆訪問內置屬性並更新其值。根據應用程序的要求，開發人員可以使用索引或屬性名稱 [文檔屬性集合](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# 管理內置屬性的代碼" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="管理自定義屬性" %}}

為了管理用戶定義的屬性，API 提供 [自定義文檔屬性](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties)，開發人員可以輕鬆訪問已添加的屬性以及添加新屬性。為了添加自定義屬性， [添加方法](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) 的 [自定義文檔屬性集合](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) 類添加屬性並返回新屬性的引用作為 [Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) 目的。 DocumentProperty 類用於檢索文檔屬性的名稱、值和類型，如 [文檔屬性名稱](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [文檔屬性.值](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [文檔屬性類型](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) 返回其中之一 [財產類型](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) 枚舉值。 
 
{{% blocks/products/pf/feature-page-code h3="C# 在 Excel 文件中添加元數據的代碼" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# 刪除 Excel 文件中的自定義屬性的代碼" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
