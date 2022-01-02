---
title: Manage Excel File Metadata via Java
url: /java/metadata/
description: View, add, edit, remove or extract Excel files metadata with just few lines of Java code
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Manage Microsoft<sup>&reg;</sup> Excel File Metadata via Java" h2="View, add, update, delete or extract custom and built-in Excel file properties using server side Java APIs." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) supports the management of built-in (system-defined) properties such as title, author name, document statistics etc as well as custom (user-defined) properties in the form of name/value pair. There is [Workbook class](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) to load the files, and [WorksheetCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) deals with collection of worksheets as well as [Worksheet class](https://apireference.aspose.com/cells/java/com.aspose.cells/Worksheet) for representing single worksheet. For accessing builtin and custom properties, BuiltInDocumentProperties, CustomDocumentProperties makes the process simple for metadata management. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Managing System Defined Properties" %}}

For managing built-in properties, API provides [BuiltInDocumentProperties](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties), and programmers can easily access a built-in property and update its value. Depending on application requirement, developers can use the index or property name from the [DocumentPropertyCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Code to Manage System Defined Properties" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata">}}
{{% blocks/products/pf/feature-page-section  h2="Managing Custom Defined Properties" %}}

For handling custom properties, API provides [CustomDocumentProperties](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties), and developers can easily access existing properties as well as add new properties using [add method](https://apireference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) of [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class adds the property and returns a reference for the new property as an [Properties.DocumentProperty](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) object. DocumentProperty class is used to retrieve the name, value, and type of the document property as [DocumentProperty.Name](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) that returns one of the [PropertyType](https://apireference.aspose.com/cells/java/com.aspose.cells/PropertyType) enumeration values. 
 
{{% blocks/products/pf/feature-page-code h3="Java Code to Add Metadata in Excel File" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}


{{% blocks/products/pf/feature-page-code h3="Java Code to Delete Custom Property in Excel File" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
