---
title: 管理 Excel 檔案元資料 via .NET C#
description: 只需幾行 C# 程式碼即可查看、新增、編輯、刪除或提取 Excel 檔案元數據
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="管理 Microsoft<sup>&reg;</sup> Excel 檔案元資料 via .NET" h2="使用伺服器端 .NET API 檢視、新增、更新、刪除或擷取內建和自訂 Excel 檔案屬性。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/zh-hant/net/)支援管理系統定義（內建）屬性，如標題、作者姓名、文件統計等，以及使用者定義（自訂）屬性（以名稱-值對的形式）。有[作業本類](https://reference.aspose.com/cells/net/aspose.cells/workbook)載入文件，以及[工作表集合](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection)處理工作表的收集以及[工作表類](https://reference.aspose.com/cells/net/aspose.cells/worksheet)用於表示單一工作表。與這些類別一起，BuiltInDocumentProperties、CustomDocumentProperties 讓元資料管理流程變得簡單。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="管理內建屬性" %}}

為了管理系統定義的屬性，API 提供[內建文件屬性](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties)，程式設計師可以輕鬆存取內建屬性並更新其值。根據應用程式的要求，開發人員可以使用索引或屬性名稱[文檔屬性集合](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# 管理內建屬性的程式碼" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="管理自訂屬性" %}}

為了管理使用者定義的屬性，API 提供[自訂文件屬性](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties)，開發人員可以輕鬆存取已新增的屬性以及新增屬性。為了新增自訂屬性，[添加方法](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index)的[自訂文件屬性集合](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection)類別添加屬性並傳回新屬性的引用作為[屬性.文檔屬性](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty)目的。 DocumentProperty 類別用於擷取文件屬性的名稱、值和類型，如下所示[文檔屬性.名稱](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [文檔屬性.值](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [文檔屬性.類型](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type)返回其中之一[財產種類](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype)枚舉值。
 
{{% blocks/products/pf/feature-page-code h3="C# 在 Excel 檔案中新增元資料的程式碼" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# 刪除 Excel 檔案中的自訂屬性的程式碼" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
