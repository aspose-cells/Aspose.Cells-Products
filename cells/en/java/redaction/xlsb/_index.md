---
title: Search and replace text in XLSB document via Java 
weight: 4590

description: Java sample code to redact sensitive information in XLSB file on Java Runtime Environment for JSP/JSF Application and Desktop Applications.
keywords: [Java Aspose.Cells., Java Search and replace text in XLSB file., Java redact XLSB file., Java edit XLSB file., Java XLSB file redaction., Java Search and replace string in XLSB file]
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Redact XLSB Formats in Java" h2="Native and high performance XLSB document sensitive redaction information using server-side Aspose.Cells for Java APIs, without the use of any software like Microsoft or Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="How to Redact XLSB File Using Java" %}}

 In order to redact XLSB file, we’ll use [Aspose.Cells for Java](https://products.aspose.com/cells/java) API which is a feature-rich, powerful and easy to use redaction API for Java platform. You can download its latest version directly from [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) and install it within your Maven-based project by adding the following configurations to the pom.xml.

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

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Redact XLSB Files in Java" %}}

{{% blocks/products/pf/agp/text %}}

 A basic document search and replace text in contents, comments or metadata with [Aspose.Cells for Java](https://products.aspose.com/cells/java) APIs can be done with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

+  Load XLSB file.
+  Select the relevant sheet.
+  Define and Specity FindOptions.
+  Specify the range where you want to search
+  Loop through each cell and use getCells().find(...).
+  Replace the value.
+  Save the workbook.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with Java Runtime Environment for JSP/JSF Application and Desktop Applications.
-  Get latest version of Aspose.Cells for Java directly from
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Redact XLSB Files - Java" offSpacer="" %}}

```cs
Workbook workbook = new Workbook(dataDir + "sourceFile.xlsb");

Worksheet worksheet = workbook.getWorksheets().get(0);

// Specify the range where you want to search
// Here the range is E3:H6
CellArea area = CellArea.createCellArea("E3", "H6");

// Specify Find options
FindOptions opts = new FindOptions();
opts.setLookInType(LookInType.VALUES);
opts.setLookAtType(LookAtType.ENTIRE_CONTENT);
opts.setRange(area);

Cell cell = null;

do {
	// Search the cell with value search within range
	cell = worksheet.getCells().find("search", cell, opts);

	// If no such cell found, then break the loop
	if (cell == null)
		break;

	// Replace the cell with value replace
	cell.putValue("replace");

} while (true);

// Save the workbook
workbook.save(dataDir + "output.xlsb");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="About Aspose.Cells for Java API" %}}

 Aspose.Cells API can be used to create, edit, convert and render Microsoft Excel formats to different formats. Moreover, it can be used for comprehensive charting, scalable reporting and reliable calculations within software applications. Aspose.Cells is a standalone API and it does not require any software like Microsoft or OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSB Redaction Live Demos" sectionDescription="Search and replace text in contents, comments or metadata in XLSB documents right now by visiting our [Live Demos website](https://products.aspose.app/cells/redaction). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your XLSB files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be redacted instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB file format specifies the Excel Binary File Format, which is a collection of records and structures that specify Excel workbook content. The content can include unstructured or semi-structured tables of numbers, text, or both numbers and text, formulas, external data connections, charts and images. Unlike XLSX (which is based on Open XML file format), the XLSB represents binary Excel workbook file. XLSB files can be read and written to faster which makes them useful for working with large files. XLSB is seldom used to store workbooks as XLSX (and previously XLS) are the most common user selected file formats for saving workbooks. It can be opened by Microsoft Office 2007 and above. 

    {{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Redaction Documents" subTitle="Using Java, one can easily redact different formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xls/" name="XLS" description="Excel Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsm/" name="XLSM" description="Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsx/" name="XLSX" description="OOXML Excel File" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
