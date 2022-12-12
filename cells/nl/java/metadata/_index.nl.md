---
title: Beheer Excel-bestandsmetagegevens via Java

description: Metadata van Excel-bestanden bekijken, toevoegen, bewerken, verwijderen of extraheren met slechts enkele regels Java-code
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Excel-bestandsmetagegevens via Java" h2="Bekijk, voeg toe, update, verwijder of extraheer aangepaste en ingebouwde Excel-bestandseigenschappen met server-side Java API\'s." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) ondersteunt het beheer van ingebouwde (door het systeem gedefinieerde) eigenschappen zoals titel, naam van de auteur, documentstatistieken enz. evenals aangepaste (door de gebruiker gedefinieerde) eigenschappen in de vorm van een naam/waarde-paar. Er is [Werkboek klasse](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) om de bestanden te laden, en [WerkbladCollectie](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) gaat over het verzamelen van werkbladen en ook over [Werkblad klas](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) voor het vertegenwoordigen van een enkel werkblad. Voor toegang tot ingebouwde en aangepaste eigenschappen maakt BuiltInDocumentProperties, CustomDocumentProperties het proces eenvoudig voor metagegevensbeheer. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Door het systeem gedefinieerde eigenschappen beheren" %}}

Voor het beheren van ingebouwde eigenschappen biedt API [Ingebouwde Documenteigenschappen](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties), en programmeurs kunnen gemakkelijk toegang krijgen tot een ingebouwde eigenschap en de waarde ervan bijwerken. Afhankelijk van de applicatievereiste kunnen ontwikkelaars de index- of eigenschapnaam uit de [DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Code om door het systeem gedefinieerde eigenschappen te beheren" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Aangepast gedefinieerde metagegevens toevoegen en verwijderen" %}}

Voor het afhandelen van aangepaste eigenschappen biedt API [CustomDocumentEigenschappen](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties), en ontwikkelaars kunnen eenvoudig toegang krijgen tot bestaande eigendommen en nieuwe eigenschappen toevoegen met behulp van [methode toevoegen](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) van [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class voegt de eigenschap toe en retourneert een referentie voor de nieuwe eigenschap als an [Eigenschappen.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) voorwerp. De klasse DocumentProperty wordt gebruikt om de naam, waarde en het type van de documenteigenschap op te halen als [DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) dat retourneert een van de [Eigendom type](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) opsomming waarden. 
 
{{% blocks/products/pf/feature-page-code h3="Java Code om metagegevens toe te voegen in Excel-bestand" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Code om aangepaste eigenschap in Excel-bestand te verwijderen" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
