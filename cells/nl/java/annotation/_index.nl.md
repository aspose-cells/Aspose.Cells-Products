---
title: Excel-bestand annotaties via Java
url: /nl/java/annotation/
description: Gegevensannotatie van Excel- en OpenOffice-spreadsheets toevoegen of verwijderen met Java-bibliotheek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Excel-bestandsannotaties via Java" h2="Voeg eenvoudige notities in voor annotaties of verwijder opmerkingen op celniveau in Excel-spreadsheets in op Java gebaseerde toepassingen." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) biedt ondersteuning voor het beheren van annotaties op celniveau door opmerkingen toe te voegen, te openen en te verwijderen. API biedt [Commentaar](https://apireference.aspose.com/cells/java/com.aspose.cells/Comment), [OpmerkingCollectie](https://apireference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [ThreadedCommentaar](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) en [ThreadedCommentCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) voor het afhandelen van opmerkingen in alle aspecten.
Ondersteunde bestandsindelingen zijn ODS, XLS, XLSX, XLSB en XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gegevensaantekeningen in Excel-bestanden" %}}
Opmerkingen in werkbladen beheren - Er is geen limiet aan het aantal opmerkingen dat een blad heeft in MS Excel. Men kan zoveel toevoegen als van toepassingsvereiste. Het proces van het toevoegen van opmerkingen is, maak [Werkboek](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) class-object of laad een bestaand bestand met Workbook class. Krijg toegang tot al zijn opmerkingen met getComments(). Verkrijg de celindex en gebruik [setOpmerking](https://apireference.aspose.com/cells/java/com.aspose.cells/comment#Note) voor het invoegen van opmerkingen. Bovendien kan API alle opmerkingen verwijderen. 

{{% blocks/products/pf/feature-page-code h3="Java Code om opmerkingen toe te voegen binnen Excel-bestand" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Code om opmerkingen in Excel-bestand te verwijderen" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}