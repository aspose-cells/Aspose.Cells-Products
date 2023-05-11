---
title: Opmerkingen invoegen in Excel via .NET
description:  C# broncodes voor het invoegen van opmerkingen in Microsoft Excel-bestanden met behulp van .NET Library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-opmerkingen invoegen via .NET" h2="Maak Excel-documenten en voeg opmerkingen in met behulp van server-side API\'s in .NET-gebaseerde applicaties." >}}
{{% blocks/products/pf/feature-page-summary %}}

 U kunt opmerkingen aan cellen toevoegen. Als een cel een opmerking heeft, verschijnt er een indicator in de hoek van de cel. Opmerkingen verschijnen wanneer u uw cursor over een cel beweegt. Deze opmerkingen kunnen worden gebruikt voor discussie, speciale instructies of opmaak van documentinhoud.[.NET Excel-bibliotheek](/cells/nl/net/)ondersteunt het invoegen van opmerkingen in Excel-bestanden. Hiervoor biedt de API een[Opmerking](https://reference.aspose.com/cells/net/aspose.cells/comment) class for comments bouwsteen.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Opmerkingen in Excel-bestand invoegen" %}}

 Opmerkingen invoegen met Excel API is eenvoudig. Proces is, creëren[Werkmap klasse](https://reference.aspose.com/cells/net/aspose.cells/workbook) object en selecteer het eerste werkblad of het relevante blad door de index op te geven. Voeg de vereiste celgegevens in met behulp van[PutValue-methode](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Voeg commentaar toe aan het werkblad met behulp van[OpmerkingCollection](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 'S[Methode toevoegen](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Code om commentaar in te voegen in Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
