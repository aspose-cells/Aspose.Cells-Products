---
title: Beheer Excel-bestandsmetagegevens via .NET C#

description: Metadata van Excel-bestanden bekijken, toevoegen, bewerken, verwijderen of extraheren met slechts enkele regels C#-code
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Excel-bestandsmetagegevens via .NET" h2="Bekijk, voeg toe, update, verwijder of extraheer ingebouwde en aangepaste Excel-bestandseigenschappen met server-side .NET API\'s." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) ondersteunt het beheer van door het systeem gedefinieerde (ingebouwde) eigenschappen zoals titel, naam van de auteur, documentstatistieken enz. evenals door de gebruiker gedefinieerde (aangepaste) eigenschappen in de vorm van een naam-waardepaar. Er is [Werkboek klasse](https://reference.aspose.com/cells/net/aspose.cells/workbook) om de bestanden te laden, en [WerkbladCollectie](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) gaat over het verzamelen van werkbladen en ook over [Werkblad klas](https://reference.aspose.com/cells/net/aspose.cells/worksheet) voor het vertegenwoordigen van een enkel werkblad. Samen met deze klassen, BuiltInDocumentProperties, maakt CustomDocumentProperties het proces eenvoudig voor het beheer van metagegevens. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ingebouwde eigenschappen beheren" %}}

Voor het beheren van door het systeem gedefinieerde eigenschappen biedt API [Ingebouwde Documenteigenschappen](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties), en programmeurs kunnen gemakkelijk toegang krijgen tot een ingebouwde eigenschap en de waarde ervan bijwerken. Afhankelijk van de applicatievereiste kunnen ontwikkelaars de index- of eigenschapnaam uit de [DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Code om ingebouwde eigenschappen te beheren" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Aangepast gedefinieerde eigenschappen beheren" %}}

Voor het beheren van door de gebruiker gedefinieerde eigenschappen biedt API [CustomDocumentEigenschappen](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties), en ontwikkelaars kunnen gemakkelijk toegang krijgen tot reeds toegevoegde eigenschappen en nieuwe eigenschappen toevoegen. Om aangepaste eigenschappen toe te voegen, [Methode toevoegen](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) van [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class voegt de eigenschap toe en retourneert een referentie voor de nieuwe eigenschap als an [Eigenschappen.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) voorwerp. De klasse DocumentProperty wordt gebruikt om de naam, waarde en het type van de documenteigenschap op te halen als [DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) dat retourneert een van de [Eigendom type](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) opsomming waarden. 
 
{{% blocks/products/pf/feature-page-code h3="C# Code om metagegevens toe te voegen in Excel-bestand" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Code om aangepaste eigenschap in Excel-bestand te verwijderen" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
