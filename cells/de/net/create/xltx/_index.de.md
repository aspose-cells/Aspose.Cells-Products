---
title: Erstellen Sie MS Excel XLTX-Dateien über C# 
url: /de/net/create-xltx/ 
description: C# Beispielcode zum Generieren von XLTX-Dokumenten. Verwenden Sie diesen Code zum Erstellen von MS Excel XLTX-Dateien in VB.NET, Asp.NET oder einer beliebigen .NET-basierten Anwendung.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Erstellen Sie XLTX-Dokumente über C#" h2="Programmgesteuerte Erstellung nativer und leistungsstarker MS Excel XLTX-Tabellen mithilfe serverseitiger .NET-APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Das dynamische Generieren einer MS Excel XLTX-Datei innerhalb einer laufenden Anwendung ist einfach. Um XLTX-Dokumente von Grund auf neu zu erstellen, ohne dass MS Office erforderlich ist, verwenden wir
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, das verschiedene Funktionen zum Erstellen, Bearbeiten und Konvertieren von Tabellenkalkulationen mithilfe der .NET-Plattform bietet. Entwickler können Code zum Schreiben von Daten, Generieren von Diagrammen oder Grafiken sowie zum Erstellen von Tabellen in Tabellenkalkulationen einfach verbessern.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="So erstellen Sie XLTX über C#" %}}

{{% blocks/products/pf/agp/text %}}

 Für die Entwickler ist es einfach, MS Excel XLTX-Tabellen in nur wenigen Codezeilen zu erstellen, zu laden, zu ändern und zu konvertieren, während verschiedene Berichtsanwendungen für die Datenverarbeitung ausgeführt werden.

{{% /blocks/products/pf/agp/text %}}

1. Fügen Sie den Namespace in Ihre Klassendatei ein1. Instanz der Workbook-Klasse erstellen.1. Greifen Sie auf das erste Arbeitsblatt der Arbeitsmappe zu.1. Holen Sie sich die gewünschte(n) Zelle(n) des Arbeitsblatts und geben Sie den Wert in die Zelle(n) ein.1. Verwenden Sie die Save-Methode, um die Arbeitsmappe als XLTX-Datei zu speichern.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie einfach sicher, dass das System über Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin-Plattformen sowie eine Entwicklungsumgebung wie Microsoft Visual Studio verfügt. 

{{% /blocks/products/pf/agp/text %}}

- Von der Kommandozeile installieren als <code>nuget install Aspose.Cells</code> oder über die Package Manager Console von Visual Studio mit <code>Install-Package Aspose.Cells</code>.- Alternativ holen Sie sich den Offline-MSI-Installer oder alle DLLs in einer ZIP-Datei ab <a href="https://downloads.aspose.com/cells/net">Downloads</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Der folgende Quellcode zeigt, wie eine MS Excel XLTX-Datei mit C# erstellt wird." offSpacer="" %}}

```cs

// Instanz der Workbook-Klasse erstellen.
Workbook wkb = new Workbook();

// Greifen Sie auf das erste Arbeitsblatt der Arbeitsmappe zu.
Worksheet sht = wkb.Worksheets[0];

// Holen Sie sich die gewünschte(n) Zelle(n) des Arbeitsblatts.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// Geben Sie den Wert in die Zelle(n) ein.
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Speichern Sie die Arbeitsmappe als .xltx-Datei.
wkb.Save("created_one.xltx");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Eine Programmierbibliothek für Excel-Tabellenkalkulationen, die plattformübergreifende Anwendungen mit der Fähigkeit zum Generieren, Ändern, Konvertieren, Rendern und Drucken von MS Excel XLTX-Dateien erstellen, erstellen kann. .NET Excel API konvertiert nicht nur zwischen Tabellenkalkulationsformaten, sondern kann auch Excel-Dateien als Bilder, PDF, HTML, ODS und mehr wiedergeben und ist somit die perfekte Wahl für den Austausch von Dokumenten in branchenüblichen Formaten.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTX" readMoreLink="https://docs.fileformat.com/spreadsheet/xltx/" >}}
Dateien mit der Erweiterung .xltx stellen Microsoft Excel-Vorlagendateien dar, die auf den Office OpenXML-Dateiformatspezifikationen basieren. Es wird verwendet, um eine Standardvorlagendatei zu erstellen, die zum Generieren von XLSX-Dateien verwendet werden kann, die dieselben Einstellungen wie in der XLTX-Datei angegeben aufweisen.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Spreadsheet-Generierung" subTitle="Sie können auch andere Microsoft Excel-Formate erstellen, einschließlich der unten aufgeführten." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xls/" name="XLS" description="Microsoft Excel-Tabelle (Legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsx/" name="XLSX" description="Öffnen Sie die XML-Arbeitsmappe" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsb/" name="XLSB" description="Excel-Binärarbeitsmappe" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsm/" name="XLSM" description="Makrofähige Tabellenkalkulation" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlt/" name="XLT" description="Excel 97-2003-Vorlage" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltx/" name="XLTX" description="Excel-Vorlage" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltm/" name="XLTM" description="Excel-Vorlage mit Makros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-csv/" name="CSV" description="Komma-getrennte Werte" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-tsv/" name="TSV" description="Tabulatorgetrennte Werte" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-ods/" name="ODS" description="OpenDocument-Tabelle" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
