---
title: Hantera Excel-filmetadata via Java
description: Visa, lägg till, redigera, ta bort eller extrahera Excel-filers metadata med bara några rader Java-kod
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hantera Microsoft<sup>&reg;</sup> Metadata för Excel-fil via Java" h2="Visa, lägg till, uppdatera, ta bort eller extrahera anpassade och inbyggda Excel-filegenskaper med hjälp av API:er på serversidan Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/sv/java/) stöder hantering av inbyggda (systemdefinierade) egenskaper såsom titel, författarens namn, dokumentstatistik etc samt anpassade (användardefinierade) egenskaper i form av namn/värdepar. Det finns[Arbetsbok klass](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) för att ladda filerna och[Arbetsbladssamling](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) behandlar insamling av arbetsblad samt[Arbetsbladsklass](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) för att representera ett enda kalkylblad. För att komma åt inbyggda och anpassade egenskaper gör BuiltInDocumentProperties, CustomDocumentProperties processen enkel för metadatahantering.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Hantera systemdefinierade egenskaper" %}}

 För skötsel av inbyggda fastigheter tillhandahåller API[BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) och programmerare kan enkelt komma åt en inbyggd egenskap och uppdatera dess värde. Beroende på applikationskrav kan utvecklare använda indexet eller egenskapsnamnet från[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Kod för att hantera systemdefinierade egenskaper" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Lägg till och ta bort anpassade metadata" %}}

För hantering av anpassade egenskaper tillhandahåller API[CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , och utvecklare kan enkelt komma åt befintliga egenskaper samt lägga till nya egenskaper med hjälp av[lägga till metod](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) av[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class lägger till egenskapen och returnerar en referens för den nya egenskapen som en[Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) objekt. DocumentProperty-klassen används för att hämta namn, värde och typ av dokumentegenskapen som[DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) som returnerar en av[PropertyType](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) uppräkningsvärden.
 
{{% blocks/products/pf/feature-page-code h3="Java Kod för att lägga till metadata i Excel-fil" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Kod för att ta bort anpassad egendom i Excel-fil" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
