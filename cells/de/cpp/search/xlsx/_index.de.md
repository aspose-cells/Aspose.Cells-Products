---
title:  Durchsuchen Sie das Dokument XLSX, ohne es über C++ zu öffnen
weight: 9280
description: C++ Beispielcode zum Suchen von Wörtern mit Muster in der Datei XLSX in der Laufzeitumgebung C++ für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.
keywords: [C++ Aspose.Cells., C++ search words with pattern in XLSX file., C++ find words with pattern in XLSX file., C++ search string with pattern in XLSX file., C++ find words with pattern in XLSX file., C++ search words in excel file., C++ find words in excel file., C++ search string in excel file., C++ find string in excel file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Suchen Sie nach XLSX-Formaten in C++" h2="Native und leistungsstarke XLSX Dokumentensuche mit serverseitigen Aspose.Cells for C++ APIs, ohne den Einsatz von Software wie Microsoft oder Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So durchsuchen Sie die Datei XLSX mit C++" %}}

 Um die Datei XLSX zu durchsuchen, verwenden wir
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API, eine funktionsreiche, leistungsstarke und benutzerfreundliche Plattform für die Dokumentensuche. Sie können die neueste Version direkt herunterladen, indem Sie sie einfach öffnen
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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Durchsuchen von XLSX-Dateien in C++" %}}

{{% blocks/products/pf/agp/text %}}

 Eine einfache Dokumentensuche mit Aspose.Cells-APIs kann mit nur wenigen Codezeilen durchgeführt werden.

{{% /blocks/products/pf/agp/text %}}

+ Laden Sie die Datei XLSX, indem Sie eine Arbeitsmappenklasse instanziieren.
+ Instanziieren Sie die Klasse „ReplaceOptions“.
+ Legen Sie das erforderliche Muster wie SetCaseSensitive(bool value), SetMatchEntireCellContents(bool value) fest.
Verwenden Sie die Methode Workbook::Replace(...) mit relevanten Optionen.
+ Speichern Sie die Datei XLSX mit der Methode Workbook::Save(...).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ unterstützt auf allen wichtigen Plattformen und Betriebssystemen. Bitte stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows oder ein kompatibles Betriebssystem mit C++ Laufzeitumgebung für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.
-  Fügen Sie in Ihrem Projekt einen Verweis auf die DLL Aspose.Cells for C++ hinzu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Suche XLSX Dateien – C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load XLSX file
Workbook  wkb(srcDir + u"sourceFile.xlsx");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as XLSX file
wkb.Save(outDir + u"outputFile.xlsx");

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

    {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSX Live-Demos durchsuchen" sectionDescription=" Suchen Sie jetzt nach Text, Wörtern und Phrasen in XLSX-Dokumenten, indem Sie unsere besuchen[Live-Demos-Website](https://products.aspose.app/cells/search). Die Live-Demo bietet folgende Vorteile" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API muss nicht heruntergeladen werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es ist nicht nötig, Code zu schreiben." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Laden Sie einfach Ihre XLSX-Dateien hoch." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Das Suchergebnis erscheint sofort." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX " readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
 XLSX ist ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Das neue Format basiert auf einer Struktur, die gemäß den Open Packaging Conventions organisiert ist, wie in Teil 2 des OOXML-Standards ECMA-376 beschrieben ein Zip-Paket, das eine Reihe von XML-Dateien enthält. Die zugrunde liegende Struktur und die Dateien können durch einfaches Entpacken der .xlsx-Datei untersucht werden

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Suchdokumente" subTitle="Mit C++ kann man auch andere Dateien durchsuchen, darunter." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="Komma-getrennte Werte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="Durch Tabulatoren getrennte Werte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="Text dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Excel-Binärformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="Binäre Excel-Arbeitsmappendatei" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
