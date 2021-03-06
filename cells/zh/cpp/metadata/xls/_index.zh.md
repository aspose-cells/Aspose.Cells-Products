---
title: 通过 C++ 编辑或查看 XLS 文档元数据 
weight: 2150
url: /zh/cpp/metadata/xls/ 
description: C++ 在 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 运行时环境上编辑或查看 XLS 文件元数据的示例代码。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C++ 提取 XLS 元数据" h2="构建您自己的 C++ 应用，以使用服务器端 API 添加、编辑、删除或提取 XLS 文件中的元数据。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 获取 XLS 元数据" %}}

 为了提取 XLS 元数据，我们将使用
 [Aspose.Cells 代表 C++](https://products.aspose.com/cells/cpp) 
 API，它是一个功能丰富、功能强大且易于使用的文档元数据提取 API，适用于 C++ 平台。可以直接下载最新版本，直接打开
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 包管理器，搜索
 **Aspose.Cells.Cpp** 
 并安装。您也可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 提取 XLS 元数据的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 访问存储在 XLS 文件中的有用信息，包括 XLS 文件的接收时间、处理时间、时间戳等。

{{% /blocks/products/pf/agp/text %}}

+ 使用 CreateIWorkbookMetadata 加载 XLS 文件
+ 使用 CreateIMetadataOptions 创建选项
+ 通过 GetICustomDocumentProperties() 和 AddIDocumentProperty 添加新属性
+ 保存 XLS 文档

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ 支持所有主要平台和操作系统。请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 C++ 运行时环境的兼容操作系统，适用于 Windows 32 位、Windows 64 位和 Linux 64 位。- Aspose.Cells 用于您的项目中引用的 C++ 个 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="提取 XLS 的元数据 - C++" offSpacer="" %}}

```cs

intrusive_ptr<IMetadataOptions> options = Factory::CreateIMetadataOptions(MetadataType_DocumentProperties);
intrusive_ptr<IWorkbookMetadata> meta = Factory::CreateIWorkbookMetadata(new String("c:\\book1.xls"), options);
meta->GetICustomDocumentProperties()->AddIDocumentProperty(new String("test"), (StringPtr)new String("test"));
meta->Save(new String("c:\\book2.xls"));  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="关于 Aspose.Cells 的 C++ API" %}}

 Aspose.Cells API 可用于创建、编辑、转换 Microsoft Excel 格式并将其呈现为不同的格式。此外，它还可用于软件应用程序中的综合图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何软件，如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="通过在线应用程序提取 XLS 的元数据" sectionDescription="使用我们的查看和编辑 XLS 文档的元数据 [现场演示](https://products.aspose.app/cells/metadata) 具有以下好处。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载或设置任何东西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 XLS 文件并编辑文档属性" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" 立即获取生成文件的下载链接" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
带有 XLS 扩展名的文件代表 Excel 二进制文件格式。此类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。 Excel 保存的文件称为工作簿，其中每个工作簿可以有一个或多个工作表。数据在工作表中以表格形式存储和显示给用户，可以跨越数值、文本数据、公式、外部数据连接、图像和图表。 Microsoft Excel 等应用程序可让您将工作簿数据导出为多种不同格式，包括 PDF、CSV、XLSX、TXT、HTML、XPS 等。随着 Microsoft Excel 2007 的发布，XLS 文件格式被更开放和结构化的格式 XLSX 所取代。最新版本仍然支持创建和读取 XLS 文件，尽管 XLSX 是现在的首选。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的元数据格式" subTitle="使用 C++，还可以处理许多其他格式的元数据，包括" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/ods/" name="消耗臭氧层物质" description="OpenDocument 电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsm/" name="XLSM" description="电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}