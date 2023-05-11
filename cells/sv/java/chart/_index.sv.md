---
title: Skapa Excel-diagram och konvertera till bilder via Java
description:  Java källkod för att rita och konvertera diagram eller diagram i Microsoft Excel med hjälp av Java Library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konvertering och skapande av Excel-fildiagram via Java" h2="Konvertera Excel-dokumentdiagram till bilder samt skapa olika diagram med hjälp av API:er på serversidan inom Java-baserade applikationer." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Att analysera data via diagram visar den större bilden och det är lätt att fatta mer välgrundade beslut med tydligare insikter.[Java Excel-bibliotek](/cells/sv/java/) stöder ritning av olika diagramskapande listade av[ChartType](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) inklusive paj-, pyramid-, linje- och bubbeldiagram. Dessutom konverterar den också diagram till bilder. API tillhandahåller en[Diagram klass](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)för att representera ett enda Excel-diagram.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Konvertera Excel-diagram till bilder" %}}

 Processen att konvertera diagram till bilder inklusive JPG, PNG, TIFF, BMP etc är att använda[Arbetsbok](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) klass för att ladda Excel-filen, välj den relevanta[arbetsblad](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) som innehåller diagrammen eller iterera genom varje diagram i varje kalkylblad. Definiera[ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) och rendera utdatabilden av diagrammet med hjälp av[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Kod för att konvertera Excel-diagram till bild" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Skapa diagram i Excel-fil" %}}

 Att skapa diagram med Excel API är enkelt, eftersom API tillhandahåller uppsättning av olika klasser som Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection etc för olika typer av diagram. Processen är, Skapa Workbook-klassobjekt och välj det första kalkylbladet eller det relevanta bladet genom att tillhandahålla dess index. För datakälla för diagrammet, infoga värden i kalkylbladsceller med hjälp av[satt värde](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)metod. Använd ChartCollection samlingar[lägga till metod](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) för att lägga till diagrammet, definiera typ av diagram med ChartType-uppräkningen. Få tillgång till det nya diagramobjektet från ChartCollection-samlingen genom att skicka dess index. Använd[Seriekollektion](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) diagramobjekt för att ange diagrammets datakälla.

{{% blocks/products/pf/feature-page-code h3="Java Kod för att skapa Excel-diagram" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
