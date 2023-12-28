---
title: Podziel arkusz arkusza programu Excel mądrze w C#
description: Kody źródłowe C# wyjaśniające, jak dzielić pliki Excel Microsoft na wiele plików w aplikacjach Visual C#.NET
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Dzielenie pliku Excel via .NET" h2="Podziel pojedynczy dokument Excel na różne pliki przy użyciu kodu C# w aplikacjach opartych na .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteka Excela](/cells/pl/net/) jest w stanie podzielić dokument Excel na wiele arkuszy kalkulacyjnych w aplikacjach opartych na .NET. Obsługiwane formaty plików to XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Podziel dokument Excel na wiele plików" %}}
Najprostszym sposobem podziału arkuszy plików Excel jest uzyskanie dostępu do wszystkich arkuszy za pośrednictwem[Arkusze ćwiczeń](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Iterowanie po każdym arkuszu i wywoływanie metody[Kopiuj](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) metoda. Na koniec zapisz go w określonej ścieżce.

 + Załaduj plik Excel z pełną ścieżką za pomocą[Zajęcia ze skoroszytu](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Iteruj po każdym arkuszu
+ Utwórz nowy obiekt klasy skoroszytu
 + Skopiuj arkusz przez[Metoda kopiowania](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Wywołaj metodę Save() i podaj nazwę pliku (pełną ścieżkę) posiadającą odpowiedni SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Kod do dzielenia plików Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Podziel arkusz programu Excel na panele" %}}

 Do dzielenia okna arkusza na panele służy API[Metoda podziału](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) klasy arkusza, która zapewnia podzielony widok arkusza. Aby usunąć widok podzielony, zapewnia API[Usuń metodę Split](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Na koniec zapisz go w określonej ścieżce.

{{% blocks/products/pf/feature-page-code h3="C# Kod umożliwiający podzielenie okna arkusza programu Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Kod umożliwiający usunięcie podzielonego widoku panoramicznego" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
