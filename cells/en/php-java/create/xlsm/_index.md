---
title: Create XLSM - Create XLSM file in PHP
description: Aspose Excel. PHP Create XLSM File quickly and easily with Aspose.Cells. Generate XLSM file using PHP. Create XLSM in PHP. PHP XLSM Creater. 
keywords: [Aspose Excel., PHP Aspose.Cells., PHP Create XLSM file., Generate XLSM file in PHP., Create XLSM file using PHP., Write data to XLSM file via PHP., Create a XLSM file in PHP., PHP Generate a XLSM file., PHP XLSM Creater]
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Create XLSM File in PHP" h2="High-speed PHP library for creating XLSM file. This is a professional software solution to import and export XLSX, PDF, and many other formats using PHP." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-php-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for PHP" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-php-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/php-java" installationsDocsLink="https://docs.aspose.com/cells/php-java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/php-java" learnAsLink="https://docs.aspose.com/cells/php-java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Create XLSM File Using PHP" %}}

How to create XLSM file? With Aspose.Cells for PHP via Java library, you can easily create XLSM file programmatically with  a few lines of code. [Aspose.Cells for PHP via Java](https://products.aspose.com/cells/php-java/) is capable of building cross-platform applications with the ability to generate, modify, convert, render and print all Excel files. PHP Excel API not only convert between spreadsheet formats, it can also render Excel files as images, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT and more, thus making it a perfect choice to exchange documents in industry-standard formats. 


{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="How to Create XLSM in PHP" %}}

{{% blocks/products/pf/agp/text %}}

 It is easy for the developers to create, load, modify and convert XLSM files within running different reporting applications for data processing in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1.  Install 'Aspose.Cells for PHP via Java'.
1.  Add a library reference (import the library) to your PHP project.
1.  Create an instance of [Workbook](https://reference.aspose.com/cells/php/aspose.cells/Workbook) class.
1.  Access the relevant worksheet using getWorksheets.get() method.
1.  Select the relevant cell, input the value into the desired cell using the cell name, like A1, B3, etc.
1.  Save the workbook as XLSM format using the save() method.

{{% blocks/products/pf/agp/code-block title="Sample code shows how to create XLSM file in PHP." offSpacer="" %}}

```python

require_once("Java.inc");
require_once("lib/aspose.cells.php");

use aspose\cells;
use aspose\cells\Workbook;


$workbook = new Workbook();
$sheets = $workbook->getWorksheets();
$cells = $sheets->get(0)->getCells();

// Add relevant content in the cell
$cells->get("A1")->putValue("ColumnA");
$cells->get("B1")->putValue("ColumnB");
$cells->get("A2")->putValue("ValueA");
$cells->get("B2")->putValue("ValueB");


// Save the workbook as XLSM file
$workbook->save("Excel.xlsm"); 

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="PHP library to create XLSM file" %}}

{{% blocks/products/pf/agp/text %}}

There are three options to install "Aspose.Cells for PHP via Java" onto your system. Please choose one that resembles your needs and follow the step-by-step instructions:

{{% /blocks/products/pf/agp/text %}}

1.  Install Aspose.Cells for PHP via Java in Windows. See [Documentation](https://docs.aspose.com/cells/php-java/setup-and-installation-guidelines/#windows)
1.  Install Aspose.Cells for PHP via Java in Linux. See [Documentation](https://docs.aspose.com/cells/php-java/setup-and-installation-guidelines/#linux)
1.  Install Aspose.Cells for PHP via Java in macOS. See [Documentation](https://docs.aspose.com/cells/php-java/setup-and-installation-guidelines/#mac)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for PHP via Java is platform independent API and can be used on any platform (Windows, Linux, MacOS etc.) where PHP 7 or greater versions is installed. The machine must have Oracle JDK 7 or greater versions before setting up the installation.
 
{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}Files with XLSM extension is a type of Spreadsheet files that support Macros. From application point of view, a Macro is set of instructions that are used for automating processes. A macro is used to record the steps that are performed repeatedly and facilitates performing the actions by running the macro again. Macros are programmed with Microsoft’s Visual Basic for Applications (VBA) from within the Excel Workbook using the Visual Basic Editor and can be run/debug directly from there.{{< /blocks/products/pf/agp/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Spreadsheet Generation" subTitle="You can also create other Microsoft Excel formats including few listed below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/xls/" name="XLS" description="Microsoft Excel Spreadsheet (Legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/xlsx/" name="XLSX" description="Open XML Workbook" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/xlsb/" name="XLSB" description="Excel Binary Workbook" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/xlsm/" name="XLSM" description="Macro-enabled Spreadsheet" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/xlt/" name="XLT" description="Excel 97 - 2003 Template" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/xltx/" name="XLTX" description="Excel Template" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/xltm/" name="XLTM" description="Excel Macro-Enabled Template" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/csv/" name="CSV" description="Comma Separated Values" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/tsv/" name="TSV" description="Tab Separated Values" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/ods/" name="ODS" description="OpenDocument Spreadsheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/pdf/" name="PDF" description="Portable Document Format" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/php-java/create/html/" name="HTML" description="Hyper Text Markup Language" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
