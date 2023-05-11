---
title: Anmerkungen zu Excel-Dateien via Java
description: Fügen Sie Datenanmerkungen von Excel- und OpenOffice-Tabellen mit der Bibliothek Java hinzu oder entfernen Sie sie.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Verwalten Sie Microsoft<sup>&reg;</sup> Excel-Dateianmerkungen via Java" h2="Fügen Sie einfache Notizen für Anmerkungen ein oder löschen Sie Kommentare auf Zellenebene in Excel-Tabellen in Java-basierten Anwendungen." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/de/java/) Bietet Unterstützung für die Verwaltung von Anmerkungen auf Zellenebene durch Hinzufügen, Zugreifen auf und Löschen von Kommentaren. API bietet[Kommentar](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [Kommentarsammlung](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [ThreadedComment](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) Und[ThreadedCommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) für den Umgang mit Kommentaren in allen Belangen.
Zu den unterstützten Dateiformaten gehören ODS, XLS, XLSX, XLSB und XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Datenanmerkungen zu Excel-Dateien" %}}
 Verwalten von Kommentaren in Arbeitsblättern – In MS Excel gibt es keine Begrenzung für die Anzahl der Kommentare in einem Arbeitsblatt. Man kann so viel hinzufügen, wie es die Anwendungsanforderungen erfordern. Der Prozess zum Hinzufügen von Kommentaren ist: Erstellen[Arbeitsmappe](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)Klassenobjekt oder laden Sie eine vorhandene Datei mithilfe der Arbeitsmappenklasse. Greifen Sie mit getComments() auf alle Kommentare zu. Holen Sie sich den Zellindex und verwenden Sie ihn[setNote](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) zum Einfügen von Kommentaren. Darüber hinaus ist API in der Lage, alle Kommentare zu entfernen.

{{% blocks/products/pf/feature-page-code h3="Java Code zum Hinzufügen von Kommentaren innerhalb einer Excel-Datei" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Code zum Entfernen von Kommentaren in einer Excel-Datei" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
