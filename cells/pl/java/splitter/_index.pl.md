---
title: Podziel arkusz kalkulacyjny Excel na arkusze w Java
description: Java kody źródłowe wyjaśniające, jak podzielić pliki Excel Microsoft na wiele dokumentów przy użyciu biblioteki Excel Java
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Dzielenie pliku Excel via Java" h2="Podziel arkusz kalkulacyjny Excel na arkusze w aplikacjach opartych na Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Istnieje wiele scenariuszy, gdy zachodzi potrzeba podzielenia plików Excel na przykład arkusza kalkulacyjnego zawierającego dane uczniów z przydzieleniem pojedynczego arkusza dla każdego ucznia. Istnieje także potrzeba podzielenia każdego arkusza na osobny plik. Aby zautomatyzować aplikację via Java,[Java Excel API](/cells/pl/java/) czy istnieje podział dokumentu Excel na arkusze. Obsługiwane formaty to XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Podziel dokument Excel na wiele plików" %}}

 Najprostszym sposobem podzielenia pliku Excel na arkusz jest uzyskanie dostępu do wszystkich arkuszy, przeglądanie każdego arkusza i zapisywanie jeden po drugim w żądanym formacie. Do ładowania arkusza zapewnia numer API[zeszyt ćwiczeń](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) klasa.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) metoda pobiera całkowitą liczbę arkuszy. Iteruj po każdym arkuszu i używaj[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) aby uzyskać dostęp do określonego arkusza. Przenieś wybrane dane arkusza do nowo utworzonego obiektu klasy Workbook za pomocą[Metoda kopiowania](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Na koniec zapisz go w wymaganym formacie.

{{% blocks/products/pf/feature-page-code h3="Java Kod do dzielenia plików Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Podziel arkusz programu Excel na panele" %}}

API zapewnia również funkcjonalność dzielenia arkusza Excel na różne panele. Proces polega na załadowaniu pliku przy użyciu klasy Workbook. Wybierz pierwszy arkusz lub dowolny wymagany arkusz, podając jego indeks. Wywołaj setActiveCell mającą odpowiedni indeks komórki jako parametr. Na koniec podziel okno arkusza na różne panele, wywołując metodę split().

{{% blocks/products/pf/feature-page-code h3="Java Kod umożliwiający podzielenie arkusza programu Excel na widok panelu" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
