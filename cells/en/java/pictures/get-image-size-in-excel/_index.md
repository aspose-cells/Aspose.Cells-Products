---
title: Get Images/Pictures Size In Excel via Java 
weight: 10

description: Gets Images/Pictures size in Excel using Aspose.Cells' Java API without any software such as Microsoft or Open Office, Adobe PDF, etc.
keywords: [Java Aspose.Cells., Java Get Images/Pictures Size In Excel., Java Obtain Images/Pictures Size In Excel., Java Access Images/Pictures Size In Excel]
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Get Images/Pictures Size In Excel via Java" h2="Using Aspose.Cells' API to work with various objects without any software like Microsoft or Open Office, Adobe PDF, etc." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="How to get images/pictures size in Excel File Using Java" %}}

 In order to get images/pictures size in Excel File, we’ll use
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API which is a feature-rich, powerful and easy to use API for Java platform. You can download its latest version directly from
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 and install it within your Maven-based project by adding the following configurations to the pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

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

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to get images/pictures size in Excel file via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

+  Loading the XLSX file with full path.
+  Select Worksheet via its index.
+  Select picture object via its index from 'Pictures' attribute of Worksheet.
+  There are various ways to get the size from a selected picture object.The parts are listed below, for more information, please refer to [MORE](https://reference.aspose.com/cells/java/com.aspose.cells/picture/).Notice:'Width' and 'Height' are the dimensions shown in the excel may be larger or smaller than the original picture.
    + [Width](https://reference.aspose.com/cells/java/com.aspose.cells/picture/#getWidth--) Represents the width of shape, in unit of pixels.
    + [Height](https://reference.aspose.com/cells/java/com.aspose.cells/picture/#getHeight--) Represents the height of shape, in unit of pixel.
    + [OriginalWidth](https://reference.aspose.com/cells/java/com.aspose.cells/picture/#getOriginalWidth--) Gets the original width of the picture, in unit of pixels.
    + [OriginalHeight](https://reference.aspose.com/cells/java/com.aspose.cells/picture/#getOriginalHeight--) Gets the original height of the picture, in unit of pixels.


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows or a compatible OS with Java Runtime Environment for JSP/JSF Application and Desktop Applications.
- Get latest version of Aspose.Cells for Java directly from Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/text %}}
 
 There are also two size-related attributes 'getWidthScale()' and 'getHeightScale()', which respectively represent the percentages of the current display width and height to the actual width and height.
 It should be noted that there is a certain error in these two attribute values, please do not use them in the case of high precision requirements.
 
 The following code sample demonstrates how to get the size and display zoom ratio of an image/picture.

{{% /blocks/products/pf/agp/text %}}

{{% blocks/products/pf/agp/code-block title="Get size of images/pictures - Java" offSpacer="" %}}

{{< gist "aspose-cells-gists" "5876dc77e47649b66bdb5deefb4b5639" "GetPictureSize.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Cells for Java API" %}}

 Aspose.Cells API can be used to create, edit, convert and render Microsoft Excel formats to different formats. Moreover, it can be used for comprehensive charting, scalable reporting and reliable calculations within software applications. Aspose.Cells is a standalone API and it does not require any software like Microsoft or OpenOffice.  


    {{% /blocks/products/pf/agp/content %}}

    


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
