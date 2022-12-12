---
title: Voeg verschillende Excel-bestanden samen tot één bestand in Java

description: Voeg Excel-bestanden samen met Java in meerdere bladen of op één blad. Voeg Excel-documenten samen, combineer of voeg ze samen tot PDF, afbeeldingen en HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-bestand samenvoegen via Java" h2="Combineer twee of meer Excel-bestanden in één spreadsheet met Java code" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel-bibliotheek](/cells/java/) biedt meerdere manieren om werkmappen te combineren met verschillende soorten inhoud, zoals formules, afbeeldingen, gegevens, grafieken enz. in een enkel spreadsheetdocument. Ondersteunde bestandsindelingen zijn XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV en meer.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combineer Excel-bestanden met afbeeldingen en grafieken" %}}
De eenvoudigste manier om twee Excel-bestanden met afbeeldingen en grafieken te combineren, is door de [Werkmap.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) methode. Het maakt het mogelijk om Excel-bestanden van een vergelijkbaar type samen te voegen tot een enkele spreadsheet.
{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-bestanden te combineren" %}}

```cs
// laad eerste Excel-bestand
var book1 = new Workbook("with-charts.xlsx");
// laad tweede Excel-bestand in een apart exemplaar
var book2 = new Workbook("with-images.xlsx");

// twee werkmappen samenvoegen
book1.combine(book2);
// sla de doelwerkmap op 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Meerdere Excel-bestanden samenvoegen" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) methode ondersteunt het samenvoegen van gegevens, stijl en formules van een Excel-bestand naar een nieuwe spreadsheet met hetzelfde formaat. Het is een efficiënte manier om verschillende bestanden samen te voegen terwijl u caching gebruikt. 
{{% blocks/products/pf/feature-page-code h3="Java Code om meerdere Excel-bestanden samen te voegen" %}}

```cs
// maak een array (lengte=2)
String[] files = new String[2];
// specificeer bestandspaden die moeten worden samengevoegd
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// voeg de bestanden samen om het resultaat op te slaan
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Excel-bestanden samenvoegen door werkbladen te kopiëren" %}}
[Werkblad.kopie](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)kan worden gebruikt om gegevens en opmaak van een bronwerkblad naar een ander werkblad binnen of tussen werkmappen te kopiëren. De methode neemt het bronwerkbladobject als parameter.
{{% blocks/products/pf/feature-page-code h3="Java Code om werkbladen tussen werkmappen te kopiëren" %}}

```cs
// Maak een werkboek.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Maak nog een werkmap.
Workbook excelWorkbook1 = new Workbook();

// Kopieer het eerste blad van het eerste boek naar het tweede boek.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Bewaar het bestand.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
