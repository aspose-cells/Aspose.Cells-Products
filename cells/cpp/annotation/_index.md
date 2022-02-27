---
title: Excel File Annotations via C++
url: /cpp/annotation/
description: Add or remove data annotation comments of Excel and OpenOffice spreadsheets with C++ library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Manage Microsoft<sup>&reg;</sup> Excel File Annotations via C++" h2="Add or remove simple notes for annotation or comments within C++ based applications." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) provides support to manage annotations at cell level by adding, accessing and removing comments. API provides [IComment](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) and [ICommentCollection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) as well as [GetIComments()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) for handling comments in all aspects. Supported Excel formats include ODS, XLS, XLSX, XLSB and XLSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Excel Files Data Annotations" %}}
Manipulating Comments in Worksheets - It is not limited that how many comments a sheet has in MS Excel. One can insert as much as of application need. Process of inserting comments is, create [IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class object to load an existing file and select worksheet where you want to add the comment. Get all of its comments using getComments(). Add the comment using [Add](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > cellName) method. Get the cell index and use [setNote](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) for inserting comments. Moreover, API is capable of removing all comments. Few of the methods are [ClearComments()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) to Clears all comments in designer spreadsheet. Moreover, [RemoveAt](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) method to removes the element at a specified index or with specified name.

{{% blocks/products/pf/feature-page-code h3="C++ Code to Add Comments Within Excel File" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation">}}