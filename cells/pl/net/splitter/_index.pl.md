---
title: Podziel arkusz kalkulacyjny programu Excel na C#
description: C# kody źródłowe, które wyjaśniają, jak podzielić Microsoft pliki programu Excel na wiele plików w aplikacjach Visual C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Dzielenie plików programu Excel via .NET" h2="Podziel pojedynczy dokument Excel na różne pliki przy użyciu kodu C# w aplikacjach opartych na .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Biblioteka programu Excel](/cells/pl/net/) jest w stanie podzielić dokument programu Excel na wiele arkuszy kalkulacyjnych w aplikacjach opartych na numerze .NET. Obsługiwane formaty plików to XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Podziel dokument programu Excel na wiele plików" %}}
 Najprostszym sposobem dzielenia arkuszy plików Excela jest dostęp do wszystkich arkuszy za pomocą[Karty pracy](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Iteracja w każdym arkuszu i wywoływanie metody[Kopiuj](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) metoda. Na koniec zapisywanie go w określonej ścieżce.

 + Załaduj plik Excel z pełną ścieżką za pomocą[Klasa skoroszytu](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Iteruj przez każdy arkusz
+ Utwórz nowy obiekt klasy skoroszytu
 + Skopiuj arkusz przez[Metoda kopiowania](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Wywołaj metodę Save() i podaj nazwę pliku (pełną ścieżkę) posiadającą odpowiedni SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Kod do dzielenia plików Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Podziel arkusz programu Excel na panele" %}}

 Aby podzielić okno arkusza na panele, API zapewnia[Metoda dzielona](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) klasy arkusza, która udostępnia podzielony widok arkusza. Aby usunąć widok podzielony API zapewnia[Metoda RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Na koniec zapisz go w określonej ścieżce.

{{% blocks/products/pf/feature-page-code h3="C# Kod do podziału okna arkusza programu Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Kod do usunięcia podzielonego widoku panoramy" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
