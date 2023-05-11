---
title: Excel diagramok létrehozása és konvertálása képekké via .NET
description:  C# forráskód diagram vagy diagram rajzolásához és konvertálásához Microsoft Excelben a .NET könyvtár használatával.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel fájldiagramok létrehozása és konvertálása via .NET" h2="Hozzon létre Excel-dokumentumdiagramokat, és konvertáljon képekké kiszolgálóoldali API-k segítségével a .NET alapú alkalmazásokon belül." >}}
{{% blocks/products/pf/feature-page-summary %}}
 A diagramok rajzolása az adatok grafikus megjelenítésének művészete az egyszerű elemzés érdekében.[.NET Excel Library](/cells/hu/net/) támogatja az Excel-fájlokon belüli diagramok rajzolását. A API támogatja a felsorolt különböző diagramok létrehozását[ChartType Enumeration](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) beleértve a kör-, piramis-, vonal- és buborékdiagramokat. Ezenkívül a diagramokat képekké alakítja. API biztosít a[Grafikonok osztály](https://reference.aspose.com/cells/net/aspose.cells.charts) diagram építőelemekhez.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Hozzon létre diagramokat az Excel fájlban" %}}

 A diagramok létrehozása az Excel API használatával egyszerű. A folyamat a létrehozás[Munkafüzet osztály](https://reference.aspose.com/cells/net/aspose.cells/workbook) objektumot, és az index megadásával válassza ki az első munkalapot vagy a megfelelő lapot. Illessze be a szükséges cellaadatokat a segítségével[PutValue módszer](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Adjon hozzá diagramot a munkalaphoz a Charts gyűjtemény használatával[Módszer hozzáadása](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Adja meg a[ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) ChartType felsorolásból.
{{% blocks/products/pf/feature-page-code h3="C# Kód Excel-diagramok létrehozásához" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Konvertálja az Excel diagramokat képekké" %}}

 A diagramok képpé konvertálásának folyamata a következő: Használja a Workbook osztályt az Excel fájl betöltéséhez, válassza ki a diagramokat tartalmazó megfelelő munkalapot, és hívja meg a[ToImage módszer](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) az átalakításhoz.

{{% blocks/products/pf/feature-page-code h3="C# Kód az Excel-diagram képpé konvertálásához" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
