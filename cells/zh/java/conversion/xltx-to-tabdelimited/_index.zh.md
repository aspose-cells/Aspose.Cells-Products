---
title: 通过 Java 将 XLTX 转换为 TABDELIMITED 
url: /zh/java/conversion/xltx-to-tabdelimited/ 
description: XLTX 格式到 TABDELIMITED 文件的示例 Java 转换代码。程序员可以使用此示例代码将 Excel 和 OpenOffice 电子表格导出到任何基于 Web 或桌面 Java 的应用程序中的 TABDELIMITED。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 Java 将 XLTX 转换为 TABDELIMITED" h2="XLTX 到 TABDELIMITED Java 转换以使用内部部署 Java 库将单个或多个页面转换为 TABDELIMITED。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TABDELIMITED" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 将 XLTX 转换为 TABDELIMITED" %}}

 为了将 XLTX 渲染为 TABDELIMITED，我们将使用
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

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 XLTX 转换为 TABDELIMITED 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 Java 开发人员只需几行代码即可轻松地将 XLTX 文件转换为 TABDELIMITED。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Workbook 类的实例加载 XLTX 文件1. 调用 Workbook.save 方法1. 使用 TABDELIMITED 扩展名和 SaveFormat 作为参数传递输出路径1. 检查生成的 TABDELIMITED 文件的指定路径

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 Java 转换源代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 应用程序和桌面应用程序运行时环境的兼容操作系统。- 直接从 Maven 获取最新版本的 Aspose.Cells for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTX 到 TABDELIMITED Java 转换源代码" offSpacer="" %}}

```cs
// 在 Workbook 实例中加载 XLTX 文件
Workbook book = new Workbook("template.xltx");
// 将 XLTX 保存为 TABDELIMITED
book.save("output.tabdelimited", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLTX 到 TABDELIMITED 转换现场演示" sectionDescription="[将 XLTX 转换为 TABDELIMITED](https://products.aspose.app/cells/conversion/xltx-to-tabdelimited) 立即访问我们的现场演示网站。现场演示具有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 XLTX 文件，它就会立即转换为 TABDELIMITED。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将获得下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 电子表格操作库" %}}

 Excel API 可用于创建、编辑、转换 Microsoft Excel 格式并将其呈现为不同的格式。此外，它还可用于软件应用程序中的综合图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何软件，例如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTX" readMoreLink="https://docs.fileformat.com/spreadsheet/xltx/" >}}

带有 XLTX 扩展名的文件表示基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板文件。它用于创建一个标准模板文件，该文件可用于生成 XLSX 文件，这些文件具有与 XLTX 文件中指定的相同的设置。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 XLTX 转换为许多其他文件格式，包括下面列出的几种文件格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-bmp/" name="XLTX 转 BMP" description="位图图像" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-csv/" name="XLTX 转 CSV" description="逗号分隔值" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-dif/" name="XLTX 转 DIF" description="数据交换格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-emf/" name="XLTX 到 EMF" description="增强的元文件格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-gif/" name="XLTX 转 GIF" description="图形交换格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-html/" name="XLTX 转 HTML" description="超文本标记语言" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-jpeg/" name="XLTX 转 JPEG" description="JPEG图像" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-mhtml/" name="XLTX 转 MHTML" description="网页存档格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-ods/" name="XLTX 转 ODS" description="OpenDocument 电子表格文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-pdf/" name="XLTX 转 PDF" description="便携式文件格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-png/" name="XLTX转PNG" description="便携式网络图形" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-svg/" name="XLTX 转 SVG" description="可缩放矢量图形" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-tiff/" name="XLTX 转 TIFF" description="标记图像格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-tsv/" name="XLTX 转 TSV" description="制表符分隔值" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-txt/" name="XLTX 转 TXT" description="文本文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlm/" name="XLTX 转 XLM" description="Excel 宏文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xls/" name="XLTX 转 XLS" description="Excel 二进制格式" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlsb/" name="XLTX 转 XLSB" description="二进制 Excel 工作簿文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlsx/" name="XLTX 到 XLSX" description="OOXML Excel 文件" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlt/" name="XLTX 到 XLT" description="微软 Excel 模板" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xltm/" name="XLTX 到 XLTM" description="Excel 启用宏的模板" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xps/" name="XLTX 转 XPS" description="XML 纸张规格" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-json/" name="XLTX 转 JSON" description="JavaScript 对象表示法" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}