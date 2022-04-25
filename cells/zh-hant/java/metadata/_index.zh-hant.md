---
title: 通過 Java 管理 Excel 文件元數據
url: /zh-hant/java/metadata/
description: 只需幾行 Java 代碼即可查看、添加、編輯、刪除或提取 Excel 文件元數據
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通過 Java 管理 Microsoft<sup>&reg;</sup> Excel 文件元數據" h2="使用服務器端 Java API 查看、添加、更新、刪除或提取自定義和內置 Excel 文件屬性。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[JavaExcel API](/cells/java/) 支持管理內置（系統定義）屬性，如標題、作者姓名、文檔統計等以及名稱/值對形式的自定義（用戶定義）屬性。有 [工作簿類](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) 加載文件，以及 [工作表集合](https://apireference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) 處理工作表的集合以及 [工作表類](https://apireference.aspose.com/cells/java/com.aspose.cells/Worksheet) 用於表示單個工作表。對於訪問內置和自定義屬性，BuiltInDocumentProperties、CustomDocumentProperties 簡化了元數據管理的過程。 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="管理系統定義的屬性" %}}

為了管理內置屬性，API 提供 [內置文檔屬性](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties), 程序員可以輕鬆訪問內置屬性並更新其值。根據應用程序的要求，開發人員可以使用索引或屬性名稱 [文檔屬性集合](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java 管理系統定義屬性的代碼" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="添加和刪除自定義元數據" %}}

為了處理自定義屬性，API 提供 [自定義文檔屬性](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties), 開發人員可以輕鬆訪問現有屬性以及使用添加新屬性 [添加方法](https://apireference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)） 的 [自定義文檔屬性集合](https://apireference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) 類添加屬性並返回新屬性的引用作為 [Properties.DocumentProperty](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) 目的。 DocumentProperty 類用於檢索文檔屬性的名稱、值和類型，如 [文檔屬性名稱](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [文檔屬性.值](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [文檔屬性類型](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) 返回其中之一 [財產類型](https://apireference.aspose.com/cells/java/com.aspose.cells/PropertyType) 枚舉值。 
 
{{% blocks/products/pf/feature-page-code h3="Java 在 Excel 文件中添加元數據的代碼" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java 刪除 Excel 文件中的自定義屬性的代碼" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
