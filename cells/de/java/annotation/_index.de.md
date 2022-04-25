---
title: Anmerkungen zu Excel-Dateien über Java
url: /de/java/annotation/
description: Hinzufügen oder Entfernen von Datenanmerkungen von Excel- und OpenOffice-Tabellen mit der Java-Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Verwalten Sie Microsoft<sup>&reg;</sup> Excel-Dateianmerkungen über Java" h2="Fügen Sie einfache Notizen für Anmerkungen ein oder löschen Sie Kommentare auf Zellenebene von Excel-Tabellen in Java-basierten Anwendungen." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) bietet Unterstützung für die Verwaltung von Anmerkungen auf Zellenebene durch Hinzufügen, Aufrufen und Löschen von Kommentaren. API bietet [Kommentar](https://apireference.aspose.com/cells/java/com.aspose.cells/Comment), [Kommentarsammlung](https://apireference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [ThreadedComment](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) und [ThreadedCommentCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) für den Umgang mit Kommentaren in allen Aspekten.
Zu den unterstützten Dateiformaten gehören ODS, XLS, XLSX, XLSB und XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Datenanmerkungen in Excel-Dateien" %}}
Verwalten von Kommentaren in Arbeitsblättern – Es gibt keine Begrenzung dafür, wie viele Kommentare ein Blatt in MS Excel hat. Man kann so viel hinzufügen, wie es für die Anwendung erforderlich ist. Der Vorgang zum Hinzufügen von Kommentaren ist Erstellen [Arbeitsmappe](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) -Klassenobjekt oder laden Sie eine vorhandene Datei mit der Workbook-Klasse. Greifen Sie mit getComments() auf alle seine Kommentare zu. Holen Sie sich den Zellenindex und verwenden Sie ihn [setHinweis](https://apireference.aspose.com/cells/java/com.aspose.cells/comment#Note) zum Einfügen von Kommentaren. Außerdem kann API alle Kommentare entfernen. 

{{% blocks/products/pf/feature-page-code h3="Java Code zum Hinzufügen von Kommentaren in einer Excel-Datei" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Code zum Entfernen von Kommentaren in einer Excel-Datei" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}