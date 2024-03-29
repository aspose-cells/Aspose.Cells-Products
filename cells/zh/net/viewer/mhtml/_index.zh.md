---
title: 查看 MHTML 文件格式 via .NET
description: C# 源代码，用于在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上加载、渲染和显示 MHTML 文档。
keywords: [C# Aspose.Cells., c# view MHTL files., c# how to render MHTL document., c# load and display MHTL files., MHTL File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="MHTML 文件查看器 for .NET" h2="查看 Excel 和 OpenOffice 电子表格，例如 MHTML，无需 Microsoft Excel 或 Office Automation。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 查看 MHTML 文件" %}}

为了查看 MHTML 文件，我们将使用<a href="https://products.aspose.com/cells/net">Aspose.Cells for .NET</a>API 这是一个功能丰富、功能强大且易于使用的 API 适用于 C# 平台，可与任何查看器一起使用。打开<a href="https://www.nuget.org/packages/aspose.cells">NuGet</a>包管理器，搜索<b>Aspose.Cells</b>并安装。您还可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C# 查看 MHTML 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells使得开发者只需几行代码就可以轻松查看MHTML文件。

{{% /blocks/products/pf/agp/text %}}

1. 在 Workbook 实例中加载 MHTML 文件
1. 创建 HtmlSaveOptions 的实例并将 ExportHeadings 属性设置为 true
1. 使用Workbook.Save方法将MHTML文件保存为HTML格式
1. 使用 Process.Start 在默认浏览器中加载结果 HTML


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for .NET 在所有主要操作系统上均受支持。只需确保您满足以下先决条件即可。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 或具有 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台的兼容操作系统
- 开发环境如Microsoft Visual Studio
- 在项目中添加对 Aspose.Cells for .NET DLL 的引用

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# 查看MHTML文件的示例代码" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the MHTML file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.mhtml");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the MHTML file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Cells API 可用于创建、编辑、转换和渲染 Microsoft Excel 格式为不同的格式。此外，它还可用于软件应用程序中的全面图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何像 Microsoft 或 OpenOffice 这样的软件。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="免费应用程序查看 MHTML" sectionDescription="查看我们的现场演示[查看MHTML](https://products.aspose.app/cells/viewer/mhtml)具有以下好处。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="无需下载或设置任何东西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="无需编写或编译代码" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上传 MHTML 文件并点击“查看”按钮" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="如果需要，请从链接下载 MHTML 文件" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}
扩展名为 MHTML 的文件代表一种网页存档格式，可以由许多不同的应用程序创建。该格式称为存档格式，因为它将 Web HTML 代码和相关资源保存在单个文件中。这些资源包括链接到网页的任何内容，例如图像、小程序、动画、音频文件等。 MHTML 文件可以在各种应用程序中打开，例如 Internet Explorer 和 Microsoft Word。 Microsoft Windows 使用 MHTML 文件格式来记录在使用 Windows 上出现问题的任何应用程序期间观察到的问题场景。 MHTML 文件格式对页面内容进行编码，类似于 message/rfc822 中定义的规范，这是纯文本电子邮件相关规范。该格式的实际规范详见 RFC 2557。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的查看器格式" subTitle="使用C#，您还可以查看许多其他文件格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="逗号分隔值" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="OpenDocument 电子表格文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/tsv/" name="TSV" description="制表符分隔值" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="文本文档" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="Excel 二进制格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="二进制 Excel 工作簿文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="电子表格文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlt/" name="XLT" description="Microsoft Excel 模板" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Excel 宏启用模板" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Office OpenXML Excel 模板" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
