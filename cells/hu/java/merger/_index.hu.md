---
title: "Különböző Excel-fájlok egyesítése a következőben: Java"
url: /hu/java/merger/
description: Egyesítse az Excel-fájlokat a Java használatával több lapra vagy egyetlen lapra. Egyesítse, kombinálja vagy fűzze össze Excel-dokumentumokat PDF-be, Képekbe és HTML-be is.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-fájl egyesítése a következőn keresztül: Java" h2="Kombináljon két vagy több Excel-fájlt egyetlen táblázatban a Java kód használatával" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel-könyvtár](/cells/java/) többféle lehetőséget biztosít a különféle típusú tartalommal, például képletekkel, képekkel, adatokkal, diagramokkal stb. rendelkező munkafüzetek egyetlen táblázatkezelő dokumentumban való kombinálására. A támogatott fájlformátumok közé tartozik az XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV és még sok más.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinálja az Excel fájlokat képekkel és diagramokkal" %}}
A legegyszerűbb módja annak, hogy két képeket és diagramokat tartalmazó Excel-fájlt kombináljon, ha meghívja a [Munkafüzet.kombinálni](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) módszerrel. Lehetővé teszi a hasonló típusú Excel fájlok egyetlen táblázatba való egyesítését.
{{% blocks/products/pf/feature-page-code h3="Java Kód az Excel-fájlok kombinálásához" %}}

```cs
// töltse be az első Excel fájlt
var book1 = new Workbook("with-charts.xlsx");
// töltse be a második Excel-fájlt egy külön példányba
var book2 = new Workbook("with-images.xlsx");

// két munkafüzet egyesítése
book1.combine(book2);
// mentse el a célmunkafüzetet 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Egyesítsen több Excel-fájlt" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) A módszer támogatja az Excel-fájl adatainak, stílusának és képleteinek egyesítését egy új, azonos formátumú táblázattal. Ez egy hatékony módja több fájl egyesítésének gyorsítótár használata közben. 
{{% blocks/products/pf/feature-page-code h3="Java Kód több Excel-fájl egyesítéséhez" %}}

```cs
// tömb létrehozása (hossz=2)
String[] files = new String[2];
// adja meg az egyesítendő fájl elérési útját
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// egyesítse a fájlokat az eredmény mentéséhez
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Excel-fájlok egyesítése munkalapok másolásával" %}}
[Munkalap.másolat](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)használható adatok és formázások másolására egy forrásmunkalapról egy másik munkalapra a munkafüzeteken belül vagy a munkafüzetek között. A metódus a forrás munkalap objektumot veszi paraméterként.
{{% blocks/products/pf/feature-page-code h3="Java Kód munkalapok munkafüzetek közötti másolásához" %}}

```cs
// Hozzon létre egy munkafüzetet.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Hozzon létre egy másik munkafüzetet.
Workbook excelWorkbook1 = new Workbook();

// Másolja át az első könyv első lapját a második könyvbe.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Mentse el a fájlt.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}