---
title: 通过 C++ 从 XLS 文档中提取文本和图像
weight: 7610
description: C++ 示例代码，用于从 C++ 运行时环境上的 XLS 文件中提取文本和图像，适用于 Windows 32 位、Windows 64 位和 Linux 64 位。
keywords: [C++ Aspose.Cells., C++ Extract text and images from XLS file., C++ How to Parse XLS File., C++ Extract text from XLS file., Extract images from XLS file using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="解析 C++ 中的 XLS 格式" h2="使用服务器端 Aspose.Cells for C++ API 进行本机和高性能 XLS 文档解析，无需使用任何软件（如 Microsoft 或 Adobe PDF）。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 解析 XLS 文件" %}}

为了解析 XLS 文件，我们将使用[Aspose.Cells for C++](https://products.aspose.com/cells/cpp)API 是一个功能丰富、功能强大且易于使用的文档解析 API for C++ 平台。您可以直接下载其最新版本，只需打开[NuGet](https://www.nuget.org/packages/aspose.cells)包管理器，搜索**Aspose.Cells.Cpp**并安装。您也可以从程序包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="解析 C++ 中的 XLS 文件的步骤" %}}

{{% blocks/products/pf/agp/text %}}

一个基本的文档解析
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
只需几行代码即可完成 API。解析 Microsoft Excel XLS、XLSX、XLSM、XLSB 和 OpenDocument ODS 文件中的文本和图像。

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ 支持所有主要平台和操作系统。请确保您满足以下先决条件。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 或与 C++ 运行环境兼容的操作系统，适用于 Windows 32 位、Windows 64 位和 Linux 64 位。
- 在您的项目中添加对 Aspose.Cells for C++ DLL 的引用。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="解析 XLS 文件 - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// extract images from Worksheets 
// open a template Excel file
Workbook workbook(u"sampleExtractImagesFromWorksheets.xls");

// get the first worksheet
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// get the first Picture in the first worksheet
Picture pic = worksheet.GetPictures().Get(0);

// Note: you may evaluate the image format before specifying the image path
// define ImageOrPrintOptions
ImageOrPrintOptions printoption;

// specify the image format
printoption.SetImageType(ImageType::Jpeg);

// save the image
pic.ToImage(u"outputExtractImagesFromWorksheets.jpg", printoption);

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="关于 Aspose.Cells for C++ API" %}}

 Aspose.Cells API 可用于创建、编辑、转换和呈现 Microsoft Excel 格式为不同格式。此外，它还可用于在软件应用程序中进行全面的图表绘制、可扩展的报告和可靠的计算。Aspose.Cells 是一个独立的 API，它不需要任何软件，如 Microsoft 或 OpenOffice。



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="在线 XLS 解析器现场演示" sectionDescription="立即访问我们的[现场演示网站](https://products.aspose.app/cells/parser)现场演示有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text="无需下载Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上传您的 XLS 文件。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="它将立即被解析。" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
扩展名为 XLS 的文件代表 Excel 二进制文件格式。此类文件可由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。Excel 保存的文件称为工作簿，每个工作簿可以有一个或多个工作表。数据以表格格式存储在工作表中并显示给用户，可以涵盖数值、文本数据、公式、外部数据连接、图像和图表。Microsoft Excel 等应用程序允许您将工作簿数据导出为多种不同格式，包括 PDF、CSV、XLSX、TXT、HTML、XPS 和其他几种格式。随着 Microsoft Excel 2007 的发布，XLS 文件格式已被更开放、更结构化的格式 XLSX 所取代。最新版本仍然支持创建和读取 XLS 文件，尽管 XLSX 现在是首选。

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的解析文档" subTitle="使用 C++，可以轻松解析其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/ods/" name="ODS" description="开放文档电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsb/" name="XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsm/" name="XLSM" description="电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
