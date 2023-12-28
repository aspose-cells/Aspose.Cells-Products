---
title: Megjegyzések beszúrása Excel via .NET-be
description:  C# forráskódok, amelyek segítségével megjegyzést lehet beszúrni a Microsoft Excel-fájlokba a .NET könyvtár használatával.
keywords: [C# Aspose.Cells., add excel comments., insert excel comments., access excel comments., remove excel comments., delete excel comments., add comments in excel., insert comments in excel., access comments in excel., remove comments in excel., delete comments in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel megjegyzések beszúrása via .NET" h2="Hozzon létre Excel-dokumentumokat és szúrjon be megjegyzéseket kiszolgálóoldali API-k segítségével a .NET alapú alkalmazásokban." >}}
{{% blocks/products/pf/feature-page-summary %}}

 Megjegyzéseket fűzhet a cellákhoz. Ha egy cellához megjegyzés tartozik, egy jelző jelenik meg a cella sarkában. A megjegyzések akkor jelennek meg, ha a kurzort egy cellára viszi.Ezek a megjegyzések vitákhoz, speciális utasításokhoz vagy a dokumentumtartalom megjelöléséhez használhatók.[.NET Excel Library](/cells/hu/net/)támogatja a megjegyzések beszúrását Excel-fájlokba.Ehhez a API a[Megjegyzés](https://reference.aspose.com/cells/net/aspose.cells/comment) osztály megjegyzésekhez építőelem.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Megjegyzések beszúrása Excel fájlba" %}}

 A megjegyzések beszúrása az Excel API használatával egyszerű. A folyamat a létrehozás[Munkafüzet osztály](https://reference.aspose.com/cells/net/aspose.cells/workbook)objektumot, és az index megadásával válassza ki az első munkalapot vagy a megfelelő lapot. Illessze be a szükséges cellaadatokat a segítségével[PutValue módszer](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Megjegyzés hozzáadása a munkalaphoz a használatával[CommentCollection](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 's[Módszer hozzáadása](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Kód a megjegyzés beszúrásához az Excelben" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
