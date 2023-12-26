---
title: 通过 C++ 管理 Excel 文件元数据
description: 使用 C++ 库查看、添加、编辑、删除或提取 Excel 文件元数据
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C++ 管理 Microsoft<sup>&reg;</sup> Excel 文档元数据" h2="在 C++ 应用程序中查看、插入、更新、删除或提取自定义和内置 Excel 文档属性。" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Excel 中的元数据 - 如何查看、插入和删除 Excel 文件元数据。[C++ Excel 库](/cells/zh/cpp/)通过支持内置/系统定义的属性（例如作者姓名、标题、文档统计信息等），有时需要检查最后文件何时被修改或保存以及自定义/用户定义的属性，以简单的方式提供便利名称/值对。为了自动化该过程，库支持创建和维护大型元数据 Excel 文件。[练习册](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class 按路径、流和特殊 FileFormatType 打开工作簿。因此，请使用适当的方法加载文件以进行进一步处理。下面列出的可能性很少，开发人员可以根据应用程序需求轻松增强他们的代码。
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="读取和更新内置属性" %}}

为了自动化内置属性，API 提供了[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/)返回 DocumentProperties 集合的方法，该集合表示电子表格的所有内置文档属性。访问所有内置属性后，使用相关方法如 GetTitle()、GetSubject() 等访问相关属性。为了更新属性，API 提供了 SetTitle、SetSubject、SetAuthor、SetComments 等方法。查看[内置文档属性集合](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/)用于所需的功能。

{{% blocks/products/pf/feature-page-code h3="C++ 读取系统定义属性的代码" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ 更新内置属性的代码" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="查看和添加自定义属性" %}}

为了处理自定义属性，API 提供[工作簿::获取自定义文档属性](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/)返回电子表格的所有自定义文档属性集合。首先通过此方法访问自定义属性，开发人员可以使用相关方法添加属性，如 AddIDocumentProperty、AddLinkToContentProperty 以及类似地使用 UpdateLinkedPropertyValue、UpdateLinkedRange 来更新分别链接到内容和链接范围的自定义文档属性值。开发者可以使用相关方法[自定义文档属性的集合](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ 查看自定义属性的代码" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ 在 Excel 文件中添加元数据的代码" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
