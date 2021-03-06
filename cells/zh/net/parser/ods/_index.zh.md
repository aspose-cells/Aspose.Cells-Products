---
title: 通过 .NET 从 ODS 文档中提取文本和图像 
weight: 6970
url: /zh/net/parser/ods/ 
description: C# 源代码，用于从 .NET Framework、.NET Core、Mono 或 Xamarin 平台上的 ODS 文件中提取文本和图像。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="解析 C# 中的 ODS 格式" h2="使用服务器端 Aspose.Cells for .NET API 进行本机和高性能 ODS 文档解析，无需使用 Microsoft 或 Adobe PDF 等任何软件。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 解析 ODS 文件" %}}

 为了解析 ODS 文件，我们将使用
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API 是一个功能丰富、功能强大且易于使用的文档操作 API，适用于 C# 平台。打开
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 包管理器，搜索
 **Aspose.Cells** 
 并安装。您也可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# 中解析 ODS 文件的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 一个基本的文档解析
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 只需几行代码即可完成 API。从 Microsoft Excel XLS、XLSX、XLSM、XLSB 和 OpenDocument ODS 文件中解析文本和图像。

{{% /blocks/products/pf/agp/text %}}

+ 加载 ODS 文件。
+ 选择工作表。
+ 获取图片和图片类型。
+保存图像。
+ 保存文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 所有主要平台和操作系统都支持我们的 API。在执行以下代码之前，请确保您的系统具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 .NET Framework、.NET Core、Mono 或 Xamarin 平台的兼容操作系统- Microsoft Visual Studio 等开发环境- Aspose.Cells for .NET 项目中引用的 DLL - 使用上面的下载按钮从 NuGet 安装
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="解析 ODS 文件 - C#" offSpacer="" %}}

```cs
    // 从工作表中提取图像 
    // 打开模板 Excel 文件
    Workbook workbook = new Workbook("sampleExtractImagesFromWorksheets.ods");
    
    // 获取第一个工作表
    Worksheet worksheet = workbook.Worksheets[0];
    
    // 在第一个工作表中获取第一张图片
    Aspose.Cells.Drawing.Picture pic = worksheet.Pictures[0];
    
    // 设置输出图像文件路径
    string picformat = pic.ImageType.ToString();
                
    // 注意：您可以在指定图像路径之前评估图像格式
    // 定义 ImageOrPrintOptions
    Aspose.Cells.Rendering.ImageOrPrintOptions printoption = new  Aspose.Cells.Rendering.ImageOrPrintOptions();
    
    // 指定图像格式
    printoption.ImageType =  Aspose.Cells.Drawing.ImageType.Jpeg;
                
    // 保存图像
    pic.ToImage("outputExtractImagesFromWorksheets.jpg", printoption);  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="关于Aspose.Cells for .NET API" %}}

 Aspose.Cells API 可用于创建、编辑、转换 Microsoft Excel 格式并将其呈现为不同的格式。此外，它还可用于软件应用程序中的综合图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何软件，如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="在线 ODS 解析器现场演示" sectionDescription="立即从 ODS 文档中提取文本和图像，请访问我们的 [现场演示网站](https://products.aspose.app/cells/parser).现场演示有以下好处" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 ODS 文件。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" 它将立即被解析。" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
具有 ODS 扩展名的文件代表用户可编辑的 OpenDocument 电子表格文档格式。数据在 ODF 文件中存储为行和列。它是基于 XML 的格式，是开放文档格式 (ODF) 系列中的几个子类型之一。该格式被指定为 OASIS 发布和维护的 ODF 1.2 规范的一部分。 Windows 和其他操作系统上的许多应用程序可以打开 ODS 文件进行编辑和操作，包括 Microsoft Excel、NeoOffice 和 LibreOffice。 ODS 文件还可以通过不同的应用程序转换为其他电子表格格式以及 XLS、XLSX 等。 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的解析格式" subTitle="使用 C#，可以轻松解析其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xls/" name="XLS" description="Excel 二进制格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsb/" name="XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsm/" name="XLSM" description="电子表格文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}