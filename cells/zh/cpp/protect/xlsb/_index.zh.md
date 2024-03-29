---
title: 通过 C++ 保护和锁定 XLSB 文档
weight: 4860
description: 在 C++ 运行时环境（适用于 Windows 32 位、Windows 64 位和 Linux 64 位）上使用密码锁定 XLSB 文件的 C++ 示例代码。
keywords: [C++ Aspose.Cells., C++ Lock XLSB files., C++ How to Protect and lock XLSB document., C++ Protect XLSB files., Encrypt XLSB Files using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C++ 加密 XLSB 文件" h2="使用 .NET 库对 Excel 电子表格进行密码保护，包括 XLSB 格式。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp/" installationsDocsLink="https://docs.aspose.com/cells/cpp/" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 保护 XLSB 文件" %}}

为了保护 XLSB 文件，我们将使用
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API这是一个功能丰富、功能强大且易于使用的文档加密API for C++平台。您可以直接下载最新版本，打开即可
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
包管理器，搜索
 **Aspose.Cells.Cpp** 
并安装。您还可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 保护 XLSB 文件的步骤" %}}

{{% blocks/products/pf/agp/text %}}

只需几行代码即可使用 Aspose.Cells API 进行文档保护。

{{% /blocks/products/pf/agp/text %}}

1. 使用Workbook类加载XLSB文件
1. 使用带有 ProtectionType 和密码的 Protect(..) 方法
1. 通过Save()方法保存受保护的XLSB文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for C++ 支持所有主要平台和操作系统。请确保您具备以下先决条件。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 或具有 C++ 运行时环境的兼容操作系统，适用于 Windows 32 位、Windows 64 位和 Linux 64 位。
- 在项目中添加对 Aspose.Cells for C++ DLL 的引用。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// load the ODS Excel file 
Workbook book(u"unlocked.xlsb");

// access the first worksheet
Worksheet worksheet = book.GetWorksheets().Get(0);

// protect the worksheet with password
worksheet.Protect(ProtectionType::All, u"password", nullptr);

// protect the whole workbook with password
book.Protect(ProtectionType::All, u"password");

// save the modified file in default format
book.Save(u"protected.xlsb");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="关于 Aspose.Cells for C++ API" %}}

 Aspose.Cells API 可用于创建、编辑、转换和渲染 Microsoft Excel 格式为不同的格式。此外，它还可用于软件应用程序中的全面图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何像 Microsoft 或 OpenOffice 这样的软件。



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="免费保护应用程序 XLSB" sectionDescription="查看我们的现场演示[加密XLSB文件](https://products.aspose.app/cells/protect/xlsb)具有以下好处。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text="无需下载或设置任何东西" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="无需编写或编译代码" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上传 XLSB 文件并点击“解锁”按钮" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="从链接下载生成的 XLSB 文件" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB 文件格式指定 Excel 二进制文件格式，它是指定 Excel 工作簿内容的记录和结构的集合。内容可以包括非结构化或半结构化的数字表、文本表、或数字和文本表、公式、外部数据连接、图表和图像。与 XLSX（基于 Open XML 文件格式）不同，XLSB 表示二进制 Excel 工作簿文件。 XLSB 文件的读取和写入速度更快，这使得它们对于处理大文件非常有用。 XLSB 很少用于存储工作簿，因为 XLSX（以及之前的 XLS）是用户选择的最常见的用于保存工作簿的文件格式。可以用Microsoft Office 2007及以上版本打开。

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的保护文件" subTitle="使用C++，可以保护其他文件，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/ods/" name="ODS" description="OpenDocument 电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xls/" name="XLS" description="Excel 二进制格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsm/" name="XLSM" description="电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
