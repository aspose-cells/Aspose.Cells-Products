---
title: Excel-filanteckningar NET C#
description: Lägg till eller ta bort datakommentarer för Excel- och OpenOffice-kalkylblad med bara några rader med C#-kod.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ta bort Microsoft<sup>&reg;</sup> Excel-filanteckningar via .NET" h2="Lägg till eller ta bort anteckningar för Excel-filer med C#-koden i .NET-baserade applikationer." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel-bibliotek](/cells/sv/net/) ger stöd för att hantera anteckningar på cellnivå genom att lägga till, komma åt och ta bort kommentarer. Med hjälp av kommentarer på cellnivå kan relevant information lagras för slutanvändare. Filformat som stöds inkluderar ODS, XLS, XLSX, XLSB och XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel-filer Dataanteckningar" %}}
 Hantera kommentarer i arbetsblad - Det finns ingen gräns för hur många kommentarer ett ark har i MS Excel. Man kan lägga till så mycket som av ansökan krav. Vi kommer att använda[Kommentar Klass](https://reference.aspose.com/cells/net/aspose.cells/comment)för all denna funktionalitet.

+ Ladda Excel-fil med Workbook-klassobjekt
+ Gå till det relevanta arbetsbladet och dess relevanta index Cell
+ Ring RemoveAt med Cell ID för att ta bort det
 + Använd[Notera egendom](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) för att lägga till kommentarer innehåll
+ Spara arbetsboken före och efter anropet RemoveAt-metoden för att jämföra

{{% blocks/products/pf/feature-page-code h3="C# Kod för att komma åt, infoga och ta bort Excel-filer Cell Kommentarer" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
