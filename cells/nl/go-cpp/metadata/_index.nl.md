---
title: Beheer Excel-bestandmetadata met Go via C++
description: Metagegevens van Excel-bestanden bekijken, toevoegen, bewerken, verwijderen of extraheren met Go via de bibliotheek C++
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer de metagegevens van het Excel-document Microsoft via Go via C++" h2="Bekijk, voeg in, werk bij, verwijder of extraheer aangepaste en ingebouwde Excel-documenteigenschappen binnen toepassingen met code C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metagegevens in Excel - Zo kunt u metagegevens in een Excel-bestand bekijken, invoegen en verwijderen.[Ga via C++ Excel-bibliotheek](/cells/nl/go-cpp/)Het vereenvoudigt het proces door ingebouwde/systeemgedefinieerde eigenschappen te ondersteunen, zoals auteursnaam, titel, documentstatistieken, enz., die soms nodig zijn om bijvoorbeeld te controleren wanneer een bestand voor het laatst is gewijzigd of opgeslagen. Daarnaast kunnen ook aangepaste/gebruikersgedefinieerde eigenschappen in de vorm van naam/waarde-paren worden gebruikt. Om dit proces te automatiseren, ondersteunt de bibliotheek het aanmaken en beheren van grote Excel-bestanden met metadata.[Werkboek](https://reference.aspose.com/cells/go-cpp/workbook/) Deze klasse opent een werkmap op basis van een pad, een stream of een specifiek bestandstype. Het bestand wordt dus geladen met de juiste methode voor verdere verwerking. Enkele van de mogelijkheden worden hieronder opgesomd en ontwikkelaars kunnen hun code eenvoudig aanpassen aan de behoeften van de applicatie.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ingebouwde eigenschappen lezen en bijwerken" %}}

 Voor het automatiseren van de ingebouwde eigenschappen biedt API de volgende mogelijkheden.[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Deze methode retourneert een DocumentProperties-verzameling die alle ingebouwde documenteigenschappen van het spreadsheet vertegenwoordigt. Nadat alle ingebouwde eigenschappen zijn opgevraagd, kunt u de relevante eigenschappen benaderen met behulp van de bijbehorende methoden, zoals GetTitle(), GetSubject(), enz. Om de eigenschappen bij te werken, biedt API methoden zoals SetTitle, SetSubject, SetAuthor, SetComments, enz. Bekijk de[ingebouwde documenteigenschappenverzameling](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) voor de vereiste functie.

{{% blocks/products/pf/feature-page-code h3="Gebruik code C++ om systeemgedefinieerde eigenschappen te lezen." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Gebruik code C++ om de ingebouwde eigenschappen bij te werken." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Aangepaste eigenschappen bekijken en toevoegen" %}}

 Voor het beheren van aangepaste eigenschappen biedt API de mogelijkheid.[Werkmap::AangepasteDocumentEigenschappenOphalen](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)Deze methode retourneert de volledige verzameling aangepaste documenteigenschappen van het spreadsheet. Ontwikkelaars kunnen via deze methode eerst toegang krijgen tot de aangepaste eigenschappen en vervolgens relevante methoden gebruiken om eigenschappen toe te voegen, zoals AddIDocumentProperty en AddLinkToContentProperty. Op dezelfde manier kunnen ze UpdateLinkedPropertyValue en UpdateLinkedRange gebruiken om de waarde van een aangepaste documenteigenschap bij te werken die respectievelijk naar inhoud en naar een gekoppeld bereik verwijst.[verzameling aangepaste documenteigenschappen](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Ga via code C++ naar de aangepaste eigenschappen." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Gebruik code C++ om metadata toe te voegen aan een Excel-bestand." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}