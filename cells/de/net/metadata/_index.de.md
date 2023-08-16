---
title: Excel-Dateimetadaten verwalten via .NET C#
description: Mit nur wenigen Zeilen C#-Code können Sie Metadaten von Excel-Dateien anzeigen, hinzufügen, bearbeiten, entfernen oder extrahieren
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Verwalten Sie Microsoft<sup>&reg;</sup> Excel-Datei-Metadaten via .NET" h2="Anzeigen, Hinzufügen, Aktualisieren, Entfernen oder Extrahieren integrierter und benutzerdefinierter Excel-Dateieigenschaften mithilfe serverseitiger .NET-APIs." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/de/net/) unterstützt die Verwaltung systemdefinierter (integrierter) Eigenschaften wie Titel, Autorenname, Dokumentstatistiken usw. sowie benutzerdefinierter (benutzerdefinierter) Eigenschaften in Form von Name-Wert-Paaren. Es gibt[Arbeitsbuchklasse](https://reference.aspose.com/cells/net/aspose.cells/workbook) um die Dateien zu laden, und[WorksheetCollection](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection)befasst sich mit der Sammlung von Arbeitsblättern sowie[Arbeitsblattklasse](https://reference.aspose.com/cells/net/aspose.cells/worksheet) zur Darstellung eines einzelnen Arbeitsblattes. Zusammen mit diesen Klassen, BuiltInDocumentProperties, vereinfacht CustomDocumentProperties den Prozess für die Metadatenverwaltung.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Integrierte Eigenschaften verwalten" %}}

 Für die Verwaltung systemdefinierter Eigenschaften bietet API[BuiltInDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) und Programmierer können problemlos auf eine integrierte Eigenschaft zugreifen und deren Wert aktualisieren. Je nach Anwendungsanforderung können Entwickler den Index- oder Eigenschaftsnamen aus dem verwenden[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Code zum Verwalten integrierter Eigenschaften" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Benutzerdefinierte Eigenschaften verwalten" %}}

 Für die Verwaltung benutzerdefinierter Eigenschaften bietet API[CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) und Entwickler können problemlos auf bereits hinzugefügte Eigenschaften zugreifen und neue Eigenschaften hinzufügen. Um benutzerdefinierte Eigenschaften hinzuzufügen,[Methode hinzufügen](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) von[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) Die Klasse fügt die Eigenschaft hinzu und gibt eine Referenz für die neue Eigenschaft als zurück[Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty)Objekt. Die DocumentProperty-Klasse wird verwendet, um den Namen, den Wert und den Typ der Dokumenteigenschaft abzurufen[DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) das gibt einen der zurück[Art der Immobilie](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) Aufzählungswerte.
 
{{% blocks/products/pf/feature-page-code h3="C# Code zum Hinzufügen von Metadaten in einer Excel-Datei" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Code zum Entfernen benutzerdefinierter Eigenschaften in Excel-Datei" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
