---
title: Erstellen Sie MHTML-Dateien über Python 
url: /de/python-java/create-mhtml/ 
description: Python Beispielcode zum Generieren von MHTML-Dokumenten. Verwenden Sie diesen Code zum Erstellen von MHTML-Dateien in der Anwendung Python.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Erstellen Sie MHTML-Dokumente über Python" h2="Native und leistungsstarke MHTML-Erstellung programmgesteuert mit Python-APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/python" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Das dynamische Generieren einer MHTML-Datei innerhalb einer laufenden Anwendung ist einfach. Um MHTML-Dokumente von Grund auf neu zu erstellen, ohne dass MS Office erforderlich ist, verwenden wir
 [Aspose.Cells für Python](https://pypi.org/project/aspose-cells) 
 API, das verschiedene Funktionen zum Erstellen, Bearbeiten und Konvertieren von Tabellenkalkulationen mithilfe der Python-Plattform bietet. Entwickler können Code zum Schreiben von Daten, Generieren von Diagrammen oder Grafiken sowie zum Erstellen von Tabellen in Tabellenkalkulationen einfach verbessern.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="So erstellen Sie MHTML über Python" %}}

{{% blocks/products/pf/agp/text %}}

 Für die Entwickler ist es einfach, MHTML in nur wenigen Codezeilen zu erstellen, zu laden, zu modifizieren und zu konvertieren, während verschiedene Berichtsanwendungen für die Datenverarbeitung ausgeführt werden.

{{% /blocks/products/pf/agp/text %}}

1. Importieren Sie asposecells in Ihre Codedatei.1. Instanz der Workbook-Klasse erstellen.1. Greifen Sie auf das erste Arbeitsblatt der Arbeitsmappe zu.1. Holen Sie sich die gewünschte(n) Zelle(n) des Arbeitsblatts und geben Sie den Wert in die Zelle(n) ein.1. Verwenden Sie die Save-Methode, um die Arbeitsmappe als MHTML-Datei zu speichern.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells für Python über Java ist plattformunabhängig API und kann auf jeder Plattform (Windows, Linux und MacOS) verwendet werden, stellen Sie einfach sicher, dass das System Java 1.8 oder höher hat, [Python](https://www.python.org/downloads/) 3,5 oder höher. 

{{% /blocks/products/pf/agp/text %}}

- Installieren Sie Java und fügen Sie es der PATH-Umgebungsvariable hinzu, zum Beispiel: <code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.- Installieren Sie Aspose.Cells für Python über Java von <a href="https://pypi.org/project/aspose-cells/">pypi</a>, verwenden Sie den Befehl als: <code>$ pip install aspose-cells</code>.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Der folgende Quellcode zeigt, wie eine MHTML-Datei mit Python erstellt wird." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

// Workbook-Objekt erstellen.
workbook = Workbook(FileFormatType.MHTML)

// Greifen Sie auf das erste Arbeitsblatt der Arbeitsmappe zu.
worksheet = workbook.getWorksheets().get(0)

// Holen Sie sich die gewünschte(n) Zelle(n) des Arbeitsblatts und geben Sie den Wert in die Zelle(n) ein.
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Speichern Sie die Arbeitsmappe als MHTML-Datei.
workbook.save("output.mhtml")

jpype.shutdownJVM()


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Eine Programmierbibliothek für Excel-Tabellenkalkulationen, die plattformübergreifende Anwendungen mit der Fähigkeit zum Generieren, Ändern, Konvertieren, Rendern und Drucken von MHTML-Dateien erstellen kann. Python API konvertiert nicht nur zwischen Tabellenkalkulationsformaten, sondern kann auch Excel-Dateien als Bilder, PDF, HTML, ODS und mehr wiedergeben und ist somit die perfekte Wahl für den Austausch von Dokumenten in branchenüblichen Formaten.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}
Dateien mit der Erweiterung MHTML stellen ein Archivformat für Webseiten dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format wird als Archivformat bezeichnet, da es den Web-HTML-Code und die zugehörigen Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien und so weiter. MHTML-Dateien können in einer Vielzahl von Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Microsoft Windows verwendet das MHTML-Dateiformat zum Aufzeichnen von Problemszenarien, die während der Verwendung einer Anwendung unter Windows beobachtet wurden, die Probleme aufwirft. Das MHTML-Dateiformat codiert die Seiteninhalte ähnlich den in message/rfc822 definierten Spezifikationen, bei denen es sich um E-Mail-bezogene Spezifikationen im Klartext handelt.
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}   

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Spreadsheet-Generierung" subTitle="Sie können auch andere Microsoft Excel-Formate erstellen, einschließlich der unten aufgeführten." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xls/" name="XLS" description="Microsoft Excel-Tabelle (Legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsx/" name="XLSX" description="Öffnen Sie die XML-Arbeitsmappe" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsb/" name="XLSB" description="Excel-Binärarbeitsmappe" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsm/" name="XLSM" description="Makrofähige Tabellenkalkulation" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlt/" name="XLT" description="Excel 97-2003-Vorlage" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltx/" name="XLTX" description="Excel-Vorlage" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltm/" name="XLTM" description="Excel-Vorlage mit Makros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-csv/" name="CSV" description="Komma-getrennte Werte" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-tsv/" name="TSV" description="Tabulatorgetrennte Werte" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-ods/" name="ODS" description="OpenDocument-Tabelle" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
