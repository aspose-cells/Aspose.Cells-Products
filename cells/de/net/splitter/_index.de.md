---
title: Teilen Sie das Excel-Arbeitsblatt weise in C#
url: /de/net/splitter/
description: C#-Quellcodes, die erklären, wie Microsoft Excel-Dateien in Visual C#.NET-Anwendungen in mehrere Dateien aufgeteilt werden
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-Dateiaufteilung über .NET" h2="Einzelnes Excel-Dokument mithilfe von C#-Code in .NET-basierten Anwendungen in verschiedene Dateien aufteilen" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel-Bibliothek](/cells/net/) ist in der Lage, Excel-Dokumente innerhalb von .NET-basierten Anwendungen in mehrere Tabellenkalkulationen aufzuteilen. Zu den unterstützten Dateiformaten gehören XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel-Dokument in mehrere Dateien aufteilen" %}}
Der einfachste Weg, Excel-Dateien blattweise aufzuteilen, ist der Zugriff auf alle Blätter über [Arbeitsblätter](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Iterieren durch jedes Blatt und Aufrufen der [Kopieren](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) Methode. Speichern Sie es schließlich in einem bestimmten Pfad. 

+ Laden Sie die Excel-Datei mit vollständigem Pfad mit [Klasse Arbeitsbuch](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Iteriere durch jedes Blatt
+ Erstellen Sie ein neues Workbook-Klassenobjekt
+ Kopieren Sie das Blatt über [Kopiermethode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Rufen Sie die Save()-Methode auf und übergeben Sie den Dateinamen (vollständiger Pfad) mit dem relevanten SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Code zum Teilen von Excel-Dateien" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Teilen Sie das Excel-Arbeitsblatt in Bereiche auf" %}}

Zum Aufteilen des Arbeitsblattfensters in Bereiche bietet API [Split-Methode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) der Arbeitsblattklasse, die die geteilte Ansicht des Arbeitsblatts bereitstellt. Zum Entfernen der geteilten Ansicht stellt API bereit [RemoveSplit-Methode](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Speichern Sie es schließlich in einem angegebenen Pfad. 

{{% blocks/products/pf/feature-page-code h3="C# Code zum Aufteilen des Excel-Arbeitsblattfensters" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Code zum Entfernen der geteilten Schwenkansicht" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
