---
title: Skapa Excel-filer via Java
url: /sv/java/assembly/
description: Generera Microsoft Excel-kalkylblad från ett mallark med hjälp av Java kalkylarksbibliotek
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Skapa Microsoft<sup>&reg;</sup> Excel-mallbaserade rapporter via Java" h2="Generera bulkrapporter för Excel-filer baserat på en fördefinierad mall i Java-baserade applikationer." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel-bibliotek](/cells/java/) stöder generering av mallbaserade Excel-filer för generering av massrapporter. Det behövs för de flesta fall som att skapa avgiftskrav, resultatkort och patientjournaler etc. Mallar är fördefinierade mönster. Under Java-koden genererar bulk excel-filer på samma sätt som malldokument har fyllts med data. Filformat som stöds inkluderar XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Skapa rapporter baserade på förutformad Excel-mall" %}}

Med hjälp av Java Assembly API kan utvecklare enkelt programmera koden för generering av massrapporter genom att inkludera kodavsnitten nedan. API tillhandahåller [importera data](https://docs.aspose.com/cells/java/import-and-export-data/) funktioner från olika källor och skapa Excel-dokument beroende på dessa data. För mallbaserade mönster tillhandahåller API en [WorkbookDesigner klass](https://reference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner) att representera ett designerkalkylblad. Processen är att skapa dess objekt och använda den för att öppna mallfilen. Ställ in datakällan, som kan vara Array, DataTable, Json etc. Bearbeta den för att importera data och spara filen i önskat format. Programmerare kan sammanställa data till rapporter i andra filformat inklusive XLS, XLSX, XLSB, XLSM, ODS enligt nedanstående länkar.



{{% blocks/products/pf/feature-page-code h3="Java Kod för att skapa Excel-rapporter" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}