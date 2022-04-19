---
title: Excel-Tabelle in Arbeitsblätter in Java aufteilen
url: /de/java/splitter/
description: Java Quellcodes, die erklären, wie Microsoft Excel-Dateien mithilfe der Java Excel-Bibliothek in mehrere Dokumente aufgeteilt werden
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-Dateiaufteilung über Java" h2="Teilen Sie die Excel-Tabelle in Arbeitsblätter innerhalb von Java-basierten Anwendungen auf" >}}
{{% blocks/products/pf/feature-page-summary %}}
Es gibt eine Vielzahl von Szenarien, wenn Excel-Dateien wie eine Tabelle mit Schülerdaten aufgeteilt werden müssen, wobei jedem Schüler ein einzelnes Blatt zugewiesen werden muss. Und es ist notwendig, jedes Blatt schülerweise als separate Datei aufzuteilen. Um es über die Anwendung Java zu automatisieren, [Java Excel API](/cells/java/) ist da, um Excel-Dokumente blattweise aufzuteilen. Zu den unterstützten Formaten gehören XLS, XLSX, XLSB, XLSM, ODS. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel-Dokument in mehrere Dateien aufteilen" %}}

Die einfachste Möglichkeit, eine Excel-Datei in ein Blatt aufzuteilen, besteht darin, auf alle Blätter zuzugreifen, jedes Blatt zu durchlaufen und eines nach dem anderen im gewünschten Format zu speichern. Zum Laden des Arbeitsblatts stellt API bereit [Arbeitsmappe](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) Klasse. [getWorksheets().getCount()](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) Methode erhält die Gesamtzahl der Blätter. Durchlaufen Sie jedes Blatt und verwenden Sie es [getWorksheets().get(sheetindex)](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) für den Zugriff auf ein bestimmtes Blatt. Verschieben Sie die ausgewählten Blattdaten mithilfe von in das neu erstellte Arbeitsmappen-Klassenobjekt [Kopiermethode](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Speichern Sie es schließlich im erforderlichen Format.

{{% blocks/products/pf/feature-page-code h3="Java Code zum Teilen von Excel-Dateien" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Teilen Sie das Excel-Arbeitsblatt in Bereiche auf" %}}

API bietet auch Funktionen zum Aufteilen von Excel-Arbeitsblättern in verschiedene Bereiche. Prozess ist, Laden Sie die Datei mit der Workbook-Klasse. Wählen Sie das erste Arbeitsblatt oder ein beliebiges erforderliches Blatt aus, indem Sie seinen Index angeben. Rufen Sie die setActiveCell mit dem relevanten Zellindex als Parameter auf. Und schließlich teilen Sie das Arbeitsblattfenster in verschiedene Bereiche auf, indem Sie die Methode split() aufrufen.

{{% blocks/products/pf/feature-page-code h3="Java Code zum Aufteilen einer Excel-Tabelle in eine Bereichsansicht" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}