---
title: Slå ihop olika Excel-filer till en enda i Java
description: Slå ihop Excel-filer med Java till flera ark eller ett enda ark. Slå samman, kombinera eller sammanfoga Excel-dokument till PDF, Bilder och HTML också.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-filsammanslagning via Java" h2="Kombinera två eller flera Excel-filer i ett enda kalkylblad med Java-koden" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel-bibliotek](/cells/sv/java/) ger flera sätt att kombinera arbetsböcker med olika typer av innehåll som formler, bilder, data, diagram etc till ett enda kalkylarksdokument. Filformat som stöds inkluderar XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, 347618 och fler.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinera Excel-filer med bilder och diagram" %}}
 Det enklaste sättet att kombinera två Excel-filer med bilder och diagram är att anropa[Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) metod. Det gör det möjligt att slå samman Excel-filer av liknande typ till ett enda kalkylblad.
{{% blocks/products/pf/feature-page-code h3="Java Kod för att kombinera Excel-filer" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Slå samman flera Excel-filer" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles)Metoden stöder sammanslagning av data, stil och formler för en Excel-fil till ett nytt kalkylblad i samma format. Det är ett effektivt sätt att slå samman flera filer samtidigt som du använder cachning.
{{% blocks/products/pf/feature-page-code h3="Java Kod för att slå samman flera Excel-filer" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Slå ihop Excel-filer genom att kopiera arbetsblad" %}}
[Arbetsblad.kopia](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) kan användas för att kopiera data och formatering från ett källark till ett annat kalkylblad inom eller mellan arbetsböcker. Metoden tar källarksobjektet som en parameter.
{{% blocks/products/pf/feature-page-code h3="Java Kod för att kopiera arbetsblad mellan arbetsböcker" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Andra sammanslagningsformat som stöds" subTitle="Med hjälp av Java kan man också slå ihop många andra filformat inklusive..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Kommaseparerade värden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Arkivformat för webbsidor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Tab-separerade värden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Textdokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Excel binärt format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Binär Excel arbetsbok fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Kalkylbladsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML Excel-fil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Excel-mall" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Excel Macro-aktiverad mall" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
