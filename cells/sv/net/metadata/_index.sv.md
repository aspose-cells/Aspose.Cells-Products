---
title: Hantera Excel-filmetadata via .NET C#
url: /sv/net/metadata/
description: Visa, lägg till, redigera, ta bort eller extrahera Excel-filers metadata med bara några rader med C#-kod
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hantera Microsoft<sup>&reg;</sup> Excel-filmetadata via .NET" h2="Visa, lägg till, uppdatera, ta bort eller extrahera inbyggda och anpassade Excel-filegenskaper med hjälp av serversidans .NET API:er." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) stöder hantering av systemdefinierade (inbyggda) egenskaper såsom titel, författarens namn, dokumentstatistik etc samt användardefinierade (anpassade) egenskaper i form av namn-värdepar. Det finns [Arbetsbok klass](https://apireference.aspose.com/cells/net/aspose.cells/workbook) för att ladda filerna, och [Arbetsbladssamling](https://apireference.aspose.com/cells/net/aspose.cells/worksheetcollection) behandlar insamling av arbetsblad samt [Arbetsbladsklass](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) för att representera ett enda kalkylblad. Tillsammans med dessa klasser, BuiltInDocumentProperties, gör CustomDocumentProperties processen enkel för metadatahantering. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Hantera inbyggda egenskaper" %}}

För hantering av systemdefinierade egenskaper tillhandahåller API [BuiltInDocumentProperties](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties), och programmerare kan enkelt komma åt en inbyggd egenskap och uppdatera dess värde. Beroende på applikationskrav kan utvecklare använda index- eller egenskapsnamnet från [DocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Kod för att hantera inbyggda egenskaper" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Hantera anpassade definierade egenskaper" %}}

För hantering av användardefinierade egenskaper tillhandahåller API [CustomDocumentProperties](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties), och utvecklare kan enkelt komma åt redan tillagda egenskaper samt lägga till nya egenskaper. För att lägga till anpassade egenskaper, [Lägg till metod](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) av [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) klass lägger till egenskapen och returnerar en referens för den nya egenskapen som en [Properties.DocumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty) objekt. Klassen DocumentProperty används för att hämta namn, värde och typ av dokumentegenskapen som [DocumentProperty.Name](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) som returnerar en av [PropertyType](https://apireference.aspose.com/cells/net/aspose.cells.properties/propertytype) uppräkningsvärden. 
 
{{% blocks/products/pf/feature-page-code h3="C# Kod för att lägga till metadata i Excel-fil" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Kod för att ta bort anpassad egendom i Excel-fil" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
