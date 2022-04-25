---
title: Sloučit různé soubory Excel do jednoho v Java
url: /cs/java/merger/
description: Sloučit soubory Excel pomocí Java do více listů nebo jednoho listu. Slučujte, kombinujte nebo spojujte dokumenty Excel do PDF, obrázků a HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Sloučení souborů Microsoft<sup>&reg;</sup> Excel prostřednictvím Java" h2="Zkombinujte dva nebo více souborů aplikace Excel do jedné tabulky pomocí kódu Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Knihovna Excel](/cells/java/) poskytuje několik způsobů, jak kombinovat sešity s různými typy obsahu, jako jsou vzorce, obrázky, data, grafy atd., do jednoho tabulkového dokumentu. Mezi podporované formáty souborů patří XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV a další.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinujte soubory aplikace Excel s obrázky a grafy" %}}
Nejjednodušší způsob, jak zkombinovat dva soubory aplikace Excel s obrázky a grafy, je volání [Sešit.kombinovat](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) metoda. Umožňuje sloučit soubory Excel podobného typu do jedné tabulky.
{{% blocks/products/pf/feature-page-code h3="Java Kód pro kombinování souborů aplikace Excel" %}}

```cs
// načtěte první soubor Excel
var book1 = new Workbook("with-charts.xlsx");
// načíst druhý soubor aplikace Excel do samostatné instance
var book2 = new Workbook("with-images.xlsx");

// sloučit dva sešity
book1.combine(book2);
// uložit cílový sešit 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Sloučit více souborů aplikace Excel" %}}
[CellsHelper.mergeFiles](https://apireference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) metoda podporuje sloučení dat, stylu a vzorců souboru Excel do nové tabulky stejného formátu. Je to efektivní způsob, jak sloučit několik souborů při použití ukládání do mezipaměti. 
{{% blocks/products/pf/feature-page-code h3="Java Kód pro sloučení několika souborů aplikace Excel" %}}

```cs
// vytvořit pole (délka=2)
String[] files = new String[2];
// zadejte cesty k souborům, které mají být sloučeny
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// sloučit soubory a uložit výsledek
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Sloučení souborů aplikace Excel zkopírováním pracovních listů" %}}
[Worksheet.copy](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)lze použít ke kopírování dat a formátování ze zdrojového listu do jiného listu v rámci nebo mezi sešity. Metoda bere jako parametr objekt zdrojového listu.
{{% blocks/products/pf/feature-page-code h3="Java Kód pro kopírování sešitů mezi sešity" %}}

```cs
// Vytvořte sešit.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Vytvořte další sešit.
Workbook excelWorkbook1 = new Workbook();

// Zkopírujte první list první knihy do druhé knihy.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Uložte soubor.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}