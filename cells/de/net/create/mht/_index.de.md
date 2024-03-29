---
title: MHT erstellen – MHT-Datei in C# erstellen
description:  Aspose Excel. C# Erstellen Sie schnell und einfach eine MHT-Datei mit Aspose.Cells. Erstellen Sie eine MHT-Datei mit C#. Erstellen Sie MHT in C#. C# MHT Creator.
keywords: [Aspose Excel., C# Aspose.Cells., C# Create MHT file., Generate MHT file in C#., Create MHT file using C#., Write data to MHT file via C#., Create a MHT file in C#., C# Generate a MHT file., C# MHT Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Erstellen Sie eine MHT-Datei in C#" h2="Hochgeschwindigkeitsbibliothek C# zum Erstellen von MHT. Dies ist eine professionelle Softwarelösung zum Importieren und Exportieren von XLSX, PDF und vielen anderen Formaten auf .NET Framework-, .NET Core- oder Mono-Plattformen." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Erstellen Sie eine MHT-Datei mit C#" %}}
 Wie erstelle ich eine MHT-Datei? Mit der Bibliothek Aspose.Cells for .NET können Sie mit wenigen Codezeilen ganz einfach eine MHT-Datei programmgesteuert erstellen.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)ist in der Lage, plattformübergreifende Anwendungen zu erstellen und alle Excel-Dateien zu generieren, zu ändern, zu konvertieren, zu rendern und zu drucken. .NET Excel API konvertiert nicht nur zwischen Tabellenkalkulationsformaten, sondern kann auch Excel-Dateien als Bilder, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT und mehr rendern, was es zur perfekten Wahl für den Austausch von Dokumenten in branchenüblichen Formaten macht. Offen[NuGet](https://www.nuget.org/packages/aspose.cells) Paketmanager, suchen Sie nach Aspose.Cells und installieren Sie. Sie können auch den folgenden Befehl über die Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Paket-Manager-Konsolenbefehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}
 
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="So erstellen Sie MHT in C#" %}}

{{% blocks/products/pf/agp/text %}}

 Für die Entwickler ist es einfach, MHT-Dateien in verschiedenen Berichtsanwendungen zur Datenverarbeitung in nur wenigen Codezeilen zu erstellen, zu laden, zu ändern und zu konvertieren.

{{% /blocks/products/pf/agp/text %}}

1.  Fügen Sie den Namespace in Ihre Klassendatei ein
1.  Erstellen Sie eine Arbeitsmappenklasseninstanz.
1.  Greifen Sie auf das erste Arbeitsblatt der Arbeitsmappe zu.
1.  Holen Sie sich die gewünschte(n) Zelle(n) des Arbeitsblatts und geben Sie den Wert in die Zelle(n) ein.
1.  Verwenden Sie die Save-Methode, um die Arbeitsmappe als MHT-Datei zu speichern.

{{% blocks/products/pf/agp/code-block title="Der Beispielcode zeigt, wie eine MHT-Datei in C# erstellt wird." offSpacer="" %}}

```cs

// Create Workbook class instance.
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet sht = wkb.Worksheets[0];

// Get the desired cell(s) of the worksheet.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// input the value into the cell(s).
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Save the Workbook as .mht file.
wkb.Save("created_one.mht");

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="C#-Bibliothek zum Erstellen einer MHT-Datei" %}}

{{% blocks/products/pf/agp/text %}}

Es gibt zwei alternative Möglichkeiten, „Aspose.Cells for .NET“ auf Ihrem System zu installieren. Bitte wählen Sie eines aus, das Ihren Anforderungen entspricht, und befolgen Sie die Schritt-für-Schritt-Anleitung:

{{% /blocks/products/pf/agp/text %}}

1.  Installieren Sie a[NuGet Paket](https://www.nuget.org/packages/Aspose.Cells/) . Sehen[Dokumentation](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Installieren Sie die Bibliothek mit[Paket-Manager-Konsole](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) innerhalb der Visual Studio-IDE

{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie vor dem Ausführen des Konvertierungsbeispielcodes .NET sicher, dass die folgenden Voraussetzungen erfüllt sind.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows oder ein kompatibles Betriebssystem mit den Plattformen .NET, .NET Core, Windows Azure oder Mono.
-  Entwicklungsumgebung wie Microsoft Visual Studio.
-  Fügen Sie in Ihrem Projekt einen Verweis auf die DLL Aspose.Cells for .NET hinzu.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHT" readMoreLink="https://docs.fileformat.com/web/mht/" >}}Eine Datei mit der Erweiterung .mht ist ein MIME-fähiges Archivierungsdateiformat, das verschiedene Datentypen in einer einzigen Datei enthält. Es kann Daten wie Text, Bilder, Seitenstil in Form von CSS-Dateien, JavaScript und andere Ressourcen als darin eingebettete Ressourcen speichern. MHT-Dateien mit dem MIME-Typ message/rfc822 kapseln den gesamten Inhalt einer HTML-Datei als eine einzige Archivdatei zur Speicherung bei der Archivierung auf Speichergeräten. Mit Softwareanwendungen wie Microsoft Word können Sie Ihre WORD-Dokumente in MHT konvertieren, indem Sie sie als MHT-Datei exportieren. MHT-Dateien können mit gängigen Browsern wie Microsoft Internet Explorer und Google Chrome geöffnet werden.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Tabellenkalkulationserstellung" subTitle="Sie können auch andere Microsoft Excel-Formate erstellen, darunter einige der unten aufgeführten." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xls/" name="XLS" description="Microsoft Excel-Tabelle (Legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsx/" name="XLSX" description="Öffnen Sie die XML-Arbeitsmappe" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsb/" name="XLSB" description="Excel-Binärarbeitsmappe" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsm/" name="XLSM" description="Makrofähige Tabellenkalkulation" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlt/" name="XLT" description="Excel 97 - 2003-Vorlage" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltx/" name="XLTX" description="Excel-Vorlage" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltm/" name="XLTM" description="Excel-Makro-fähige Vorlage" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/csv/" name="CSV" description="Komma-getrennte Werte" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/tsv/" name="TSV" description="Tabulatorgetrennte Werte" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/ods/" name="ODS" description="OpenDocument-Tabelle" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/pdf/" name="PDF" description="Tragbares Dokumentformat" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/html/" name="HTML" description="Hyper Text Markup Language" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
