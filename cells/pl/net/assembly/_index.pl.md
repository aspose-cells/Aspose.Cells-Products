---
title: Wygeneruj pliki Excela pod numerem C#
description: Wygeneruj arkusze kalkulacyjne Excel Microsoft z arkusza szablonu, używając kodu C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Tworzenie plików na podstawie szablonu programu Excel via .NET" h2="Generuj raporty w pliku Excel na podstawie predefiniowanego szablonu w aplikacjach opartych na numerze .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteka programu Excel](/cells/pl/net/) obsługuje generowanie plików Excel opartych na szablonach do masowego generowania raportów. Szablony to wstępnie zaprojektowane formaty, używane do tworzenia raportów o tym samym wzorcu. Kod .NET tworzy nowy plik programu Excel taki sam jak dokument szablonu po wypełnieniu danymi. Obsługiwane formaty plików to XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Twórz raporty na podstawie wstępnie zaprojektowanego szablonu programu Excel" %}}

Zautomatyzowanie procesu tworzenia tych samych plików wzorców jest łatwe przy użyciu zestawu .NET API. Istnieją różne sposoby[zaimportować dane](https://docs.aspose.com/cells/net/import-data-into-worksheet/#importing-data-from-json) i generować pliki Excel. API zapewnia[Klasa WorkbookDesigner](https://reference.aspose.com/cells/net/aspose.cells/workbookdesigner) do reprezentowania arkusza projektanta. Utwórz jego obiekt i użyj go do otwarcia pliku szablonu. Ustaw źródło danych, którym może być DataTable, Array, plik Json itp. Przetwórz je, aby zaimportować dane i zapisz plik z danymi w wymaganym formacie. Programiści mogą łączyć dane w raporty w innych formatach plików, korzystając z poniższych łączy.



{{% blocks/products/pf/feature-page-code h3="C# Kod do generowania raportów Excel" %}}

{{< gist "aspose-com-gists" "5c193070f1b6acdc3eed001f52eadbc2" "generate-excel-reports.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Generate" afterslug="Reports" >}}
