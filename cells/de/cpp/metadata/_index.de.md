---
title: Verwalten Sie Excel-Dateimetadaten über C++
description: Mit der Bibliothek C++ können Sie Metadaten von Excel-Dateien anzeigen, hinzufügen, bearbeiten, entfernen oder extrahieren
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Verwalten Sie Microsoft<sup>&reg;</sup> Excel-Dokumentmetadaten über C++" h2="Anzeigen, Einfügen, Aktualisieren, Entfernen oder Extrahieren benutzerdefinierter und integrierter Excel-Dokumenteigenschaften in C++-Anwendungen." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadaten in Excel – So zeigen Sie Metadaten einer Excel-Datei an, fügen sie ein und entfernen sie.[C++ Excel-Bibliothek](/cells/de/cpp/) Erleichtert wird dies auf einfache Weise durch die Unterstützung der integrierten/systemdefinierten Eigenschaften wie Autorenname, Titel, Dokumentstatistiken usw., die manchmal benötigt werden, um zu überprüfen, wann die Datei zuletzt geändert oder gespeichert wurde, zusammen mit benutzerdefinierten/benutzerdefinierten Eigenschaften in Form von Name/Wert-Paare. Um den Prozess zu automatisieren, unterstützt die Bibliothek die Erstellung und Verwaltung großer Metadaten-Excel-Dateien.[Arbeitsmappe](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)Klasse Öffnet eine Arbeitsmappe nach Pfad, Stream und speziellem FileFormatType. Laden Sie die Datei also mit der geeigneten Methode zur weiteren Verarbeitung. Nur wenige der unten aufgeführten Möglichkeiten und Entwickler können ihren Code entsprechend den Anwendungsanforderungen problemlos erweitern.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Integrierte Eigenschaften lesen und aktualisieren" %}}

 Für die Automatisierung der integrierten Eigenschaften sorgt API[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) Methode, die eine DocumentProperties-Auflistung zurückgibt, die alle integrierten Dokumenteigenschaften der Tabelle darstellt. Nachdem Sie auf alle integrierten Eigenschaften zugegriffen haben, greifen Sie mit entsprechenden Methoden wie GetTitle(), GetSubject() usw. auf die relevanten Eigenschaften zu. Um die Eigenschaften zu aktualisieren, stellt API Methoden wie SetTitle, SetSubject, SetAuthor, SetComments usw. bereit. Sehen Sie sich die an[Integrierte Dokumenteigenschaftensammlung](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) für die gewünschte Funktion.

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Lesen systemdefinierter Eigenschaften" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Aktualisieren integrierter Eigenschaften" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Benutzerdefinierte Eigenschaften anzeigen und hinzufügen" %}}

Für die Handhabung benutzerdefinierter Eigenschaften bietet API[Arbeitsmappe::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) Dadurch wird die gesamte Sammlung benutzerdefinierter Dokumenteigenschaften der Tabelle zurückgegeben. Durch den ersten Zugriff auf die benutzerdefinierten Eigenschaften über diese Methode können Entwickler relevante Methoden verwenden, um Eigenschaften wie AddIDocumentProperty, AddLinkToContentProperty hinzuzufügen und auf ähnliche Weise UpdateLinkedPropertyValue und UpdateLinkedRange verwenden, um benutzerdefinierte Dokumenteigenschaftswerte zu aktualisieren, die jeweils auf den Inhalt und den verknüpften Bereich verweisen. Entwickler können relevante Methoden von verwenden[Sammlung benutzerdefinierter Dokumenteigenschaften](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Code zum Anzeigen benutzerdefinierter Eigenschaften" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Code zum Hinzufügen von Metadaten in einer Excel-Datei" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
