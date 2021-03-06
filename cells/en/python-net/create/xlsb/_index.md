---
title: Create MS Excel XLSB Files via Python 
url: /python-net/create-xlsb/ 
description: Python Sample code for generating XLSB documents. Use this code for creating MS Excel XLSB files within Python application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Create XLSB Documents via Python" h2="Native and high performance MS Excel XLSB spreadsheet creation programmatically using Python APIs." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/python-net" installationsDocsLink="https://docs.aspose.com/cells/python-net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/python-net" learnAsLink="https://docs.aspose.com/cells/python-net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Generating MS Excel XLSB file dynamically within running application is easy. In order to create XLSB documents from scratch without requiring MS Office, we will use
 [Aspose.Cells for Python](https://pypi.org/project/aspose-cells) 
 API that offers different features for spreadsheets creation, manipulation and conversion using Python platform. Developers can easily enhance code for writing data, generating charts or graphs as well as creating table in spreadsheets.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="How to Create XLSB via Python" %}}

{{% blocks/products/pf/agp/text %}}

 It is easy for the developers to create, load, modify and convert MS Excel XLSB spreadsheet within running different reporting applications for data processing in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1.  Import asposecells in your code file.
1.  Create Workbook class instance.
1.  Access the first worksheet of the workbook.
1.  Get the desired cell(s) of the worksheet and input the value into the cell(s).
1.  Use Save method to save the workbook as XLSB file.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Python via .NET is platform-independent API and can be used on any platform (Windows, Linux), just make sure that system have [Python](https://www.python.org/downloads/) 3.7 or higher. 

{{% /blocks/products/pf/agp/text %}}


- Install Aspose.Cells for Python via .NET from <a href="https://pypi.org/project/aspose-cells-python/">pypi</a>, use command as: <code>$ pip install aspose-cells-python</code>.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Following source code shows how to create a MS Excel XLSB file using Python." offSpacer="" %}}

```cs

import aspose.cells
from aspose.cells import Workbook, FileFormatType

// Create Workbook object.
workbook = Workbook(FileFormatType.XLSB)

// Access the first worksheet of the workbook.
worksheet = workbook.worksheets.get(0)

// Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.cells.get("A1").put_value("ColumnA")
worksheet.cells.get("B1").put_value("ColumnB")
worksheet.cells.get("A2").put_value("ValueA")
worksheet.cells.get("B2").put_value("ValueB")

// Save the workbook as XLSB file.
workbook.save("output.xlsb")

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 An Excel Spreadsheet Programming Library capable of building cross-platform applications with the ability to generate, modify, convert, render and print MS Excel XLSB files. Python API not only convert between spreadsheet formats, it can also render Excel files as images, PDF, HTML, ODS and more, thus making it a perfect choice to exchange documents in industry-standard formats.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
XLSB file format specifies the Excel Binary File Format, which is a collection of records and structures that specify Excel workbook content. The content can include unstructured or semi-structured tables of numbers, text, or both numbers and text, formulas, external data connections, charts and images. Unlike XLSX (which is based on Open XML file format), the XLSB represents binary Excel workbook file. XLSB files can be read and written to faster which makes them useful for working with large files. XLSB is seldom used to store workbooks as XLSX (and previously XLS) are the most common user selected file formats for saving workbooks. It can be opened by Microsoft Office 2007 and above.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}   

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Spreadsheet Generation" subTitle="You can also create other Microsoft Excel formats including few listed below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create-xls/" name="XLS" description="Microsoft Excel Spreadsheet (Legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create-xlsx/" name="XLSX" description="Open XML Workbook" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create-xlsb/" name="XLSB" description="Excel Binary Workbook" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create-xlsm/" name="XLSM" description="Macro-enabled Spreadsheet" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create-xlt/" name="XLT" description="Excel 97 - 2003 Template" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create-xltx/" name="XLTX" description="Excel Template" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create-xltm/" name="XLTM" description="Excel Macro-Enabled Template" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create-csv/" name="CSV" description="Comma Separated Values" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create-tsv/" name="TSV" description="Tab Separated Values" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-net/create-ods/" name="ODS" description="OpenDocument Spreadsheet" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
