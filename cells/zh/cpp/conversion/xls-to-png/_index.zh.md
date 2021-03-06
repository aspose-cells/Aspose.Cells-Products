---
title: 通过 C++ 应用程序将 XLS 转换为 PNG 
weight: 80
url: /zh/cpp/conversion/xls-to-png/ 
description: XLS 文档到 PNG 格式的示例 C++ 转换代码。程序员可以在任何 C++ 应用程序中使用此源代码进行批量 XLS 到 PNG 的转换。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C++ 将 XLS 转换为 PNG" h2="使用 C++ 库的高性能 XLS 到 PNG 转换，无需安装 Microsoft Excel、OpenOffice 或 Adobe Acrobat。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 将 XLS 转换为 PNG" %}}

 为了将 XLS 转换为 PNG，我们将使用
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

{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 将 XLS 转换为 PNG 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 开发人员只需几行代码即可轻松地将 XLS 文件转换为 PNG。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Factory::CreateIWorkbook 加载 XLS 文件。1. 选择第一个工作表。1. 设置 (PNG) 选项。1. 遍历工作表的每一页并进行渲染。1. 在兼容程序中打开 PNG 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 C++ 转换示例代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 C++ 运行时环境的兼容操作系统，适用于 Windows 32 位、Windows 64 位和 Linux 64 位。- Aspose.Cells 用于您的项目中引用的 C++ 个 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS 到 PNG C++ 转换源代码" offSpacer="" %}}

```cs
// 输出目录路径。
StringPtr outDir = new String("OutputDirectoryPath");

// 加载 XLS。
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.xls");

// 访问第一个工作表。
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// 创建图像或打印选项对象。
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// 指定图像格式。
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetPng());

// 指定水平和垂直分辨率
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// 根据指定的图像或打印选项渲染工作表。
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// 获取页数。
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// 为字符串连接创建字符串构建器对象。
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// 将每个页面一张一张地渲染为 png 图像。
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImagePNG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".png"));

	// 获取输出图像路径。
	StringPtr outputPNG = sb->ToString();

	// 将工作表转换为 png 图像。
	sr->ToImage(i, outputPNG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLS 到 PNG 转换现场演示" sectionDescription="[将 XLS 转换为 PNG](https://products.aspose.app/cells/conversion/xls-to-png) 立即访问我们的现场演示网站。现场演示具有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 XLS 文件，它就会立即转换为 PNG。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将获得下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel 文件操作库" %}}

 Excel API 可用于创建、编辑、转换 Microsoft Excel 格式并将其呈现为不同的格式。此外，它还可用于软件应用程序中的综合图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何软件，例如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

带有 XLS 扩展名的文件代表 Excel 二进制文件格式。此类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。 Excel 保存的文件称为工作簿，其中每个工作簿可以有一个或多个工作表。数据在工作表中以表格形式存储和显示给用户，可以跨越数值、文本数据、公式、外部数据连接、图像和图表。 Microsoft Excel 等应用程序可让您将工作簿数据导出为多种不同格式，包括 PDF、CSV、XLSX、TXT、HTML、XPS 等。随着 Microsoft Excel 2007 的发布，XLS 文件格式被更开放和结构化的格式 XLSX 所取代。最新版本仍然支持创建和读取 XLS 文件，尽管 XLSX 是现在的首选。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" >}}

PNG，便携式网络图形，是指一种使用无损压缩的光栅图像文件格式。此文件格式是作为图形交换格式 (GIF) 的替代品而创建的，没有版权限制。但是，PNG 文件格式不支持动画。 PNG文件格式支持无损图像压缩，使其在用户中很受欢迎。随着时间的推移，PNG 已经发展成为最常用的图像文件格式之一。几乎所有操作系统都支持打开 PNG 文件。例如，Microsoft Windows 查看器能够打开 PNG 文件，因为操作系统默认支持作为安装的一部分。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 XLS 转换为许多其他文件格式，包括下面列出的几种文件格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-bmp/" name="XLS 转 BMP" description="位图图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-csv/" name="XLS 转 CSV" description="逗号分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-dif/" name="XLS 转 DIF" description="数据交换格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-emf/" name="XLS 转 EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-gif/" name="XLS 转 GIF" description="图形交换格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-html/" name="XLS 转 HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-jpeg/" name="XLS 转 JPEG" description="JPEG图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-mhtml/" name="XLS 转 MHTML" description="网页存档格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-ods/" name="XLS 转 ODS" description="OpenDocument 电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-pdf/" name="XLS转PDF" description="便携式文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-svg/" name="XLS 转 SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tiff/" name="XLS 转 TIFF" description="标记图像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tsv/" name="XLS 转 TSV" description="制表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsb/" name="XLS 转 XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsm/" name="XLS 到 XLSM" description="电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsx/" name="XLS 到 XLSX" description="OOXML Excel 文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltm/" name="XLS 转 XLTM" description="Excel 启用宏的模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltx/" name="XLS 到 XLTX" description="Office OpenXML Excel 模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xps/" name="XLS 转 XPS" description="XML 纸张规格" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}