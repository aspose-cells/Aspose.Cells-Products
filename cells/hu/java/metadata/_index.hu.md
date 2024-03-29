---
title: via Java számú Excel-fájl metaadatainak kezelése
description: Tekintse meg, adja hozzá, szerkessze, távolítsa el vagy bontsa ki az Excel-fájlok metaadatait mindössze néhány sornyi Java kóddal
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A Microsoft<sup>&reg;</sup> Excel fájl metaadatainak kezelése via Java" h2="Egyéni és beépített Excel-fájltulajdonságok megtekintése, hozzáadása, frissítése, törlése vagy kibontása a kiszolgálóoldali Java API-k segítségével." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/hu/java/) támogatja a beépített (rendszer által meghatározott) tulajdonságok, például cím, szerző neve, dokumentumstatisztika stb., valamint egyedi (felhasználó által meghatározott) tulajdonságok kezelését név/érték pár formájában. Van[Munkafüzet osztály](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) a fájlok betöltéséhez, és[Munkalapgyűjtemény](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) feladatlapok gyűjtésével, valamint[Feladatlap osztály](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) egyetlen munkalap ábrázolására. A beépített és egyéni tulajdonságok eléréséhez a BuiltInDocumentProperties, a CustomDocumentProperties egyszerűvé teszi a metaadatkezelés folyamatát.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="A rendszer által meghatározott tulajdonságok kezelése" %}}

 A beépített ingatlanok kezelését a API biztosítja[BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) a programozók pedig könnyen hozzáférhetnek egy beépített tulajdonsághoz és frissíthetik annak értékét. Az alkalmazás követelményeitől függően a fejlesztők használhatják az indexet vagy a tulajdonság nevét a[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Kód a rendszer által meghatározott tulajdonságok kezeléséhez" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Egyéni definiált metaadatok hozzáadása és eltávolítása" %}}

Az egyéni tulajdonságok kezeléséhez a API rendelkezik[CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , és a fejlesztők egyszerűen hozzáférhetnek a meglévő ingatlanokhoz, valamint új tulajdonságokat adhatnak hozzá a használatával[módszer hozzáadása](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) nak,-nek[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) osztály hozzáadja a tulajdonságot, és visszaadja az új tulajdonság referenciáját an[Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) tárgy. A DocumentProperty osztály a dokumentumtulajdonság nevének, értékének és típusának lekérésére szolgál[DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) amely visszaadja az egyik[PropertyType](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) felsorolási értékek.
 
{{% blocks/products/pf/feature-page-code h3="Java Kód a metaadatok hozzáadásához az Excel-fájlban" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Kód az egyéni tulajdonság törléséhez az Excel-fájlban" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
