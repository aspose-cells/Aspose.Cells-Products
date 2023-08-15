---
title: 管理 Excel 文件元数据 via Java
description: 只需几行 Java 代码即可查看、添加、编辑、删除或提取 Excel 文件元数据
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="管理 Microsoft<sup>&reg;</sup> Excel 文件元数据 via Java" h2="使用服务器端 Java API 查看、添加、更新、删除或提取自定义和内置 Excel 文件属性。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/zh/java/)支持管理内置（系统定义）属性，例如标题、作者姓名、文档统计信息等，以及名称/值对形式的自定义（用户定义）属性。有[作业本类](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)加载文件，以及[工作表集合](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection)处理工作表的收集以及[工作表类](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet)用于表示单个工作表。对于访问内置和自定义属性，BuiltInDocumentProperties、CustomDocumentProperties 使元数据管理过程变得简单。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="管理系统定义的属性" %}}

为了管理内置属性，API 提供[内置文档属性](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)，程序员可以轻松访问内置属性并更新其值。根据应用程序的要求，开发人员可以使用索引或属性名称[文档属性集合](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java 管理系统定义属性的代码" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="添加和删除自定义元数据" %}}

为了处理自定义属性，API 提供[自定义文档属性](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties)，开发人员可以轻松访问现有属性以及使用以下命令添加新属性[添加方法](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)） 的[自定义文档属性集合](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection)类添加属性并返回新属性的引用作为[属性.文档属性](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty)目的。 DocumentProperty 类用于检索文档属性的名称、值和类型，如下所示[文档属性.名称](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [文档属性.值](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [文档属性.类型](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type)返回其中之一[财产种类](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType)枚举值。
 
{{% blocks/products/pf/feature-page-code h3="Java 在 Excel 文件中添加元数据的代码" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java 删除 Excel 文件中的自定义属性的代码" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
