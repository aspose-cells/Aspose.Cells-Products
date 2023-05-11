---
title: Utwórz pliki Excela via Java
description: Wygeneruj arkusze kalkulacyjne Microsoft Excel z arkusza szablonu przy użyciu biblioteki arkuszy kalkulacyjnych Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Tworzenie raportów na podstawie szablonu programu Excel via Java" h2="Generuj masowe raporty w formacie Excel w oparciu o predefiniowany szablon w aplikacjach opartych na numerze Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Biblioteka programu Excel](/cells/pl/java/)obsługuje generowanie plików Excel opartych na szablonach do masowego generowania raportów. Jest to potrzebne w większości przypadków, takich jak tworzenie zestawień opłat, kart wyników, kart pacjentów itp. Szablony to predefiniowane wzorce. Poniższy kod Java generuje zbiorcze pliki programu Excel tak samo, jak dokument szablonu po wypełnieniu danymi. Obsługiwane formaty plików to XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Twórz raporty na podstawie wstępnie zaprojektowanego szablonu programu Excel" %}}

 Za pomocą Java Assembly API programiści mogą łatwo zaprogramować kod generowania raportów zbiorczych, dołączając poniższe fragmenty kodu. API zapewnia[zaimportować dane](https://docs.aspose.com/cells/java/import-and-export-data/) funkcji z różnych źródeł i tworzyć dokumenty Excel w zależności od tych danych. W przypadku wzorów opartych na szablonach numer API zapewnia[Klasa WorkbookDesigner](https://reference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner)do reprezentowania arkusza projektanta. Proces polega na utworzeniu jego obiektu i użyciu go do otwarcia pliku szablonu. Ustaw źródło danych, którym może być Array, DataTable, Json itp. Przetwórz je, aby zaimportować dane i zapisz plik w żądanym formacie. Programiści mogą łączyć dane w raporty w innych formatach plików, w tym XLS, XLSX, XLSB, XLSM, ODS, korzystając z poniższych łączy.



{{% blocks/products/pf/feature-page-code h3="Java Kod do tworzenia raportów programu Excel" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}
