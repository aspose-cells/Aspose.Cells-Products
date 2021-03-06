---
title: Wandeln Sie SPREADSHEETML über die Anwendung C++ in SVG um 
url: /de/cpp/conversion/spreadsheetml-to-svg/ 
description: Beispiel-Umwandlungscode C++ für das SPREADSHEETML-Dokument in das SVG-Format. Programmierer können diesen Quellcode für die Batch-Konvertierung von SPREADSHEETML in SVG in jeder C++-Anwendung verwenden.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Wandeln Sie SPREADSHEETML über C++ in SVG um" h2="Leistungsstarke SPREADSHEETML-zu-SVG-Konvertierung mit der C++-Bibliothek ohne die Notwendigkeit einer Installation von Microsoft Excel, OpenOffice oder Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="SPREADSHEETML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie SPREADSHEETML in SVG mit C++" %}}

 Um SPREADSHEETML in SVG zu konvertieren, verwenden wir
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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von SPREADSHEETML in SVG über C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-Entwickler können SPREADSHEETML-Dateien in nur wenigen Codezeilen ganz einfach in SVG konvertieren.

{{% /blocks/products/pf/agp/text %}}

1. Laden Sie die SPREADSHEETML-Datei mit Factory::CreateIWorkbook.1. Wählen Sie das erste Arbeitsblatt aus.1. Legen Sie (SVG)-Optionen fest.1. Durchlaufen Sie jede Blattseite und rendern Sie.1. Öffnen Sie die SVG-Datei in einem kompatiblen Programm.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie vor dem Ausführen des Conversion-Beispielcodes C++ sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit C++ Runtime Environment für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.- Aspose.Cells für C++ DLL, auf die in Ihrem Projekt verwiesen wird.
- Microsoft Windows oder ein kompatibles Betriebssystem mit C++ Runtime Environment für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.- Aspose.Cells für C++ DLL, auf die in Ihrem Projekt verwiesen wird.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Quellcode für die Umwandlung von SPREADSHEETML in SVG C++" offSpacer="" %}}

```cs
// Verzeichnispfad ausgeben.
StringPtr outDir = new String("OutputDirectoryPath");

// Laden Sie das SPREADSHEETML.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.spreadsheetml");

// Greifen Sie auf das erste Arbeitsblatt zu.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Bild- oder Druckoptionsobjekt erstellen.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Geben Sie das Bildformat an.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetSvg());

// Legen Sie die horizontale und vertikale Auflösung fest
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Rendern Sie das Blatt in Bezug auf die angegebenen Bild- oder Druckoptionen.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Seitenzahl erhalten.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Erstellen Sie ein String-Builder-Objekt für String-Verkettungen.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Rendern Sie jede Seite einzeln in ein SVG-Bild.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageSVG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".svg"));

	// Rufen Sie den Ausgabebildpfad ab.
	StringPtr outputSVG = sb->ToString();

	// Konvertieren Sie das Arbeitsblatt in ein SVG-Bild.
	sr->ToImage(i, outputSVG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Live-Demos für die Umwandlung von SPREADSHEETML in SVG" sectionDescription="[Wandeln Sie SPREADSHEETML in SVG um](https://products.aspose.app/cells/conversion/spreadsheetml-to-svg) jetzt, indem Sie unsere Live-Demo-Website besuchen. Die Live-Demo hat die folgenden Vorteile" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API muss nicht heruntergeladen werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es muss kein Code geschrieben werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre SPREADSHEETML-Datei hoch, sie wird sofort in SVG konvertiert." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Sie erhalten den Download-Link." >}}

    {{% blocks/products/pf/agp/content h2="C++ Bibliothek zur Bearbeitung von Excel-Dateien" %}}

 Excel API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SPREADSHEETML" readMoreLink="/{{spreadsheetml_url}}" >}}

{{spreadsheetml}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/page-description-language/svg/" >}}

SVG-Dateien sind skalierbare Vektorgrafiken, die ein XML-basiertes Textformat zur Beschreibung des Erscheinungsbilds von Bildern verwenden. Das Wort Skalierbar bezieht sich darauf, dass das SVG ohne Qualitätsverlust auf verschiedene Größen skaliert werden kann. Die textbasierte Beschreibung solcher Dateien macht sie auflösungsunabhängig. Es ist eines der am häufigsten verwendeten Formate zum Erstellen von Websites und Druckgrafiken, um Skalierbarkeit zu erreichen. Das Format kann allerdings nur für zweidimensionale Grafiken verwendet werden. SVG-Dateien können in fast allen modernen Browsern angezeigt/geöffnet werden, einschließlich Chrome, Internet Explorer, Firefox und Safari.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}