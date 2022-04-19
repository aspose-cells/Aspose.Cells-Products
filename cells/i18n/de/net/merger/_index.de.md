---
title: Zusammenführung von Excel-Dateien API .NET C#
url: /de/net/merger/
description: Verketten Sie Excel- und OpenOffice-Tabellendateien mit nur wenigen Zeilen C#-Code.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Zusammenführen von Microsoft<sup>&reg;</sup> Excel-Dateien über .NET" h2="Kombinieren Sie 2 oder mehr Excel-Dateien in einer einzigen Tabelle mit C#-Code" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel-Bibliothek](/cells/net/) bietet mehrere Möglichkeiten, Arbeitsmappen mit verschiedenen Arten von Inhalten wie Formeln, Daten, Bildern, Diagrammen usw. in einer einzigen Tabellenkalkulationsdatei zu kombinieren. Zu den unterstützten Dateiformaten gehören XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV und mehr.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinieren Sie Excel-Dateien mit Bildern und Diagrammen" %}}
Der einfachste Weg, 2 Excel-Dateien mit Bildern und Diagrammen zu kombinieren, ist der Aufruf der [Workbook.Combine](https://apireference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) Methode. Es ermöglicht das Zusammenführen von Excel-Dateien ähnlichen Typs in einer einzigen Tabelle.
{{% blocks/products/pf/feature-page-code h3="C# Code zum Kombinieren von Excel-Dateien" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Mehrere Excel-Dateien zusammenführen" %}}
[CellsHelper.MergeFiles](https://apireference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) -Methode unterstützt das Zusammenführen von Daten, Stil und Formeln einer Excel-Datei mit einer neuen Tabelle im gleichen Format. Es ist eine effiziente Möglichkeit, mehrere Dateien zusammenzuführen, während Caching verwendet wird. 
{{% blocks/products/pf/feature-page-code h3="C# Code zum Zusammenführen mehrerer Excel-Dateien" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Excel-Dateien durch Kopieren von Arbeitsblättern zusammenführen" %}}
[Arbeitsblatt.Kopieren](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) kann verwendet werden, um Daten und Formatierungen von einem Quellarbeitsblatt in ein anderes Arbeitsblatt innerhalb oder zwischen Arbeitsmappen zu kopieren. Die Methode nimmt das Quellarbeitsblattobjekt als Parameter.
{{% blocks/products/pf/feature-page-code h3="C# Code zum Kopieren von Arbeitsblättern in Excel-Dateien" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}