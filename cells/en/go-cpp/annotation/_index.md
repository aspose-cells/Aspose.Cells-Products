---
title: Add or Remove Excel File Annotations with Go via C++
description: Add or remove data annotation comments of Excel and OpenOffice spreadsheets with Go via C++ library.
keywords: [Go via C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Manage Microsoft<sup>&reg;</sup> Excel File Annotations with Go via C++ " h2="Add or remove simple notes for annotation or comments within Go via C++ based applications." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Go via C++ Excel API](/cells/go-cpp/) provides support to manage annotations at cell level by adding, accessing and removing comments. API provides [Comment](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/) and [CommentCollection](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/) as well as [GetComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/getcomments/) for handling comments in all aspects. Supported Excel formats include ODS, XLS, XLSX, XLSB and XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Excel Files Data Annotations" %}}
Manipulating Comments in Worksheets - It is not limited that how many comments a sheet has in MS Excel. One can insert as much as of application need. Process of inserting comments is, create [Workbook](https://reference.aspose.com/cells/go-cpp/aspose.cells/workbook/) class object to load an existing file and select worksheet where you want to add the comment. Get all of its comments using getComments(). Add the comment using [Add(const char16_t* cellName)](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/add/) method. Get the cell index and use [SetNote](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/setnote/) for inserting comments. Moreover, API is capable of removing all comments. Few of the methods are [ClearComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/clearcomments/) to Clears all comments in designer spreadsheet. Moreover, ***RemoveAt*** method to removes the element at a specified index or with specified name.

{{% blocks/products/pf/feature-page-code h3="Go via C++ Code to Add Comments Within Excel File" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-comment-in-excel.go" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation">}}

{{< /blocks/products/pf/feature-page-wrap >}}
