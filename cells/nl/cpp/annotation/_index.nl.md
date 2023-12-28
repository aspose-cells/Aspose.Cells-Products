---
title: Excel-bestandsannotaties toevoegen of verwijderen via C++
description: Voeg opmerkingen bij gegevensannotaties van Excel- en OpenOffice-spreadsheets toe of verwijder ze met de bibliotheek C++.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Excel-bestandsannotaties via C++" h2="Voeg eenvoudige notities toe of verwijder deze voor annotaties of opmerkingen binnen op C++ gebaseerde applicaties." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++Excel API](/cells/nl/cpp/) biedt ondersteuning voor het beheren van annotaties op celniveau door opmerkingen toe te voegen, te openen en te verwijderen. API verstrekt[Opmerking](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) En[Commentaarverzameling](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) net zoals[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)voor het afhandelen van opmerkingen in alle aspecten. Ondersteunde Excel-formaten zijn onder meer ODS, XLS, XLSX, XLSB en XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel-bestanden Gegevensannotaties" %}}
 Commentaar in werkbladen manipuleren - Het is niet beperkt tot het aantal opmerkingen dat een blad heeft in MS Excel. Men kan zoveel inbrengen als nodig is. Het proces van het invoegen van opmerkingen is: creëren[Werkboek](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) class-object om een bestaand bestand te laden en een werkblad te selecteren waaraan u de opmerking wilt toevoegen. Haal al het commentaar op met getComments(). Voeg de opmerking toe met[Add(const char16_t* celnaam)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) methode. Haal de celindex op en gebruik deze[StelOpmerking in](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) voor het invoegen van opmerkingen. Bovendien kan API alle opmerkingen verwijderen. Er zijn maar weinig methoden[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) naar Wist alle opmerkingen in het ontwerperspreadsheet. Bovendien,***VerwijderenBij*** methode om het element op een opgegeven index of met een opgegeven naam te verwijderen.

{{% blocks/products/pf/feature-page-code h3="C++ Code om opmerkingen toe te voegen aan het Excel-bestand" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
