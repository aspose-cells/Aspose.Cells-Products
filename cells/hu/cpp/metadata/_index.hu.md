---
title: "Az Excel fájl metaadatainak kezelése a következőn keresztül: C++"
url: /hu/cpp/metadata/
description: Az Excel-fájlok metaadatainak megtekintése, hozzáadása, szerkesztése, eltávolítása vagy kibontása a C++ könyvtár használatával
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A Microsoft<sup>&reg;</sup> Excel dokumentum metaadatainak kezelése a következőn keresztül: C++" h2="Egyéni és beépített Excel-dokumentumtulajdonságok megtekintése, beszúrása, frissítése, eltávolítása vagy kibontása a(z) C++ alkalmazásokban." >}}
{{% blocks/products/pf/feature-page-summary %}}
Metaadatok az Excelben – Az Excel fájl metaadatainak megtekintése, beillesztése és eltávolítása. [C++ Excel-könyvtár](/cells/cpp/) A faclitates könnyen elérhető azáltal, hogy támogatja a beépített / rendszer által definiált tulajdonságokat, mint például a szerző neve, címe, dokumentumstatisztikái stb., amelyek időnként szükségesek, mint például annak ellenőrzése, hogy mikor módosult vagy mentett utoljára fájl, valamint egyéni / felhasználó által meghatározott tulajdonságok formájában név/érték párok. A folyamat automatizálása érdekében a könyvtár támogatja a nagy metaadat-fájlok létrehozását és karbantartását. [CreateIWorkbook metódus](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) nak,-nek [Gyári osztály](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory) Nyisson meg egy munkafüzetet elérési út, adatfolyam és speciális FileFormatType szerint. Tehát töltse be a fájlt a megfelelő módszerrel a további feldolgozáshoz. Az alább felsorolt lehetőségek közül néhány, és a fejlesztők könnyedén javíthatják kódjukat az alkalmazás követelményei szerint. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Olvassa el és frissítse a beépített tulajdonságokat" %}}

A beépített tulajdonságok automatizálásához a API biztosítja [GetIBuiltInDocumentProperties()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) metódus, amely egy DocumentProperties gyűjteményt ad vissza, amely a táblázat összes beépített dokumentumtulajdonságát reprezentálja. Az összes beépített tulajdonság elérése után érje el a megfelelő tulajdonságokat a megfelelő metódusokkal, például GetTitle(), GetSubject() stb. A tulajdonságok frissítéséhez a API olyan metódust biztosít, mint a SetTitle, SetSubject, SetAuthor, SetComments stb. [beépített dokumentumtulajdon-gyűjtemény](https://apireference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) a szükséges funkcióhoz.

{{% blocks/products/pf/feature-page-code h3="C++ Kód a rendszer által meghatározott tulajdonságok olvasásához" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Kód a beépített tulajdonságok frissítéséhez" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Egyéni definiált tulajdonságok megtekintése és hozzáadása" %}}

Az egyéni tulajdonságok kezeléséhez a API rendelkezik [IWorkbookMetadata::GetICustomDocumentProperties](https://apireference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) amely visszaadja a táblázat összes egyéni dokumentumtulajdonság-gyűjteményét. Először is, ha ezzel a módszerrel hozzáférnek az egyéni tulajdonságokhoz, a fejlesztők megfelelő módszereket használhatnak olyan tulajdonságok hozzáadására, mint az AddIDocumentProperty, AddLinkToContentProperty, és hasonlóképpen az UpdateLinkedPropertyValue, UpdateLinkedRange segítségével frissíthetik az egyéni dokumentumtulajdonság értékét, amely a tartalomra, illetve a hivatkozott tartományra hivatkozik. A fejlesztők a megfelelő módszert használhatják [egyéni dokumentumtulajdonságok gyűjteménye](https://apireference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Kód az egyéni tulajdonságok megtekintéséhez" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Kód metaadatok hozzáadásához az Excel-fájlban" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}