---
title: Hantera Excel-filmetadata via C++

description: Visa, lägg till, redigera, ta bort eller extrahera Excel-filers metadata med hjälp av C++-biblioteket
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hantera Microsoft<sup>&reg;</sup> Excel-dokumentmetadata via C++" h2="Visa, infoga, uppdatera, ta bort eller extrahera anpassade och inbyggda Excel-dokumentegenskaper i C++ applikationer." >}}
{{% blocks/products/pf/feature-page-summary %}}
Metadata i Excel - Hur man visar, infogar och tar bort excelfilens metadata. [C++ Excel-bibliotek](/cells/cpp/) faclitates är på ett enkelt sätt genom att stödja de inbyggda / systemdefinierade egenskaperna såsom författarens namn, titel, dokumentstatistik etc som behövs någon gång som att kontrollera när den sista filen ändras eller sparas tillsammans med anpassade / användardefinierade egenskaper i form av namn/värdepar. För att automatisera processen stöder biblioteket att skapa och underhålla stora Excel-filer med metadata. [CreateIWorkbook-metoden](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) av [Fabriksklass](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Öppna en arbetsbok efter sökväg, efter ström och med speciell filformattyp. Så ladda filen med lämplig metod för vidare bearbetning. Få av de möjligheter som anges nedan och utvecklare kan enkelt förbättra sin kod enligt applikationskrav. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Läs och uppdatera inbyggda egenskaper" %}}

För att automatisera de inbyggda egenskaperna tillhandahåller API [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) metod som returnerar en DocumentProperties-samling som representerar alla inbyggda dokumentegenskaper i kalkylarket. Efter att ha kommit åt alla inbyggda egenskaper, få åtkomst till de relevanta egenskaperna med relevant metod som GetTitle(), GetSubject() etc. För att uppdatera egenskaperna tillhandahåller API metoder som SetTitle, SetSubject, SetAuthor, SetComments etc. Visa [inbyggd dokumentegendomssamling](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) för önskad funktion.

{{% blocks/products/pf/feature-page-code h3="C++ Kod för att läsa systemdefinierade egenskaper" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Kod för att uppdatera inbyggda egenskaper" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Visa och lägg till anpassade definierade egenskaper" %}}

För hantering av anpassade egenskaper tillhandahåller API [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) som returnerar alla anpassade dokumentegenskaper i kalkylarket. För det första, genom att komma åt de anpassade egenskaperna via den här metoden, kan utvecklare använda relevanta metoder för att lägga till egenskaper som AddIDocumentProperty, AddLinkToContentProperty och på liknande sätt använda UpdateLinkedPropertyValue, UpdateLinkedRange för att uppdatera värde för anpassade dokumentegenskaper som länkar till innehåll respektive till länkat intervall. Utvecklare kan använda relevant metod från [samling av anpassade dokumentegenskaper](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Kod för att visa anpassade egenskaper" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Kod för att lägga till metadata i Excel-fil" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
