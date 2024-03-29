---
title: 通过C++从XLSM文档中提取文本和图像
weight: 570
description: C++ 示例代码，用于在 C++ 运行时环境中从 XLSM 文件中提取文本和图像，适用于 Windows 32 位、Windows 64 位和 Linux 64 位。
keywords: [C++ Aspose.Cells., C++ Extract text and images from XLSM file., C++ How to Parse XLSM File., C++ Extract text from XLSM file., Extract images from XLSM file using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="解析 C++ 中的 XLSM 格式" h2="使用服务器端 Aspose.Cells for C++ API 进行本机高性能 XLSM 文档解析，无需使用 Microsoft 或 Adobe PDF 等任何软件。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 解析 XLSM 文件" %}}

为了解析 XLSM 文件，我们将使用[Aspose.Cells for C++](https://products.aspose.com/cells/cpp)API这是一个功能丰富、功能强大且易于使用的文档解析API for C++平台。您可以直接下载最新版本，打开即可[NuGet](https://www.nuget.org/packages/aspose.cells)包管理器，搜索**Aspose.Cells.Cpp**并安装。您还可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="解析C++中的XLSM文件的步骤" %}}

{{% blocks/products/pf/agp/text %}}

基本文档解析[Aspose.Cells for C++](https://products.aspose.com/cells/cpp)只需几行代码即可完成 API。解析 Microsoft Excel XLS、XLSX、XLSM、XLSB 和 OpenDocument ODS 文件中的文本和图像。

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ 支持所有主要平台和操作系统。请确保您具备以下先决条件。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 或具有 C++ 运行时环境的兼容操作系统，适用于 Windows 32 位、Windows 64 位和 Linux 64 位。
- 在项目中添加对 Aspose.Cells for C++ DLL 的引用。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="解析 XLSM 文件 - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// extract images from Worksheets 
// open a template Excel file
Workbook workbook(u"sampleExtractImagesFromWorksheets.xlsm");

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

 Aspose.Cells API 可用于创建、编辑、转换和渲染 Microsoft Excel 格式为不同的格式。此外，它还可用于软件应用程序中的全面图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何像 Microsoft 或 OpenOffice 这样的软件。



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="在线 XLSM 解析器现场演示" sectionDescription="立即访问我们的网站，从 XLSM 文档中提取文本和图像[现场演示网站](https://products.aspose.app/cells/parser)。现场演示有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text="无需下载Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上传您的 XLSM 文件即可。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="它将立即被解析。" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
扩展名为 XLSM 的文件是一种支持宏的电子表格文件。从应用程序的角度来看，宏是用于自动化流程的指令集。宏用于记录重复执行的步骤，并通过再次运行宏来方便执行操作。宏是使用 Visual Basic 编辑器在 Excel 工作簿中使用 Microsoft 的 Visual Basic for Applications (VBA) 进行编程的，并且可以直接从那里运行/调试。

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的解析文档" subTitle="使用 C++，可以轻松解析其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/ods/" name="ODS" description="OpenDocument 电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xls/" name="XLS" description="Excel 二进制格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsb/" name="XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
