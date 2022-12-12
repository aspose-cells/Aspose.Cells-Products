---
title: "Megjegyzések beszúrása Excelbe a következőn keresztül: .NET"

description: C# forráskódok, amelyek segítségével megjegyzéseket szúrhat be Microsoft Excel-fájlokba a .NET Library használatával. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel megjegyzések beszúrása a következőn keresztül: .NET" h2="Hozzon létre Excel-dokumentumokat és szúrjon be megjegyzéseket szerveroldali API-k segítségével a .NET-alapú alkalmazásokba." >}}
{{% blocks/products/pf/feature-page-summary %}}

Megjegyzéseket fűzhet a cellákhoz. Ha egy cellához megjegyzés tartozik, egy jelző jelenik meg a cella sarkában. A megjegyzések akkor jelennek meg, ha a kurzort egy cellára viszi.Ezek a megjegyzések használhatók megvitatásra, speciális utasításokra vagy a dokumentumtartalom megjelölésére. [.NET Excel-könyvtár](/cells/net/) támogatja a megjegyzések beszúrását Excel-fájlokba.Ehhez a(z) API a [Megjegyzés](https://reference.aspose.com/cells/net/aspose.cells/comment) osztály megjegyzésekhez építőelem.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Megjegyzések beszúrása Excel fájlba" %}}

A megjegyzések beszúrása az Excel API használatával egyszerű. A folyamat a létrehozás [Munkafüzet osztály](https://reference.aspose.com/cells/net/aspose.cells/workbook) objektumot, és az index megadásával válassza ki az első munkalapot vagy a megfelelő lapot. Illessze be a szükséges cellaadatokat a segítségével [PutValue módszer](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Megjegyzés hozzáadása a munkalaphoz a használatával [CommentCollection](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)'s [Módszer hozzáadása](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Kód a megjegyzés beszúrásához az Excelben" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
