---
title:  Bearbeiten oder Anzeigen von XLS-Dokumentmetadaten über C++
weight: 2150
description: C++ Beispielcode zum Bearbeiten oder Anzeigen von XLS-Dateimetadaten in der C++-Laufzeitumgebung für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.
keywords: [C++ Aspose.Cells., C++ view xls metadata., C++ add xls metadata., C++ insert xls metadata., C++ edit xls metadata., C++ remove xls metadata., C++ extract xls metadata., C++ modify xls metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Extrahieren Sie XLS-Metadaten über C++" h2="Erstellen Sie Ihre eigenen C++-Apps, um mithilfe serverseitiger APIs Metadaten aus XLS-Dateien hinzuzufügen, zu bearbeiten, zu entfernen oder zu extrahieren." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So erhalten Sie XLS-Metadaten mit C++" %}}

Um XLS-Metadaten zu extrahieren, verwenden wir
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API, eine funktionsreiche, leistungsstarke und benutzerfreundliche Plattform zur Extraktion von Dokumentmetadaten. Sie können die neueste Version direkt herunterladen, indem Sie sie einfach öffnen
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 Paketmanager, suchen Sie nach
 **Aspose.Cells.Cpp** 
 und installieren. Sie können auch den folgenden Befehl über die Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Befehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Extrahieren von Metadaten von XLS über C++" %}}

{{% blocks/products/pf/agp/text %}}

 Greifen Sie auf nützliche Informationen zu, die in der Datei XLS gespeichert sind, einschließlich wann die Datei XLS empfangen, verarbeitet, mit einem Zeitstempel versehen usw. wurde.

{{% /blocks/products/pf/agp/text %}}

+ Erstellen Sie Optionen mit MetadataOptions
+ Laden Sie die Datei XLS mit WorkbookMetadata
+ Fügen Sie neue Eigenschaften durch GetCustomDocumentProperties() und Add hinzu
+ Dokument XLS speichern

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ unterstützt auf allen wichtigen Plattformen und Betriebssystemen. Bitte stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows oder ein kompatibles Betriebssystem mit C++ Laufzeitumgebung für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.
-  Fügen Sie in Ihrem Projekt einen Verweis auf die DLL Aspose.Cells for C++ hinzu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extrahieren Sie Metadaten von XLS - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

//Load the sample excel file
MetadataOptions options(MetadataType::Document_Properties);
WorkbookMetadata meta(u"c:\\book1.xls", options);
//Add a new custom property
meta.GetCustomDocumentProperties().Add(u"test", u"test");
//Save the output excel file
meta.Save(u"c:\\book2.xls"); 

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Über Aspose.Cells for C++ API" %}}

 Aspose.Cells API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extrahieren Sie Metadaten von XLS über die Online-App" sectionDescription=" Anzeigen und Bearbeiten von Metadaten zu XLS-Dokumenten mithilfe unseres[Live-Demos](https://products.aspose.app/cells/metadata) mit folgenden Vorteilen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Sie müssen nichts herunterladen oder einrichten" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es ist nicht nötig, Code zu schreiben" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre XLS-Datei hoch und bearbeiten Sie die Dokumenteigenschaften" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Erhalten Sie sofort den Download-Link für die resultierende Datei" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Dateien mit der Erweiterung XLS repräsentieren das Excel-Binärdateiformat. Solche Dateien können mit Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Die von Excel gespeicherte Datei wird als Arbeitsmappe bezeichnet, wobei jede Arbeitsmappe ein oder mehrere Arbeitsblätter enthalten kann. Daten werden im Tabellenformat im Arbeitsblatt gespeichert und den Benutzern angezeigt und können numerische Werte, Textdaten, Formeln, externe Datenverbindungen, Bilder und Diagramme umfassen. Mit Anwendungen wie Microsoft Excel können Sie Arbeitsmappendaten in verschiedene Formate exportieren, darunter PDF, CSV, XLSX, TXT, HTML, XPS und mehrere andere. Das Dateiformat XLS wurde mit der Veröffentlichung von Microsoft Excel 2007 durch ein offeneres und strukturierteres Format, XLSX, ersetzt. Die neuesten Versionen unterstützen weiterhin das Erstellen und Lesen von XLS-Dateien, obwohl XLSX jetzt die erste Wahl ist.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Metadatenformate" subTitle="Mit C++ kann man auch Metadaten vieler anderer Formate bearbeiten, darunter" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/ods/" name="ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="Binäre Excel-Arbeitsmappendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsm/" name="XLSM" description="Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsx/" name="XLSX" description="OOXML-Excel-Datei" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
