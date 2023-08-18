---
title: Sloučit různé soubory Excel do jednoho v Java
description: Sloučit soubory aplikace Excel pomocí Java do více listů nebo jednoho listu. Sloučit, kombinovat nebo zřetězit dokumenty aplikace Excel také na PDF, Obrázky a HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Sloučení souborů aplikace Excel via Java" h2="Zkombinujte dva nebo více souborů aplikace Excel do jedné tabulky pomocí kódu Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Knihovna Excel](/cells/cs/java/) poskytuje několik způsobů, jak kombinovat sešity s různými typy obsahu, jako jsou vzorce, obrázky, data, grafy atd., do jednoho tabulkového dokumentu. Mezi podporované formáty souborů patří XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV a další, CSV, 0781.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinujte soubory aplikace Excel s obrázky a grafy" %}}
 Nejjednodušší způsob, jak zkombinovat dva soubory aplikace Excel s obrázky a grafy, je volání[Sešit.kombinovat](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) metoda. Umožňuje sloučit soubory Excel podobného typu do jedné tabulky.
{{% blocks/products/pf/feature-page-code h3="Java Kód pro kombinování souborů aplikace Excel" %}}

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

{{% blocks/products/pf/feature-page-section h2="Sloučit více souborů aplikace Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles)metoda podporuje sloučení dat, stylu a vzorců souboru Excel do nové tabulky stejného formátu. Je to efektivní způsob, jak sloučit několik souborů při použití ukládání do mezipaměti.
{{% blocks/products/pf/feature-page-code h3="Java Kód pro sloučení několika souborů aplikace Excel" %}}

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

{{% blocks/products/pf/feature-page-section h2="Sloučení souborů aplikace Excel zkopírováním pracovních listů" %}}
[Worksheet.copy](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) lze použít ke kopírování dat a formátování ze zdrojového listu do jiného listu v rámci nebo mezi sešity. Metoda přebírá objekt zdrojového listu jako parametr.
{{% blocks/products/pf/feature-page-code h3="Java Kód pro kopírování sešitů mezi sešity" %}}

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

{{< blocks/products/pf/agp/other-supported-section title="Další podporované slučovací formáty" subTitle="Pomocí Java lze také sloučit mnoho dalších formátů souborů, včetně..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="hodnoty oddělené čárkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Formát archivu webové stránky" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Hodnoty oddělené tabulátory" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Textový dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Binární soubor sešitu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Soubor tabulky" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Soubor Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Excel šablona" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Šablona s podporou maker aplikace Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
