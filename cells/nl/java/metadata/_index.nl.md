---
title: Beheer Excel-bestandsmetagegevens via Java
description: Metagegevens van Excel-bestanden bekijken, toevoegen, bewerken, verwijderen of extraheren met slechts enkele regels Java-code
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Metagegevens van Excel-bestand via Java" h2="Bekijk, voeg toe, update, verwijder of extraheer aangepaste en ingebouwde Excel-bestandseigenschappen met behulp van server-side Java API\'s." >}}
{{% blocks/products/pf/feature-page-summary %}}
[JavaExcel API](/cells/nl/java/) ondersteunt het beheer van ingebouwde (door het systeem gedefinieerde) eigenschappen zoals titel, auteursnaam, documentstatistieken enz., evenals aangepaste (door de gebruiker gedefinieerde) eigenschappen in de vorm van een naam/waarde-paar. Er bestaat[Werkmap klasse](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) om de bestanden te laden, en[WerkbladVerzameling](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) behandelt ook het verzamelen van werkbladen[Werkblad klasse](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) voor het weergeven van één werkblad. Voor toegang tot ingebouwde en aangepaste eigenschappen maakt BuiltInDocumentProperties, CustomDocumentProperties het proces voor metagegevensbeheer eenvoudig.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Door het systeem gedefinieerde eigenschappen beheren" %}}

 Voor het beheren van ingebouwde eigenschappen biedt API[BuiltInDocumentEigenschappen](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) en programmeurs hebben eenvoudig toegang tot een ingebouwde eigenschap en kunnen de waarde ervan bijwerken. Afhankelijk van de toepassingsvereisten kunnen ontwikkelaars de index- of eigenschapsnaam uit de[DocumentEigenschapCollectie](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Code om door het systeem gedefinieerde eigenschappen te beheren" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Op maat gedefinieerde metadata toevoegen en verwijderen" %}}

Voor het verwerken van aangepaste eigenschappen biedt API[Aangepaste documenteigenschappen](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , en ontwikkelaars hebben eenvoudig toegang tot bestaande eigenschappen en kunnen nieuwe eigenschappen toevoegen met behulp van[methode toevoegen](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) van[AangepasteDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class voegt de eigenschap toe en retourneert een referentie voor de nieuwe eigenschap als een[Eigenschappen.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) voorwerp. De klasse DocumentProperty wordt gebruikt om de naam, waarde en het type van de documenteigenschap op te halen[DocumentEigenschap.Naam](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) dat retourneert een van de[Eigendom type](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) opsommingswaarden.
 
{{% blocks/products/pf/feature-page-code h3="Java Code om metagegevens toe te voegen aan het Excel-bestand" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Code om aangepaste eigenschap in Excel-bestand te verwijderen" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
