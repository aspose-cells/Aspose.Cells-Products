---
title: Oszd fel az Excel munkalapot a C# számon
description: C# forráskódok, amelyek elmagyarázzák, hogyan lehet a Microsoft Excel-fájlokat több fájlra felosztani a Visual C#.NET alkalmazásokban
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-fájl felosztása via .NET" h2="Egyetlen Excel dokumentum felosztása különböző fájlokra a C# kód használatával a .NET alapú alkalmazásokon belül" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel Library](/cells/hu/net/) képes Excel dokumentumot több táblázatra felosztani a .NET alapú alkalmazásokon belül. A támogatott fájlformátumok: XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ossza fel az Excel-dokumentumot több fájlra" %}}
 Az Excel-fájlok lapos felosztásának legegyszerűbb módja az, hogy az összes munkalapot eléri a következőn keresztül[Munkalapok](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Iterálva az egyes lapokat, és meghívja a[Másolat](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) módszer. Végül elmenti egy megadott útvonalra.

 + Töltse be az Excel fájlt a teljes elérési úttal a használatával[Munkafüzet osztály](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Iteráció minden lapon keresztül
+ Hozzon létre egy új munkafüzet osztályobjektumot
 + Másolja a lapot a következőn keresztül[Másolási módszer](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Hívja meg a Save() metódust, és adja át a fájlnevet (teljes elérési utat) a megfelelő SaveFormat formátummal.

{{% blocks/products/pf/feature-page-code h3="C# Kód Excel-fájlok felosztásához" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Ossza fel az Excel munkalapot ablaktáblákra" %}}

 A API a API biztosítja a munkalapablak panelekre való felosztását[Split módszer](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split)munkalap osztály, amely a munkalap osztott nézetét biztosítja. A osztott nézet eltávolításához a API szám tartozik[RemoveSplit módszer](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Végül mentse el egy megadott útvonalra.

{{% blocks/products/pf/feature-page-code h3="C# Kód az Excel munkalapablak felosztásához" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Kód az osztott panorámakép eltávolításához" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
