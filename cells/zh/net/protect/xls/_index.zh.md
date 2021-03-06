---
title: 通过 .NET 保护和锁定 XLS 文档 
weight: 7010
url: /zh/net/protect/xls/ 
description: C# 用于在 .NET Framework、.NET Core、Mono 或 Xamarin 平台上使用密码锁定 XLS 文件的源代码。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C# 加密 XLS 文件" h2="使用 .NET 库对包括 XLS 格式的 Excel 电子表格进行密码保护。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 保护 XLS 文件" %}}

 为了保护 XLS 文件，我们将使用
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API 是一个功能丰富、功能强大且易于使用的文档保护 API，适用于 C# 平台。打开
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 包管理器，搜索
 **Aspose.Cells** 
 并安装。您也可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C# 保护 XLS" %}}

{{% blocks/products/pf/agp/text %}}

 你需要
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 在您的项目中引用以执行以下工作流程。

{{% /blocks/products/pf/agp/text %}}

1. 使用 XLS 文件的路径实例化 Workbook 类1. 获取默认或任何工作表以添加保护1. 使用 Worksheet.Protect 方法保护工作表1. 使用 Workbook.Protect 方法保护工作簿1. 以 XLS 格式保存结果
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET 在所有主要操作系统上都受支持。只需确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 .NET Framework、.NET Core、Mono 或 Xamarin 平台的兼容操作系统- Microsoft Visual Studio 等开发环境- Aspose.Cells for .NET 在您的项目中引用
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="" %}}

```cs

// 加载 XLS Excel 文件 
var book = new Aspose.Cells.Workbook("unlocked.xls");

// 访问第一个工作表
var worksheet = book.Worksheets[0];

// 用密码保护工作表
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// 用密码保护整个工作簿
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// 以默认格式保存修改后的文件
book.Save("protected.xls");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="关于Aspose.Cells for .NET API" %}}

 Aspose.Cells API 可用于创建、编辑、转换 Microsoft Excel 格式并将其呈现为不同的格式。此外，它还可用于软件应用程序中的综合图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何软件，如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="保护 XLS 的免费应用程序" sectionDescription="查看我们的现场演示 [加密 XLS 文件](https://products.aspose.app/cells/protect/xls) 具有以下好处。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载或设置任何东西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写或编译代码" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传 XLS 文件并点击“解锁”按钮" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" 从链接下载生成的 XLS 文件" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
带有 XLS 扩展名的文件代表 Excel 二进制文件格式。此类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。 Excel 保存的文件称为工作簿，其中每个工作簿可以有一个或多个工作表。数据在工作表中以表格形式存储和显示给用户，可以跨越数值、文本数据、公式、外部数据连接、图像和图表。 Microsoft Excel 等应用程序可让您将工作簿数据导出为多种不同格式，包括 PDF、CSV、XLSX、TXT、HTML、XPS 等。随着 Microsoft Excel 2007 的发布，XLS 文件格式被更开放和结构化的格式 XLSX 所取代。最新版本仍然支持创建和读取 XLS 文件，尽管 XLSX 是现在的首选。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的保护格式" subTitle="使用 C#，可以轻松保护其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="消耗臭氧层物质" description="OpenDocument 电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}