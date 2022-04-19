---
title: Excel-bestand annotaties via C++
url: /nl/cpp/annotation/
description: Voeg opmerkingen bij gegevensannotaties van Excel- en OpenOffice-spreadsheets toe of verwijder ze met de bibliotheek C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Beheer Microsoft<sup>&reg;</sup> Excel-bestandsannotaties via C++" h2="Voeg eenvoudige notities toe of verwijder ze voor annotaties of opmerkingen in op C++ gebaseerde applicaties." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) biedt ondersteuning voor het beheren van annotaties op celniveau door opmerkingen toe te voegen, te openen en te verwijderen. API biedt [ICommentaar](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) en [ICommentCollection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) net zoals [GetIComments()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) voor het afhandelen van opmerkingen in alle aspecten. Ondersteunde Excel-indelingen zijn ODS, XLS, XLSX, XLSB en XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gegevensaantekeningen in Excel-bestanden" %}}
Opmerkingen in werkbladen manipuleren - Het is niet beperkt tot het aantal opmerkingen dat een blad heeft in MS Excel. Men kan zoveel inbrengen als van toepassing is. Het proces van het invoegen van opmerkingen is, maken [IWerkboek](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class-object om een bestaand bestand te laden en selecteer het werkblad waaraan u de opmerking wilt toevoegen. Krijg al zijn opmerkingen met getComments(). Voeg de opmerking toe met [Toevoegen](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > celnaam) methode. Verkrijg de celindex en gebruik [setOpmerking](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) voor het invoegen van opmerkingen. Bovendien kan API alle opmerkingen verwijderen. Enkele van de methoden zijn: [ClearComments()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) tot Wist alle opmerkingen in de ontwerperspreadsheet. Bovendien, [VerwijderAt](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) om het element op een opgegeven index of met een opgegeven naam te verwijderen.

{{% blocks/products/pf/feature-page-code h3="C++ Code om opmerkingen toe te voegen binnen Excel-bestand" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}