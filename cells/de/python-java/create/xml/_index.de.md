---
title: XML erstellen - XML-Datei in Python erstellen
description:  Aspose Excel. Python Excel. Python Erstellen Sie schnell und einfach XML-Dateien mit Aspose.Cells. Generieren Sie XML-Dateien mit Python Excel-Bibliothek. Erstellen Sie XML in Python Excel-Bibliothek. Python XML-Ersteller.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create XML file., Generate XML file in Python Excel Library., Create XML file using Python Excel Library., Write data to XML file via Python Excel Library., Create a XML file in Python Excel Library., Python Generate a XML file., Python XML Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XML-Datei in der Excel-Bibliothek Python erstellen" h2="Hochgeschwindigkeits-Excel-Bibliothek Python zum Erstellen von XML-Dateien. Dies ist eine professionelle Softwarelösung zum Importieren und Exportieren von XLSX, PDF und vielen anderen Formaten mit Python." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Erstellen Sie eine XML-Datei mit der Excel-Bibliothek Python" %}}

Wie erstelle ich eine XML-Datei? Mit der Excel-Bibliothek Aspose.Cells for Python via Java können Sie mit wenigen Codezeilen ganz einfach programmgesteuert eine XML-Datei erstellen.[Aspose.Cells for Python](https://pypi.org/project/aspose-cells)kann plattformübergreifende Anwendungen erstellen und alle Excel-Dateien generieren, ändern, konvertieren, rendern und drucken. Python Excel API konvertiert nicht nur zwischen Tabellenkalkulationsformaten, sondern kann Excel-Dateien auch als Bilder rendern, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT und mehr und ist daher die perfekte Wahl für den Austausch von Dokumenten in Industriestandardformaten.

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="So erstellen Sie XML in der Excel-Bibliothek Python" %}}

{{% blocks/products/pf/agp/text %}}

 Für Entwickler ist es einfach, mit nur wenigen Codezeilen XML-Dateien in verschiedenen laufenden Berichtsanwendungen zur Datenverarbeitung zu erstellen, zu laden, zu ändern und zu konvertieren.

{{% /blocks/products/pf/agp/text %}}

1.  Importieren Sie Asposecells in Ihre Codedatei.
1.  Erstellen Sie eine Instanz der Workbook-Klasse.
1.  Greifen Sie auf das erste Arbeitsblatt der Arbeitsmappe zu.
1. Holen Sie sich die gewünschte(n) Zelle(n) des Arbeitsblatts und geben Sie den Wert in die Zelle(n) ein.
1.  Verwenden Sie die Methode „Speichern“, um die Arbeitsmappe als XML-Datei zu speichern.

{{% blocks/products/pf/agp/code-block title="Beispielcode zeigt, wie eine XML-Datei in der Excel-Bibliothek Python erstellt wird." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

# Create Workbook object.
workbook = Workbook(FileFormatType.XML)

# Access the first worksheet of the workbook.
worksheet = workbook.getWorksheets().get(0)

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

# Save the workbook as XML file.
workbook.save("output.xml")

jpype.shutdownJVM()

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python Excel-Bibliothek zum Erstellen einer XML-Datei" %}}

{{% blocks/products/pf/agp/text %}}

Es gibt drei Möglichkeiten, „Aspose.Cells for Python via Java“ auf Ihrem System zu installieren. Bitte wählen Sie eine Option, die Ihren Anforderungen entspricht, und folgen Sie den Schritt-für-Schritt-Anweisungen:

{{% /blocks/products/pf/agp/text %}}

1.  Installieren Sie Aspose.Cells for Python via Java in Windows. Siehe[Dokumentation](https://docs.aspose.com/cells/python-java/getting-started/#windows)
1.  Installieren Sie Aspose.Cells for Python via Java in Linux. Siehe[Dokumentation](https://docs.aspose.com/cells/python-java/getting-started/#linux)
1.  Installieren Sie Aspose.Cells for Python via Java in macOS. Siehe[Dokumentation](https://docs.aspose.com/cells/python-java/getting-started/#macos)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Python via Java ist plattformunabhängig API und kann auf jeder Plattform (Windows, Linux und MacOS) verwendet werden. Stellen Sie lediglich sicher, dass das System Java 1.8 oder höher hat.[Python](https://www.python.org/downloads/) 3,5 oder höher.

{{% /blocks/products/pf/agp/text %}}

-  Installieren Sie Java und fügen Sie es der Umgebungsvariable PATH hinzu, zum Beispiel:<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  Installieren Sie Aspose.Cells for Python via Java von<a href="https://pypi.org/project/aspose-cells/">pypi</a> , verwenden Sie den Befehl wie folgt:<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" >}}XML steht für Extensible Markup Language, die ähnlich wie HTML ist, sich aber durch die Verwendung von Tags zur Definition von Objekten unterscheidet. Die Grundidee hinter der Entwicklung des XML-Dateiformats war, Daten zu speichern und zu transportieren, ohne von Software- oder Hardwaretools abhängig zu sein. Seine Popularität verdankt es seiner Fähigkeit, sowohl von Menschen als auch von Maschinen gelesen zu werden. Dadurch können gemeinsame Datenprotokolle in Form von Objekten erstellt werden, die über Netzwerke wie das World Wide Web (WWW) gespeichert und geteilt werden können. Das „X“ in XML steht für erweiterbar, was bedeutet, dass die Sprache je nach Benutzeranforderungen auf eine beliebige Anzahl von Symbolen erweitert werden kann. Aufgrund dieser Funktionen wird es von vielen Standarddateiformaten verwendet, wie beispielsweise Microsoft Open XML, LibreOffice OpenDocument, XHTML und SVG.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Tabellenkalkulationsfunktionen" subTitle="Sie können auch andere Microsoft Excel-Formate erstellen, darunter einige der unten aufgeführten." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xls/" name="XLS" description="Microsoft Excel-Tabelle (Legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsx/" name="XLSX" description="Öffnen Sie die XML-Arbeitsmappe" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsb/" name="XLSB" description="Binäre Excel-Arbeitsmappe" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsm/" name="XLSM" description="Tabellenkalkulation mit Makros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlt/" name="XLT" description="Excel 97 - 2003 Vorlage" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltx/" name="XLTX" description="Excel-Vorlage" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltm/" name="XLTM" description="Excel-Vorlage mit Makros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/csv/" name="CSV" description="Komma-getrennte Werte" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/tsv/" name="TSV" description="Tabulatorgetrennte Werte" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/ods/" name="ODS" description="OpenDocument-Tabelle" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/pdf/" name="PDF" description="Portables Dokumentformat" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/html/" name="HTML" description="Hypertext-Markup-Sprache" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
