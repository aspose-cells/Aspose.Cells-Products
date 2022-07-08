---
title: Create Excel Files via Java
url: /java/assembly/
description: Generate Microsoft Excel spreadsheets from a template sheet using Java spreadsheet library
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Template Based Reports Creation via Java" h2="Generate bulk Excel file reports based on a predefined template within Java based applications." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel Library](/cells/java/) supports generating template based Excel files for bulk report generation. It is needed for most cases such as creating fee challans, result cards and patient records etc. Templates are predefined patterns. Below Java code generates the bulk excel files same as template document having filled with data. Supported file formats include XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Create Reports Based on Predesigned Excel Template" %}}

Using Java Assembly API developers can easily program the bulk report generation code by including the below code snippts. API provides [import data](https://docs.aspose.com/cells/java/import-and-export-data/) feature from different sources and create Excel documents depending on that data. For template based patterns, API provides a [WorkbookDesigner class](https://reference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner) to represent a designer worksheet. Process is, Create its object and use it to open template file. Set the datasource, that may be Array, DataTable, Json etc. Process it to import data and save the file in desired format. Programmers can assemble data into reports in other file formats including XLS, XLSX, XLSB, XLSM, ODS as of below listed links.



{{% blocks/products/pf/feature-page-code h3="Java Code to Create Excel Reports" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports">}}