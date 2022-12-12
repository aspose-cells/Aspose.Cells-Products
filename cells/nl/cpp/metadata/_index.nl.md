---
title: Beheer Excel-bestandsmetagegevens via C++

description: Metadata van Excel-bestanden bekijken, toevoegen, bewerken, verwijderen of extraheren met behulp van C++ bibliotheek
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Excel-documentmetagegevens via C++" h2="Aangepaste en ingebouwde Excel-documenteigenschappen in C++-toepassingen bekijken, invoegen, bijwerken, verwijderen of extraheren." >}}
{{% blocks/products/pf/feature-page-summary %}}
Metadata in Excel - Metadata van Excel-bestanden bekijken, invoegen en verwijderen. [C++ Excel-bibliotheek](/cells/cpp/) faclitates is op een gemakkelijke manier door de ingebouwde / door het systeem gedefinieerde eigenschappen te ondersteunen, zoals de naam van de auteur, titel, documentstatistieken enz. die soms nodig zijn om te controleren wanneer het bestand voor het laatst is gewijzigd of opgeslagen, samen met aangepaste / door de gebruiker gedefinieerde eigenschappen in de vorm van naam/waarde-paren. Om het proces te automatiseren, ondersteunt de bibliotheek het maken en onderhouden van grote metadata Excel-bestanden. [CreateIWorkbook-methode](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) van [Fabrieksklasse](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Open een werkmap op pad, op stream en op speciaal FileFormatType. Dus laad het bestand met de juiste methode voor verdere verwerking. Er zijn maar weinig van de onderstaande mogelijkheden en ontwikkelaars kunnen hun code eenvoudig verbeteren op basis van de toepassingsvereisten. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ingebouwde eigenschappen lezen en bijwerken" %}}

Voor het automatiseren van de ingebouwde eigenschappen biedt API [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) methode die een DocumentProperties-verzameling retourneert die alle ingebouwde documenteigenschappen van het werkblad vertegenwoordigt. Nadat u alle ingebouwde eigenschappen hebt geopend, opent u de relevante eigenschappen met behulp van relevante methoden zoals GetTitle(), GetSubject() enz. Om de eigenschappen bij te werken, biedt API methoden zoals SetTitle, SetSubject, SetAuthor, SetComments enz. Bekijk de [ingebouwde verzameling documenteigenschappen](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) voor de gewenste functie.

{{% blocks/products/pf/feature-page-code h3="C++ Code om door het systeem gedefinieerde eigenschappen te lezen" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Code om ingebouwde eigenschappen bij te werken" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Aangepast gedefinieerde eigenschappen bekijken en toevoegen" %}}

Voor het afhandelen van aangepaste eigenschappen biedt API [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) die alle aangepaste documenteigenschappen van de spreadsheet retourneert. Door eerst toegang te krijgen tot de aangepaste eigenschappen via deze methode, kunnen ontwikkelaars relevante methoden gebruiken om eigenschappen zoals AddIDocumentProperty, AddLinkToContentProperty toe te voegen en op dezelfde manier UpdateLinkedPropertyValue, UpdateLinkedRange gebruiken om de aangepaste documenteigenschapswaarde bij te werken die respectievelijk naar inhoud en naar gekoppeld bereik verwijst. Ontwikkelaars kunnen de relevante methode gebruiken van [verzameling van aangepaste documenteigenschappen](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Code om aangepaste eigenschappen te bekijken" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Code om metagegevens toe te voegen in Excel-bestand" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
