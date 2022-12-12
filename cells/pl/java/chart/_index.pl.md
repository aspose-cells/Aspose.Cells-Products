---
title: Twórz wykresy Excel i konwertuj na obrazy za pomocą Java

description: Java kod źródłowy do rysowania i konwertowania wykresu lub diagramu w programie Microsoft Excel przy użyciu biblioteki Java. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konwersja i tworzenie wykresów plików Excela za pomocą Java" h2="Konwertuj wykresy dokumentów programu Excel na obrazy, a także twórz różne wykresy za pomocą interfejsów API po stronie serwera w aplikacjach opartych na Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

Analiza danych za pomocą wykresów pokazuje szerszy obraz i ułatwia podejmowanie bardziej świadomych decyzji dzięki jaśniejszym wglądom. [Java Biblioteka Excela](/cells/java/) obsługuje rysowanie różnych tworzenia wykresów wymienionych przez [Typ wykresu](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) w tym wykresy kołowe, piramidowe, liniowe i bąbelkowe. Co więcej, konwertuje również wykresy na obrazy. API zapewnia [Klasa wykresów](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) do reprezentowania pojedynczego wykresu Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Konwertuj wykresy Excela na obrazy" %}}

Proces konwersji wykresów do obrazów, w tym JPG, PNG, TIFF, BMP itp., Użyj [zeszyt ćwiczeń](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) klasę, aby załadować plik Excel, wybierz odpowiednią [zadanie](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) zawierające wykresy lub iteruj po każdym wykresie w każdym arkuszu. Definiować [Opcje obrazu lub wydruku](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) i renderuj obraz wyjściowy wykresu za pomocą [Wykres.do obrazu](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Kod do konwersji wykresu Excel na obraz" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Twórz wykresy w pliku Excel" %}}

Tworzenie wykresów za pomocą programu Excel API jest proste, ponieważ API udostępnia zestaw różnych klas, takich jak Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection itp. dla różnych rodzajów wykresów. Proces to Utwórz obiekt klasy Workbook i wybierz pierwszy arkusz lub odpowiedni arkusz, podając jego indeks. W przypadku źródła danych wykresu wstaw wartości do komórek arkusza za pomocą [ustalić wartość](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) metoda. Użyj kolekcji ChartCollection [dodaj metodę](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)), aby dodać wykres, zdefiniuj typ wykresu za pomocą wyliczenia ChartType. Uzyskaj dostęp do nowego obiektu Chart z kolekcji ChartCollection, przekazując jego indeks. Użyj [SeriaKolekcja](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) obiekt wykresu, aby określić źródło danych wykresu.

{{% blocks/products/pf/feature-page-code h3="Java Kod do tworzenia wykresów Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
