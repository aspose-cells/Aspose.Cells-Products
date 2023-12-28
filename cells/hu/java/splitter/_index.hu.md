---
title: Ossza fel az Excel-táblázatot munkalapokra a Java címen
description: Java forráskódok, amelyek elmagyarázzák, hogyan lehet a Microsoft Excel-fájlokat több dokumentumra felosztani a Java Excel könyvtár használatával
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-fájl felosztása via Java" h2="Ossza fel az Excel-táblázatot munkalapokra a Java alapú alkalmazásokon belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
Különféle forgatókönyvek léteznek, amikor szükség van az Excel-fájlok felosztására, például a tanulók adatait tartalmazó táblázatra, minden tanuló számára egyetlen lap kiosztásával. És minden lapot külön fájlként kell felosztani a tanulók számára. Az automatizáláshoz via Java alkalmazás,[Java Excel API](/cells/hu/java/) ott van az Excel dokumentum laponkénti felosztása. A támogatott formátumok: XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ossza fel az Excel-dokumentumot több fájlra" %}}

 Az Excel fájl lapra való felosztásának legegyszerűbb módja a következő: Hozzáférés az összes munkalaphoz, ismétlés az egyes lapokon, és egyenként mentheti a kívánt formátumban. A munkalap betöltéséhez a API biztosítja[Munkafüzet](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) módszer a lapok teljes számát kapja. Ismételje meg az egyes lapokat, és használja[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) adott lap eléréséhez. Helyezze át a kiválasztott lapadatokat az újonnan létrehozott munkafüzet osztályobjektumba a használatával[Másolási módszer](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Végül mentse el a kívánt formátumba.

{{% blocks/products/pf/feature-page-code h3="Java Kód Excel-fájlok felosztásához" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Ossza fel az Excel munkalapot ablaktáblákra" %}}

A API az Excel-munkalap különböző ablaktáblákra való felosztását is biztosítja. A folyamat a következő: Töltse be a fájlt a Workbook osztály segítségével. Válassza ki az első munkalapot vagy bármely szükséges lapot az index megadásával. Hívja meg a setActiveCell-t, amelynek paramétere a megfelelő cellaindex. Végül a split() metódus meghívásával ossza fel a munkalap ablakot különböző ablaktáblákra.

{{% blocks/products/pf/feature-page-code h3="Java Kód az Excel munkalap panelnézetre való felosztásához" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
