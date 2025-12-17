---
title: Excel-diagramok létrehozása és képekké konvertálása a Go segítségével a C++-es telefonszámon
description: A C++ forráskód segítségével rajzolhat és konvertálhat diagramokat vagy diagramokat a Microsoft Excelben a Go via C++ könyvtár segítségével.
keywords: [Go via C++ Aspose.Cells., Go via C++ Convert chart to image., Go via C++ Save chart to image., Go via C++ chart to image., create charts in Go via C++., insert charts in Go via C++., manage charts in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hozz létre Microsoft<sup>&reg;</sup> Excel-diagramokat és konvertálj képekké a Go segítségével a C++-es verzión keresztül" h2="Excel dokumentumok diagramjait képekké konvertálhatja, valamint diagramokat hozhat létre, beleértve a kör-, piramis-, vonal- és buborékdiagramokat a Go via C++ alapú alkalmazásokban." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Az Excel táblázatok segítségével átfogó képet kaphatunk az adatokról, és könnyen elemezhetjük azokat, hogy helyes döntéseket hozhassunk.[Látogasson el a C++-es Excel könyvtárba](/cells/hu/go-cpp/) támogatja a különböző listázott diagramok létrehozását[enum Aspose::Cells::Diagramok::Diagramtípus
](https://reference.aspose.com/cells/go-cpp/charttype/) beleértve a terület-, sáv-, kör-, piramis-, vonal- és buborékdiagramokat. Továbbá, diagramok képekké konvertálásához a API-es számon egy[Képhez](https://reference.aspose.com/cells/go-cpp/chart/toimage_string/) módszer a kívánt képformátumba.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel-diagramok létrehozása" %}}

 Az Excel diagram létrehozásának folyamata a következő: hozzunk létre egy példányt a diagramból.[Munkafüzet osztály](https://reference.aspose.com/cells/go-cpp/workbook/) és válassza ki a kívánt[Munkalap](https://reference.aspose.com/cells/go-cpp/worksheet/) . Adja hozzá a diagramot a következővel:[Metódus hozzáadása](https://reference.aspose.com/cells/go-cpp/chartcollection/addfloatingchart/) a vonatkozó paraméterekkel, beleértve a diagram típusát is. A diagramhoz indexen és[Hozzáadás](https://reference.aspose.com/cells/go-cpp/seriescollection/add_string_bool_bool/) diagram adatforrása.

{{% blocks/products/pf/feature-page-code h3="Menj végig a C++ kódon Excel-diagramok létrehozásához" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "create-excel-chart.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Diagramok konvertálása képekké" %}}


A diagramok konvertálásához először létre kell hozni a megfelelő típusú diagramot a fenti kóddal, vagy a megfelelő munkalapról kell elérni. Meg kell adni a kép kimeneti mentési útvonalát, és a ToImage metódust kell használni a konvertáláshoz.


{{% blocks/products/pf/feature-page-code h3="Menj végig a C++ kódon az Excel-diagramok konvertálásához" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "convert-excel-chart-to-image.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{< /blocks/products/pf/feature-page-wrap >}}