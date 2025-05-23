---
title: Create HTM - Create HTM file in Node.js
description: Aspose Excel. Node.js Create HTM File quickly and easily with Aspose.Cells. Generate HTM file using Node.js. Create HTM in Node.js. Node.js HTM Creater. 
keywords: [Aspose Excel., Node.js Aspose.Cells., Node.js Create HTM file., Generate HTM file in Node.js., Create HTM file using Node.js., Write data to HTM file via Node.js., Create a HTM file in Node.js., Node.js Generate a HTM file., Node.js HTM Creater]
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Create HTM File in Node.js" h2="Native and high performance HTM file creation programmatically without Micorsoft Office using Node.js library." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Node.js" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/nodejs-cpp" installationsDocsLink="https://docs.aspose.com/cells/nodejs-cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/nodejs-cpp" learnAsLink="https://docs.aspose.com/cells/nodejs-cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Create HTM File Using Node.js" %}}

How to create HTM file? With Aspose.Cells for Node.js via C++ library, you can easily Create HTM file programmatically with  a few lines of code. [Aspose.Cells for Node.js via C++](https://products.aspose.com/cells/nodejs-cpp) is capable of building cross-platform applications with the ability to generate, modify, convert, render and print all Excel files. C++ Excel API not only convert between spreadsheet formats, it can also render Excel files as images, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT and more, thus making it a perfect choice to exchange documents in industry-standard formats. You can easily use Aspose.Cells for Node.js via C++ from <a href="https://www.npmjs.com/package/aspose.cells.node">NPM</a> with the following command, use command as: <code> $ npm install aspose.cells.node</code>.



{{% /blocks/products/pf/agp/content %}}                                                                             


{{% blocks/products/pf/agp/content h2="How to Create HTM in Node.js" %}}

{{% blocks/products/pf/agp/text %}}

 It is easy for the developers to create, load, modify and convert HTM files within running reporting applications for data processing in just few lines of code.

{{% /blocks/products/pf/agp/text %}}

1.  Create an object of the Workbook class.
1.  Get the first sheet into a Worksheet object.
1.  Use Worksheet.getCells() method to get the cells of the worksheet into a Cells object.
1.  Use Cells.get() method to access the desired cell of the worksheet into a Cell object.
1.  Use Cell.putValue() method to input value into the cell.
1.  Save the workbook as .htm file using Save() method.

{{% blocks/products/pf/agp/code-block title="Sample code shows how to create HTM file in Node.js." offSpacer="" %}}

```cs
const AsposeCells = require("aspose.cells.node");

// Create an object of the Workbook class.
var wkb = new AsposeCells.Workbook();
// Get the first sheet into an Worksheet object.
var wsc = wkb.getWorksheets();
var ws = wsc.get(0);

// Use Worksheet.getCells() method to get the cells of the worksheet into an Cells object.
var cells = ws.getCells();


// Use Cells.Get() method to access the desired cell of the worksheet into an Cell object.
var cell00 = cells.get(0, 0);
var cell01 = cells.get(0, 1);
var cell10 = cells.get(1, 0);
var cell11 = cells.get(1, 1);


// Use Cell.PutValue() method to input value into the cell.
cell00.putValue("ColumnA");
cell01.putValue("ColumnB");
cell10.putValue("ValueA");
cell11.putValue("ValueB");


// Save workbook to resultFile folder
wkb.save("created_one.htm");

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Node.js library to create HTM file" %}}

{{% blocks/products/pf/agp/text %}}
You can easily use Aspose.Cells for Node.js via C++ from NPM with the following command. See [Documentation](https://docs.aspose.com/cells/nodejs-cpp/getting-started/#install-from-npm)

{{% /blocks/products/pf/agp/text %}}
If you encounter any problems during the installation process, please refer to https://www.npmjs.com/package/package.

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Node.js via C++ is a feature-rich and scalable API to process Excel spreadsheets. Node.js API offers Excel file format conversion, worksheets styling to the most granular level, chart creation & rendering, reliable formula calculation engine and much more. Aspose.Cells for Node.js via C++ is platform independent API and can be used on any platform (Windows, Linux, MacOS etc.) where Node.js is installed.
 
{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/about-file-text fileFormat="HTM" readMoreLink="https://docs.fileformat.com/web/htm/" >}}Files with .htm extension represent Hypertext Markup Language for creating web pages for display in web browsers such as Google Chrome, Internet Explorer, Firefox and a number of others. It defines the markups for creating static pages to be published on World Wide Web (WWW) for access by others. These markups tell the browsers how to display a web page��s contents. Such pages can contain plain text, images, hyperlinks to other pages, videos and other media information. When a web page is published, you can have a look at the markup code behind it by viewing its page source. Modern browsers allow to inspect each section of a web page where each sub-division or markup element in the HTM source is elaborated.{{< /blocks/products/pf/agp/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Sheets Generation" subTitle="You can also create other Microsoft Excel files including few listed below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/xls/" name="XLS" description="Microsoft Excel Spreadsheet (Legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/xlsx/" name="XLSX" description="Open XML Workbook" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/xlsb/" name="XLSB" description="Excel Binary Workbook" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/xlsm/" name="XLSM" description="Macro-enabled Spreadsheet" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/xlt/" name="XLT" description="Excel 97 - 2003 Template" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/xltx/" name="XLTX" description="Excel Template" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/xltm/" name="XLTM" description="Excel Macro-Enabled Template" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/csv/" name="CSV" description="Comma Separated Values" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/tsv/" name="TSV" description="Tab Separated Values" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/ods/" name="ODS" description="OpenDocument Spreadsheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/pdf/" name="PDF" description="Portable Document Format" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/nodejs-cpp/create/html/" name="HTML" description="Hyper Text Markup Language" >}} 


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
