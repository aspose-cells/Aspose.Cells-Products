---
title: Voeg verschillende Excel-bestanden samen tot één bestand in Java
description: Voeg Excel-bestanden samen met Java in meerdere bladen of één blad. Voeg Excel-documenten samen, combineer of voeg ze samen tot PDF, Afbeeldingen en HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-bestanden samenvoegen via Java" h2="Combineer twee of meer Excel-bestanden in één spreadsheet met behulp van code Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel-bibliotheek](/cells/nl/java/)biedt meerdere manieren om werkmappen met verschillende soorten inhoud, zoals formules, afbeeldingen, gegevens, grafieken enz., te combineren in één enkel spreadsheetdocument. Ondersteunde bestandsformaten zijn onder meer XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV en meer.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combineer Excel-bestanden met afbeeldingen en grafieken" %}}
 De eenvoudigste manier om twee Excel-bestanden met afbeeldingen en grafieken te combineren, is door de[Werkmap.combineren](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) methode. Hiermee kunt u Excel-bestanden van een vergelijkbaar type samenvoegen tot één spreadsheet.
{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-bestanden te combineren" %}}

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

{{% blocks/products/pf/feature-page-section h2="Meerdere Excel-bestanden samenvoegen" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) methode ondersteunt het samenvoegen van gegevens, stijl en formules van een Excel-bestand naar een nieuw spreadsheet met hetzelfde formaat. Het is een efficiënte manier om meerdere bestanden samen te voegen terwijl u caching gebruikt.
{{% blocks/products/pf/feature-page-code h3="Java Code om verschillende Excel-bestanden samen te voegen" %}}

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

{{% blocks/products/pf/feature-page-section h2="Voeg Excel-bestanden samen door werkbladen te kopiëren" %}}
[Werkblad.kopie](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)kan worden gebruikt om gegevens en opmaak van een bronwerkblad naar een ander werkblad binnen of tussen werkmappen te kopiëren. De methode neemt het bronwerkbladobject als parameter.
{{% blocks/products/pf/feature-page-code h3="Java Code om werkbladen tussen werkmappen te kopiëren" %}}

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

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde samenvoegformaten" subTitle="Met behulp van Java kan men ook vele andere bestandsformaten samenvoegen, waaronder .." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Door komma\'s gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="HyperText-opmaaktaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Archiefformaat webpagina" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="OpenDocument-spreadsheetbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Door tabs gescheiden waarden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Tekstdocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Excel binair formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Binair Excel-werkmapbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Spreadsheet-bestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML Excel-bestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Excel-sjabloon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Excel-sjabloon met macro\'s" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
