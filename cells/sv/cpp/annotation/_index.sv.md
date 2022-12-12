---
title: Excel-filkommentarer via C++

description: Lägg till eller ta bort datakommentarer för Excel- och OpenOffice-kalkylblad med C++-biblioteket.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hantera Microsoft<sup>&reg;</sup> Excel-filkommentarer via C++" h2="Lägg till eller ta bort enkla anteckningar för kommentarer eller kommentarer i C++-baserade applikationer." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) ger stöd för att hantera anteckningar på cellnivå genom att lägga till, komma åt och ta bort kommentarer. API tillhandahåller [IKommentera](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) och [IComment Collection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) såväl som [GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) för att hantera kommentarer i alla aspekter. Excel-format som stöds inkluderar ODS, XLS, XLSX, XLSB och XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel-filer Dataanteckningar" %}}
Manipulera kommentarer i arbetsblad - Det är inte begränsat till hur många kommentarer ett ark har i MS Excel. Man kan infoga så mycket som applikationsbehovet. Processen för att infoga kommentarer är, skapa [IArbetsbok](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) klassobjekt för att ladda en befintlig fil och välj kalkylblad där du vill lägga till kommentaren. Få alla dess kommentarer med getComments(). Lägg till kommentaren med [Lägg till](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > cellName) metod. Hämta cellindex och använd [setNote](https://reference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) för att lägga in kommentarer. Dessutom kan API ta bort alla kommentarer. Få av metoderna är det [RensaComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) till Rensar alla kommentarer i designerkalkylbladet. Dessutom, [Ta bortAt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) för att ta bort elementet vid ett angivet index eller med angivet namn.

{{% blocks/products/pf/feature-page-code h3="C++ Kod för att lägga till kommentarer i Excel-fil" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
