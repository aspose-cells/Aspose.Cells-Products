---
title: Verwalten Sie Metadaten von Excel-Dateien über .NET C#
url: /de/net/metadata/
description: Metadaten von Excel-Dateien mit nur wenigen C#-Codezeilen anzeigen, hinzufügen, bearbeiten, entfernen oder extrahieren
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Metadaten von Microsoft<sup>&reg;</sup> Excel-Dateien über .NET verwalten" h2="Anzeigen, Hinzufügen, Aktualisieren, Entfernen oder Extrahieren integrierter und benutzerdefinierter Excel-Dateieigenschaften mithilfe serverseitiger .NET-APIs." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) unterstützt die Verwaltung systemdefinierter (integrierter) Eigenschaften wie Titel, Autorenname, Dokumentstatistiken usw. sowie benutzerdefinierter (benutzerdefinierter) Eigenschaften in Form von Name-Wert-Paaren. Es gibt [Klasse Arbeitsbuch](https://apireference.aspose.com/cells/net/aspose.cells/workbook) um die Dateien zu laden, und [Arbeitsblattsammlung](https://apireference.aspose.com/cells/net/aspose.cells/worksheetcollection) befasst sich mit der Sammlung von Arbeitsblättern sowie [Klasse Arbeitsblatt](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) zur Darstellung eines einzelnen Arbeitsblatts. Zusammen mit diesen Klassen machen BuiltInDocumentProperties, CustomDocumentProperties den Prozess für die Metadatenverwaltung einfach. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Integrierte Eigenschaften verwalten" %}}

Für die Verwaltung systemdefinierter Eigenschaften stellt API bereit [BuiltInDocumentProperties](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties), und Programmierer können einfach auf eine integrierte Eigenschaft zugreifen und ihren Wert aktualisieren. Je nach Anwendungsanforderung können Entwickler den Index- oder Eigenschaftsnamen aus der verwenden [DocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Code zum Verwalten integrierter Eigenschaften" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Verwalten benutzerdefinierter Eigenschaften" %}}

Für die Verwaltung benutzerdefinierter Eigenschaften bietet API [CustomDocumentProperties](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties), und Entwickler können problemlos auf bereits hinzugefügte Eigenschaften zugreifen und neue Eigenschaften hinzufügen. Um benutzerdefinierte Eigenschaften hinzuzufügen, [Methode hinzufügen](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) von [CustomDocumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) Die Klasse fügt die Eigenschaft hinzu und gibt eine Referenz für die neue Eigenschaft als zurück [Properties.DocumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty) Objekt. Die DocumentProperty-Klasse wird verwendet, um den Namen, den Wert und den Typ der Dokumenteigenschaft als abzurufen [Dokumenteigenschaft.Name](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://apireference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) das gibt eines der zurück [Art der Immobilie](https://apireference.aspose.com/cells/net/aspose.cells.properties/propertytype) Aufzählungswerte. 
 
{{% blocks/products/pf/feature-page-code h3="C# Code zum Hinzufügen von Metadaten in Excel-Datei" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Code zum Entfernen benutzerdefinierter Eigenschaften in Excel-Datei" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
