---
title: Manage Excel File Metadata via .NET C#
url: /net/metadata/
description: View, add, edit, remove or extract Excel files metadata with just few lines of C# code
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Manage Microsoft<sup>&reg;</sup> Excel File Metadata via .NET" h2="View, add, update, remove or extract built-in and custom Excel file properties using server side .NET APIs." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) supports the management of system-defined (built-in) properties such as title, author name, document statistics etc as well as user-defined (custom) properties in the form of name-value pair. There is [Workbook class](https://reference.aspose.com/cells/net/aspose.cells/workbook) to load the files, and [WorksheetCollection](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) deals with collection of worksheets as well as [Worksheet class](https://reference.aspose.com/cells/net/aspose.cells/worksheet) for representing single worksheet. Along with these classes, BuiltInDocumentProperties, CustomDocumentProperties makes the process simple for metadata management. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Managing Built-in Properties" %}}

For managing system-defined properties, API provides [BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties), and programmers can easily access a built-in property and update its value. Depending on application requirement, developers can use the index or property name from the [DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Code to Manage Builtin Properties" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata">}}
{{% blocks/products/pf/feature-page-section  h2="Managing Custom Defined Properties" %}}

For managing user-defined properties, API provides [CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties), and developers can easily access already added properties as well as add new properties. In order to add custom properties, [Add method](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) of [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class adds the property and returns a reference for the new property as an [Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) object. DocumentProperty class is used to retrieve the name, value, and type of the document property as [DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) that returns one of the [PropertyType](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) enumeration values. 
 
{{% blocks/products/pf/feature-page-code h3="C# Code to Add Metadata in Excel File" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}


{{% blocks/products/pf/feature-page-code h3="C# Code to Remove Custom Property in Excel File" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
