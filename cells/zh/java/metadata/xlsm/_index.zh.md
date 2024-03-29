---
title: 编辑或查看 XLSM 文件元数据 via Java
weight: 9030
description: Java 用于在 JSP/JSF 应用程序和桌面应用程序的 Java 运行时环境上编辑或查看 XLSM 格式元数据的示例代码。
keywords: [Java Aspose.Cells., Java view xlsm metadata., Java add xlsm metadata., Java insert xlsm metadata., Java edit xlsm metadata., Java remove xlsm metadata., Java extract xlsm metadata., Java modify xlsm metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="提取 XLSM 元数据 via Java" h2="构建您自己的 Java 应用程序，以使用服务器端 API 添加、编辑、删除或提取 XLSM 文件中的元数据。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 提取 XLSM 元数据" %}}

为了获取 XLSM 文件元数据，我们将使用
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
API 这是一个功能丰富、功能强大且易于使用的元数据API for Java 平台。您可以直接从以下位置下载其最新版本
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
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

{{% blocks/products/pf/agp/code-block title="依赖性" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="提取 XLSM via Java 元数据的步骤" %}}

{{% blocks/products/pf/agp/text %}}

访问 XLSM 文件中存储的有用信息，包括 XLSM 文件的接收时间、处理时间、时间戳等。

{{% /blocks/products/pf/agp/text %}}

在 WorkbookMetadata 中加载 XLSM 文件
使用相关选项创建 MetadataOptions 对象
设置相关属性
保存XLSM元数据信息

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Java 支持所有主要平台和操作系统。请确保您具备以下先决条件。

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows 或具有 Java JSP/JSF 应用程序和桌面应用程序运行时环境的兼容操作系统。
- 直接从 Aspose.Cells for Java 获取最新版本
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="提取 XLSM - Java 的元数据" offSpacer="" %}}

```cs

// Open Workbook metadata
MetadataOptions options = new MetadataOptions(MetadataType.DOCUMENT_PROPERTIES);
WorkbookMetadata meta = new WorkbookMetadata("Sample1.xlsm", options);

// Set some properties
meta.getCustomDocumentProperties().add("test", "test");

// Save the metadata info
meta.save("Sample1.out.xlsm");

// Open the workbook
Workbook w = new Workbook("Sample1.out.xlsm");

// Read document property
System.out.println(w.getCustomDocumentProperties().get("test"));  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="关于 Aspose.Cells for Java API" %}}

 Aspose.Cells API 可用于创建、编辑、转换和渲染 Microsoft Excel 格式为不同的格式。此外，它还可用于软件应用程序中的全面图表、可扩展报告和可靠计算。 Aspose.Cells 是一个独立的 API，它不需要任何像 Microsoft 或 OpenOffice 这样的软件。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="通过在线应用程序提取 XLSM 的元数据" sectionDescription="使用我们的查看和编辑 XLSM 文档的元数据[现场演示](https://products.aspose.app/cells/metadata)具有以下好处。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="无需下载或设置任何东西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="无需编写任何代码" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上传您的 XLSM 文件并编辑文档属性" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="立即获取结果文件的下载链接" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
扩展名为 XLSM 的文件是一种支持宏的电子表格文件。从应用程序的角度来看，宏是用于自动化流程的指令集。宏用于记录重复执行的步骤，并通过再次运行宏来方便执行操作。宏是使用 Visual Basic 编辑器在 Excel 工作簿中使用 Microsoft 的 Visual Basic for Applications (VBA) 进行编程的，并且可以直接从那里运行/调试。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的元数据格式" subTitle="使用Java，人们还可以操作许多其他格式的元数据，包括" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/ods/" name="ODS" description="OpenDocument 电子表格文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xls/" name="XLS" description="Excel 二进制格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsb/" name="XLSB" description="二进制 Excel 工作簿文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsx/" name="XLSX" description="OOXML Excel 文件" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
