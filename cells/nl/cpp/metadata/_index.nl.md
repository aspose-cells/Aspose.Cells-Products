---
title: Beheer metagegevens van Excel-bestanden via C++
description: Bekijk, voeg toe, bewerk, verwijder of extraheer de metadata van Excel-bestanden met behulp van de C++-bibliotheek
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Excel Document Metadata via C++" h2="Bekijk, voeg in, update, verwijder of extraheer aangepaste en ingebouwde Excel-documenteigenschappen binnen C++-applicaties." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadata in Excel - Metadata van Excel-bestanden bekijken, invoegen en verwijderen.[C++ Excel-bibliotheek](/cells/nl/cpp/) vergemakkelijkt op een gemakkelijke manier door de ingebouwde / door het systeem gedefinieerde eigenschappen zoals auteursnaam, titel, documentstatistieken enz. Soms nodig om te controleren wanneer het bestand voor het laatst is gewijzigd of opgeslagen, samen met aangepaste / door de gebruiker gedefinieerde eigenschappen in de vorm van naam/waarde-paren. Om het proces te automatiseren, ondersteunt de bibliotheek het maken en onderhouden van grote metadata-Excel-bestanden.[CreateIWorkbook-methode](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) van[Fabrieks klasse](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory)Open een werkmap op pad, op stream en op speciaal FileFormatType. Laad het bestand dus met de juiste methode voor verdere verwerking. Er zijn maar weinig van de onderstaande mogelijkheden en ontwikkelaars kunnen hun code eenvoudig verbeteren op basis van de toepassingsvereisten.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ingebouwde eigenschappen lezen en bijwerken" %}}

 Voor het automatiseren van de ingebouwde eigenschappen biedt API[GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) methode die een DocumentProperties-verzameling retourneert die alle ingebouwde documenteigenschappen van het werkblad vertegenwoordigt. Na toegang tot alle ingebouwde eigenschappen, opent u de relevante eigenschappen met behulp van de relevante methode zoals GetTitle(), GetSubject() etc. Om de eigenschappen bij te werken, biedt API methoden zoals SetTitle, SetSubject, SetAuthor, SetComments etc. Bekijk de[ingebouwde verzameling documenteigenschappen](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) voor de gewenste functie.

{{% blocks/products/pf/feature-page-code h3="C++ Code om door het systeem gedefinieerde eigenschappen te lezen" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Code om ingebouwde eigenschappen bij te werken" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Bekijk en voeg aangepaste gedefinieerde eigenschappen toe" %}}

Voor het afhandelen van aangepaste eigenschappen biedt API[IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) dat retourneert alle verzameling aangepaste documenteigenschappen van de spreadsheet. Door eerst toegang te krijgen tot de aangepaste eigenschappen via deze methode, kunnen ontwikkelaars relevante methoden gebruiken om eigenschappen toe te voegen zoals AddIDocumentProperty, AddLinkToContentProperty en op dezelfde manier UpdateLinkedPropertyValue, UpdateLinkedRange gebruiken om de aangepaste documenteigenschapswaarde bij te werken die respectievelijk naar inhoud en naar gekoppeld bereik linkt. Ontwikkelaars kunnen de relevante methode gebruiken van[verzameling aangepaste documenteigenschappen](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Code om aangepaste eigenschappen te bekijken" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Code om metagegevens toe te voegen aan Excel-bestand" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
