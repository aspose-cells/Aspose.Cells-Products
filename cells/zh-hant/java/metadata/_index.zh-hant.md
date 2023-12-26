---
title: 管理 Excel 檔案元資料 via Java
description: 只需幾行 Java 程式碼即可查看、新增、編輯、刪除或提取 Excel 檔案元數據
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="管理 Microsoft<sup>&reg;</sup> Excel 檔案元資料 via Java" h2="使用伺服器端 Java API 檢視、新增、更新、刪除或擷取自訂和內建 Excel 檔案屬性。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/zh-hant/java/)支援管理內建（系統定義）屬性，例如標題、作者姓名、文件統計資料等，以及名稱/值對形式的自訂（使用者定義）屬性。有[作業本類](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)載入文件，以及[工作表集合](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection)處理工作表的收集以及[工作表類](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet)用於表示單一工作表。對於存取內建和自訂屬性，BuiltInDocumentProperties、CustomDocumentProperties 讓元資料管理流程變得簡單。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="管理系統定義的屬性" %}}

為了管理內建屬性，API 提供[內建文件屬性](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)，程式設計師可以輕鬆存取內建屬性並更新其值。根據應用程式的要求，開發人員可以使用索引或屬性名稱[文檔屬性集合](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java 管理系統定義屬性的代碼" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="新增和刪除自訂元數據" %}}

為了處理自訂屬性，API 提供[自訂文件屬性](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties)，開發人員可以輕鬆存取現有屬性以及使用以下命令新增屬性[添加方法](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)） 的[自訂文件屬性集合](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection)類別添加屬性並傳回新屬性的引用作為[屬性.文檔屬性](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty)目的。 DocumentProperty 類別用於擷取文件屬性的名稱、值和類型，如下所示[文檔屬性.名稱](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [文檔屬性.值](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [文檔屬性.類型](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type)返回其中之一[財產種類](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType)枚舉值。
 
{{% blocks/products/pf/feature-page-code h3="Java 在 Excel 檔案中新增元資料的程式碼" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java 刪除 Excel 檔案中的自訂屬性的程式碼" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
