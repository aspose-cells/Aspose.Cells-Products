---
title: Metadaten von Excel-Dateien über C++ verwalten
url: /de/cpp/metadata/
description: Anzeigen, Hinzufügen, Bearbeiten, Entfernen oder Extrahieren von Metadaten von Excel-Dateien mithilfe der C++-Bibliothek
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Verwalten Sie Metadaten von Microsoft<sup>&reg;</sup> Excel-Dokumenten über C++" h2="Anzeigen, Einfügen, Aktualisieren, Entfernen oder Extrahieren benutzerdefinierter und integrierter Excel-Dokumenteigenschaften in C++-Anwendungen." >}}
{{% blocks/products/pf/feature-page-summary %}}
Metadaten in Excel - So zeigen Sie Metadaten von Excel-Dateien an, fügen sie ein und entfernen sie. [C++ Excel-Bibliothek](/cells/cpp/) Erleichtert wird dies auf einfache Weise durch die Unterstützung der integrierten / systemdefinierten Eigenschaften wie Autorenname, Titel, Dokumentstatistiken usw., die manchmal benötigt werden, um zu überprüfen, wann die letzte Datei geändert oder gespeichert wurde, zusammen mit benutzerdefinierten / benutzerdefinierten Eigenschaften in Form von Name/Wert-Paare. Um den Prozess zu automatisieren, unterstützt die Bibliothek das Erstellen und Verwalten großer Metadaten-Excel-Dateien. [CreateIWorkbook-Methode](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) von [Fabrikklasse](https://apireference.aspose.com/cells/cpp/class/aspose.cells.factory) Öffnen Sie eine Arbeitsmappe nach Pfad, nach Stream und nach speziellem FileFormatType. Laden Sie also die Datei mit geeigneter Methode zur weiteren Bearbeitung. Nur wenige der unten aufgeführten Möglichkeiten und Entwickler können ihren Code entsprechend den Anwendungsanforderungen leicht erweitern. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Eingebaute Eigenschaften lesen und aktualisieren" %}}

Für die Automatisierung der integrierten Eigenschaften stellt API bereit [GetIBuiltInDocumentProperties()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) -Methode, die eine DocumentProperties-Auflistung zurückgibt, die alle integrierten Dokumenteigenschaften der Tabelle darstellt. Nachdem Sie auf alle integrierten Eigenschaften zugegriffen haben, greifen Sie mit entsprechenden Methoden wie GetTitle(), GetSubject() usw. auf die relevanten Eigenschaften zu. Um die Eigenschaften zu aktualisieren, stellt API Methoden wie SetTitle, SetSubject, SetAuthor, SetComments usw. bereit [eingebaute Sammlung von Dokumenteneigenschaften](https://apireference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) für gewünschte Funktion.

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Lesen systemdefinierter Eigenschaften" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Aktualisieren integrierter Eigenschaften" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Benutzerdefinierte Eigenschaften anzeigen und hinzufügen" %}}

Für die Handhabung benutzerdefinierter Eigenschaften stellt API bereit [IWorkbookMetadata::GetICustomDocumentProperties](https://apireference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) die alle benutzerdefinierten Dokumenteigenschaften der Tabelle zurückgibt. Beim ersten Zugriff auf die benutzerdefinierten Eigenschaften über diese Methode können Entwickler relevante Methoden verwenden, um Eigenschaften wie AddIDocumentProperty, AddLinkToContentProperty hinzuzufügen, und in ähnlicher Weise UpdateLinkedPropertyValue, UpdateLinkedRange verwenden, um den benutzerdefinierten Dokumenteigenschaftswert zu aktualisieren, der mit dem Inhalt bzw. dem verknüpften Bereich verknüpft ist. Entwickler können die entsprechende Methode von verwenden [Sammlung benutzerdefinierter Dokumenteigenschaften](https://apireference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Anzeigen benutzerdefinierter Eigenschaften" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Code zum Hinzufügen von Metadaten in Excel-Datei" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}