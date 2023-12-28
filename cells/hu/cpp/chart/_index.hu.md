---
title: Hozzon létre Excel-diagramokat és konvertáljon képekké a C++ számon keresztül
description: C++ forráskód diagram vagy diagram rajzolásához és konvertálásához Microsoft Excelben a C++ könyvtár használatával
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hozzon létre Microsoft<sup>&reg;</sup> Excel-diagramokat és konvertáljon képekké a C++ számon keresztül" h2="A C++ alapú alkalmazásokban Excel-dokumentumdiagramokat konvertálhat képekké, valamint diagramokat hozhat létre, beleértve a kör-, piramis-, vonal- és buborékdiagramokat." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Az Excel diagramok segítségével átfogóbb képet kaphat, és könnyen elemezheti az adatokat a helyes döntések meghozatalához.[C++ Excel Library](/cells/hu/cpp/) által felsorolt különböző diagramok létrehozását támogatja[enum Aspose::Cells::Diagramok::ChartType
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/) beleértve a terület-, oszlop-, kör-, piramis-, vonal- és buborékdiagramokat. Ezenkívül a diagramok képpé konvertálásához a API a[Elképzelni](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/) módszert a kívánt képformátumba.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Hozzon létre Excel diagramokat" %}}

 Az Excel diagram létrehozásának folyamata az, hogy hozzon létre egy példányt a[Munkafüzet osztály](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) és válassza ki a kívántat[Munkalap](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/) . Adja hozzá a diagramot a segítségével[Módszer hozzáadása](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/)releváns paraméterekkel, beleértve a diagram típusát. A diagram elérése az indexen és a[Hozzáadás](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/) a diagram adatforrása.

{{% blocks/products/pf/feature-page-code h3="C++ Kód Excel-diagramok létrehozásához" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Diagramok konvertálása képekké" %}}


A diagramok konvertálásához először létre kell hozni a megfelelő típusú diagramot a fenti kóddal, vagy elérni a megfelelő lapról. Határozza meg a kép kimeneti mentési útvonalát, és használja a ToImage módszert az átalakításhoz.

 
{{% blocks/products/pf/feature-page-code h3="C++ Kód az Excel diagramok konvertálásához" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
