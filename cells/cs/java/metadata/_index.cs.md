---
title: Spravujte metadata souboru Excel prostřednictvím Java
url: /cs/java/metadata/
description: Zobrazujte, přidávejte, upravujte, odebírejte nebo extrahujte metadata souborů Excel pomocí několika řádků kódu Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Spravujte metadata souboru Microsoft<sup>&reg;</sup> Excel prostřednictvím Java" h2="Zobrazte, přidejte, aktualizujte, odstraňte nebo extrahujte vlastní a vestavěné vlastnosti souborů aplikace Excel pomocí rozhraní API Java na straně serveru." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) podporuje správu vestavěných (systémem definovaných) vlastností, jako je název, jméno autora, statistiky dokumentu atd., stejně jako vlastní (uživatelem definované) vlastnosti ve formě páru název/hodnota. Tady je [Třída sešitu](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) k načtení souborů a [Kolekce pracovních listů](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) zabývá se také sběrem pracovních listů [Třída pracovních listů](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) pro reprezentaci jednoho listu. Pro přístup k vestavěným a uživatelským vlastnostem BuiltInDocumentProperties, CustomDocumentProperties zjednodušují proces správy metadat. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Správa vlastností definovaných systémem" %}}

Pro správu vestavěných vlastností poskytuje API [BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties)a programátoři mohou snadno přistupovat k vestavěné vlastnosti a aktualizovat její hodnotu. V závislosti na požadavcích aplikace mohou vývojáři použít index nebo název vlastnosti z [DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Kód pro správu vlastností definovaných systémem" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Přidat a odebrat vlastní definovaná metadata" %}}

Pro zpracování vlastních vlastností poskytuje API [CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties)a vývojáři mohou snadno přistupovat ke stávajícím vlastnostem a také přidávat nové vlastnosti pomocí [přidat metodu](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) z [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) třída přidá vlastnost a vrátí odkaz na novou vlastnost jako an [Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) objekt. Třída DocumentProperty se používá k načtení názvu, hodnoty a typu vlastnosti dokumentu jako [DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) který vrací jeden z [Typ majetku](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) výčtové hodnoty. 
 
{{% blocks/products/pf/feature-page-code h3="Java Kód pro přidání metadat do souboru Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Kód pro odstranění uživatelské vlastnosti v souboru Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
