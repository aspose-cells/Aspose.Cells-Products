---
title: Konvertieren Sie XLS in GIF über die Anwendung C++ 
weight: 8820
url: /de/cpp/conversion/xls-to-gif/ 
description: Beispiel-Umwandlungscode C++ für das XLS-Dokument in das GIF-Format. Programmierer können diesen Quellcode für die Batch-Konvertierung von XLS in GIF in jeder C++-Anwendung verwenden.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie XLS in GIF über C++" h2="Leistungsstarke XLS-zu-GIF-Konvertierung mit der C++-Bibliothek ohne die Notwendigkeit einer Installation von Microsoft Excel, OpenOffice oder Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie XLS in GIF mit C++" %}}

 Um XLS in GIF zu konvertieren, verwenden wir
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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von XLS in GIF über C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++-Entwickler können XLS-Dateien in nur wenigen Codezeilen ganz einfach in GIF konvertieren.

{{% /blocks/products/pf/agp/text %}}

1. Laden Sie die XLS-Datei mit Factory::CreateIWorkbook.1. Wählen Sie das erste Arbeitsblatt aus.1. Legen Sie (GIF)-Optionen fest.1. Durchlaufen Sie jede Blattseite und rendern Sie.1. Öffnen Sie die GIF-Datei in einem kompatiblen Programm.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie vor dem Ausführen des Conversion-Beispielcodes C++ sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit C++ Runtime Environment für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.- Aspose.Cells für C++ DLL, auf die in Ihrem Projekt verwiesen wird.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS-zu-GIF-C++-Konvertierungsquellcode" offSpacer="" %}}

```cs
// Verzeichnispfad ausgeben.
StringPtr outDir = new String("OutputDirectoryPath");

// Laden Sie das XLS.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.xls");

// Greifen Sie auf das erste Arbeitsblatt zu.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Bild- oder Druckoptionsobjekt erstellen.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Geben Sie das Bildformat an.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetGif());

// Legen Sie die horizontale und vertikale Auflösung fest
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Rendern Sie das Blatt in Bezug auf die angegebenen Bild- oder Druckoptionen.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Seitenzahl erhalten.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Erstellen Sie ein String-Builder-Objekt für String-Verkettungen.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Rendern Sie jede Seite einzeln in ein GIF-Bild.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageGIF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".gif"));

	// Rufen Sie den Ausgabebildpfad ab.
	StringPtr outputGIF = sb->ToString();

	// Konvertieren Sie das Arbeitsblatt in ein GIF-Bild.
	sr->ToImage(i, outputGIF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLS-zu-GIF-Konvertierung Live-Demos" sectionDescription="[Konvertieren Sie XLS in GIF](https://products.aspose.app/cells/conversion/xls-to-gif) jetzt, indem Sie unsere Live-Demo-Website besuchen. Die Live-Demo hat die folgenden Vorteile" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API muss nicht heruntergeladen werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es muss kein Code geschrieben werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre XLS-Datei hoch, sie wird sofort in GIF konvertiert." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Sie erhalten den Download-Link." >}}

    {{% blocks/products/pf/agp/content h2="C++ Bibliothek zur Bearbeitung von Excel-Dateien" %}}

 Excel API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

Dateien mit der Erweiterung XLS stellen das Excel-Binärdateiformat dar. Solche Dateien können von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Von Excel gespeicherte Dateien werden als Arbeitsmappe bezeichnet, wobei jede Arbeitsmappe ein oder mehrere Arbeitsblätter enthalten kann. Daten werden gespeichert und Benutzern im Tabellenformat im Arbeitsblatt angezeigt und können numerische Werte, Textdaten, Formeln, externe Datenverbindungen, Bilder und Diagramme umfassen. Mit Anwendungen wie Microsoft Excel können Sie Arbeitsmappendaten in verschiedene Formate exportieren, darunter PDF, CSV, XLSX, TXT, HTML, XPS und einige andere. Das XLS-Dateiformat wurde mit der Veröffentlichung von Microsoft Excel 2007 durch ein offeneres und strukturierteres Format, XLSX, ersetzt. Die neuesten Versionen bieten weiterhin Unterstützung für das Erstellen und Lesen von XLS-Dateien, obwohl XLSX jetzt die erste Wahl ist.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

Ein GIF oder Graphical Interchange Format ist eine Art stark komprimiertes Bild. GIF gehört Unisys und verwendet den LZW-Komprimierungsalgorithmus, der die Bildqualität nicht beeinträchtigt. Für jedes Bild sind in GIF normalerweise bis zu 8 Bit pro Pixel und bis zu 256 Farben im gesamten Bild zulässig. Im Gegensatz zu einem JPEG-Bild, das bis zu 16 Millionen Farben darstellen kann und ziemlich an die Grenzen des menschlichen Auges stößt. Als das Internet aufkam, blieben GIFs die beste Wahl, da sie eine geringe Bandbreite erforderten und für die Grafiken kompatibel waren, die Volltonbereiche verbrauchen. Ein animiertes GIF kombiniert zahlreiche Bilder oder Frames in einer einzigen Datei und zeigt sie in einer Sequenz an, um einen animierten Clip oder ein kurzes Video zu erstellen. Die Farbbeschränkungen betragen bis zu 256 für jedes Bild und sind wahrscheinlich am wenigsten geeignet, um andere Bilder und Fotos mit Farbverlauf zu reproduzieren.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können XLS auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-bmp/" name="XLS ZU BMP" description="Bitmap-Bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-csv/" name="XLS ZU CSV" description="Komma-getrennte Werte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-dif/" name="XLS ZU DIF" description="Datenaustauschformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-emf/" name="XLS ZU EMF" description="Verbessertes Metafile-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-html/" name="XLS ZU HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-jpeg/" name="XLS ZU JPEG" description="JPEG-Bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-mhtml/" name="XLS ZU MHTML" description="Archivformat für Webseiten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-ods/" name="XLS ZU ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-pdf/" name="XLS ZU PDF" description="Portables Dokumentenformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-png/" name="XLS ZU PNG" description="Portable Netzwerkgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-svg/" name="XLS ZU SVG" description="Skalierbare Vektorgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tiff/" name="XLS ZU TIFF" description="Markiertes Bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tsv/" name="XLS ZUM TSV" description="Tabulatorgetrennte Werte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsb/" name="XLS ZU XLSB" description="Binäre Excel-Arbeitsmappendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsm/" name="XLS ZU XLSM" description="Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsx/" name="XLS BIS XLSX" description="OOXML-Excel-Datei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltm/" name="XLS ZU XLTM" description="Makrofähige Excel-Vorlage" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltx/" name="XLS ZU XLTX" description="Office OpenXML-Excel-Vorlage" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xps/" name="XLS ZU XPS" description="XML-Papierspezifikationen" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}