---
title: "Az Excel-táblázat felosztása munkalapokra itt: Java"

description: Java forráskód, amely elmagyarázza, hogyan oszthat fel Microsoft Excel fájlokat több dokumentumra az Java Excel könyvtár használatával
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-fájl felosztása a következőn keresztül: Java" h2="Ossza fel az Excel-táblázatot munkalapokra a Java alapú alkalmazásokon belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Különféle forgatókönyvek léteznek, amikor szükség van az Excel-fájlok felosztására, például egy tanulói adatokat tartalmazó táblázatra, minden tanuló számára egyetlen lap kiosztásával. És minden egyes lapot külön fájlként kell felosztani. A Java alkalmazáson keresztül történő automatizáláshoz, [Java Excel API](/cells/java/) ott van az Excel dokumentum laponkénti felosztása. A támogatott formátumok közé tartozik az XLS, XLSX, XLSB, XLSM, ODS. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ossza fel az Excel-dokumentumot több fájlra" %}}

Az Excel fájl lapra való felosztásának legegyszerűbb módja a következő: Hozzáférés az összes munkalaphoz, ismétlés az egyes lapokon, és egyenként mentheti a kívánt formátumban. A munkalap betöltéséhez a API biztosítja [Munkafüzet](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály. [getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) módszer a teljes lapszámot kapja. Ismételje meg az egyes lapokat, és használja [getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) adott lap eléréséhez. Helyezze át a kiválasztott lapadatokat az újonnan létrehozott munkafüzet osztályobjektumba a használatával [Másolási módszer](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Végül mentse el a kívánt formátumba.

{{% blocks/products/pf/feature-page-code h3="Java Kód az Excel-fájlok felosztásához" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Ossza fel az Excel munkalapot ablaktáblákra" %}}

A API lehetőséget biztosít az Excel-munkalapok különböző panelekre való felosztására is. A folyamat a következő: Töltse be a fájlt a Workbook osztály segítségével. Válassza ki az első munkalapot vagy bármely szükséges lapot az index megadásával. Hívja meg a setActiveCell-t, amelynek paramétere a megfelelő cellaindex. Végül a split() metódus meghívásával ossza fel a munkalap ablakot különböző ablaktáblákra.

{{% blocks/products/pf/feature-page-code h3="Java Kód az Excel munkalap panelnézetre való felosztásához" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
