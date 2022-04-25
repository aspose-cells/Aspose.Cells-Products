---
title: Excel-filkommentarer via Java
url: /sv/java/annotation/
description: Lägg till eller ta bort datakommentarer för Excel- och OpenOffice-kalkylblad med Java-biblioteket.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Hantera Microsoft<sup>&reg;</sup> Excel-filkommentarer via Java" h2="Infoga enkla anteckningar för anteckningar eller ta bort kommentarer på cellnivå i Excel-kalkylark i Java-baserade applikationer." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) ger stöd för att hantera anteckningar på cellnivå genom att lägga till, komma åt och ta bort kommentarer. API tillhandahåller [Kommentar](https://apireference.aspose.com/cells/java/com.aspose.cells/Comment), [Kommentarsamling](https://apireference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [Trådad kommentar](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) och [ThreadedComment Collection](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) för att hantera kommentarer i alla aspekter.
Filformat som stöds inkluderar ODS, XLS, XLSX, XLSB och XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel-filer Dataanteckningar" %}}
Hantera kommentarer i arbetsblad - Det finns ingen gräns för hur många kommentarer ett ark har i MS Excel. Man kan lägga till så mycket som av ansökan krav. Processen att lägga till kommentarer är att skapa [Arbetsbok](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) klassobjekt eller ladda en befintlig fil med Workbook-klassen. Få åtkomst till alla dess kommentarer med getComments(). Hämta cellindex och använd [setNote](https://apireference.aspose.com/cells/java/com.aspose.cells/comment#Note) för att lägga in kommentarer. Dessutom kan API ta bort alla kommentarer. 

{{% blocks/products/pf/feature-page-code h3="Java Kod för att lägga till kommentarer i Excel-fil" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Kod för att ta bort kommentarer i Excel-fil" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}