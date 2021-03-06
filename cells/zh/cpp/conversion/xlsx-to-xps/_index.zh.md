---
title: 通过 C++ 应用程序将 XLSX 转换为 XPS 
weight: 1880
url: /zh/cpp/conversion/xlsx-to-xps/ 
description: XLSX 文档到 XPS 格式的示例 C++ 转换代码。程序员可以使用此源代码在任何 C++ 应用程序中进行批量 XLSX 到 XPS 的转换。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C++ 将 XLSX 转换为 XPS" h2="使用 C++ 库的高性能 XLSX 到 XPS 转换，无需安装 Microsoft Excel、OpenOffice 或 Adobe Acrobat。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XPS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 将 XLSX 转换为 XPS" %}}

 为了将 XLSX 转换为 XPS，我们将使用
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

{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 将 XLSX 转换为 XPS 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 开发人员只需几行代码即可轻松地将 XLSX 文件转换为 XPS。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Factory::CreateIWorkbook 加载 XLSX 文件。1. 调用 Save() 方法。1. 传递带有 (XPS) 文件扩展名的输出文件路径。1. XPS 文件将保存在指定路径。1. 在兼容程序中打开 XPS 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 C++ 转换示例代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 C++ 运行时环境的兼容操作系统，适用于 Windows 32 位、Windows 64 位和 Linux 64 位。- Aspose.Cells 用于您的项目中引用的 C++ 个 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSX 到 XPS C++ 转换源代码" offSpacer="" %}}

```cs
// 加载 XLSX。
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsx");

// 以 XPS 格式保存。
wkb->Save(u"convertedFile.xps", SaveFormat_Xps);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLSX 到 XPS 转换现场演示" sectionDescription="[将 XLSX 转换为 XPS](https://products.aspose.app/cells/conversion/xlsx-to-xps) 立即访问我们的现场演示网站。现场演示具有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 XLSX 文件，它就会立即转换为 XPS。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将获得下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel 文件操作库" %}}

 Excel API 可用于创建、编辑、转换 Microsoft Excel 格式并将其呈现为不同的格式。此外，它还可用于软件应用程序中的综合图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何软件，例如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}

XLSX 是 Microsoft 在 Microsoft Office 2007 发布时引入的 Microsoft Excel 文档的众所周知的格式。基于根据 OOXML 标准 ECMA-376 第 2 部分中概述的开放打包约定组织的结构，新格式为一个包含许多 XML 文件的 zip 包。只需解压缩 .xlsx 文件即可检查底层结构和文件。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XPS" readMoreLink="https://docs.fileformat.com/page-description-language/xps/" >}}

XPS 文件表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。此格式由 Microsoft 开发，用于替代 EMF 文件格式，类似于 PDF 文件格式，但在文档的布局、外观和打印信息中使用 XML。事实上，更合理的说法是 XPS 是对 PDF 的尝试，但由于多种原因未能获得 PDF 所拥有的足够普及。 Microsoft 从 Windows 7 开始默认提供 XPS Document Writer 用于创建 XPS 文件。 XPS 文件可以通过在打印文档时选择“Microsoft XPS Document Writer”作为打印机来生成。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 XLSX 转换为许多其他文件格式，包括下面列出的几种文件格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-bmp/" name="XLSX 转 BMP" description="位图图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-csv/" name="XLSX 转 CSV" description="逗号分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-dif/" name="XLSX 转 DIF" description="数据交换格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-emf/" name="XLSX 到 EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-gif/" name="XLSX 转 GIF" description="图形交换格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-html/" name="XLSX 转 HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-jpeg/" name="XLSX 转 JPEG" description="JPEG图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-mhtml/" name="XLSX 转 MHTML" description="网页存档格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-ods/" name="XLSX 转 ODS" description="OpenDocument 电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-pdf/" name="XLSX 转 PDF" description="便携式文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-png/" name="XLSX转PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-svg/" name="XLSX 转 SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-tiff/" name="XLSX 转 TIFF" description="标记图像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-tsv/" name="XLSX 转 TSV" description="制表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xls/" name="XLSX 到 XLS" description="Excel 二进制格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xlsb/" name="XLSX 转 XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xlsm/" name="XLSX 到 XLSM" description="电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xltm/" name="XLSX 到 XLTM" description="Excel 启用宏的模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xltx/" name="XLSX 到 XLTX" description="Office OpenXML Excel 模板" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}