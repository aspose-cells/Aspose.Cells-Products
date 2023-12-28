---
title: Skapa Excel-diagram och konvertera till bilder via C++
description: C++ källkod för att rita och konvertera diagram eller diagram i Microsoft Excel med hjälp av C++ Library
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa Microsoft<sup>&reg;</sup> Excel-diagram och konvertera till bilder via C++" h2="Konvertera Excel-dokumentdiagram till bilder samt skapa diagram inklusive cirkel-, pyramid-, linje- och bubbeldiagram inom C++-baserade applikationer." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Med hjälp av Excel-diagram kan man få en större bild och enkelt analysera data för att fatta rätt beslut.[C++ Excel-bibliotek](/cells/sv/cpp/) stöder att skapa olika diagram listade av[enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/) inklusive områdes-, stapel-, cirkel-, pyramid-, linje- och bubbeldiagram. Dessutom, För konvertering av diagram till bilder, tillhandahåller API en[Att föreställa sig](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/) omvandlas till önskat bildformat.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Skapa Excel-diagram" %}}

 Processen att skapa Excel-diagram är att skapa en instans av[Arbetsbok klass](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) och välj önskad[Arbetsblad](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/) . Lägg till diagrammet med[Lägg till metod](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/)med relevanta parametrar inklusive diagramtyp. Få tillgång till diagrammet via index och[Lägg till](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/) datakällan för diagram.

{{% blocks/products/pf/feature-page-code h3="C++ Kod för att skapa Excel-diagram" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Konvertera diagram till bilder" %}}


För att konvertera diagram, skapa först diagram som av relevant typ med ovanstående kod eller få tillgång till det från relevant blad. Definiera utdatasparvägen för bilden och använd ToImage-metoden för konvertering.

 
{{% blocks/products/pf/feature-page-code h3="C++ Kod för att konvertera Excel-diagram" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
