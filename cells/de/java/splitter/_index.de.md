---
title: Teilen Sie die Excel-Tabelle in Java in Arbeitsblätter auf
description: Java Quellcodes, die erklären, wie Microsoft Excel-Dateien mithilfe der Java Excel-Bibliothek in mehrere Dokumente aufgeteilt werden
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-Dateiaufteilung via Java" h2="Teilen Sie eine Excel-Tabelle in Arbeitsblätter in Java-basierten Anwendungen auf" >}}
{{% blocks/products/pf/feature-page-summary %}}
Es gibt verschiedene Szenarien, wenn Excel-Dateien wie eine Tabellenkalkulation mit Schülerdaten aufgeteilt werden müssen, wobei jedem Schüler ein einzelnes Blatt zugewiesen werden muss. Und es ist notwendig, jedes Blatt schülerweise in eine separate Datei aufzuteilen. Um die Anwendung via Java zu automatisieren,[Java Excel API](/cells/de/java/) Gibt es die Möglichkeit, Excel-Dokumente blattweise aufzuteilen? Zu den unterstützten Formaten gehören XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Teilen Sie ein Excel-Dokument in mehrere Dateien auf" %}}

 Der einfachste Weg, eine Excel-Datei in Arbeitsblätter aufzuteilen, besteht darin, auf alle Arbeitsblätter zuzugreifen, jedes Arbeitsblatt zu durchlaufen und eines nach dem anderen im gewünschten Format zu speichern. Für das Laden des Arbeitsblattes sorgt API[Arbeitsmappe](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) Klasse.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) Methode ermittelt die Gesamtzahl der Blätter. Gehen Sie jedes Blatt durch und verwenden Sie es[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) für den Zugriff auf ein bestimmtes Blatt. Verschieben Sie die ausgewählten Blattdaten mit in das neu erstellte Arbeitsmappenklassenobjekt[Kopiermethode](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Speichern Sie es abschließend im erforderlichen Format.

{{% blocks/products/pf/feature-page-code h3="Java Code zum Teilen von Excel-Dateien" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Teilen Sie das Excel-Arbeitsblatt in Bereiche auf" %}}

API bietet auch die Möglichkeit, ein Excel-Arbeitsblatt in verschiedene Bereiche aufzuteilen. Der Prozess besteht darin, die Datei mithilfe der Workbook-Klasse zu laden. Wählen Sie das erste Arbeitsblatt oder ein beliebiges erforderliches Blatt aus, indem Sie dessen Index angeben. Rufen Sie setActiveCell mit dem relevanten Zellindex als Parameter auf. Und schließlich teilen Sie das Arbeitsblattfenster in verschiedene Bereiche auf, indem Sie die Methode split() aufrufen.

{{% blocks/products/pf/feature-page-code h3="Java Code zum Aufteilen einer Excel-Tabelle in eine Fensteransicht" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
