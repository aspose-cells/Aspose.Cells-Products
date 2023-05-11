---
title: Twórz wykresy Excel i konwertuj na obrazy via Java
description:  Java kod źródłowy do rysowania i konwertowania wykresu lub diagramu w programie Excel Microsoft przy użyciu biblioteki Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konwersja i tworzenie wykresów plików programu Excel via Java" h2="Konwertuj wykresy dokumentów programu Excel na obrazy, a także twórz różne wykresy za pomocą interfejsów API po stronie serwera w aplikacjach opartych na numerze Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Analizowanie danych za pomocą wykresów pokazuje szerszy obraz i łatwo jest podejmować bardziej świadome decyzje dzięki jaśniejszym wglądom.[Java Biblioteka programu Excel](/cells/pl/java/) obsługuje rysowanie różnych tworzenia wykresów wymienionych przez[Typ wykresu](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) w tym wykresy kołowe, piramidalne, liniowe i bąbelkowe. Co więcej, konwertuje również wykresy na obrazy. API zapewnia[Klasa wykresów](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)do reprezentowania pojedynczego wykresu programu Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Konwertuj wykresy programu Excel na obrazy" %}}

 Proces konwersji wykresów na obrazy, w tym JPG, PNG, TIFF, BMP itp.[zeszyt ćwiczeń](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) class, aby załadować plik Excel, wybierz odpowiedni[zadanie](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) zawierający wykresy lub przeglądaj każdy wykres w każdym arkuszu. Definiować[ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) i wyrenderuj obraz wyjściowy wykresu za pomocą[Wykres do obrazu](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Kod konwertujący wykres programu Excel na obraz" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Twórz wykresy w pliku Excel" %}}

 Tworzenie wykresów za pomocą programu Excel API jest proste, ponieważ API zapewnia zestaw różnych klas, takich jak Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection itp. dla różnych rodzajów wykresów. Proces polega na utworzeniu obiektu klasy Workbook i wybraniu pierwszego arkusza lub odpowiedniego arkusza poprzez podanie jego indeksu. Jako źródło danych wykresu wstaw wartości do komórek arkusza za pomocą[ustalić wartość](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)metoda. Użyj kolekcji ChartCollection[dodaj metodę](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ), aby dodać wykres, zdefiniuj typ wykresu za pomocą wyliczenia ChartType. Uzyskaj dostęp do nowego obiektu Chart z kolekcji ChartCollection, przekazując jego indeks. Użyj[Kolekcja serii](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) wykresu, aby określić źródło danych wykresu.

{{% blocks/products/pf/feature-page-code h3="Java Kod do tworzenia wykresów programu Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
