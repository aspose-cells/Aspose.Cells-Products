---
title: Metadaten von Excel-Dateien über Java verwalten
url: /de/java/metadata/
description: Metadaten von Excel-Dateien mit nur wenigen Java-Codezeilen anzeigen, hinzufügen, bearbeiten, entfernen oder extrahieren
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Metadaten von Microsoft<sup>&reg;</sup> Excel-Dateien über Java verwalten" h2="Anzeigen, Hinzufügen, Aktualisieren, Löschen oder Extrahieren benutzerdefinierter und integrierter Excel-Dateieigenschaften mithilfe serverseitiger Java-APIs." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) unterstützt die Verwaltung von integrierten (systemdefinierten) Eigenschaften wie Titel, Autorenname, Dokumentstatistiken usw. sowie von benutzerdefinierten (benutzerdefinierten) Eigenschaften in Form von Name/Wert-Paaren. Es gibt [Klasse Arbeitsbuch](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) um die Dateien zu laden, und [Arbeitsblattsammlung](https://apireference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) befasst sich mit der Sammlung von Arbeitsblättern sowie [Klasse Arbeitsblatt](https://apireference.aspose.com/cells/java/com.aspose.cells/Worksheet) zur Darstellung eines einzelnen Arbeitsblatts. Für den Zugriff auf integrierte und benutzerdefinierte Eigenschaften vereinfachen BuiltInDocumentProperties, CustomDocumentProperties den Prozess für die Metadatenverwaltung. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Verwalten von systemdefinierten Eigenschaften" %}}

Für die Verwaltung integrierter Eigenschaften bietet API [BuiltInDocumentProperties](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties), und Programmierer können einfach auf eine integrierte Eigenschaft zugreifen und ihren Wert aktualisieren. Je nach Anwendungsanforderung können Entwickler den Index- oder Eigenschaftsnamen aus der verwenden [DocumentPropertyCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Code zum Verwalten systemdefinierter Eigenschaften" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Hinzufügen und Entfernen von benutzerdefinierten Metadaten" %}}

Für die Handhabung benutzerdefinierter Eigenschaften stellt API bereit [CustomDocumentProperties](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties), und Entwickler können problemlos auf vorhandene Eigenschaften zugreifen und neue Eigenschaften hinzufügen [Methode hinzufügen](https://apireference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean)) von [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) Die Klasse fügt die Eigenschaft hinzu und gibt eine Referenz für die neue Eigenschaft als zurück [Properties.DocumentProperty](https://apireference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) Objekt. Die DocumentProperty-Klasse wird verwendet, um den Namen, den Wert und den Typ der Dokumenteigenschaft als abzurufen [Dokumenteigenschaft.Name](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://apireference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) das gibt eines der zurück [Art der Immobilie](https://apireference.aspose.com/cells/java/com.aspose.cells/PropertyType) Aufzählungswerte. 
 
{{% blocks/products/pf/feature-page-code h3="Java Code zum Hinzufügen von Metadaten in Excel-Datei" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Code zum Löschen einer benutzerdefinierten Eigenschaft in einer Excel-Datei" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
