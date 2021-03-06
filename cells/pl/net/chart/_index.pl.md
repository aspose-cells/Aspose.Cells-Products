---
title: Tworzenie wykresów Excel i konwersja do obrazów za pomocą .NET
url: /pl/net/chart/
description: C# kod źródłowy do rysowania i konwertowania wykresu lub diagramu w programie Microsoft Excel przy użyciu biblioteki .NET. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Tworzenie i konwersja wykresów plików Excela za pomocą .NET" h2="Twórz wykresy dokumentów programu Excel i konwertuj na obrazy za pomocą interfejsów API po stronie serwera w aplikacjach opartych na .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
Rysowanie wykresów to sztuka graficznego wyświetlania danych w celu łatwej analizy. [.NET Biblioteka Excela](/cells/net/) obsługuje rysowanie wykresów w plikach Excel. API obsługuje różne tworzenie wykresów wymienione w [Wyliczenie typu wykresu](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) w tym wykresy kołowe, piramidowe, liniowe i bąbelkowe. Co więcej, konwertuje również wykresy na obrazy. API zapewnia [Klasa wykresów](https://apireference.aspose.com/cells/net/aspose.cells.charts) dla bloków konstrukcyjnych wykresu.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Twórz wykresy w pliku Excel" %}}

Tworzenie wykresów za pomocą programu Excel API jest proste. Proces to tworzenie [Zajęcia ze skoroszytu](https://apireference.aspose.com/cells/net/aspose.cells/workbook) obiekt i wybierz pierwszy arkusz lub odpowiedni arkusz, podając jego indeks. Wstaw wymagane dane komórek za pomocą [Metoda PutValue](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Dodaj wykres do arkusza roboczego, korzystając z kolekcji wykresów [Dodaj metodę](https://apireference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). Określić [Typ wykresu](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) z wyliczenia ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Kod do tworzenia wykresów Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Konwertuj wykresy Excela na obrazy" %}}

Proces konwersji wykresów na obrazy polega na użyciu klasy Workbook do załadowania pliku Excel, wybraniu odpowiedniego zadania zawierającego wykresy i wywołaniu [Metoda ToImage](https://apireference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) do konwersji.

{{% blocks/products/pf/feature-page-code h3="C# Kod do konwersji wykresu Excel na obraz" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}