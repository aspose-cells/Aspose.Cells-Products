---
title: Különböző Excel-fájlok egyesítése egyetlen Java-es számon
description: Egyesítse az Excel fájlokat a Java használatával több lapra vagy egyetlen lapra. Egyesítse, egyesítse vagy fűzze össze az Excel-dokumentumokat a PDF-es, a Képek és a HTML-es számokkal is.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-fájl egyesítése via Java" h2="Kombináljon két vagy több Excel-fájlt egyetlen táblázatban a Java kód használatával" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel Library](/cells/hu/java/)többféle lehetőséget biztosít a különféle típusú tartalommal, például képletekkel, képekkel, adatokkal, diagramokkal stb. rendelkező munkafüzetek egyetlen táblázatkezelő dokumentumban való kombinálására. A támogatott fájlformátumok a XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, CSV, 3081 és még sok más.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinálja az Excel fájlokat képekkel és diagramokkal" %}}
 A legegyszerűbb módja annak, hogy két képeket és diagramokat tartalmazó Excel-fájlt kombináljon, ha meghívja a[Munkafüzet.kombinálni](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) módszerrel. Lehetővé teszi a hasonló típusú Excel fájlok egyetlen táblázatba való egyesítését.
{{% blocks/products/pf/feature-page-code h3="Java Kód az Excel-fájlok kombinálásához" %}}

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

{{% blocks/products/pf/feature-page-section h2="Egyesítsen több Excel-fájlt" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) A módszer támogatja az Excel-fájl adatainak, stílusának és képleteinek egyesítését egy új, azonos formátumú táblázattal. Ez egy hatékony módja több fájl egyesítésének gyorsítótár használata közben.
{{% blocks/products/pf/feature-page-code h3="Java Kód több Excel-fájl egyesítéséhez" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel-fájlok egyesítése munkalapok másolásával" %}}
[Munkalap.másolat](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)használható adatok és formázások másolására egy forrásmunkalapról egy másik munkalapra a munkafüzeteken belül vagy a munkafüzetek között. A metódus a forrás munkalap objektumot veszi paraméterként.
{{% blocks/products/pf/feature-page-code h3="Java Kód munkalapok munkafüzetek közötti másolásához" %}}

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

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott egyesítő formátumok" subTitle="A Java használatával számos más fájlformátum is egyesíthető, beleértve a..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Vesszővel elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Weboldal archív formátuma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="OpenDocument táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Tabulátorral elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Szöveges dokumentum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Excel bináris formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Bináris Excel munkafüzet fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML Excel fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Excel-sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Excel-makró-kompatibilis sablon" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
