---
title: Splits Excel-spreadsheet in werkbladen in Java
description: Java broncodes waarin wordt uitgelegd hoe u Microsoft Excel-bestanden in meerdere documenten kunt splitsen met behulp van de Java Excel-bibliotheek
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-bestanden splitsen via Java" h2="Splits Excel-spreadsheet in werkbladen binnen op Java gebaseerde applicaties" >}}
{{% blocks/products/pf/feature-page-summary %}}
Er zijn verschillende scenario's waarbij Excel-bestanden moeten worden gesplitst, zoals een spreadsheet met gegevens van leerlingen, met toewijzing van een enkel blad voor elke leerling. En het is nodig om elk blad als een afzonderlijk bestand te splitsen. Om de via Java-applicatie te automatiseren,[JavaExcel API](/cells/nl/java/) is er om Excel-documenten per blad te splitsen. Ondersteunde formaten zijn onder meer XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Splits Excel-document in meerdere bestanden" %}}

 De eenvoudigste manier om een Excel-bestand in een blad te splitsen is door alle bladen te openen, elk blad te doorlopen en één voor één op te slaan in het gewenste formaat. Voor het laden van het werkblad biedt API[Werkboek](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) klas.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) methode krijgt het totale aantal vellen. Herhaal elk blad en gebruik het[getWorksheets().get(bladindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) voor toegang tot een specifiek blad. Verplaats de geselecteerde bladgegevens naar het nieuw gemaakte werkmapklasseobject met behulp van[Kopieer methode](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Sla het ten slotte op in het gewenste formaat.

{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-bestanden te splitsen" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Splits het Excel-werkblad in deelvensters" %}}

API biedt ook functionaliteit voor het splitsen van Excel-werkbladen in verschillende deelvensters. Het proces is: laad het bestand met behulp van de werkmapklasse. Selecteer het eerste werkblad of een gewenst blad door de index ervan op te geven. Roep de setActiveCell aan met de relevante celindex als parameter. En tenslotte splitst u het werkbladvenster in verschillende deelvensters door de methode split() aan te roepen.

{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-werkblad te splitsen in deelvensterweergave" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
