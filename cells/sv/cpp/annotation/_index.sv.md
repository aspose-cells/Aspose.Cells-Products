---
title: Lägg till eller ta bort Excel-filkommentarer via C++
description: Lägg till eller ta bort datakommentarer från Excel- och OpenOffice-kalkylblad med C++-biblioteket.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hantera Microsoft<sup>&reg;</sup> Excel-filanteckningar via C++" h2="Lägg till eller ta bort enkla anteckningar för kommentarer eller kommentarer inom C++-baserade applikationer." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/sv/cpp/) ger stöd för att hantera anteckningar på cellnivå genom att lägga till, komma åt och ta bort kommentarer. API tillhandahåller[Kommentar](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) och[Kommentarsamling](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) såväl som[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)för att hantera kommentarer i alla aspekter. Excel-format som stöds inkluderar ODS, XLS, XLSX, XLSB och XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel-filer Dataanteckningar" %}}
 Manipulera kommentarer i arbetsblad - Det är inte begränsat till hur många kommentarer ett ark har i MS Excel. Man kan infoga hur mycket som helst efter behov. Processen för att infoga kommentarer är att skapa[Arbetsbok](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) klassobjekt för att ladda en befintlig fil och välj kalkylblad där du vill lägga till kommentaren. Få alla dess kommentarer med getComments(). Lägg till kommentaren med[Add(const char16_t* cellName)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) metod. Hämta cellindex och använd[SetNote](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) för att lägga in kommentarer. Dessutom kan API ta bort alla kommentarer. Få av metoderna är det[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) till Rensar alla kommentarer i designerkalkylbladet. Dessutom,***Ta bortAt*** metod för att ta bort elementet vid ett angivet index eller med angivet namn.

{{% blocks/products/pf/feature-page-code h3="C++ Kod för att lägga till kommentarer i Excel-fil" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
