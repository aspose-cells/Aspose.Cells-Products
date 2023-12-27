---
title: Fügen Sie Excel-Dateianmerkungen über C++ hinzu oder entfernen Sie sie
description: Fügen Sie mit der Bibliothek C++ Datenanmerkungen zu Excel- und OpenOffice-Tabellen hinzu oder entfernen Sie sie.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Verwalten Sie Microsoft<sup>&reg;</sup> Excel-Dateianmerkungen über C++" h2="Fügen Sie einfache Notizen für Anmerkungen oder Kommentare in C++-basierten Anwendungen hinzu oder entfernen Sie sie." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/de/cpp/) Bietet Unterstützung für die Verwaltung von Anmerkungen auf Zellenebene durch Hinzufügen, Zugreifen auf und Entfernen von Kommentaren. API bietet[Kommentar](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) Und[Kommentarsammlung](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) sowie[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)für den Umgang mit Kommentaren in allen Belangen. Zu den unterstützten Excel-Formaten gehören ODS, XLS, XLSX, XLSB und XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Datenanmerkungen zu Excel-Dateien" %}}
 Bearbeiten von Kommentaren in Arbeitsblättern – Es gibt keine Beschränkung hinsichtlich der Anzahl der Kommentare, die ein Blatt in MS Excel enthält. Man kann so viel einfügen, wie der Anwendungsbedarf erfordert. Der Prozess zum Einfügen von Kommentaren ist: Erstellen[Arbeitsmappe](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) Klassenobjekt, um eine vorhandene Datei zu laden und das Arbeitsblatt auszuwählen, in das Sie den Kommentar einfügen möchten. Rufen Sie alle Kommentare mit getComments() ab. Fügen Sie den Kommentar mit hinzu[Add(const char16_t* cellName)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) Methode. Holen Sie sich den Zellindex und verwenden Sie ihn[SetNote](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) zum Einfügen von Kommentaren. Darüber hinaus ist API in der Lage, alle Kommentare zu entfernen. Nur wenige der Methoden sind[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) bis Löscht alle Kommentare in der Designer-Tabelle. Darüber hinaus,***RemoveAt*** Methode zum Entfernen des Elements an einem angegebenen Index oder mit dem angegebenen Namen.

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Hinzufügen von Kommentaren innerhalb einer Excel-Datei" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
