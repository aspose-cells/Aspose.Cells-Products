---
title: Metadata van Excel-bestanden beheren via .NET C#
description: Metadata van Excel-bestanden bekijken, toevoegen, bewerken, verwijderen of extraheren met slechts enkele regels code C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Excel-bestand Metadata via .NET" h2="Bekijk, voeg toe, update, verwijder of extraheer ingebouwde en aangepaste Excel-bestandseigenschappen met behulp van server-side .NET API\'s." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/nl/net/) ondersteunt het beheer van door het systeem gedefinieerde (ingebouwde) eigenschappen zoals titel, auteursnaam, documentstatistieken enz., evenals door de gebruiker gedefinieerde (aangepaste) eigenschappen in de vorm van een naam-waardepaar. Er bestaat[Werkmap klasse](https://reference.aspose.com/cells/net/aspose.cells/workbook) om de bestanden te laden, en[WerkbladVerzameling](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection)houdt zich ook bezig met het verzamelen van werkbladen[Werkblad klasse](https://reference.aspose.com/cells/net/aspose.cells/worksheet) voor het weergeven van een enkel werkblad. Samen met deze klassen maken BuiltInDocumentProperties, CustomDocumentProperties het proces eenvoudig voor metadatabeheer.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ingebouwde eigenschappen beheren" %}}

 Voor het beheer van door het systeem gedefinieerde eigenschappen biedt API[BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) , en programmeurs hebben eenvoudig toegang tot een ingebouwde eigenschap en kunnen de waarde ervan bijwerken. Afhankelijk van de toepassingsvereisten kunnen ontwikkelaars de index- of eigenschapsnaam uit de[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Code om ingebouwde eigenschappen te beheren" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Beheer van op maat gedefinieerde eigenschappen" %}}

 Voor het beheer van door de gebruiker gedefinieerde eigenschappen biedt API[CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , en ontwikkelaars hebben eenvoudig toegang tot reeds toegevoegde eigenschappen en kunnen ook nieuwe eigenschappen toevoegen. Om aangepaste eigenschappen toe te voegen,[Methode toevoegen](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) van[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class voegt de eigenschap toe en retourneert een referentie voor de nieuwe eigenschap als een[Eigenschappen.DocumentEigenschap](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty)voorwerp. De klasse DocumentProperty wordt gebruikt om de naam, de waarde en het type van de documenteigenschap op te halen als[DocumentEigenschap.Naam](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentEigendom.Waarde](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) dat retourneert een van de[Eigendom type](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) opsomming waarden.
 
{{% blocks/products/pf/feature-page-code h3="C# Code om metagegevens toe te voegen aan Excel-bestand" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Code om aangepaste eigenschap in Excel-bestand te verwijderen" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
