---
title: Dela upp Excel-kalkylblad i kalkylblad i Java
description: Java källkoder som förklarar hur man delar upp Microsoft Excel-filer i flera dokument med hjälp av Java Excel-bibliotek
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-fildelning via Java" h2="Dela upp Excel-kalkylblad i kalkylblad inom Java-baserade applikationer" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Det finns olika scenarier, när det finns behov av att dela upp Excel-filer som ett kalkylblad som innehåller elevdata med tilldelning av ett ark för varje elev. Och det finns behov av att dela upp varje ark elevmässigt som en separat fil. För att automatisera det via Java-applikation,[Java Excel API](/cells/sv/java/) är till för att dela upp Excel-dokument arkvis. Format som stöds inkluderar XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dela upp Excel-dokument i flera filer" %}}

 Det enklaste sättet att dela upp Excel-fil i ark är, komma åt alla ark, iterera genom varje ark och spara ett och ett i önskat format. För att ladda arbetsbladet tillhandahåller API[Arbetsbok](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) klass.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) metoden får totalt antal ark. Gå igenom varje ark och använd[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get)för att komma åt ett specifikt blad. Flytta den valda arkdatan till det nyskapade Workbook-klassobjektet med hjälp av[Kopieringsmetod](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Spara den till sist i önskat format.

{{% blocks/products/pf/feature-page-code h3="Java Kod för att dela upp Excel-filer" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Dela upp Excel-kalkylblad i rutor" %}}

API ger också funktionalitet för att dela upp Excel-kalkylblad i olika rutor. Processen är att ladda filen med Workbook-klassen. Välj det första kalkylbladet eller ett önskat ark genom att tillhandahålla dess index. Anropa setActiveCell som har relevant cellindex som parameter. Och slutligen dela upp kalkylbladets fönster i olika rutor genom att anropa split()-metoden.

{{% blocks/products/pf/feature-page-code h3="Java Kod för att dela upp Excel-ark i fönstervy" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
