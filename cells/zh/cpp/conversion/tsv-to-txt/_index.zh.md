---
title: 通过 C++ 应用程序将 TSV 转换为 TXT 
url: /zh/cpp/conversion/tsv-to-txt/ 
description: TSV 文档到 TXT 格式的示例 C++ 转换代码。程序员可以使用此源代码在任何 C++ 应用程序中进行批量 TSV 到 TXT 的转换。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C++ 将 TSV 转换为 TXT" h2="使用 C++ 库的高性能 TSV 到 TXT 转换，无需安装 Microsoft Excel、OpenOffice 或 Adobe Acrobat。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="TXT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 将 TSV 转换为 TXT" %}}

 为了将 TSV 转换为 TXT，我们将使用
 [Aspose.Cells 代表 C++](https://products.aspose.com/cells/cpp) 
 API 是一个功能丰富、功能强大且易于使用的文档操作和转换 API C++ 平台。可以直接下载最新版本，直接打开
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 包管理器，搜索
 Aspose.Cells.Cpp 
 并安装。您也可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 将 TSV 转换为 TXT 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 开发人员只需几行代码即可轻松地将 TSV 文件转换为 TXT。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Factory::CreateIWorkbook 加载 TSV 文件。1. 调用 Save() 方法。1. 使用 (TXT) 文件扩展名传递输出文件路径。1. TXT 文件将保存在指定路径。1. 在兼容程序中打开 TXT 文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 C++ 转换示例代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 C++ 运行时环境的兼容操作系统，适用于 Windows 32 位、Windows 64 位和 Linux 64 位。- Aspose.Cells 用于您的项目中引用的 C++ 个 DLL。
- Microsoft Windows 或具有 C++ 运行时环境的兼容操作系统，适用于 Windows 32 位、Windows 64 位和 Linux 64 位。- Aspose.Cells 用于您的项目中引用的 C++ 个 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSV 到 TXT C++ 转换源代码" offSpacer="" %}}

```cs
// 加载 TSV。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tsv");

// 以 TXT 格式保存。
wkb->Save(u"convertedFile.txt", SaveFormat_Txt);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TSV 到 TXT 转换现场演示" sectionDescription="[将 TSV 转换为 TXT](https://products.aspose.app/cells/conversion/tsv-to-txt) 立即访问我们的现场演示网站。现场演示具有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 TSV 文件，它将立即转换为 TXT。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将获得下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel 文件操作库" %}}

 Excel API 可用于创建、编辑、转换 Microsoft Excel 格式并将其呈现为不同的格式。此外，它还可用于软件应用程序中的综合图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何软件，例如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

制表符分隔值 (TSV) 文件格式表示用纯文本格式的制表符分隔的数据。该文件格式类似于 CSV，用于以结构化方式组织数据，以便在不同应用程序之间导入和导出。该格式主要用于电子表格应用程序和数据库中的数据导入/导出和交换。 TSV 文件中的每条记录都包含在单行文本文件中，其中每个字段值由制表符分隔。 TSV 文件格式的媒体类型是文本/制表符分隔值。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}

具有 .TXT 扩展名的文件表示包含行形式的纯文本的文本文档。文本文档中的段落由回车识别，用于更好地安排文件内容。可以在不同操作系统上的任何文本编辑器或文字处理应用程序中打开标准文本文档。这种文件中包含的所有文本都是人类可读的格式，并由字符序列表示。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 TSV 转换为许多其他文件格式，包括下面列出的几种文件格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-bmp/" name="TSV转BMP" description="位图图像" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-csv/" name="TSV 转 CSV" description="逗号分隔值" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-dif/" name="TSV转DIF" description="数据交换格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-emf/" name="TSV 到 EMF" description="增强的元文件格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-gif/" name="TSV转GIF" description="图形交换格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-html/" name="TSV 转 HTML" description="超文本标记语言" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-jpeg/" name="TSV转JPEG" description="JPEG图像" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-mhtml/" name="TSV转MHTML" description="网页存档格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-ods/" name="TSV 到 ODS" description="OpenDocument 电子表格文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-pdf/" name="TSV转PDF" description="便携式文件格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-png/" name="TSV转PNG" description="便携式网络图形" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-svg/" name="TSV转SVG" description="可缩放矢量图形" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-tiff/" name="TSV 转 TIFF" description="标记图像格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xls/" name="TSV 转 XLS" description="Excel 二进制格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsb/" name="TSV 转 XLSB" description="二进制 Excel 工作簿文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsm/" name="TSV 转 XLSM" description="电子表格文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xlsx/" name="TSV 转 XLSX" description="OOXML Excel 文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltm/" name="TSV 转 XLTM" description="Excel 启用宏的模板" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xltx/" name="TSV 转 XLTX" description="Office OpenXML Excel 模板" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/tsv-to-xps/" name="TSV 转 XPS" description="XML 纸张规格" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}