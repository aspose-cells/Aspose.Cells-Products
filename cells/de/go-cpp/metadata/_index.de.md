---
title: Verwalten Sie Excel-Datei-Metadaten mit Go über C++
description: Metadaten von Excel-Dateien mit Go über die Bibliothek C++ anzeigen, hinzufügen, bearbeiten, entfernen oder extrahieren
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Verwalten Sie die Metadaten des Excel-Dokuments Microsoft<sup>&reg;</sup> über Go über C++" h2="Benutzerdefinierte und integrierte Excel-Dokumenteigenschaften in C++-Anwendungen anzeigen, einfügen, aktualisieren, entfernen oder extrahieren." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadaten in Excel – So zeigen Sie Metadaten in Excel-Dateien an, fügen sie ein und entfernen sie.[Gehen Sie über die C++ Excel-Bibliothek](/cells/de/go-cpp/)Die Bibliothek vereinfacht die Arbeit, indem sie die integrierten/systemdefinierten Eigenschaften wie Autorenname, Titel, Dokumentstatistiken usw. unterstützt, die beispielsweise benötigt werden, um zu prüfen, wann eine Datei zuletzt geändert oder gespeichert wurde. Zusätzlich werden benutzerdefinierte Eigenschaften in Form von Name-Wert-Paaren unterstützt. Um den Prozess zu automatisieren, ermöglicht die Bibliothek das Erstellen und Verwalten großer Metadaten-Excel-Dateien.[Arbeitsmappe](https://reference.aspose.com/cells/go-cpp/workbook/) Diese Klasse öffnet eine Arbeitsmappe über Pfad, Datenstrom oder einen speziellen Dateityp. Laden Sie die Datei anschließend mit der entsprechenden Methode zur Weiterverarbeitung. Einige der Möglichkeiten sind unten aufgeführt; Entwickler können ihren Code leicht an die Anwendungsanforderungen anpassen.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Eingebaute Eigenschaften lesen und aktualisieren" %}}

 Zur Automatisierung der integrierten Eigenschaften bietet API Folgendes:[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Die Methode gibt eine DocumentProperties-Sammlung zurück, die alle integrierten Dokumenteigenschaften der Tabelle repräsentiert. Nach dem Zugriff auf alle integrierten Eigenschaften können Sie die relevanten Eigenschaften mit entsprechenden Methoden wie GetTitle(), GetSubject() usw. aufrufen. Zum Aktualisieren der Eigenschaften bietet API Methoden wie SetTitle, SetSubject, SetAuthor, SetComments usw. an.[integrierte Dokumenteneigenschaftensammlung](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) für die erforderliche Funktion.

{{% blocks/products/pf/feature-page-code h3="Gehen Sie über den Code C++ zum Lesen der systemdefinierten Eigenschaften." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Gehen Sie über den Code C++ zur Aktualisierung der integrierten Eigenschaften." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Benutzerdefinierte Eigenschaften anzeigen und hinzufügen" %}}

 Für die Bearbeitung benutzerdefinierter Eigenschaften bietet API[Workbook::GetCustomDocumentProperties](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)Diese Methode gibt die gesamte Sammlung benutzerdefinierter Dokumenteigenschaften der Tabelle zurück. Entwickler können über diese Methode auf die benutzerdefinierten Eigenschaften zugreifen und anschließend entsprechende Methoden wie `AddIDocumentProperty` und `AddLinkToContentProperty` verwenden, um Eigenschaften hinzuzufügen. Analog dazu können sie mit `UpdateLinkedPropertyValue` und `UpdateLinkedRange` den Wert einer benutzerdefinierten Dokumenteigenschaft aktualisieren, die auf den Inhalt bzw. den verknüpften Bereich verweist.[Sammlung benutzerdefinierter Dokumenteigenschaften](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Gehen Sie über den Code C++ zu den benutzerdefinierten Eigenschaften." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Gehen Sie über den Code C++ zum Hinzufügen von Metadaten in einer Excel-Datei." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}