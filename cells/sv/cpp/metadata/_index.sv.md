---
title: Hantera Excel-filmetadata via C++
description: Visa, lägg till, redigera, ta bort eller extrahera Excel-filers metadata med hjälp av C++-biblioteket
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hantera Microsoft<sup>&reg;</sup> Excel-dokumentmetadata via C++" h2="Visa, infoga, uppdatera, ta bort eller extrahera anpassade och inbyggda Excel-dokumentegenskaper i C++-applikationer." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadata i Excel - Hur man visar, infogar och tar bort excelfilens metadata.[C++ Excel-bibliotek](/cells/sv/cpp/) faclitates är på ett enkelt sätt genom att stödja de inbyggda / systemdefinierade egenskaperna såsom författarens namn, titel, dokumentstatistik etc som behövs någon gång som att kontrollera när den sista filen ändras eller sparas tillsammans med anpassade / användardefinierade egenskaper i form av namn/värdepar. För att automatisera processen stöder biblioteket att skapa och underhålla stora Excel-filer med metadata.[Arbetsbok](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class Öppnar en arbetsbok efter sökväg, efter ström och efter speciell filformattyp. Så ladda filen med lämplig metod för vidare bearbetning. Få av de möjligheter som listas nedan och utvecklare kan enkelt förbättra sin kod enligt applikationskrav.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Läs och uppdatera inbyggda egenskaper" %}}

 För automatisering av de inbyggda egenskaperna tillhandahåller API[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) metod som returnerar en DocumentProperties-samling som representerar alla inbyggda dokumentegenskaper i kalkylarket. Efter att ha kommit åt alla inbyggda egenskaper, få åtkomst till de relevanta egenskaperna med relevant metod som GetTitle(), GetSubject() etc. För att uppdatera egenskaperna tillhandahåller API metoder som SetTitle, SetSubject, SetAuthor, SetComments etc. Visa[inbyggd dokumentegendomssamling](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) för önskad funktion.

{{% blocks/products/pf/feature-page-code h3="C++ Kod för att läsa systemdefinierade egenskaper" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Kod för att uppdatera inbyggda egenskaper" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Visa och lägg till anpassade definierade egenskaper" %}}

För hantering av anpassade egenskaper tillhandahåller API[Arbetsbok::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) som returnerar alla anpassade dokumentegenskaper i kalkylarket. För det första, genom att komma åt de anpassade egenskaperna via den här metoden, kan utvecklare använda relevanta metoder för att lägga till egenskaper som AddIDocumentProperty, AddLinkToContentProperty och på liknande sätt använda UpdateLinkedPropertyValue, UpdateLinkedRange för att uppdatera anpassat dokumentegenskapsvärde som länkar till innehåll respektive till länkat intervall. Utvecklare kan använda relevant metod från[samling av anpassade dokumentegenskaper](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Kod för att visa anpassade egenskaper" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Kod för att lägga till metadata i Excel-fil" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
