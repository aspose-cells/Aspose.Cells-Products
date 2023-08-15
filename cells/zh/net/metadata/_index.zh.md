---
title: 管理 Excel 文件元数据 via .NET C#
description: 只需几行 C# 代码即可查看、添加、编辑、删除或提取 Excel 文件元数据
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="管理 Microsoft<sup>&reg;</sup> Excel 文件元数据 via .NET" h2="使用服务器端 .NET API 查看、添加、更新、删除或提取内置和自定义 Excel 文件属性。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/zh/net/)支持管理系统定义（内置）属性，如标题、作者姓名、文档统计等，以及用户定义（自定义）属性（以名称-值对的形式）。有[作业本类](https://reference.aspose.com/cells/net/aspose.cells/workbook)加载文件，以及[工作表集合](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection)处理工作表的收集以及[工作表类](https://reference.aspose.com/cells/net/aspose.cells/worksheet)用于表示单个工作表。与这些类一起，BuiltInDocumentProperties、CustomDocumentProperties 使元数据管理过程变得简单。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="管理内置属性" %}}

为了管理系统定义的属性，API 提供[内置文档属性](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties)，程序员可以轻松访问内置属性并更新其值。根据应用程序的要求，开发人员可以使用索引或属性名称[文档属性集合](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# 管理内置属性的代码" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="管理自定义属性" %}}

为了管理用户定义的属性，API 提供[自定义文档属性](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties)，开发人员可以轻松访问已添加的属性以及添加新属性。为了添加自定义属性，[添加方法](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index)的[自定义文档属性集合](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection)类添加属性并返回新属性的引用作为[属性.文档属性](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty)目的。 DocumentProperty 类用于检索文档属性的名称、值和类型，如下所示[文档属性.名称](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [文档属性.值](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [文档属性.类型](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type)返回其中之一[财产种类](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype)枚举值。
 
{{% blocks/products/pf/feature-page-code h3="C# 在 Excel 文件中添加元数据的代码" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# 删除 Excel 文件中的自定义属性的代码" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
