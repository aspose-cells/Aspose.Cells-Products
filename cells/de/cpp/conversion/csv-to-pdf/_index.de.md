---
title: Konvertieren Sie CSV in PDF über die Anwendung C++ 
weight: 8330
url: /de/cpp/conversion/csv-to-pdf/ 
description: Beispiel-Umwandlungscode C++ für ein CSV-Dokument in das PDF-Format. Programmierer können diesen Quellcode für die Batch-Konvertierung von CSV in PDF in jeder C++-Anwendung verwenden.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie CSV in PDF über C++" h2="Leistungsstarke CSV-zu-PDF-Konvertierung mit der C++-Bibliothek ohne die Notwendigkeit einer Installation von Microsoft Excel, OpenOffice oder Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie CSV in PDF mit C++" %}}

 Um CSV in PDF zu konvertieren, verwenden wir
 [Aspose.Cells für C++](https://products.aspose.com/cells/cpp) 
 API, eine funktionsreiche, leistungsstarke und benutzerfreundliche Dokumentbearbeitungs- und Konvertierungs-API für die C++-Plattform. Sie können die neueste Version direkt herunterladen, einfach öffnen
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 Paketmanager, suche nach
 Aspose.Cells.Cpp 
 und installieren. Sie können auch den folgenden Befehl in der Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Befehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von CSV in PDF über C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-Entwickler können CSV-Dateien in nur wenigen Codezeilen ganz einfach in PDF konvertieren.

{{% /blocks/products/pf/agp/text %}}

1. Laden Sie die CSV-Datei mit Factory::CreateIWorkbook.1. Rufen Sie die Save()-Methode auf.1. Übergeben Sie den Ausgabedateipfad mit der Dateierweiterung (PDF).1. Die PDF-Datei wird unter dem angegebenen Pfad gespeichert.1. Öffnen Sie die PDF-Datei in einem kompatiblen Programm.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie vor dem Ausführen des Conversion-Beispielcodes C++ sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit C++ Runtime Environment für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.- Aspose.Cells für C++ DLL, auf die in Ihrem Projekt verwiesen wird.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="CSV-zu-PDF-C++-Konvertierungsquellcode" offSpacer="" %}}

```cs
// Laden Sie die CSV-Datei.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.csv");

// Im PDF-Format speichern.
wkb->Save(u"convertedFile.pdf", SaveFormat_Pdf);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="CSV-zu-PDF-Konvertierung Live-Demos" sectionDescription="[Konvertieren Sie CSV in PDF](https://products.aspose.app/cells/conversion/csv-to-pdf) jetzt, indem Sie unsere Live-Demo-Website besuchen. Die Live-Demo hat die folgenden Vorteile" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API muss nicht heruntergeladen werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es muss kein Code geschrieben werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre CSV-Datei hoch, sie wird sofort in PDF konvertiert." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Sie erhalten den Download-Link." >}}

    {{% blocks/products/pf/agp/content h2="C++ Bibliothek zur Bearbeitung von Excel-Dateien" %}}

 Excel API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

Dateien mit der Erweiterung CSV (Comma Separated Values) stellen reine Textdateien dar, die Datensätze mit kommagetrennten Werten enthalten. Jede Zeile in einer CSV-Datei ist ein neuer Datensatz aus der Gruppe von Datensätzen, die in der Datei enthalten sind. Solche Dateien werden erzeugt, wenn eine Datenübertragung von einem Speichersystem zu einem anderen beabsichtigt ist. Da alle Anwendungen durch Komma getrennte Datensätze erkennen können, erfolgt der Import solcher Datendateien in die Datenbank sehr bequem. Fast alle Tabellenkalkulationsanwendungen wie Microsoft Excel oder OpenOffice Calc können CSV ohne großen Aufwand importieren. Aus solchen Dateien importierte Daten werden in Zellen einer Tabellenkalkulation zur Darstellung für den Benutzer angeordnet.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er Jahren erstellt wurde. Der Zweck dieses Dateiformats bestand darin, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware und Betriebssystem ist. PDF-Dateien können in Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox über Erweiterungen/Plug-Ins geöffnet werden. Die meisten im Handel erhältlichen Softwarepakete bieten auch die Konvertierung ihrer Dokumente in das PDF-Dateiformat an, ohne dass zusätzliche Softwarekomponenten erforderlich sind. Daher kann das PDF-Dateiformat Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich Media, digitale Signaturen, Anhänge, Metadaten, Geodaten und 3D-Objekte enthalten, die Teil des Quelldokuments werden können.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können CSV auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-bmp/" name="CSV ZU BMP" description="Bitmap-Bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-dif/" name="CSV ZU DIF" description="Datenaustauschformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-emf/" name="CSV ZU EMF" description="Verbessertes Metafile-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-gif/" name="CSV ZU GIF" description="Grafisches Austauschformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-html/" name="CSV-IN-HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-jpeg/" name="CSV ZU JPEG" description="JPEG-Bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-mhtml/" name="CSV ZU MHTML" description="Archivformat für Webseiten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-ods/" name="CSV ZU ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-png/" name="CSV ZU PNG" description="Portable Netzwerkgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-svg/" name="CSV ZU SVG" description="Skalierbare Vektorgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tiff/" name="CSV ZU TIFF" description="Markiertes Bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tsv/" name="CSV ZU TSV" description="Tabulatorgetrennte Werte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xls/" name="CSV ZU XLS" description="Excel-Binärformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsb/" name="CSV ZU XLSB" description="Binäre Excel-Arbeitsmappendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsm/" name="CSV ZU XLSM" description="Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsx/" name="CSV ZU XLSX" description="OOXML-Excel-Datei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltm/" name="CSV ZU XLTM" description="Makrofähige Excel-Vorlage" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltx/" name="CSV ZU XLTX" description="Office OpenXML-Excel-Vorlage" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xps/" name="CSV ZU XPS" description="XML-Papierspezifikationen" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}