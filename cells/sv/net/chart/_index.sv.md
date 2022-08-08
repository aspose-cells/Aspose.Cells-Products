---
title: Skapa Excel-diagram och konvertera till bilder via .NET
url: /sv/net/chart/
description: C# källkod för att rita och konvertera diagram eller diagram i Microsoft Excel med hjälp av .NET Library. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-fildiagram skapas och konverteras via .NET" h2="Skapa Excel-dokumentdiagram och konvertera till bilder med hjälp av API:er på serversidan i .NET-baserade applikationer." >}}
{{% blocks/products/pf/feature-page-summary %}}
Att rita diagram är en konst att visa data grafiskt för enkel analys. [.NET Excel-bibliotek](/cells/net/) stöder ritning av diagram i Excel-filer. API stöder olika diagramskapande som listas i [ChartType Enumeration](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) inklusive paj-, pyramid-, linje- och bubbeldiagram. Dessutom konverterar den också diagram till bilder. API tillhandahåller en [Diagram klass](https://reference.aspose.com/cells/net/aspose.cells.charts) för diagrambyggstenar.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Skapa diagram i Excel-fil" %}}

Det är enkelt att skapa diagram med Excel API. Processen är, Skapa [Arbetsbok klass](https://reference.aspose.com/cells/net/aspose.cells/workbook) objekt och välj det första kalkylbladet eller det relevanta bladet genom att tillhandahålla dess index. Infoga de nödvändiga celldata med hjälp av [PutValue-metoden](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Lägg till diagram i kalkylbladet med hjälp av diagramsamlingar [Lägg till metod](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). Specificera [ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) från ChartType-uppräkning.
{{% blocks/products/pf/feature-page-code h3="C# Kod för att skapa Excel-diagram" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Konvertera Excel-diagram till bilder" %}}

Processen för att konvertera diagram till bilder är att använda klassen Workbook för att ladda Excel-filen, välja det relevanta arbetsbladet som innehåller diagrammen och anropa [ToImage-metoden](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) för konvertering.

{{% blocks/products/pf/feature-page-code h3="C# Kod för att konvertera Excel-diagram till bild" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}