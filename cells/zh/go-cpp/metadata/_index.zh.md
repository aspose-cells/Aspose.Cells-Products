---
title: 通过 C++ 使用 Go 管理 Excel 文件元数据
description: 使用 Go 和 C++ 库查看、添加、编辑、删除或提取 Excel 文件元数据
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Go 管理 MicrosoftExcel 文档元数据" h2="在 C++ 应用程序中查看、插入、更新、删除或提取自定义和内置的 Excel 文档属性。" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Excel 中的元数据 - 如何查看、插入和删除 Excel 文件元数据。[通过 C++ Excel 库](/cells/zh/go-cpp/)该库通过支持内置/系统定义的属性（例如作者姓名、标题、文档统计信息等）来简化操作，这些属性有时用于检查文件的最后修改或保存时间，以及以名称/值对形式提供的自定义/用户定义属性。为了实现流程自动化，该库还支持创建和维护大型元数据 Excel 文件。[工作簿](https://reference.aspose.com/cells/go-cpp/workbook/)该类可以通过路径、流或特定的文件格式类型打开工作簿。因此，它会使用适当的方法加载文件以进行后续处理。以下列出了一些可能性，开发人员可以根据应用程序的需求轻松地增强代码。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="读取和更新内置属性" %}}

为了实现内置属性的自动化，API 提供了[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)该方法返回一个 DocumentProperties 集合，该集合表示电子表格的所有内置文档属性。访问所有内置属性后，可以使用相应的方法（例如 GetTitle()、GetSubject() 等）访问相关属性。要更新属性，API 提供了诸如 SetTitle、SetSubject、SetAuthor、SetComments 等方法。查看详情[内置文档属性集合](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)实现所需功能。

{{% blocks/products/pf/feature-page-code h3="通过代码 C++ 读取系统定义属性" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="通过代码 C++ 更新内置属性" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="查看和添加自定义属性" %}}

对于处理自定义属性，API 提供[工作簿::获取自定义文档属性](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)该方法返回电子表格的所有自定义文档属性集合。首先，通过此方法访问自定义属性后，开发人员可以使用相关方法添加属性，例如 AddIDocumentProperty 和 AddLinkToContentProperty；同样，可以使用 UpdateLinkedPropertyValue 和 UpdateLinkedRange 分别更新链接到内容和链接范围的自定义文档属性值。开发人员可以使用来自以下位置的相关方法：[自定义文档属性集合](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="通过代码 C++ 查看自定义属性" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="使用代码 C++ 在 Excel 文件中添加元数据" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}