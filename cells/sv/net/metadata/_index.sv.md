---
title: Hantera Excel-filmetadata via .NET C#
description: Visa, lägg till, redigera, ta bort eller extrahera Excel-filers metadata med bara några rader C#-kod
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hantera Microsoft<sup>&reg;</sup> Metadata för Excel-fil via .NET" h2="Visa, lägg till, uppdatera, ta bort eller extrahera inbyggda och anpassade Excel-filegenskaper med hjälp av API:er på serversidan .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/sv/net/) stöder hantering av systemdefinierade (inbyggda) egenskaper såsom titel, författarens namn, dokumentstatistik etc samt användardefinierade (anpassade) egenskaper i form av namn-värdepar. Det finns[Arbetsbok klass](https://reference.aspose.com/cells/net/aspose.cells/workbook) för att ladda filerna och[Arbetsbladssamling](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) behandlar insamling av arbetsblad samt[Arbetsbladsklass](https://reference.aspose.com/cells/net/aspose.cells/worksheet) för att representera ett enda kalkylblad. Tillsammans med dessa klasser, BuiltInDocumentProperties, gör CustomDocumentProperties processen enkel för metadatahantering.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Hantera inbyggda egenskaper" %}}

 För hantering av systemdefinierade egenskaper tillhandahåller API[BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) , och programmerare kan enkelt komma åt en inbyggd egenskap och uppdatera dess värde. Beroende på applikationskrav kan utvecklare använda indexet eller egenskapsnamnet från[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Kod för att hantera inbyggda egenskaper" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Hantera anpassade definierade egenskaper" %}}

 För hantering av användardefinierade egenskaper tillhandahåller API[CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , och utvecklare kan enkelt komma åt redan tillagda egenskaper samt lägga till nya egenskaper. För att lägga till anpassade egenskaper,[Lägg till metod](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) av[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class lägger till egenskapen och returnerar en referens för den nya egenskapen som en[Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) objekt. DocumentProperty-klassen används för att hämta namn, värde och typ av dokumentegenskapen som[DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) som returnerar en av[PropertyType](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) uppräkningsvärden.
 
{{% blocks/products/pf/feature-page-code h3="C# Kod för att lägga till metadata i Excel-fil" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Kod för att ta bort anpassad egendom i Excel-fil" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
