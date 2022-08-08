---
title: Infoga kommentarer i Excel via .NET
url: /sv/net/comment/
description: C# källkoder för att infoga kommentarer i Microsoft Excel-filer med hjälp av .NET bibliotek. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Infogning av Excel-kommentarer via .NET" h2="Skapa Excel-dokument och infoga kommentarer med hjälp av API:er på serversidan i .NET-baserade applikationer." >}}
{{% blocks/products/pf/feature-page-summary %}}

Du kan lägga till kommentarer till celler. När en cell har en kommentar visas en indikator i hörnet av cellen. Kommentarer visas när du håller muspekaren över en cell. Dessa kommentarer kan användas för diskussion, speciella instruktioner eller markering av dokumentinnehåll. [.NET Excel-bibliotek](/cells/net/) stöder att infoga kommentarer i Excel-filer. För detta tillhandahåller API en [Kommentar](https://reference.aspose.com/cells/net/aspose.cells/comment) klass för kommentarer byggsten.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Infoga kommentarer i Excel-fil" %}}

Det är enkelt att infoga kommentarer med Excel API. Processen är, Skapa [Arbetsbok klass](https://reference.aspose.com/cells/net/aspose.cells/workbook) objekt och välj det första kalkylbladet eller det relevanta bladet genom att tillhandahålla dess index. Infoga de nödvändiga celldata med hjälp av [PutValue-metoden](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Lägg till kommentar till kalkylbladet genom att använda [Kommentarsamling](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)s [Lägg till metod](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Kod för att infoga kommentar i Excel" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
