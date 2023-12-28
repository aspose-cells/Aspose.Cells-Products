---
title: Hozzon létre Excel-diagramokat és konvertáljon képekké via Java
description:  Java forráskód diagram vagy diagram rajzolásához és konvertálásához Microsoft Excelben a Java könyvtár használatával.
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel fájldiagramok átalakítása és létrehozása via Java" h2="Java alapú alkalmazásokon belüli kiszolgálóoldali API-k segítségével Excel-dokumentumdiagramokat konvertálhat képekké, valamint különféle diagramokat hozhat létre." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Az adatok diagramon keresztüli elemzése nagyobb képet mutat, és könnyebben megalapozottabb döntéseket hozhat, tisztább betekintéssel.[Java Excel Library](/cells/hu/java/) által felsorolt különböző diagramok rajzolását támogatja[ChartType](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) beleértve a kör-, piramis-, vonal- és buborékdiagramokat. Ezenkívül a diagramokat képekké alakítja. API biztosít a[Grafikonok osztály](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) egyetlen Excel diagram ábrázolásához.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Konvertálja az Excel diagramokat képekké" %}}

 A diagramok képpé konvertálásának folyamata, beleértve a JPG, PNG, TIFF, BMP stb.[Munkafüzet](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) osztályba az Excel fájl betöltéséhez válassza ki a megfelelőt[munkalap](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) tartalmazza a diagramokat, vagy ismételje meg az egyes munkalapok diagramjait. Határozza meg[ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) és jelenítse meg a diagram kimeneti képét a segítségével[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Kód az Excel-diagram képpé konvertálásához" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Hozzon létre diagramokat az Excel fájlban" %}}

Diagramok létrehozása az Excel API használatával egyszerű, mivel a API különböző osztályokat kínál, például Tengely, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection stb. különböző típusú diagramokhoz. A folyamat az, hogy hozzon létre munkafüzet osztályobjektumot, és válassza ki az első munkalapot vagy a megfelelő lapot az index megadásával. A diagram adatforrásaként szúrjon be értékeket a munkalap celláiba a használatával[érték beállítása](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) módszer. Használja a ChartCollection gyűjteményt[módszer hozzáadása](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) a diagram hozzáadásához adja meg a diagram típusát a ChartType felsorolással. Az új Chart objektum elérése a ChartCollection gyűjteményből az index átadásával. Használja a[SeriesCollection](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) diagram objektumot a diagram adatforrásának megadásához.

{{% blocks/products/pf/feature-page-code h3="Java Kód Excel-diagramok létrehozásához" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
