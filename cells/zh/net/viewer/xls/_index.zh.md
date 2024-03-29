---
title: 查看 XLS 文件格式 via .NET
weight: 1260
description: C# 源代码，用于在 .NET Framework、.NET Core、Mono 或 Xamarin 平台上加载、渲染和显示 XLS 文档。
keywords: [C# Aspose.Cells., c# view XLS files., c# how to render XLS document., c# load and display XLS files., XLS File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLS 文件查看器 for .NET" h2="查看 Excel 和 OpenOffice 电子表格，例如 XLS，无需 Microsoft Excel 或 Office Automation。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 查看 XLS 文件" %}}

为了查看 XLS 文件，我们将使用
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
API 这是一个功能丰富、功能强大且易于使用的 API 适用于 C# 平台，可与任何查看器一起使用。打开
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
包管理器，搜索
 **Aspose.Cells** 
并安装。您还可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C# 查看 XLS 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells使得开发者只需几行代码就可以轻松查看XLS文件。

{{% /blocks/products/pf/agp/text %}}

1. 在 Workbook 实例中加载 XLS 文件
1. 创建 HtmlSaveOptions 的实例并将 ExportHeadings 属性设置为 true
1. 使用Workbook.Save方法将XLS文件保存为HTML格式
1. 使用 Process.Start 在默认浏览器中加载结果 HTML

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for .NET 在所有主要操作系统上均受支持。只需确保您满足以下先决条件即可。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 .NET Framework、.NET Core、Mono 或 Xamarin 平台的兼容操作系统
- 开发环境如Microsoft Visual Studio
- 在项目中添加对 Aspose.Cells for .NET DLL 的引用

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# 查看XLS文件的示例代码" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the XLS file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.xls");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the XLS file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="关于 Aspose.Cells for .NET API" %}}

 Aspose.Cells API 可用于创建、编辑、转换和渲染 Microsoft Excel 格式为不同的格式。此外，它还可用于软件应用程序中的全面图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何像 Microsoft 或 OpenOffice 这样的软件。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="免费应用程序查看 XLS" sectionDescription="查看我们的现场演示[查看XLS](https://products.aspose.app/cells/viewer/xls)具有以下好处。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="无需下载或设置任何东西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="无需编写或编译代码" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上传 XLS 文件并点击“查看”按钮" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="如果需要，请从链接下载 XLS 文件" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
扩展名为 XLS 的文件代表 Excel 二进制文件格式。此类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（例如 OpenOffice Calc 或 Apple Numbers）创建。Excel 保存的文件称为工作簿，其中每个工作簿可以有一个或多个工作表。数据以工作表中的表格格式存储并显示给用户，可以涵盖数值、文本数据、公式、外部数据连接、图像和图表。 Microsoft Excel 等应用程序可让您将工作簿数据导出为多种不同的格式，包括 PDF、CSV、XLSX、TXT、HTML、XPS 等。随着 Microsoft Excel 2007 的发布，XLS 文件格式被更开放和结构化的格式 XLSX 所取代。最新版本仍然支持创建和读取 XLS 文件，尽管 XLSX 是现在使用的首选。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的查看器格式" subTitle="使用C#，您还可以查看许多其他文件格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="逗号分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="OpenDocument 电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/tsv/" name="TSV" description="制表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="文本文档" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlt/" name="XLT" description="Microsoft Excel 模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Excel 宏启用模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Office OpenXML Excel 模板" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
