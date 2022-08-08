---
title: Generuj pliki Excela przez C#
url: /pl/net/assembly/
description: Generuj arkusze kalkulacyjne Microsoft Excel z arkusza szablonu za pomocą kodu C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Tworzenie plików na podstawie szablonu Excel za pomocą .NET" h2="Generuj raporty w plikach Excel na podstawie predefiniowanego szablonu w .NET aplikacjach opartych na" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteka Excela](/cells/net/) obsługuje generowanie plików Excel opartych na szablonach do zbiorczego generowania raportów. Szablony to wstępnie zaprojektowane formaty, używane do tworzenia raportów o tych samych wzorcach. Kod .NET tworzy nowy plik Excela taki sam jak dokument szablonu po wypełnieniu danymi. Obsługiwane formaty plików to XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Twórz raporty na podstawie wstępnie zaprojektowanego szablonu Excel" %}}

Aby zautomatyzować proces tworzenia tych samych plików wzorców, można łatwo użyć .NETZłożenia API. Istnieją różne sposoby, aby [zaimportować dane](https://docs.aspose.com/cells/net/import-data-into-worksheet/#importing-data-from-json) i generować pliki Excel. API zapewnia [WorkbookDesigner class](https://reference.aspose.com/cells/net/aspose.cells/workbookdesigner) do reprezentowania arkusza projektanta. Utwórz jego obiekt i użyj go do otwarcia pliku szablonu. Ustaw źródło danych, którym może być DataTable, Array, plik Json itp. Przetwórz je, aby zaimportować dane i zapisać plik z danymi w wymaganym formacie. Programiści mogą łączyć dane w raporty w innych formatach plików, korzystając z poniższych linków.



{{% blocks/products/pf/feature-page-code h3="C# Kod do generowania raportów Excel" %}}

{{< gist "aspose-com-gists" "5c193070f1b6acdc3eed001f52eadbc2" "generate-excel-reports.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Generate" afterslug="Reports" >}}