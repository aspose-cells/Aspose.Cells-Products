---
title: A via .NET C# számú Excel-fájl metaadatainak kezelése
description: Tekintse meg, adja hozzá, szerkessze, távolítsa el vagy bontsa ki az Excel-fájlok metaadatait mindössze néhány sornyi C# kóddal
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A Microsoft<sup>&reg;</sup> Excel fájl metaadatainak kezelése via .NET" h2="Tekintse meg, adja hozzá, frissítse, távolítsa el vagy bontsa ki a beépített és egyéni Excel-fájlok tulajdonságait a kiszolgálóoldali .NET API-k segítségével." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/hu/net/) támogatja a rendszer által meghatározott (beépített) tulajdonságok, például cím, szerző neve, dokumentumstatisztika stb., valamint a felhasználó által definiált (egyéni) tulajdonságok kezelését név-érték pár formájában. Van[Munkafüzet osztály](https://reference.aspose.com/cells/net/aspose.cells/workbook) a fájlok betöltéséhez, és[Munkalapgyűjtemény](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) feladatlapok gyűjtésével, valamint[Feladatlap osztály](https://reference.aspose.com/cells/net/aspose.cells/worksheet) egyetlen munkalap ábrázolására. Ezekkel az osztályokkal együtt a BuiltInDocumentProperties és a CustomDocumentProperties egyszerűvé teszi a metaadatkezelés folyamatát.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Beépített tulajdonságok kezelése" %}}

 A rendszer által meghatározott tulajdonságok kezeléséhez a API biztosítja[BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) a programozók pedig könnyen hozzáférhetnek egy beépített tulajdonsághoz és frissíthetik annak értékét. Az alkalmazás követelményeitől függően a fejlesztők használhatják az indexet vagy a tulajdonság nevét a[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Kód a beépített tulajdonságok kezeléséhez" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Egyéni definiált tulajdonságok kezelése" %}}

 A felhasználó által meghatározott tulajdonságok kezeléséhez a API biztosítja[CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , és a fejlesztők könnyedén hozzáférhetnek a már hozzáadott tulajdonságokhoz, valamint új tulajdonságokat adhatnak hozzá. Egyéni tulajdonságok hozzáadásához[Módszer hozzáadása](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) nak,-nek[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) osztály hozzáadja a tulajdonságot, és visszaadja az új tulajdonság referenciáját an[Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) tárgy. A DocumentProperty osztály a dokumentumtulajdonság nevének, értékének és típusának lekérésére szolgál[DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) amely visszaadja az egyik[PropertyType](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) felsorolási értékek.
 
{{% blocks/products/pf/feature-page-code h3="C# Kód a metaadatok hozzáadásához az Excel-fájlban" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Kód az egyéni tulajdonság eltávolításához az Excel-fájlban" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
