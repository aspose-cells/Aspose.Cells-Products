---
title: Skapa Excel-diagram och konvertera till bilder med Go via C++
description: Gå via källkoden C++ för att rita och konvertera diagram eller diagram i Microsoft Excel med hjälp av Go via C++-biblioteket
keywords: [Go via C++ Aspose.Cells., Go via C++ Convert chart to image., Go via C++ Save chart to image., Go via C++ chart to image., create charts in Go via C++., insert charts in Go via C++., manage charts in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa Microsoft<sup>&reg;</sup> Excel-diagram och konvertera till bilder med Go via C++" h2="Konvertera Excel-dokumentdiagram till bilder samt skapa diagram inklusive cirkel-, pyramid-, linje- och bubbeldiagram i Go via C++-baserade applikationer." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Med hjälp av Excel-diagram kan man få en större bild och enkelt analysera data för att fatta rätt beslut.[Gå via C++ Excel-bibliotek](/cells/sv/go-cpp/) stöder skapande av olika diagram listade efter[enum Aspose::Cells::Diagram::Diagramtyp
](https://reference.aspose.com/cells/go-cpp/charttype/) inklusive ytdiagram, stapeldiagram, cirkeldiagram, pyramiddiagram, linjediagram och bubbeldiagram. Dessutom, för konvertering av diagram till bilder, tillhandahåller API en[Tillbild](https://reference.aspose.com/cells/go-cpp/chart/toimage_string/) metodiserat till önskat bildformat.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Skapa Excel-diagram" %}}

 Processen för att skapa ett Excel-diagram är att skapa en instans av[Arbetsboksklass](https://reference.aspose.com/cells/go-cpp/workbook/) och välj önskad[Arbetsblad](https://reference.aspose.com/cells/go-cpp/worksheet/) Lägg till diagrammet med hjälp av[Lägg till metod](https://reference.aspose.com/cells/go-cpp/chartcollection/addfloatingchart/) med relevanta parametrar inklusive diagramtyp. Få åtkomst till diagrammet via index och[Tillägga](https://reference.aspose.com/cells/go-cpp/seriescollection/add_string_bool_bool/)datakällan för diagrammet.

{{% blocks/products/pf/feature-page-code h3="Gå via C++-kod för att skapa Excel-diagram" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "create-excel-chart.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Konvertera diagram till bilder" %}}


För att konvertera diagram, skapa först ett diagram av relevant typ med hjälp av koden ovan eller öppna det från relevant ark. Definiera sökvägen för att spara utdata för bilden och använd ToImage-metoden för konvertering.


{{% blocks/products/pf/feature-page-code h3="Gå via C++-kod för att konvertera Excel-diagram" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "convert-excel-chart-to-image.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{< /blocks/products/pf/feature-page-wrap >}}