---
title:  Konvertieren Sie XLSX über C# in ein Byte-Array
weight: 7690
description: C# Beispielcode für die Konvertierung von XLSX in Byte-Array. Verwenden Sie diesen Code für die Konvertierung von Excel XLSX in Byte-Array innerhalb von VB.NET, Asp.NET oder einer anderen .NET-basierten Anwendung.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie XLSX über C# in ein Byte-Array" h2="Native und leistungsstarke Microsoft Excel XLSX Konvertierung in Byte-Arrays oder umgekehrt für die Datenverarbeitung in Tabellenkalkulationen mithilfe serverseitiger .NET APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Byte Array ist hilfreich für die Datenverarbeitung oder -speicherung. Sie können die Datei XLSX sowohl in ein Byte-Array als auch in eine konvertieren**Byte-Array bis XLSX** Dokument mit der Sprache C#. Um XLSX in ein Byte-Array umzuwandeln, verwenden wir
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, das verschiedene Funktionen für die Dokumentenbearbeitung und -konvertierung mithilfe der Plattform .NET bietet.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="So konvertieren Sie XLSX über C# in ein Byte-Array" %}}

{{% blocks/products/pf/agp/text %}}

 Für Entwickler ist es einfach, XLSX-Dateien in nur wenigen Codezeilen für weitere Bearbeitungsaufgaben zu laden und in ein Byte-Array zu konvertieren.

{{% /blocks/products/pf/agp/text %}}

1.  Fügen Sie den Namespace in Ihre Klassendatei ein
1.  Laden Sie die Eingabedatei XLSX mithilfe der Arbeitsmappe
1.  Initialisieren Sie das MemoryStream-Objekt
1.  Konvertieren Sie Stream-Daten in ein Byte-Array
1.  Verarbeiten Sie Daten nach Ihren Anforderungen

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

Stellen Sie einfach sicher, dass das System über Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Windows Azure, Mono oder Xamarin-Plattformen sowie eine Entwicklungsumgebung wie Microsoft Visual Studio verfügt.

{{% /blocks/products/pf/agp/text %}}

-  Von der Befehlszeile aus installieren als<code>nuget install Aspose.Cells</code> oder über die Package Manager-Konsole von Visual Studio mit<code>Install-Package Aspose.Cells</code>.
-  Alternativ können Sie das Offline-MSI-Installationsprogramm oder alle DLLs in einer ZIP-Datei von herunterladen<a href="https://downloads.aspose.com/cells/net">Downloads</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieser Beispielcode zeigt die Konvertierung von XLSX in das Byte-Array C#" offSpacer="" %}}

```cs
Workbook workbook = new Workbook("sourceFile.xlsx");

//Save the workbook in memory stream
MemoryStream ms = new MemoryStream();

workbook.Save(ms, SaveFormat.Xlsx);

//Read bytes from memory stream
byte[] byte_array = new byte[ms.Length];
ms.Read(byte_array, 0, byte_array.Length);

// Process the memory stream byte array data as of your requirement 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->
      
     {{% blocks/products/pf/agp/content h2="" %}}

Eine Excel-Tabellenkalkulations-Programmierbibliothek, die in der Lage ist, plattformübergreifende Anwendungen zu erstellen und alle Excel-Dateien zu generieren, zu ändern, zu konvertieren, zu rendern und zu drucken. .NET Excel API konvertiert nicht nur zwischen Tabellenkalkulationsformaten, sondern kann auch Excel-Dateien wie XLSX, PDF, HTML, ODS und mehr als Bilder rendern, was es zur perfekten Wahl für den Austausch von Dokumenten in branchenüblichen Formaten macht.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX ist ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Das neue Format basiert auf einer Struktur, die gemäß den Open Packaging Conventions organisiert ist, wie in Teil 2 des OOXML-Standards ECMA-376 beschrieben ein Zip-Paket, das eine Reihe von XML-Dateien enthält. Die zugrunde liegende Struktur und die Dateien können durch einfaches Entpacken der .xlsx-Datei untersucht werden.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

           {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können auch andere Dateiformate in Byte-Arrays konvertieren oder umgekehrt, darunter einige der unten aufgeführten." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-byte-array/" name="XLS Zu Byte-Array" description="Microsoft Excel-Tabelle (Legacy)" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-byte-array/" name="XLSX Zu Byte-Array" description="Öffnen Sie die XML-Arbeitsmappe" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsb-to-byte-array/" name="XLSB Zu Byte-Array" description="Excel-Binärarbeitsmappe" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsm-to-byte-array/" name="XLSM Zu Byte-Array" description="Makrofähige Tabellenkalkulation" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlt-to-byte-array/" name="XLT Zu Byte-Array" description="Excel 97 - 2003-Vorlage" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltx-to-byte-array/" name="XLTX Zu Byte-Array" description="Excel-Vorlage" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltm-to-byte-array/" name="XLTM Zu Byte-Array" description="Excel-Makro-fähige Vorlage" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/csv-to-byte-array/" name="CSV Zu Byte-Array" description="Durch Kommas getrennte Werte" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/tsv-to-byte-array/" name="TSV Zu Byte-Array" description="Tabulatorgetrennte Werte" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/ods-to-byte-array/" name="ODS Zu Byte-Array" description="OpenDocument-Tabelle" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-pdf/" name="XLS bis PDF" description="Tragbares Dokumentformat" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-html/" name="XLS bis HTML" description="Hyper Text Markup Language" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-pdf/" name="XLSX bis XPS" description="Microsoft Excel OOXML Excel-Datei" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-html/" name="XLSX bis HTML" description="OOXML-Excel-Datei" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-svg/" name="XLSX bis SVG" description="Skalierbare Vektorgrafiken" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-jpeg/" name="XLS bis JPEG" description="JPEG Bild" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
