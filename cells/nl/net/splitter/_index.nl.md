---
title: Splits het Excel-werkblad bladsgewijs in C#
description: C#-broncodes waarin wordt uitgelegd hoe u Microsoft Excel-bestanden in meerdere bestanden kunt splitsen in Visual C#.NET-toepassingen
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-bestanden splitsen via .NET" h2="Splits een enkel Excel-document in verschillende bestanden met behulp van C#-code binnen op .NET gebaseerde applicaties" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel-bibliotheek](/cells/nl/net/) is in staat om Excel-documenten op te splitsen in meerdere spreadsheets binnen op .NET gebaseerde applicaties. Ondersteunde bestandsformaten zijn onder meer XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Splits Excel-document in meerdere bestanden" %}}
De eenvoudigste manier om Excel-bestanden per blad te splitsen is door toegang te krijgen tot alle bladen via[Werkbladen](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Door elk blad bladeren en de[Kopiëren](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) methode. Eindelijk opslaan in een opgegeven pad.

 + Laad het Excel-bestand met het volledige pad met behulp van[Werkmap klasse](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Herhaal elk blad
+ Maak een nieuw werkboekklasseobject
 + Kopieer het blad via[Kopieer methode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Roep de Save()-methode aan en geef de bestandsnaam (volledig pad) door met de relevante SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Code om Excel-bestanden te splitsen" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Splits het Excel-werkblad in deelvensters" %}}

 Voor het splitsen van het werkbladvenster in deelvensters biedt API[Splitsmethode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) van de werkbladklasse, die de gesplitste weergave van het werkblad biedt. Om de gesplitste weergave te verwijderen, biedt API[RemoveSplit-methode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Sla het ten slotte op in een opgegeven pad.

{{% blocks/products/pf/feature-page-code h3="C# Code om Excel-werkbladvenster te splitsen" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Code om gesplitste panweergave te verwijderen" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
