---
title: C# MYSQL do EXCEL - Konwerter MYSQL do EXCEL
description: Aspose Excel. Szybko i łatwo przekonwertuj MYSQL na EXCEL za pomocą Aspose.Cells. C# MYSQL na EXCEL. C# Zapisz MYSQL w formacie EXCEL. Zapisz MYSQL jako EXCEL, używając C#.
keywords: [Aspose Excel., C# Aspose.Cells., Convert MYSQL to EXCEL in C#., Save MYSQL to EXCEL using C#., C# MYSQL to EXCEL saveformat., MYSQL to EXCEL Converter., C# Save MYSQL as EXCEL]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj MYSQL na EXCEL w C#" h2="Szybka biblioteka C# do konwersji MYSQL na EXCEL. Jest to profesjonalne rozwiązanie do importowania i eksportowania plików EXCEL, MYSQL i wielu innych formatów na platformach .NET Framework, .NET Core lub Mono." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="MYSQL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EXCEL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Konwertuj MYSQL na EXCEL za pomocą C#" %}}
 Jak przekonwertować MYSQL na EXCEL? Dzięki bibliotece Aspose.Cells for .NET możesz łatwo programowo przekonwertować MYSQL na EXCEL za pomocą kilku linii kodu.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)potrafi budować aplikacje wieloplatformowe z możliwością generowania, modyfikowania, konwertowania, renderowania i drukowania wszystkich plików Excel. .NET Excel API nie tylko konwertuje pomiędzy formatami arkuszy kalkulacyjnych, ale może także renderować pliki Excel jako obrazy, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT i więcej, co czyni go idealnym wyborem do wymiany dokumentów w formatach będących standardami branżowymi. otwarty[NuGet](https://www.nuget.org/packages/aspose.cells) menedżer pakietów, wyszukaj Aspose.Cells i zainstaluj. Możesz także użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Polecenie konsoli Menedżera pakietów" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować MYSQL na EXCEL za pomocą C#" %}}

{{% blocks/products/pf/agp/text %}}

Chcesz programowo przekonwertować dane MYSQL na EXCEL? Programiści .NET mogą łatwo załadować i przekonwertować MYSQL na EXCEL w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

1.  Zainstaluj „Aspose.Cells for .NET”.
1.  Dodaj odniesienie do biblioteki (zaimportuj bibliotekę) do swojego projektu C#.
1.  Zapytanie o dane z bazy danych MYSQL w celu uzyskania obiektu DataTable.
1.  Utwórz nowy skoroszyt i zaimportuj dane z obiektu DataTable.
1. Zapisz dane w formacie xlsx wywołując metodę Workbook.Save.

{{% blocks/products/pf/agp/code-block title="Przykładowy kod do konwersji MYSQL na EXCEL - C#" offSpacer="" %}}

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

{{% blocks/products/pf/agp/content h2="Biblioteka C# do konwersji MYSQL na EXCEL" %}}

{{% blocks/products/pf/agp/text %}}

Istnieją dwie alternatywne opcje instalacji „Aspose.Cells for .NET” w systemie. Wybierz ten, który odpowiada Twoim potrzebom i postępuj zgodnie z instrukcjami krok po kroku:

{{% /blocks/products/pf/agp/text %}}

1.  Zainstaluj[NuGet Pakiet](https://www.nuget.org/packages/Aspose.Cells/) . Widzieć[Dokumentacja](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Zainstaluj bibliotekę za pomocą[Konsola menedżera pakietów](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) w środowisku Visual Studio IDE

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem przykładowego kodu konwersji .NET upewnij się, że spełnione są następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows lub kompatybilny system operacyjny z platformami .NET, .NET Core, Windows Azure lub Mono..
-  Środowisko programistyczne, takie jak Microsoft Visual Studio.
-  Dodaj odwołanie do biblioteki DLL Aspose.Cells for .NET w swoim projekcie.

{{% /blocks/products/pf/agp/content %}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
