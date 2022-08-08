---
title: "Excel-diagramok létrehozása és konvertálása képekké a következőn keresztül: C++"
url: /hu/cpp/chart/
description: C++ forráskód a diagram vagy diagram megrajzolásához és konvertálásához Microsoft Excelben a C++ Library segítségével
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel diagramok létrehozása és konvertálása képekké a következőn keresztül: C++" h2="Konvertálja az Excel dokumentumdiagramjait képekké, valamint készítsen diagramokat, köztük kör-, piramis-, vonal- és buborékdiagramokat a C++ alapú alkalmazásokban." >}}

{{% blocks/products/pf/feature-page-summary %}}

Az Excel diagramok segítségével átfogóbb képet kaphat, és könnyen elemezheti az adatokat a helyes döntések meghozatalához. [C++ Excel-könyvtár](/cells/cpp/) által felsorolt különböző diagramok létrehozását támogatja [enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) beleértve a terület-, oszlop-, kör-, piramis-, vonal- és buborékdiagramokat. Ezenkívül a diagramok képpé konvertálásához a API a [ToImage metódus](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) a kívánt képformátumba.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Hozzon létre Excel diagramokat" %}}

Az Excel diagram létrehozásának folyamata az, hogy hozzon létre egy példányt a [IWorkbook osztály](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) és válassza ki a kívántat [Munkalap](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Adja hozzá a diagramot a segítségével [Módszer hozzáadása](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) releváns paraméterekkel, beleértve a diagram típusát. A diagram elérése az indexen és a [Hozzáadás](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) a diagram adatforrása.

{{% blocks/products/pf/feature-page-code h3="C++ Kód Excel-diagramok létrehozásához" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Diagramok konvertálása képekké" %}}


A diagramok konvertálásához először létre kell hozni a megfelelő típusú diagramot a fenti kóddal, vagy elérni a megfelelő lapról. Határozza meg a kép kimeneti mentési útvonalát, és használja a ToImage módszert az átalakításhoz.

 
{{% blocks/products/pf/feature-page-code h3="C++ Kód az Excel diagramok konvertálásához" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}