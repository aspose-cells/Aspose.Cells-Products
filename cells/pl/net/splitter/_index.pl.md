---
title: Podziel arkusz Excela mądrze w C#

description: C# kody źródłowe wyjaśniające, jak podzielić pliki Microsoft Excel na wiele plików w C#.NET aplikacjach wizualnych
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Dzielenie plików Excela przez .NET" h2="Podziel pojedynczy dokument Excel na różne pliki za pomocą C# kodu w .NET aplikacjach" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteka Excela](/cells/net/) jest w stanie podzielić dokument Excel na wiele arkuszy kalkulacyjnych w aplikacjach opartych na .NET. Obsługiwane formaty plików to XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Podziel dokument Excel na wiele plików" %}}
Najprostszym sposobem dzielenia arkuszy Excela jest dostęp do wszystkich arkuszy przez [Arkusze robocze](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Iterowanie przez każdy arkusz i wywoływanie [Kopiuj](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) metoda. Wreszcie zapisując go w określonej ścieżce. 

+ Załaduj plik Excel z pełną ścieżką za pomocą [Zajęcia ze skoroszytu](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Iteruj przez każdy arkusz
+ Utwórz nowy obiekt klasy Workbook
+ Skopiuj arkusz przez [Metoda kopiowania](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Wywołaj metodę Save() i przekaż nazwę pliku (pełną ścieżkę) z odpowiednim SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Kod do dzielenia plików Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Podziel arkusz Excela na panele" %}}

Aby podzielić okno arkusza roboczego na panele, API zapewnia [Metoda podziału](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) klasy worksheet, która udostępnia podzielony widok arkusza. Aby usunąć podzielony widok API zapewnia [Metoda RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Na koniec zapisz go pod określoną ścieżką. 

{{% blocks/products/pf/feature-page-code h3="C# Kod do dzielenia okna arkusza programu Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Kod do usuwania podzielonego widoku panoramy" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
