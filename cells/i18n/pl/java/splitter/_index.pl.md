---
title: Podziel arkusz kalkulacyjny Excel na arkusze robocze w Java
url: /pl/java/splitter/
description: Java kody źródłowe wyjaśniające, jak podzielić pliki Microsoft Excel na wiele dokumentów przy użyciu Javabiblioteki Excel
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Dzielenie plików Excela przez Java" h2="Podziel arkusz kalkulacyjny Excela na arkusze robocze w aplikacjach opartych na Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Istnieje wiele scenariuszy, gdy istnieje potrzeba podzielenia plików Excela, takich jak arkusz kalkulacyjny zawierający dane uczniów z przydziałem jednego arkusza dla każdego ucznia. I istnieje potrzeba podzielenia każdego arkusza ucznia na osobny plik. Aby zautomatyzować to za pomocą aplikacji Java, [Java Excel API](/cells/java/) jest po to, aby podzielić dokument Excel w arkuszach. Obsługiwane formaty to XLS, XLSX, XLSB, XLSM, ODS. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Podziel dokument Excel na wiele plików" %}}

Najprostszym sposobem na podzielenie pliku Excel na arkusz jest dostęp do wszystkich arkuszy, iteracja każdego arkusza i zapisywanie po kolei w żądanym formacie. Do ładowania arkusza roboczego API zapewnia [zeszyt ćwiczeń](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) klasa. [getWorksheets().getCount()](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) metoda pobiera całkowitą liczbę arkuszy. Iteruj przez każdy arkusz i używaj [getWorksheets().get(sheetindex)](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) za dostęp do określonego arkusza. Przenieś wybrane dane arkusza do nowo utworzonego obiektu klasy Workbook, używając [Metoda kopiowania](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Na koniec zapisz go w wymaganym formacie.

{{% blocks/products/pf/feature-page-code h3="Java Kod do dzielenia plików Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Podziel arkusz Excela na panele" %}}

API udostępnia również funkcję dzielenia arkusza programu Excel na różne panele. Proces polega na załadowaniu pliku przy użyciu klasy Workbook. Wybierz pierwszy arkusz lub dowolny wymagany arkusz, podając jego indeks. Wywołaj setActiveCell z odpowiednim indeksem komórki jako parametrem. I na koniec podziel okno arkusza roboczego na różne panele, wywołując metodę split().

{{% blocks/products/pf/feature-page-code h3="Java Kod do podziału arkusza Excel na widok okienka" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}