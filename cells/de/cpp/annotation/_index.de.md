---
title: Anmerkungen zu Excel-Dateien über C++
description: Fügen Sie mit der Bibliothek C++ Datenanmerkungen zu Excel- und OpenOffice-Tabellen hinzu oder entfernen Sie sie.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Verwalten Sie Microsoft<sup>&reg;</sup> Excel-Dateianmerkungen über C++" h2="Fügen Sie einfache Notizen für Anmerkungen oder Kommentare in C++-basierten Anwendungen hinzu oder entfernen Sie sie." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/de/cpp/) Bietet Unterstützung für die Verwaltung von Anmerkungen auf Zellenebene durch Hinzufügen, Zugreifen auf und Entfernen von Kommentaren. API bietet[IComment](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) Und[ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) sowie[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)für den Umgang mit Kommentaren in allen Belangen. Zu den unterstützten Excel-Formaten gehören ODS, XLS, XLSX, XLSB und XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Datenanmerkungen zu Excel-Dateien" %}}
 Bearbeiten von Kommentaren in Arbeitsblättern – Es gibt keine Beschränkung hinsichtlich der Anzahl der Kommentare, die ein Blatt in MS Excel enthält. Man kann so viel einfügen, wie der Anwendungsbedarf erfordert. Der Prozess zum Einfügen von Kommentaren ist: Erstellen[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) Klassenobjekt, um eine vorhandene Datei zu laden und das Arbeitsblatt auszuwählen, in das Sie den Kommentar einfügen möchten. Rufen Sie alle Kommentare mit getComments() ab. Fügen Sie den Kommentar mit hinzu[Hinzufügen](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384) (intrusive_ptr< Aspose::Cells::Systems::String > cellName)-Methode. Holen Sie sich den Zellindex und verwenden Sie ihn[setNote](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580) zum Einfügen von Kommentaren. Darüber hinaus ist API in der Lage, alle Kommentare zu entfernen. Nur wenige der Methoden sind[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) bis Löscht alle Kommentare in der Designer-Tabelle. Darüber hinaus,[RemoveAt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name)-Methode zum Entfernen des Elements an einem angegebenen Index oder mit dem angegebenen Namen.

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Hinzufügen von Kommentaren innerhalb einer Excel-Datei" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
