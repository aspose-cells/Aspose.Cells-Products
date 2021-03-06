---
title: Zeigen Sie XLT-Dateiformate über .NET an 
weight: 3610
url: /de/net/viewer/xlt/ 
description: C#-Quellcode zum Laden, Rendern und Anzeigen von XLT-Dokumenten auf .NET Framework-, .NET Core-, Mono- oder Xamarin-Plattformen.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLT-Dateibetrachter for .NET" h2="Zeigen Sie Excel- und OpenOffice-Tabellen wie XLT an, ohne dass Microsoft Excel oder Office Automation erforderlich sind." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLT" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So zeigen Sie XLT-Dateien mit C# an" %}}

 Um die XLT-Datei anzuzeigen, verwenden wir
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, eine funktionsreiche, leistungsstarke und benutzerfreundliche API für C#-Plattform, die mit jedem Viewer verwendet werden kann. Offen
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 Paketmanager, suche nach
 **Aspose.Cells** 
 und installieren. Sie können auch den folgenden Befehl in der Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Paket-Manager-Konsolenbefehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Anzeigen von XLT über C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells erleichtert Entwicklern das Anzeigen der XLT-Datei mit nur wenigen Codezeilen.

{{% /blocks/products/pf/agp/text %}}

1. Laden Sie die XLT-Datei in eine Instanz von Workbook1. Erstellen Sie eine Instanz von HtmlSaveOptions und setzen Sie die ExportHeadings-Eigenschaft auf true1. Speichern Sie die XLT-Datei im HTML-Format mit der Workbook.Save-Methode1. Laden Sie das resultierende HTML im Standardbrowser mit Process.Start
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET wird auf allen gängigen Betriebssystemen unterstützt. Stellen Sie einfach sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Mono oder Xamarin-Plattformen- Entwicklungsumgebung wie Microsoft Visual Studio- Aspose.Cells for .NET in Ihrem Projekt referenziert
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# Beispielcode zum Anzeigen der XLT-Datei" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// Laden Sie die XLT-Datei in eine Instanz von Workbook
var book = new Aspose.Cells.Workbook("template.xlt");
// Erstellen Sie eine Instanz von HtmlSaveOptions und setzen Sie die Eigenschaft ExportHeadings auf true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// Speichern Sie die XLT-Datei im HTML-Format
book.Save(output, options);
// resultierendes HTML im Standardbrowser laden
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Über Aspose.Cells for .NET API" %}}

 Aspose.Cells API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Kostenlose App zum Anzeigen von XLT" sectionDescription="Sehen Sie sich unsere Live-Demos an [XLT ansehen](https://products.aspose.app/cells/viewer/xlt) mit folgenden Vorteilen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Sie müssen nichts herunterladen oder einrichten" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es ist nicht erforderlich, Code zu schreiben oder zu kompilieren" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach die XLT-Datei hoch und klicken Sie auf die Schaltfläche \"Anzeigen\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Laden Sie die XLT-Datei bei Bedarf über den Link herunter" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
Dateien mit der Erweiterung .XLT sind Vorlagendateien, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office-Suite ist. Microsoft Office 97-2003 unterstützte das Erstellen neuer XLT-Dateien sowie das Öffnen dieser. Die neueste Version von Excel ist immer noch in der Lage, Vorlagendateien dieses alten Formats zu öffnen. Eine solche Vorlagendatei wird verwendet, um schnell neue Excel-Dateien mit Standarddaten und -einstellungen wie Seitenformatierung, Schriftgröße, Ränder, Diagramme usw. zu erstellen, die als neue .XLS-Dateien weiter gespeichert werden können.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Viewer-Formate" subTitle="Mit C# kann man auch viele andere Dateiformate anzeigen, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="Komma-getrennte Werte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/tsv/" name="TSV" description="Tabulatorgetrennte Werte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="Text dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="Excel-Binärformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="Binäre Excel-Arbeitsmappendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="OOXML-Excel-Datei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Makrofähige Excel-Vorlage" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Office OpenXML-Excel-Vorlage" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}