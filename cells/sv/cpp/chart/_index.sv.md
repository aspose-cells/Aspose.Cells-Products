---
title: Skapa Excel-diagram och konvertera till bilder via C++

description: C++ källkod för att rita och konvertera diagram eller diagram i Microsoft Excel med hjälp av C++ Library
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa Microsoft<sup>&reg;</sup> Excel-diagram och konvertera till bilder via C++" h2="Konvertera Excel-dokumentdiagram till bilder samt skapa diagram inklusive cirkel-, pyramid-, linje- och bubbeldiagram i C++-baserade applikationer." >}}

{{% blocks/products/pf/feature-page-summary %}}

Med hjälp av Excel-diagram kan man få en större bild och enkelt analysera data för att fatta rätt beslut. [C++ Excel-bibliotek](/cells/cpp/) stöder att skapa olika diagram listade av [enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) inklusive områdes-, stapel-, cirkel-, pyramid-, linje- och bubbeldiagram. För konvertering av diagram till bilder tillhandahåller API dessutom en [ToImage mehtod](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) till önskat bildformat.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Skapa Excel-diagram" %}}

Processen att skapa Excel-diagram är att skapa en instans av [IWorkbook klass](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) och välj önskad [Arbetsblad](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Lägg till diagrammet med [Lägg till metod](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) med relevanta parametrar inklusive diagramtyp. Få tillgång till diagrammet via index och [Lägg till](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) datakällan för diagram.

{{% blocks/products/pf/feature-page-code h3="C++ Kod för att skapa Excel-diagram" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Konvertera diagram till bilder" %}}


För att konvertera diagram, skapa först diagram som av relevant typ med ovanstående kod eller få tillgång till det från relevant ark. Definiera utdatasparvägen för bilden och använd ToImage-metoden för konvertering.

 
{{% blocks/products/pf/feature-page-code h3="C++ Kod för att konvertera Excel-diagram" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
