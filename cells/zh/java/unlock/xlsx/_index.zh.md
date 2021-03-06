---
title: 通过 Java 解锁 XLSX 文档 
weight: 310
url: /zh/java/unlock/xlsx/ 
description: Java 示例代码，用于在 Java JSP/JSF 应用程序和桌面应用程序的运行时环境中解锁受密码保护的 XLSX 文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 Java 解锁 XLSX 文件" h2="使用 Java 库从 Excel 电子表格（包括 XLSX 文件）中删除保护。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 删除保护 XLSX 文件" %}}

 为了解锁 XLSX 文件，我们将使用
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API 是一个功能丰富、功能强大且易于使用的保护API for Java 平台。您可以直接从
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

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 解锁 XLSX 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. 使用受保护的 XLSX 文件的路径实例化工作簿类1. 获取默认或任何工作表以删除保护1. 使用 Worksheet.Unprotect 方法删除工作表保护1. 使用 Workbook.Unprotect 方法删除工作簿保护1. 以 XLSX 格式保存结果
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java 支持所有主要平台和操作系统。请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="通过 C# 解锁 XLSX 文件" offSpacer="" %}}

```cs

Workbook wkb = new Workbook("source.xlsx");

WorksheetCollection wksc = wkb.getWorksheets();
Worksheet wks = wksc.get(0);

// 解除对 XLSX 的保护
wks.unprotect();

// 保存 XLSX 文件。
wkb.save("Worksheet_out.xlsx", FileFormatType.EXCEL_97_TO_2003);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="关于Aspose.Cells for Java API" %}}

 Aspose.Cells API 可用于创建、编辑、转换 Microsoft Excel 格式并将其呈现为不同的格式。此外，它还可用于软件应用程序中的综合图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何软件，如 Microsoft 或 OpenOffice。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="解锁 XLSX 的免费应用程序" sectionDescription="查看我们的现场演示 [解锁 XLSX 文件](https://products.aspose.app/cells/unlock/xlsx) 具有以下好处。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载或设置任何东西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写或编译代码" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传 XLSX 文件并点击“解锁”按钮" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" 从链接下载生成的 XLSX 文件" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX 是 Microsoft 在 Microsoft Office 2007 发布时引入的 Microsoft Excel 文档的众所周知的格式。基于根据 OOXML 标准 ECMA-376 第 2 部分中概述的开放打包约定组织的结构，新格式为一个包含许多 XML 文件的 zip 包。只需解压缩 .xlsx 文件即可检查底层结构和文件。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的解锁格式" subTitle="使用 Java，可以轻松移除不同格式的保护/解锁，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/ods/" name="消耗臭氧层物质" description="OpenDocument 电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xls/" name="XLS" description="Excel 二进制格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsb/" name="XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsm/" name="XLSM" description="电子表格文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}