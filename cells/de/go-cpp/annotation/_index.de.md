---
title: Hinzufügen oder Entfernen von Excel-Datei-Anmerkungen mit Go via C++
description: Mit Go über die Bibliothek C++ können Sie Datenkommentare in Excel- und OpenOffice-Tabellenkalkulationen hinzufügen oder entfernen.
keywords: [Go via C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Verwalten Sie die Anmerkungen in der Excel-Datei Microsoft<sup>&reg;</sup> mit Go über C++" h2="Fügen Sie über Anwendungen mit der C++ einfache Notizen für Anmerkungen oder Kommentare in Go hinzu oder entfernen Sie diese." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Gehen Sie über C++ Excel API](/cells/de/go-cpp/) bietet Unterstützung für die Verwaltung von Annotationen auf Zellebene durch Hinzufügen, Zugreifen und Entfernen von Kommentaren. API bietet[Kommentar](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/) Und[Kommentarsammlung](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/)sowie[GetComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/getcomments/) Zur Bearbeitung von Kommentaren in allen Bereichen. Unterstützte Excel-Formate sind unter anderem ODS, XLS, XLSX, XLSB und XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Datenanmerkungen in Excel-Dateien" %}}
 Kommentare in Arbeitsblättern bearbeiten – In MS Excel ist die Anzahl der Kommentare pro Arbeitsblatt nicht begrenzt. Sie können beliebig viele Kommentare hinzufügen, je nach Bedarf. Der Vorgang zum Einfügen von Kommentaren ist wie folgt: Erstellen Sie ein Arbeitsblatt.[Arbeitsmappe](https://reference.aspose.com/cells/go-cpp/aspose.cells/workbook/) Laden Sie ein Klassenobjekt, um eine vorhandene Datei zu laden und das Arbeitsblatt auszuwählen, dem Sie einen Kommentar hinzufügen möchten. Rufen Sie alle Kommentare mit `getComments()` ab. Fügen Sie den Kommentar hinzu.[Add(const char16_t* cellName)](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/add/) Methode. Ermitteln Sie den Zellenindex und verwenden Sie ihn.[SetNote](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/setnote/) zum Einfügen von Kommentaren. Darüber hinaus kann API alle Kommentare entfernen. Einige der Methoden sind:[ClearComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/clearcomments/) Löscht alle Kommentare in der Designer-Tabelle.***Entfernen bei*** Methode zum Entfernen des Elements an einem bestimmten Index oder mit einem bestimmten Namen.

{{% blocks/products/pf/feature-page-code h3="Gehen Sie über den Code C++ zum Hinzufügen von Kommentaren in der Excel-Datei." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-comment-in-excel.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
