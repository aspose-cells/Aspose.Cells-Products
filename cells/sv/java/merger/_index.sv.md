---
title: Slå ihop olika Excel-filer till en enda i Java
url: /sv/java/merger/
description: Slå samman Excel-filer med Java till flera ark eller ett enda ark. Slå samman, kombinera eller sammanfoga Excel-dokument till PDF, bilder och HTML också.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-filsammanslagning via Java" h2="Kombinera två eller flera Excel-filer i ett enda kalkylblad med Java-koden" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel-bibliotek](/cells/java/) ger flera sätt att kombinera arbetsböcker med olika typer av innehåll som formler, bilder, data, diagram etc till ett enda kalkylarksdokument. Filformat som stöds inkluderar XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV och mer.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinera Excel-filer med bilder och diagram" %}}
Det enklaste sättet att kombinera två Excel-filer med bilder och diagram är att anropa [Workbook.combine](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) metod. Det gör det möjligt att slå samman Excel-filer av liknande typ till ett enda kalkylblad.
{{% blocks/products/pf/feature-page-code h3="Java Kod för att kombinera Excel-filer" %}}

```cs
// ladda den första Excel-filen
var book1 = new Workbook("with-charts.xlsx");
// ladda den andra Excel-filen i en separat instans
var book2 = new Workbook("with-images.xlsx");

// slå samman två arbetsböcker
book1.combine(book2);
// spara målarbetsboken 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Slå samman flera Excel-filer" %}}
[CellsHelper.mergeFiles](https://apireference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) Metoden stöder sammanslagning av data, stil och formler för en Excel-fil till ett nytt kalkylblad i samma format. Det är ett effektivt sätt att slå samman flera filer samtidigt som du använder cachning. 
{{% blocks/products/pf/feature-page-code h3="Java Kod för att slå samman flera Excel-filer" %}}

```cs
// skapa en Array (längd=2)
String[] files = new String[2];
// ange filsökvägar som ska slås samman
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// slå samman filerna för att spara resultatet
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Slå ihop Excel-filer genom att kopiera arbetsblad" %}}
[Arbetsblad.kopia](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)kan användas för att kopiera data och formatering från ett källark till ett annat kalkylblad inom eller mellan arbetsböcker. Metoden tar källarksobjektet som en parameter.
{{% blocks/products/pf/feature-page-code h3="Java Kod för att kopiera arbetsblad mellan arbetsböcker" %}}

```cs
// Skapa en arbetsbok.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Skapa en annan arbetsbok.
Workbook excelWorkbook1 = new Workbook();

// Kopiera det första arket i den första boken till den andra boken.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Spara filen.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}