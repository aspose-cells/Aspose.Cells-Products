---
title: Anmerkungen zu Excel-Dateien über C++
url: /de/cpp/annotation/
description: Hinzufügen oder Entfernen von Datenanmerkungskommentaren von Excel- und OpenOffice-Tabellen mit der C++-Bibliothek.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Verwalten Sie Microsoft<sup>&reg;</sup> Excel-Dateianmerkungen über C++" h2="Fügen Sie einfache Notizen für Anmerkungen oder Kommentare in C++-basierten Anwendungen hinzu oder entfernen Sie sie." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) bietet Unterstützung für die Verwaltung von Anmerkungen auf Zellenebene durch Hinzufügen, Aufrufen und Entfernen von Kommentaren. API bietet [IKommentar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) und [ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) ebenso gut wie [GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) für den Umgang mit Kommentaren in allen Aspekten. Zu den unterstützten Excel-Formaten gehören ODS, XLS, XLSX, XLSB und XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Datenanmerkungen in Excel-Dateien" %}}
Manipulieren von Kommentaren in Arbeitsblättern – Es ist nicht beschränkt, wie viele Kommentare ein Blatt in MS Excel hat. Man kann so viel wie nötig einfügen. Der Vorgang zum Einfügen von Kommentaren ist Erstellen [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) Klassenobjekt, um eine vorhandene Datei zu laden und ein Arbeitsblatt auszuwählen, in dem Sie den Kommentar hinzufügen möchten. Holen Sie sich alle Kommentare mit getComments(). Fügen Sie den Kommentar mit hinzu [Hinzufügen](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(aufdringlich_ptr < Aspose::Cells::Systems::String > cellName)-Methode. Holen Sie sich den Zellenindex und verwenden Sie ihn [setHinweis](https://reference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) zum Einfügen von Kommentaren. Außerdem kann API alle Kommentare entfernen. Nur wenige der Methoden sind [ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) bis Löscht alle Kommentare in der Designer-Tabelle. Darüber hinaus, [EntfernenBei](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(aufdringlich_ptr< Aspose::Cells::Systems::String > name) Methode, um das Element an einem angegebenen Index oder mit einem angegebenen Namen zu entfernen.

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Hinzufügen von Kommentaren in einer Excel-Datei" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}