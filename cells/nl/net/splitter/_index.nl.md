---
title: Excel-werkblad bladsgewijs splitsen in C#
url: /nl/net/splitter/
description: C# broncodes waarin wordt uitgelegd hoe u Microsoft Excel-bestanden kunt splitsen in meerdere bestanden in Visual C#.NET-toepassingen
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-bestand splitsen via .NET" h2="Splits een enkel Excel-document in verschillende bestanden met behulp van C#-code binnen .NET-gebaseerde toepassingen" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel-bibliotheek](/cells/net/) is in staat om Excel-documenten op te splitsen in meerdere spreadsheets binnen op .NET gebaseerde toepassingen. Ondersteunde bestandsindelingen zijn XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel-document splitsen in meerdere bestanden" %}}
De eenvoudigste manier om Excel-bestanden bladsgewijs te splitsen, is: Alle bladen openen via [Werkbladen](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Elk blad doorlopen en de . aanroepen [Kopiëren](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) methode. Sla het ten slotte op in een opgegeven pad. 

+ Laad het Excel-bestand met het volledige pad met behulp van [Werkboek klasse](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Herhaal elk blad
+ Maak een nieuw werkmapklasse-object
+ Kopieer het blad via [Kopieer methode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Roep de methode Save() aan en geef de bestandsnaam (volledig pad) met relevante SaveFormat door.

{{% blocks/products/pf/feature-page-code h3="C# Code om Excel-bestanden te splitsen" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel-werkblad splitsen in deelvensters" %}}

Voor het splitsen van het werkbladvenster in deelvensters biedt API [Gesplitste methode:](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) van werkbladklasse, die de gesplitste weergave van het werkblad biedt. Gesplitste weergave verwijderen API biedt [RemoveSplit-methode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Sla het ten slotte op in een opgegeven pad. 

{{% blocks/products/pf/feature-page-code h3="C# Code om Excel-werkbladvenster te splitsen" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Code om gesplitste panweergave te verwijderen" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
