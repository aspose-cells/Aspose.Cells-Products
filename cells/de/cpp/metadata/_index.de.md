---
title: Verwalten Sie Excel-Dateimetadaten über C++
description: Mit der Bibliothek C++ können Sie Metadaten von Excel-Dateien anzeigen, hinzufügen, bearbeiten, entfernen oder extrahieren
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Verwalten Sie Microsoft<sup>&reg;</sup> Excel-Dokumentmetadaten über C++" h2="Anzeigen, Einfügen, Aktualisieren, Entfernen oder Extrahieren benutzerdefinierter und integrierter Excel-Dokumenteigenschaften in C++-Anwendungen." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadaten in Excel – So zeigen Sie Metadaten einer Excel-Datei an, fügen sie ein und entfernen sie.[C++ Excel-Bibliothek](/cells/de/cpp/) Erleichtert wird dies auf einfache Weise durch die Unterstützung der integrierten/systemdefinierten Eigenschaften wie Autorenname, Titel, Dokumentstatistiken usw., die manchmal benötigt werden, um zu überprüfen, wann die Datei zuletzt geändert oder gespeichert wurde, zusammen mit benutzerdefinierten/benutzerdefinierten Eigenschaften in Form von Name/Wert-Paare. Um den Prozess zu automatisieren, unterstützt die Bibliothek die Erstellung und Verwaltung großer Metadaten-Excel-Dateien.[CreateIWorkbook-Methode](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) von[Fabrikklasse](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory)Öffnen Sie eine Arbeitsmappe nach Pfad, Stream und speziellem FileFormatType. Laden Sie die Datei also mit der geeigneten Methode zur weiteren Verarbeitung. Nur wenige der unten aufgeführten Möglichkeiten und Entwickler können ihren Code entsprechend den Anwendungsanforderungen problemlos erweitern.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Integrierte Eigenschaften lesen und aktualisieren" %}}

 Für die Automatisierung der integrierten Eigenschaften sorgt API[GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) Methode, die eine DocumentProperties-Auflistung zurückgibt, die alle integrierten Dokumenteigenschaften der Tabelle darstellt. Nachdem Sie auf alle integrierten Eigenschaften zugegriffen haben, greifen Sie mit entsprechenden Methoden wie GetTitle(), GetSubject() usw. auf die relevanten Eigenschaften zu. Um die Eigenschaften zu aktualisieren, stellt API Methoden wie SetTitle, SetSubject, SetAuthor, SetComments usw. bereit. Sehen Sie sich die an[Integrierte Dokumenteigenschaftensammlung](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) für die gewünschte Funktion.

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Lesen systemdefinierter Eigenschaften" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Aktualisieren integrierter Eigenschaften" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Benutzerdefinierte Eigenschaften anzeigen und hinzufügen" %}}

Für die Handhabung benutzerdefinierter Eigenschaften bietet API[IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) Dadurch wird die gesamte Sammlung benutzerdefinierter Dokumenteigenschaften der Tabelle zurückgegeben. Durch den ersten Zugriff auf die benutzerdefinierten Eigenschaften über diese Methode können Entwickler relevante Methoden verwenden, um Eigenschaften wie AddIDocumentProperty, AddLinkToContentProperty hinzuzufügen und auf ähnliche Weise UpdateLinkedPropertyValue und UpdateLinkedRange verwenden, um benutzerdefinierte Dokumenteigenschaftswerte zu aktualisieren, die jeweils auf den Inhalt und den verknüpften Bereich verweisen. Entwickler können relevante Methoden von verwenden[Sammlung benutzerdefinierter Dokumenteigenschaften](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Anzeigen benutzerdefinierter Eigenschaften" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Code zum Hinzufügen von Metadaten in einer Excel-Datei" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
