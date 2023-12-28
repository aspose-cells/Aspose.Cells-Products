---
title: Beheer Excel-bestandsmetagegevens via C++
description: Bekijk, voeg toe, bewerk, verwijder of extraheer metadata van Excel-bestanden met behulp van de bibliotheek C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Excel-documentmetagegevens via C++" h2="Aangepaste en ingebouwde Excel-documenteigenschappen bekijken, invoegen, bijwerken, verwijderen of extraheren binnen C++-applicaties." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metagegevens in Excel - Metagegevens van Excel-bestanden bekijken, invoegen en verwijderen.[C++ Excel-bibliotheek](/cells/nl/cpp/) facilitates is op een eenvoudige manier door het ondersteunen van de ingebouwde / door het systeem gedefinieerde eigenschappen zoals auteursnaam, titel, documentstatistieken enz. die soms nodig zijn om te controleren wanneer het laatste bestand wordt gewijzigd of opgeslagen, samen met aangepaste / door de gebruiker gedefinieerde eigenschappen in de vorm van naam/waarde-paren. Om het proces te automatiseren ondersteunt de bibliotheek het maken en onderhouden van grote Excel-bestanden met metagegevens.[Werkboek](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class Opent een werkmap op pad, op stream en op speciaal FileFormatType. Laad het bestand dus met de juiste methode voor verdere verwerking. Er zijn maar weinig van de onderstaande mogelijkheden en ontwikkelaars kunnen hun code eenvoudig verbeteren op basis van de toepassingsvereisten.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ingebouwde eigenschappen lezen en bijwerken" %}}

 Voor het automatiseren van de ingebouwde eigenschappen biedt API[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) methode die een DocumentProperties-verzameling retourneert die alle ingebouwde documenteigenschappen van het werkblad vertegenwoordigt. Nadat u toegang heeft gekregen tot alle ingebouwde eigenschappen, krijgt u toegang tot de relevante eigenschappen met behulp van de relevante methode zoals GetTitle(), GetSubject() enz. Om de eigenschappen bij te werken, biedt API methoden zoals SetTitle, SetSubject, SetAuthor, SetComments enz. Bekijk de[ingebouwde documenteigenschapsverzameling](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) voor de gewenste functie.

{{% blocks/products/pf/feature-page-code h3="C++ Code om door het systeem gedefinieerde eigenschappen te lezen" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Code om ingebouwde eigenschappen bij te werken" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Bekijk en voeg op maat gedefinieerde eigenschappen toe" %}}

Voor het verwerken van aangepaste eigenschappen biedt API[Werkmap::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) dat de volledige verzameling aangepaste documenteigenschappen van het werkblad retourneert. Door via deze methode toegang te krijgen tot de aangepaste eigenschappen, kunnen ontwikkelaars relevante methoden gebruiken om eigenschappen toe te voegen zoals AddIDocumentProperty, AddLinkToContentProperty en op dezelfde manier UpdateLinkedPropertyValue en UpdateLinkedRange gebruiken om de aangepaste documenteigenschapswaarde bij te werken die respectievelijk naar de inhoud en naar het gekoppelde bereik linkt. Ontwikkelaars kunnen de relevante methode gebruiken van[verzameling aangepaste documenteigenschappen](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Code om aangepaste eigenschappen te bekijken" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Code om metagegevens toe te voegen aan het Excel-bestand" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
