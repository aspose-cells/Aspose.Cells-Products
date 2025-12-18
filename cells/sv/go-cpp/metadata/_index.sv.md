---
title: Hantera Excel-filmetadata med Go via C++
description: Visa, lägg till, redigera, ta bort eller extrahera metadata för Excel-filer med hjälp av Go via C++-biblioteket
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hantera Microsoft<sup>&reg;</sup> Excel-dokumentmetadata via Go via C++" h2="Visa, infoga, uppdatera, ta bort eller extrahera anpassade och inbyggda Excel-dokumentegenskaper i C++-applikationer." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadata i Excel - Hur man visar, infogar och tar bort metadata i Excel-filer.[Gå via C++ Excel-bibliotek](/cells/sv/go-cpp/)Faclitates underlättas på ett enkelt sätt genom att stödja inbyggda/systemdefinierade egenskaper som författarnamn, titel, dokumentstatistik etc. som ibland behövs för att kontrollera när en fil senast ändras eller sparas, tillsammans med anpassade/användardefinierade egenskaper i form av namn/värde-par. För att automatisera processen stöder biblioteket skapande och underhåll av stora metadatafiler i Excel.[Arbetsbok](https://reference.aspose.com/cells/go-cpp/workbook/) Klass Öppnar en arbetsbok via sökväg, ström och speciell FileFormatType. Ladda filen med lämplig metod för vidare bearbetning. Några av möjligheterna nedan visar hur utvecklare enkelt kan förbättra sin kod enligt applikationens krav.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Läs och uppdatera inbyggda egenskaper" %}}

 För att automatisera de inbyggda egenskaperna tillhandahåller API[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)metod som returnerar en DocumentProperties-samling som representerar alla inbyggda dokumentegenskaper i kalkylarket. Efter att ha öppnat alla inbyggda egenskaper, öppna relevanta egenskaper med hjälp av relevant metod som GetTitle(), GetSubject() etc. För att uppdatera egenskaperna tillhandahåller API metoder som SetTitle, SetSubject, SetAuthor, SetComments etc. Visa[inbyggd samling av dokumentegenskaper](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) för önskad funktion.

{{% blocks/products/pf/feature-page-code h3="Gå via C++-kod för att läsa systemdefinierade egenskaper" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Gå via C++-kod för att uppdatera inbyggda egenskaper" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Visa och lägg till anpassade egenskaper" %}}

 För hantering av anpassade egenskaper tillhandahåller API[Workbook::HämtaAnpassadeDokumentegenskaper](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)som returnerar alla anpassade dokumentegenskaper i kalkylbladet. För att komma åt de anpassade egenskaperna via den här metoden kan utvecklare använda relevanta metoder för att lägga till egenskaper som AddIDocumentProperty, AddLinkToContentProperty och på liknande sätt använda UpdateLinkedPropertyValue, UpdateLinkedRange för att uppdatera värdet för anpassade dokumentegenskaper som länkar till innehåll respektive länkat område. Utvecklare kan använda relevant metod från[samling av anpassade dokumentegenskaper](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Gå via C++-koden för att se anpassade egenskaper" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Gå via C++-koden för att lägga till metadata i Excel-filen" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}