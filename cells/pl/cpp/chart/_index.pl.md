---
title: Twórz wykresy programu Excel i konwertuj je na obrazy pod numerem C++
description: C++ kod źródłowy do rysowania i konwertowania wykresu lub diagramu w programie Excel Microsoft przy użyciu biblioteki C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Utwórz Microsoft<sup>&reg;</sup> wykresy programu Excel i przekonwertuj je na obrazy za pośrednictwem C++" h2="Konwertuj wykresy dokumentów programu Excel na obrazy, a także twórz wykresy, w tym wykresy kołowe, ostrosłupowe, liniowe i bąbelkowe w aplikacjach opartych na numerze C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Korzystając z wykresów Excela, można uzyskać większy obraz i łatwo analizować dane w celu podejmowania właściwych decyzji.[C++ Biblioteka programu Excel](/cells/pl/cpp/) obsługuje tworzenie różnych wykresów wymienionych przez[wyliczenie Aspose::Cells::Wykresy::Typ wykresu
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) w tym wykresy powierzchniowe, słupkowe, kołowe, ostrosłupowe, liniowe i bąbelkowe. Ponadto do konwersji wykresów na obrazy, API zapewnia[Metoda ToImage](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) do wymaganego formatu obrazu.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Twórz wykresy w Excelu" %}}

 Proces tworzenia wykresu Excel polega na utworzeniu instancji pliku[Klasa IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) i wybierz żądane[Karta pracy](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43) . Dodaj wykres za pomocą[Dodaj metodę](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) odpowiednimi parametrami, w tym typem wykresu. Uzyskaj dostęp do wykresu za pomocą indeksu i[Dodać](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) źródło danych dla wykresu.

{{% blocks/products/pf/feature-page-code h3="C++ Kod do tworzenia wykresów programu Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj wykresy na obrazy" %}}


Proces konwersji wykresów polega na utworzeniu wykresu odpowiedniego typu przy użyciu powyższego kodu lub uzyskaniu dostępu do niego z odpowiedniego arkusza. Zdefiniuj wyjściową ścieżkę zapisu obrazu i użyj metody ToImage do konwersji.

 
{{% blocks/products/pf/feature-page-code h3="C++ Kod do konwersji wykresów programu Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
