---
title: Twórz wykresy Excel i konwertuj na obrazy za pomocą C++

description: C++ kod źródłowy do rysowania i konwertowania wykresu lub diagramu w programie Microsoft Excel przy użyciu C++Biblioteki
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Twórz wykresy Microsoft<sup>&reg;</sup> Excel i konwertuj na obrazy za pomocą C++" h2="Konwertuj wykresy dokumentów Excel na obrazy, a także twórz wykresy, w tym wykresy kołowe, piramidowe, liniowe i bąbelkowe w aplikacjach opartych na C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

Korzystając z wykresów Excel, można uzyskać większy obraz i łatwo analizować dane, aby podejmować właściwe decyzje. [C++ Biblioteka Excela](/cells/cpp/) obsługuje tworzenie różnych wykresów wymienionych przez [wyliczenie Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) w tym wykresy warstwowe, słupkowe, kołowe, piramidowe, liniowe i bąbelkowe. Ponadto w przypadku konwersji wykresów na obrazy API zapewnia [Metoda do obrazu](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) w wymaganym formacie obrazu.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Twórz wykresy Excel" %}}

Proces tworzenia wykresu Excel polega na utworzeniu instancji [Klasa IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) i wybierz żądany [Arkusz roboczy](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Dodaj wykres za pomocą [Dodaj metodę](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) odpowiednimi parametrami, w tym typem wykresu. Uzyskaj dostęp do wykresu za pomocą indeksu i [Dodać](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) źródło danych dla wykresu.

{{% blocks/products/pf/feature-page-code h3="C++ Kod do tworzenia wykresów Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj wykresy na obrazy" %}}


Proces konwersji wykresów polega na utworzeniu wykresu odpowiedniego typu za pomocą powyższego kodu lub dostępie do niego z odpowiedniego arkusza. Zdefiniuj wyjściową ścieżkę zapisu obrazu i użyj metody ToImage do konwersji.

 
{{% blocks/products/pf/feature-page-code h3="C++ Kod do konwersji wykresów Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
