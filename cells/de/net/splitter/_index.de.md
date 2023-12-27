---
title: Teilen Sie das Excel-Arbeitsblatt blattweise in C# auf
description: C# Quellcodes, die erklären, wie Microsoft Excel-Dateien in mehreren Dateien in Visual C#.NET Anwendungen aufgeteilt werden
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-Dateiaufteilung via .NET" h2="Teilen Sie ein einzelnes Excel-Dokument mithilfe des C#-Codes in .NET-basierten Anwendungen in verschiedene Dateien auf" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel-Bibliothek](/cells/de/net/) ist in der Lage, Excel-Dokumente in .NET-basierten Anwendungen in mehrere Tabellen aufzuteilen. Zu den unterstützten Dateiformaten gehören XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Teilen Sie ein Excel-Dokument in mehrere Dateien auf" %}}
Der einfachste Weg, Excel-Dateien blattweise aufzuteilen, ist der Zugriff auf alle Blätter über[Arbeitsblätter](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Jedes Blatt durchlaufen und aufrufen[Kopieren](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) Methode. Schließlich wird es in einem angegebenen Pfad gespeichert.

 + Laden Sie die Excel-Datei mit vollständigem Pfad mit[Arbeitsbuchklasse](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Durchlaufen Sie jedes Blatt
+ Erstellen Sie ein neues Workbook-Klassenobjekt
 + Kopieren Sie das Blatt über[Kopiermethode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Rufen Sie die Save()-Methode auf und übergeben Sie den Dateinamen (vollständigen Pfad) mit dem relevanten SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Teilen von Excel-Dateien" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Teilen Sie das Excel-Arbeitsblatt in Bereiche auf" %}}

 Für die Aufteilung des Arbeitsblattfensters in Bereiche ist API vorgesehen[Split-Methode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) der Arbeitsblattklasse, die die geteilte Ansicht des Arbeitsblatts bereitstellt. Um die geteilte Ansicht zu entfernen, bietet API an[RemoveSplit-Methode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Speichern Sie es abschließend in einem angegebenen Pfad.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Teilen des Excel-Arbeitsblattfensters" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Code zum Entfernen der geteilten Pan-Ansicht" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
