---
title: Metagegevens van Excel-bestanden beheren via Java
description: Metadata van Excel-bestanden bekijken, toevoegen, bewerken, verwijderen of extraheren met slechts enkele regels code Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Excel-bestand Metadata via Java" h2="Bekijk, voeg toe, update, verwijder of extraheer aangepaste en ingebouwde Excel-bestandseigenschappen met behulp van server-side Java API\'s." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/nl/java/) ondersteunt het beheer van ingebouwde (door het systeem gedefinieerde) eigenschappen zoals titel, auteursnaam, documentstatistieken enz., evenals aangepaste (door de gebruiker gedefinieerde) eigenschappen in de vorm van een naam/waarde-paar. Er bestaat[Werkmap klasse](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) om de bestanden te laden, en[WerkbladVerzameling](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection)houdt zich ook bezig met het verzamelen van werkbladen[Werkblad klasse](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) voor het weergeven van een enkel werkblad. Voor toegang tot ingebouwde en aangepaste eigenschappen maken BuiltInDocumentProperties, CustomDocumentProperties het proces eenvoudig voor metadatabeheer.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Door het systeem gedefinieerde eigenschappen beheren" %}}

 Voor het beheer van ingebouwde eigenschappen biedt API[BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) , en programmeurs hebben eenvoudig toegang tot een ingebouwde eigenschap en kunnen de waarde ervan bijwerken. Afhankelijk van de toepassingsvereisten kunnen ontwikkelaars de index- of eigenschapsnaam uit de[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Code om door het systeem gedefinieerde eigenschappen te beheren" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Op maat gedefinieerde metadata toevoegen en verwijderen" %}}

Voor het afhandelen van aangepaste eigenschappen biedt API[CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , en ontwikkelaars hebben eenvoudig toegang tot bestaande eigenschappen en kunnen nieuwe eigenschappen toevoegen met behulp van[methode toevoegen](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) van[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class voegt de eigenschap toe en retourneert een referentie voor de nieuwe eigenschap als een[Eigenschappen.DocumentEigenschap](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty)voorwerp. De klasse DocumentProperty wordt gebruikt om de naam, de waarde en het type van de documenteigenschap op te halen als[DocumentEigenschap.Naam](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentEigendom.Waarde](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) dat retourneert een van de[Eigendom type](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) opsomming waarden.
 
{{% blocks/products/pf/feature-page-code h3="Java Code om metagegevens toe te voegen aan Excel-bestand" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Code om aangepaste eigenschap in Excel-bestand te verwijderen" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
