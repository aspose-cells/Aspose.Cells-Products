---
title: Search XLSX document without opening via C++ 
weight: 9280

description: C++ example code to search words with pattern in XLSX file on C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ search words with pattern in XLSX file., C++ find words with pattern in XLSX file., C++ search string with pattern in XLSX file., C++ find words with pattern in XLSX file., C++ search words in excel file., C++ find words in excel file., C++ search string in excel file., C++ find string in excel file]
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Search XLSX Formats in C++" h2="Native and high performance XLSX document search using server-side Aspose.Cells for C++ APIs, without the use of any software like Microsoft or Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Search XLSX File Using C++" %}}

 In order to search XLSX file, we’ll use
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API which is a feature-rich, powerful and easy to use document searching API for C++ platform. You can download its latest version directly, just open
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 package manager, search for
 **Aspose.Cells.Cpp** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Search XLSX Files in C++" %}}

{{% blocks/products/pf/agp/text %}}

 A basic document search using Aspose.Cells APIs can be done with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

+  Load XLSX file using Workbook class.
+  Get the cells in relevant sheet.
+  Search Numbers, Date and Text using Find method

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
-  Add reference to the Aspose.Cells for C++ DLL in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Search XLSX Files - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// searching cells containing specified string value or number
Workbook workbook("book1.xlsx");

// get cells collection
Cells cells = workbook.GetWorksheets().Get(0).GetCells();

FindOptions opts;
opts.SetLookInType(LookInType::Values);
opts.SetLookAtType(LookAtType::EntireContent);

// find the cell with the input integer or double
Cell cell1 = cells.Find(205, nullptr, opts);

if (!cell1.IsNull()) {
	std::cout << "Name of the cell containing the value: " << cell1.GetName().ToUtf8() << std::endl;
}
else {
	std::cout << "Record not found " << std::endl;
}

// find the cell with the input string
Cell cell2 = cells.Find(u"Items A", nullptr, opts);

if (!cell2.IsNull()) {
	std::cout << "Name of the cell containing the value: " + cell2.GetName().ToUtf8() << std::endl;
}
else {
	std::cout << "Record not found " << std::endl;
}

// find the cell containing with the input string
opts.SetLookAtType(LookAtType::Contains);
Cell cell3 = cells.Find(u"Data", nullptr, opts);

if (!cell3.IsNull()) {
	std::cout << "Name of the cell containing the value: " + cell3.GetName().ToUtf8() << std::endl;
}
else {
	std::cout << "Record not found " << std::endl;
}

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="About Aspose.Cells for C++ API" %}}

 Aspose.Cells API can be used to create, edit, convert and render Microsoft Excel formats to different formats. Moreover, it can be used for comprehensive charting, scalable reporting and reliable calculations within software applications. Aspose.Cells is a standalone API and it does not require any software like Microsoft or OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSX Search Live Demos" sectionDescription="Search text, words, phrases within XLSX documents right now by visiting our [Live Demos website](https://products.aspose.app/cells/search). The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your XLSX files." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Search result appears instantly." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/about-file-text fileFormat="XLSX " readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX is well-known format for Microsoft Excel documents that was introduced by Microsoft with the release of Microsoft Office 2007. Based on structure organized according to the Open Packaging Conventions as outlined in Part 2 of the OOXML standard ECMA-376, the new format is a zip package that contains a number of XML files. The underlying structure and files can be examined by simply unzipping the .xlsx file 

    {{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Search Documents" subTitle="Using C++, one can also search other files including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="Comma Separated Values" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="Tab-Separated Values" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="Text Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Excel Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="Binary Excel Workbook File" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
