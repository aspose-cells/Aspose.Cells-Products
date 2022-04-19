---
title: Excel-fájl egyesítése API .NET C#
url: /hu/net/merger/
description: Összefűzhet Excel és OpenOffice táblázatfájlokat néhány sornyi C# kóddal.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-fájl egyesítése a következőn keresztül: .NET" h2="Kombináljon 2 vagy több Excel-fájlt egyetlen táblázatban a C# kód használatával" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel-könyvtár](/cells/net/) többféle lehetőséget biztosít a munkafüzetek különféle típusú tartalommal, például képletekkel, adatokkal, képekkel, diagramokkal és így tovább egyetlen táblázatfájlba történő kombinálására. A támogatott fájlformátumok közé tartozik az XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV és még sok más.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinálja az Excel fájlokat képekkel és diagramokkal" %}}
A legegyszerűbb módja annak, hogy 2 Excel-fájlt egyesítsen képekkel és diagramokkal, ha meghívja a [Munkafüzet.Össze](https://apireference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) módszer. Lehetővé teszi a hasonló típusú Excel fájlok egyetlen táblázatba való egyesítését.
{{% blocks/products/pf/feature-page-code h3="C# Kód az Excel-fájlok kombinálásához" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Egyesítsen több Excel-fájlt" %}}
[CellsHelper.MergeFiles](https://apireference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) A módszer támogatja az Excel-fájl adatainak, stílusának és képleteinek egyesítését egy új, azonos formátumú táblázattal. Ez egy hatékony módja több fájl egyesítésének gyorsítótár használata közben. 
{{% blocks/products/pf/feature-page-code h3="C# Kód több Excel-fájl egyesítéséhez" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Excel-fájlok egyesítése munkalapok másolásával" %}}
[Munkalap.Másolás](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) használható adatok és formázások másolására egy forrásmunkalapról egy másik munkalapra a munkafüzeteken belül vagy a munkafüzetek között. A metódus a forrás munkalap objektumot veszi paraméterként.
{{% blocks/products/pf/feature-page-code h3="C# Kód munkalapok Excel-fájlok közötti másolásához" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}