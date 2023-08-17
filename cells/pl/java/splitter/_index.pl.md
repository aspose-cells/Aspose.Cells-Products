---
title: Podziel arkusz kalkulacyjny Excel na arkusze kalkulacyjne w Java
description: Java kody źródłowe, które wyjaśniają, jak podzielić Microsoft pliki programu Excel na wiele dokumentów przy użyciu biblioteki programu Excel Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Dzielenie plików programu Excel via Java" h2="Podziel arkusz kalkulacyjny Excel na arkusze robocze w aplikacjach opartych na numerze Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Istnieje wiele scenariuszy, kiedy zachodzi potrzeba podzielenia plików Excela, takich jak arkusz kalkulacyjny zawierający dane uczniów z przydziałem jednego arkusza dla każdego ucznia. I istnieje potrzeba podzielenia każdego ucznia arkusza jako osobny plik. Aby zautomatyzować aplikację via Java,[Java Excel API](/cells/pl/java/) czy istnieje możliwość podziału dokumentu Excela po arkuszach. Obsługiwane formaty to XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Podziel dokument programu Excel na wiele plików" %}}

Najprostszym sposobem podzielenia pliku Excela na arkusz jest uzyskanie dostępu do wszystkich arkuszy, przeglądanie każdego arkusza i zapisywanie jednego po drugim w żądanym formacie. Aby załadować arkusz, API zapewnia[zeszyt ćwiczeń](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) klasa.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) Metoda pobiera całkowitą liczbę arkuszy. Przejrzyj każdy arkusz i użyj[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) w celu uzyskania dostępu do określonego arkusza. Przenieś wybrane dane arkusza do nowo utworzonego obiektu klasy skoroszyt za pomocą[Metoda kopiowania](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Na koniec zapisz go w wymaganym formacie.

{{% blocks/products/pf/feature-page-code h3="Java Kod do dzielenia plików Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Podziel arkusz programu Excel na panele" %}}

API udostępnia również funkcję dzielenia arkusza programu Excel na różne panele. Proces polega na załadowaniu pliku przy użyciu klasy Workbook. Wybierz pierwszy arkusz lub dowolny wymagany arkusz, podając jego indeks. Wywołaj setActiveCell z odpowiednim indeksem komórki jako parametrem. I wreszcie podziel okno arkusza roboczego na różne panele, wywołując metodę split().

{{% blocks/products/pf/feature-page-code h3="Java Kod do podziału arkusza programu Excel na widok okienka" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
