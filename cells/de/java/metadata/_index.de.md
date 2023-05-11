---
title: Excel-Dateimetadaten verwalten via Java
description: Mit nur wenigen Zeilen Java-Code können Sie Metadaten von Excel-Dateien anzeigen, hinzufügen, bearbeiten, entfernen oder extrahieren
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Verwalten Sie Microsoft<sup>&reg;</sup> Excel-Datei-Metadaten via Java" h2="Mithilfe serverseitiger Java-APIs können Sie benutzerdefinierte und integrierte Excel-Dateieigenschaften anzeigen, hinzufügen, aktualisieren, löschen oder extrahieren." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/de/java/) unterstützt die Verwaltung integrierter (systemdefinierter) Eigenschaften wie Titel, Autorenname, Dokumentstatistiken usw. sowie benutzerdefinierter (benutzerdefinierter) Eigenschaften in Form von Name/Wert-Paaren. Es gibt[Arbeitsbuchklasse](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) um die Dateien zu laden, und[WorksheetCollection](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) befasst sich mit der Sammlung von Arbeitsblättern sowie[Arbeitsblattklasse](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) zur Darstellung eines einzelnen Arbeitsblattes. Für den Zugriff auf integrierte und benutzerdefinierte Eigenschaften, BuiltInDocumentProperties, vereinfacht CustomDocumentProperties den Prozess für die Metadatenverwaltung.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Verwalten systemdefinierter Eigenschaften" %}}

 Für die Verwaltung integrierter Eigenschaften bietet API[BuiltInDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) und Programmierer können problemlos auf eine integrierte Eigenschaft zugreifen und deren Wert aktualisieren. Je nach Anwendungsanforderung können Entwickler den Index- oder Eigenschaftsnamen aus dem verwenden[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Code zum Verwalten systemdefinierter Eigenschaften" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Benutzerdefinierte Metadaten hinzufügen und entfernen" %}}

Für die Handhabung benutzerdefinierter Eigenschaften bietet API[CustomDocumentProperties](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) und Entwickler können problemlos auf vorhandene Eigenschaften zugreifen und neue Eigenschaften hinzufügen[Methode hinzufügen](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) von[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) Die Klasse fügt die Eigenschaft hinzu und gibt eine Referenz für die neue Eigenschaft als zurück[Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) Objekt. Die DocumentProperty-Klasse wird verwendet, um den Namen, den Wert und den Typ der Dokumenteigenschaft abzurufen[DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) das gibt einen der zurück[Art der Immobilie](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) Aufzählungswerte.
 
{{% blocks/products/pf/feature-page-code h3="Java Code zum Hinzufügen von Metadaten in einer Excel-Datei" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Code zum Löschen einer benutzerdefinierten Eigenschaft in einer Excel-Datei" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
