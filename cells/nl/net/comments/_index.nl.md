---
title: Opmerkingen invoegen in Excel via .NET

description: C# broncodes voor het invoegen van opmerkingen in Microsoft Excel-bestanden met behulp van .NET Bibliotheek. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-opmerkingen invoegen via .NET" h2="Maak Excel-documenten en voeg opmerkingen in met server-side API\'s in .NET-gebaseerde applicaties." >}}
{{% blocks/products/pf/feature-page-summary %}}

U kunt opmerkingen aan cellen toevoegen. Wanneer een cel een opmerking heeft, verschijnt er een indicator in de hoek van de cel. Opmerkingen verschijnen wanneer u uw cursor over een cel beweegt. Deze opmerkingen kunnen worden gebruikt voor discussie, speciale instructies of markeringen van documentinhoud. [.NET Excel-bibliotheek](/cells/net/) ondersteunt het invoegen van opmerkingen in Excel-bestanden. Hiervoor biedt de API een [Commentaar](https://reference.aspose.com/cells/net/aspose.cells/comment) class voor opmerkingen bouwsteen.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Opmerkingen invoegen in Excel-bestand" %}}

Opmerkingen invoegen met Excel API is eenvoudig. Proces is, Creëren [Werkboek klasse](https://reference.aspose.com/cells/net/aspose.cells/workbook) object en selecteer het eerste werkblad of het relevante werkblad door de index op te geven. Voeg de vereiste celgegevens in met [PutValue-methode](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Voeg commentaar toe aan het werkblad met [OpmerkingCollectie](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)'s [Methode toevoegen](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Code om commentaar in Excel in te voegen" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
