---
title: Excel File Annotations via Java
url: /java/annotation/
description: Add or remove data annotation of Excel and OpenOffice spreadsheets with Java library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Manage Microsoft<sup>&reg;</sup> Excel File Annotations via Java" h2="Insert simple notes for annotation or delete Excel spreadsheet cell level comments within Java based applications." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) provides support to manage annotations at cell level by adding, accessing and deleting comments. API provides [Comment](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [CommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [ThreadedComment](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) and [ThreadedCommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) for handling comments in all aspects.
Supported file formats include ODS, XLS, XLSX, XLSB and XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Excel Files Data Annotations" %}}
Managing Comments in Worksheets - There is not any limit that how many comments a sheet has in MS Excel. One can add as much as of application requirement. Process of adding comments is, create [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class object or load an existing file using Workbook class. Access all of its comments using getComments(). Get the cell index and use [setNote](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) for inserting comments. Moreover, API is capable of removing all comments. 

{{% blocks/products/pf/feature-page-code h3="Java Code to Add Comments Within Excel File" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Java Code to Remove Comments Within Excel File" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation">}}