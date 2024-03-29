---
title: Unlock XLSX document via .NET 
weight: 2040

description: C# source code to unlock password protected XLSX file on .NET Framework, .NET Core, Mono or Xamarin Platforms.
keywords: [C# Aspose.Cells., c# unlock XLSX files., c# how to unlock XLSX document., c# unprotect XLSX files., remove protection from XLSX files., decrypt XLSX Files using C#]
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Unlock XLSX Spreadsheet via C#" h2="Remove protection from XLSX using .NET library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Unlock XLSX File Using C#" %}}

 In order to remove protection XLSX file, we’ll use
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API which is a feature-rich, powerful and easy to use document protection API for C# platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 package manager, search for
 **Aspose.Cells** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Unlock XLSX via C#" %}}

{{% blocks/products/pf/agp/text %}}

 You need
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 referenced in your project to execute the following workflow.

{{% /blocks/products/pf/agp/text %}}

1.  Instantiate Workbook class with path to protected XLSX file
1.  Get the default or any Worksheet to remove protection
1.  Remove Worksheet protection with Worksheet.Unprotect method
1.  Remove Workbook protection with Workbook.Unprotect method
1.  Save result in XLSX format

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET is supported on all major operating systems. Just make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Mono or Xamarin Platforms
-  Development environment like Microsoft Visual Studio
-  Add reference to the Aspose.Cells for .NET DLL in your project

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="" %}}

```cs

// instantiate a Workbook object with protected XLSX file
var workbook = new Aspose.Cells.Workbook("protected.xlsx");

// access the default worksheet in the Excel file
var worksheet = workbook.Worksheets[0];

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in XLSX format
workbook.Save("unprotected.xlsx", Aspose.Cells.SaveFormat.Auto);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Cells for .NET API" %}}

 Aspose.Cells API can be used to create, edit, convert and render Microsoft Excel formats to different formats. Moreover, it can be used for comprehensive charting, scalable reporting and reliable calculations within software applications. Aspose.Cells is a standalone API and it does not require any software like Microsoft or OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Unlock XLSX" sectionDescription="Check our live demos to [unlock XLSX files](https://products.aspose.app/cells/unlock/xlsx) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload XLSX file and hit the \"Unlock\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant XLSX file from the link" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX is well-known format for Microsoft Excel documents that was introduced by Microsoft with the release of Microsoft Office 2007. Based on structure organized according to the Open Packaging Conventions as outlined in Part 2 of the OOXML standard ECMA-376, the new format is a zip package that contains a number of XML files. The underlying structure and files can be examined by simply unzipping the .xlsx file.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Unlocking Formats" subTitle="Using C#, one can easily remove protection / unlocking of different formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xls/" name="XLS" description="Excel Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsb/" name="XLSB" description="Binary Excel Workbook File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsm/" name="XLSM" description="Spreadsheet File" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
