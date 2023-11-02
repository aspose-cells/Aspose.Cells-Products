---
title: Split Excel Spreadsheet into Worksheets in Java

description: Java source codes that explains how to split Microsoft Excel files into multiple documents using Java Excel library
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel File Splitting via Java" h2="Split Excel spreadsheet into worksheets within Java based applications" >}}
{{% blocks/products/pf/feature-page-summary %}}
There are variety of scenarios, When there is need to split Excel files like a spreadsheet containing students data with allocation of single sheet for each student. And there is need to split each sheet student wise as a separate file. To automate it via Java application, [Java Excel API](/cells/java/) is there to split Excel document sheetwise. Supported formats include XLS, XLSX, XLSB, XLSM, ODS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Split Excel Document into Multiple Files" %}}

The simplest way to split Excel file into sheet is, Access all sheets, iterate through each sheet and save one by one in the desired format. For loading the worksheet, API provides [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class. [getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) method gets total number of sheets. Iterate through each sheet and use [getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) for accessing specific sheet. Move the selected sheet data into newly created Workbook class object by using [Copy method](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Finally save it into required format.

{{% blocks/products/pf/feature-page-code h3="Java Code to Split Excel Files" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter">}}

{{% blocks/products/pf/feature-page-section  h2="Split Excel Worksheet into Panes" %}}

API also provides functionality of splitting Excel worksheet into different panes. Process is, Load the file using Workbook class. Select first worksheet or any required sheet by providing its index. Call the setActiveCell having relevant cell index as parameter. And finally split the worksheet window into different panes by calling split() method.

{{% blocks/products/pf/feature-page-code h3="Java Code to Split Excel Sheet into Pane View" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
