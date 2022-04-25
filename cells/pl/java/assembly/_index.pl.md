---
title: Twórz pliki Excela za pomocą Java
url: /pl/java/assembly/
description: Generuj arkusze kalkulacyjne Microsoft Excel z arkusza szablonu za pomocą Javabiblioteki arkuszy kalkulacyjnych
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tworzenie raportów opartych na szablonach programu Microsoft<sup>&reg;</sup> za pomocą Java" h2="Generuj zbiorcze raporty w plikach Excel na podstawie wstępnie zdefiniowanego szablonu w aplikacjach opartych na Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Biblioteka Excela](/cells/java/) obsługuje generowanie plików Excel opartych na szablonach do zbiorczego generowania raportów. Jest to potrzebne w większości przypadków, takich jak tworzenie opłat challans, karty wyników i rekordy pacjentów itp. Szablony to predefiniowane wzorce. Poniższy kod Java generuje zbiorcze pliki programu Excel, takie same jak dokument szablonu po wypełnieniu danymi. Obsługiwane formaty plików to XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Twórz raporty na podstawie wstępnie zaprojektowanego szablonu Excel" %}}

Korzystając z JavaAsembleraAPI, programiści mogą łatwo zaprogramować kod generowania zbiorczego raportu, dołączając poniższe fragmenty kodu. API zapewnia [zaimportować dane](https://docs.aspose.com/cells/java/import-and-export-data/) funkcji z różnych źródeł i tworzyć dokumenty Excel w zależności od tych danych. W przypadku wzorców opartych na szablonach API zapewnia [WorkbookDesigner class](https://apireference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner) do reprezentowania arkusza projektanta. Proces to Utwórz swój obiekt i użyj go do otwarcia pliku szablonu. Ustaw źródło danych, którym może być Array, DataTable, Json itp. Przetwórz je, aby zaimportować dane i zapisać plik w żądanym formacie. Programiści mogą łączyć dane w raporty w innych formatach plików, w tym XLS, XLSX, XLSB, XLSM, ODS, korzystając z poniższych linków.



{{% blocks/products/pf/feature-page-code h3="Java Kod do tworzenia raportów programu Excel" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}