---
title: 通过 Java 将 XLSM 转换为 GIF 
weight: 10090
url: /zh/java/conversion/xlsm-to-gif/ 
description: XLSM 格式到 GIF 文件的示例 Java 转换代码。程序员可以使用此示例代码在任何基于 Web 或桌面 Java 的应用程序中将 Excel 和 OpenOffice 电子表格导出为 GIF。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 Java 将 XLSM 转换为 GIF" h2="XLSM 到 GIF Java 转换以使用内部部署 Java 库将单个或多个页面转换为 GIF。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 将 XLSM 转换为 GIF" %}}

 为了将 XLSM 渲染为 GIF，我们将使用
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API 是一个功能丰富、功能强大且易于使用的转换API for Java 平台。您可以直接从
 [马文](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 并通过将以下配置添加到 pom.xml 将其安装在基于 Maven 的项目中。

{{% blocks/products/pf/agp/code-block title="存储库" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依赖" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 XLSM 转换为 GIF 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 Java 开发人员只需几行代码即可轻松地将 XLSM 文件转换为 GIF。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Workbook 实例加载 XLSM 文件1. 从集合中选择默认或任何工作表1. 创建和设置 ImageOrPrintOptions 的对象1. 使用 Worksheet 和 ImageOrPrintOptions 对象创建 SheetRender1. 调用 SheetRender.toImage 方法将结果保存为 GIF 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 Java 转换源代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 应用程序和桌面应用程序运行时环境的兼容操作系统。- 直接从 Maven 获取最新版本的 Aspose.Cells for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSM转GIFJava转换源码" offSpacer="" %}}

```cs
// 加载要渲染的 XLSM 文件
Workbook workbook = new Workbook("sourceFile.xlsm");
// 从集合中访问默认工作表
Worksheet worksheet = workbook.getWorksheets().get(0);
// 定义结果图像的参数
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.GIF);
// 将工作表转换为 GIF 格式的图像
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.gif");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLSM 到 GIF 转换现场演示" sectionDescription="[将 XLSM 转换为 GIF](https://products.aspose.app/cells/conversion/xlsm-to-gif) 立即访问我们的现场演示网站。现场演示具有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 XLSM 文件，它就会立即转换为 GIF。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将获得下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 电子表格操作库" %}}

 Excel API 可用于创建、编辑、转换 Microsoft Excel 格式并将其呈现为不同的格式。此外，它还可用于软件应用程序中的综合图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何软件，例如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}

带有 XLSM 扩展名的文件是一种支持宏的电子表格文件。从应用程序的角度来看，宏是一组用于自动化流程的指令。宏用于记录重复执行的步骤，并有助于通过再次运行宏来执行操作。使用 Visual Basic 编辑器从 Excel 工作簿中使用 Microsoft 的 Visual Basic for Applications (VBA) 对宏进行编程，并且可以直接从那里运行/调试。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

GIF 或图形交换格式是一种高度压缩的图像。 GIF 由 Unisys 拥有，使用不会降低图像质量的 LZW 压缩算法。对于每个图像，GIF 通常允许每个像素最多 8 位，并且整个图像最多允许 256 种颜色。与 JPEG 图像相比，JPEG 图像可以显示多达 1600 万种颜色，并且相当接近人眼的极限。早在互联网出现时，GIF 仍然是最佳选择，因为它们需要低带宽并且与消耗纯色区域的图形兼容。动画 GIF 将大量图像或帧组合到一个文件中，并按顺序显示它们以生成动画剪辑或短视频。每帧的颜色限制最多为 256 种，并且可能最不适合再现具有颜色渐变的其他图像和照片。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 XLSM 转换为许多其他文件格式，包括下面列出的几种文件格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-bmp/" name="XLSM 转 BMP" description="位图图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-csv/" name="XLSM 转 CSV" description="逗号分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-dif/" name="XLSM 转 DIF" description="数据交换格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-emf/" name="XLSM 转 EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-html/" name="XLSM 转 HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-jpeg/" name="XLSM 转 JPEG" description="JPEG图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-mhtml/" name="XLSM 转 MHTML" description="网页存档格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-ods/" name="XLSM 转 ODS" description="OpenDocument 电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-pdf/" name="XLSM 转 PDF" description="便携式文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-png/" name="XLSM转PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-svg/" name="XLSM 转 SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-tiff/" name="XLSM 转 TIFF" description="标记图像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-tsv/" name="XLSM 转 TSV" description="制表符分隔值" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-txt/" name="XLSM 转 TXT" description="文本文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xls/" name="XLSM 转 XLS" description="Excel 二进制格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xlsb/" name="XLSM 转 XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xlsx/" name="XLSM 到 XLSX" description="OOXML Excel 文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xlt/" name="XLSM 转 XLT" description="微软 Excel 模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xltm/" name="XLSM 到 XLTM" description="Excel 启用宏的模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xltx/" name="XLSM 到 XLTX" description="Office OpenXML Excel 模板" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xps/" name="XLSM 转 XPS" description="XML 纸张规格" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-json/" name="XLSM 转 JSON" description="JavaScript 对象表示法" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}