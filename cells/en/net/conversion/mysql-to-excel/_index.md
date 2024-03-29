---
title: C# MYSQL to EXCEL - MYSQL to EXCEL Converter
description: Aspose Excel. Convert MYSQL to EXCEL quickly and easily with Aspose.Cells. C# MYSQL to EXCEL. C# Save MYSQL to EXCEL. Save MYSQL as EXCEL using C#.
keywords: [Aspose Excel., C# Aspose.Cells., Convert MYSQL to EXCEL in C#., Save MYSQL to EXCEL using C#., C# MYSQL to EXCEL saveformat., MYSQL to EXCEL Converter., C# Save MYSQL as EXCEL]
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert MYSQL to EXCEL in C#" h2="High-speed C# library for converting MYSQL to EXCEL. This is a professional software solution to import and export EXCEL, MYSQL, and many other formats on .NET Framework, .NET Core or Mono Platforms." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="MYSQL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EXCEL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Convert MYSQL to EXCEL Using C#" %}}
How do I convert MYSQL to EXCEL? With Aspose.Cells for .NET library, you can easily convert MYSQL to EXCEL programmatically with  a few lines of code. [Aspose.Cells for .NET](https://products.aspose.com/cells/net) is capable of building cross-platform applications with the ability to generate, modify, convert, render and print all Excel files. .NET Excel API not only convert between spreadsheet formats, it can also render Excel files as images, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT and more, thus making it a perfect choice to exchange documents in industry-standard formats. Open [NuGet](https://www.nuget.org/packages/aspose.cells) package manager, search for Aspose.Cells and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="How to Convert MYSQL to EXCEL via C#" %}}

{{% blocks/products/pf/agp/text %}}

Need to convert MYSQL data to EXCEL programmatically? .NET developers can easily load & convert MYSQL to EXCEL in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1.  Install 'Aspose.Cells for .NET'.
1.  Add a library reference (import the library) to your C# project.
1.  Query data from the MYSQL database to obtain a DataTable object.
1.  Create a new Workbook and import data from a DataTable object.
1.  Save data to xlsx format by calling Workbook.Save method.

{{% blocks/products/pf/agp/code-block title="Sample Code to Convert MYSQL to EXCEL - C#" offSpacer="" %}}

```cs
var connectionString = "server=localhost;port=3306;user=root;password=root;database=testdb;charset=utf8mb4;";
var tableName = "areas";

string query = $"SELECT * FROM {tableName}";

using (MySqlConnection connection = new MySqlConnection(connectionString))
{
    connection.Open();
    MySqlCommand cmd = new MySqlCommand(query, connection);
    MySqlDataAdapter adapter = new MySqlDataAdapter(cmd);

    DataTable dataTable = new DataTable();
    adapter.Fill(dataTable);

    Workbook workbook = new Workbook();
    Worksheet worksheet = workbook.Worksheets[0];
    worksheet.Cells.ImportData(dataTable, 0, 0, new ImportTableOptions() { InsertRows = true });
    workbook.Save("MySQLData.xlsx");
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="C# library to convert MYSQL to EXCEL" %}}

{{% blocks/products/pf/agp/text %}}

There are two alternative options to install "Aspose.Cells for .NET" onto your system. Please choose one that resembles your needs and follow the step-by-step instructions:

{{% /blocks/products/pf/agp/text %}}

1.  Install a [NuGet Package](https://www.nuget.org/packages/Aspose.Cells/). See [Documentation](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Install the library using [Package Manager Console](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) within Visual Studio IDE

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before running the .NET conversion example code, make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET, .NET Core, Windows Azure or Mono Platforms..
-  Development environment like Microsoft Visual Studio.
-  Add reference to the Aspose.Cells for .NET DLL in your project. 

{{% /blocks/products/pf/agp/content %}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
