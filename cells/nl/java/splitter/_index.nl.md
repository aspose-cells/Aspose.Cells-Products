---
title: Excel-spreadsheet splitsen in werkbladen in Java

description: Java broncodes waarin wordt uitgelegd hoe u Microsoft Excel-bestanden in meerdere documenten kunt splitsen met behulp van Java Excel-bibliotheek
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-bestand splitsen via Java" h2="Excel-spreadsheet splitsen in werkbladen binnen Java-gebaseerde applicaties" >}}
{{% blocks/products/pf/feature-page-summary %}}
Er zijn verschillende scenario's, wanneer het nodig is om Excel-bestanden te splitsen, zoals een spreadsheet met studentengegevens met toewijzing van een enkel blad voor elke student. En het is nodig om elk blad studentgewijs te splitsen als een apart bestand. Om het te automatiseren via de toepassing Java, [Java Excel API](/cells/java/) is er om Excel-document bladsgewijs te splitsen. Ondersteunde formaten zijn XLS, XLSX, XLSB, XLSM, ODS. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel-document splitsen in meerdere bestanden" %}}

De eenvoudigste manier om een Excel-bestand in een blad te splitsen, is door alle bladen te openen, door elk blad te bladeren en één voor één op te slaan in het gewenste formaat. Voor het laden van het werkblad biedt API [Werkboek](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) klas. [getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) methode krijgt het totale aantal vellen. Doorloop elk blad en gebruik [getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) voor toegang tot een specifiek blad. Verplaats de geselecteerde bladgegevens naar het nieuw gemaakte klasseobject Werkmap met behulp van [Kopieer methode](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Sla het ten slotte op in het vereiste formaat.

{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-bestanden te splitsen" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel-werkblad splitsen in deelvensters" %}}

API biedt ook functionaliteit voor het splitsen van Excel-werkbladen in verschillende deelvensters. Proces is, Laad het bestand met behulp van de werkmapklasse. Selecteer het eerste werkblad of een gewenst blad door de index op te geven. Roep de setActiveCell aan met de relevante celindex als parameter. En splits tenslotte het werkbladvenster in verschillende deelvensters door de split()-methode aan te roepen.

{{% blocks/products/pf/feature-page-code h3="Java Code om Excel-blad op te splitsen in deelvenster" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
