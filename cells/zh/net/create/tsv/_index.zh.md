---
title: 通过 C# 创建 TSV 文件 
url: /zh/net/create-tsv/ 
description: C# 用于生成 TSV 文档的示例代码。使用此代码在 VB.NET、Asp.NET 或任何基于 .NET 的应用程序中创建 TSV 文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C# 创建 TSV 文档" h2="使用服务器端 .NET API 以编程方式创建本机和高性能 TSV（制表符分隔值）。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TSV" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 在运行的应用程序中动态生成 TSV 文件很容易。为了在不需要 MS Office 的情况下从头开始创建 TSV 文档，我们将使用
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API，它为使用 .NET 平台的电子表格创建、操作和转换提供不同的功能。开发人员可以轻松增强用于编写数据、生成图表或图形以及在电子表格中创建表格的代码。
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="如何通过 C# 创建 TSV" %}}

{{% blocks/products/pf/agp/text %}}

 开发人员只需几行代码即可在运行不同的报告应用程序中轻松创建、加载、修改和转换 TSV（制表符分隔值）以进行数据处理。

{{% /blocks/products/pf/agp/text %}}

1. 在类文件中包含命名空间1. 创建工作簿类实例。1. 访问工作簿的第一个工作表。1. 获取工作表的所需单元格并将值输入到单元格中。1. 使用 Save 方法将工作簿保存为 TSV 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 只需确保该系统具有 Microsoft Windows 或与 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台以及 Microsoft Visual Studio 等开发环境兼容的操作系统。 

{{% /blocks/products/pf/agp/text %}}

- 从命令行安装为 <code>nuget install Aspose.Cells</code> 或通过 Visual Studio 的包管理器控制台 <code>Install-Package Aspose.Cells</code>.- 或者，从以下位置获取离线 MSI 安装程序或 ZIP 文件中的所有 DLL <a href="https://downloads.aspose.com/cells/net">下载</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="以下源代码显示了如何使用 C# 创建 TSV 文件。" offSpacer="" %}}

```cs

// 创建工作簿类实例。
Workbook wkb = new Workbook();

// 访问工作簿的第一个工作表。
Worksheet sht = wkb.Worksheets[0];

// 获取工作表的所需单元格。
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// 将值输入到单元格中。
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// 将工作簿另存为 .tsv 文件。
wkb.Save("created_one.tsv");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 一个 Excel 电子表格编程库，能够构建跨平台应用程序，能够生成、修改、转换、呈现和打印 TSV 文件。 .NET Excel API 不仅可以在电子表格格式之间进行转换，它还可以将 Excel 文件呈现为图像、PDF、HTML、ODS 等，从而使其成为以行业标准格式交换文档的完美选择。

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
制表符分隔值 (TSV) 文件格式表示用纯文本格式的制表符分隔的数据。该文件格式类似于 CSV，用于以结构化方式组织数据，以便在不同应用程序之间导入和导出。该格式主要用于电子表格应用程序和数据库中的数据导入/导出和交换。 TSV 文件中的每条记录都包含在单行文本文件中，其中每个字段值由制表符分隔。 TSV 文件格式的媒体类型是文本/制表符分隔值。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的电子表格生成" subTitle="您还可以创建其他 Microsoft Excel 格式，包括下面列出的几种格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xls/" name="XLS" description="Microsoft Excel 电子表格（旧版）" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsx/" name="XLSX" description="打开 XML 工作簿" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsb/" name="XLSB" description="Excel 二进制工作簿" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsm/" name="XLSM" description="启用宏的电子表格" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlt/" name="XLT" description="Excel 97 - 2003 模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltx/" name="XLTX" description="Excel 模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltm/" name="XLTM" description="Excel 启用宏的模板" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-csv/" name="CSV" description="逗号分隔值" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-tsv/" name="硅通孔" description="制表符分隔值" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-ods/" name="消耗臭氧层物质" description="OpenDocument 电子表格" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
