---
title: Az Excel fájl metaadatainak kezelése a C++ számon keresztül
description: Az Excel-fájlok metaadatainak megtekintése, hozzáadása, szerkesztése, eltávolítása vagy kibontása a C++ könyvtár használatával
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A Microsoft<sup>&reg;</sup> Excel dokumentum metaadatainak kezelése a C++ számon keresztül" h2="Egyéni és beépített Excel-dokumentumtulajdonságok megtekintése, beszúrása, frissítése, eltávolítása vagy kibontása a C++ alkalmazásokon belül." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metaadatok az Excelben – Az Excel fájl metaadatainak megtekintése, beszúrása és eltávolítása.[C++ Excel Library](/cells/hu/cpp/) A faclitates könnyen elérhető, mivel támogatja a beépített / rendszer által meghatározott tulajdonságokat, mint például a szerző neve, címe, dokumentumstatisztikái stb. név/érték párok. A folyamat automatizálása érdekében a könyvtár támogatja a nagy metaadat-fájlok létrehozását és karbantartását.[Munkafüzet](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)osztály Megnyitja a munkafüzetet elérési út, adatfolyam és speciális FileFormatType szerint. Tehát töltse be a fájlt a megfelelő módszerrel a további feldolgozáshoz. Az alább felsorolt lehetőségek közül néhány, és a fejlesztők könnyedén javíthatják kódjukat az alkalmazási követelményeknek megfelelően.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Olvassa el és frissítse a beépített tulajdonságokat" %}}

 A beépített tulajdonságok automatizálását a API biztosítja[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) metódus, amely egy DocumentProperties gyűjteményt ad vissza, amely a táblázat összes beépített dokumentumtulajdonságát reprezentálja. Az összes beépített tulajdonság elérése után érje el a megfelelő tulajdonságokat a megfelelő metódusokkal, például GetTitle(), GetSubject() stb. A tulajdonságok frissítéséhez a API olyan metódust biztosít, mint a SetTitle, SetSubject, SetAuthor, SetComments stb.[beépített dokumentumtulajdon-gyűjtemény](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) a szükséges funkcióhoz.

{{% blocks/products/pf/feature-page-code h3="C++ Kód a rendszer által meghatározott tulajdonságok olvasásához" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Kód a beépített tulajdonságok frissítéséhez" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Egyéni definiált tulajdonságok megtekintése és hozzáadása" %}}

Az egyéni tulajdonságok kezeléséhez a API rendelkezik[Munkafüzet::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) amely visszaadja a táblázat összes egyéni dokumentumtulajdonság-gyűjteményét. Először is, ha ezzel a módszerrel hozzáférnek az egyéni tulajdonságokhoz, a fejlesztők megfelelő módszereket használhatnak olyan tulajdonságok hozzáadására, mint az AddIDocumentProperty, AddLinkToContentProperty, és hasonlóképpen az UpdateLinkedPropertyValue, UpdateLinkedRange segítségével frissíthetik az egyéni dokumentumtulajdonság értékét, amely a tartalomra, illetve a hivatkozott tartományra hivatkozik. A fejlesztők a megfelelő módszert használhatják[egyéni dokumentumtulajdonságok gyűjteménye](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Kód az egyéni tulajdonságok megtekintéséhez" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Kód a metaadatok hozzáadásához az Excel-fájlban" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
