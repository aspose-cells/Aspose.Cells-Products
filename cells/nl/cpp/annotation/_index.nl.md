---
title: Excel-bestandsaantekeningen via C++
description: Opmerkingen over gegevensannotaties van Excel- en OpenOffice-spreadsheets toevoegen of verwijderen met de C++-bibliotheek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Excel-bestandsaantekeningen via C++" h2="Voeg eenvoudige notities toe of verwijder ze voor annotaties of opmerkingen binnen op C++ gebaseerde applicaties." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/nl/cpp/) biedt ondersteuning om annotaties op celniveau te beheren door opmerkingen toe te voegen, te openen en te verwijderen. API biedt[IOpmerking](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) En[ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) net zoals[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)voor het behandelen van opmerkingen in alle aspecten. Ondersteunde Excel-indelingen zijn ODS, XLS, XLSX, XLSB en XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel-bestanden Gegevensannotaties" %}}
 Opmerkingen in werkbladen manipuleren - Het is niet beperkt tot het aantal opmerkingen dat een blad heeft in MS Excel. Men kan zoveel inbrengen als nodig is. Het proces van het invoegen van opmerkingen is, creëren[IWerkboek](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class-object om een bestaand bestand te laden en selecteer het werkblad waaraan u de opmerking wilt toevoegen. Haal al zijn opmerkingen op met behulp van getComments(). Voeg de opmerking toe met behulp van[Toevoegen](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384) (opdringerig_ptr< Aspose::Cells::Systems::String > celNaam) methode. Verkrijg de celindex en gebruik[stelOpmerking](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580) voor het invoegen van opmerkingen. Bovendien kan API alle opmerkingen verwijderen. Er zijn maar weinig methoden[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) to Wist alle opmerkingen in de designer-spreadsheet. Bovendien,[Verwijderen bij](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(opdringerig_ptr< Aspose::Cells::Systems::String > naam) methode om het element te verwijderen bij een opgegeven index of met een opgegeven naam.

{{% blocks/products/pf/feature-page-code h3="C++ Code om opmerkingen toe te voegen in Excel-bestand" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
