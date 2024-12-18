---
title: Manage Excel File Metadata with Go via C++

description: View, add, edit, remove or extract Excel files metadata using Go via C++ library
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Manage Microsoft<sup>&reg;</sup> Excel Document Metadata via Go via C++" h2="View, insert, update, remove or extract custom and built-in Excel document properties within C++ applications." >}}
{{% blocks/products/pf/feature-page-summary %}}
Metadata in Excel - How to view, insert and remove excel file metadata. [Go via C++ Excel Library](/cells/go-cpp/) faclitates is in easy way by supporting the built-in / system-defined properties such as author name, title, document statistics etc needed sometime like to check when lastly file is modified or saved along with custom / user-defined properties in the form of name/value pairs. To automate the process, library supports creating and maintaining large metadata Excel files. [Workbook](https://reference.aspose.com/cells/go-cpp/workbook/) class Opens a workbook by path, by stream and by special FileFormatType. So load the file with appropraite method for further processing. Few of the possibilities listed below and developers can easily enhance their code according to application requirement.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Read and Update Builtin Properties" %}}

For automating the built-in properties, API provides [GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) method that returns a DocumentProperties collection representing all the built-in document properties of the spreadsheet. After accessing all the builtin properties, access the relevant properties using relevant method such as GetTitle(), GetSubject() etc. To update the properties, API provides method such as SetTitle, SetSubject, SetAuthor, SetComments etc. View the [builtin document property collection](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) for required function.

{{% blocks/products/pf/feature-page-code h3="Go via C++ Code to Read System Defined Properties" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Go via C++ Code to Update Builtin Properties" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code  %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata">}}
{{% blocks/products/pf/feature-page-section  h2="View and Add Custom Defined Properties" %}}

For handling custom properties, API provides [Workbook::GetCustomDocumentProperties](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/) that returns all the custom document properties collection of the spreadsheet. Firstly accessing the custom properties via this method, developers can use relevant methods to add properties like AddIDocumentProperty, AddLinkToContentProperty and similarly use UpdateLinkedPropertyValue, UpdateLinkedRange to update custom document property value which links to content and  to linked range respectively. Developers can use relevant method from [collection of custom document properties](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Go via C++ Code to View Custom Properties" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% blocks/products/pf/feature-page-code h3="Go via C++ Code to Add Metadata in Excel File" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}