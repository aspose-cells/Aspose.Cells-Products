---
title: Konvertieren Sie FODS über Java in XLSB 
url: /de/java/conversion/fods-to-xlsb/ 
description: Beispiel-Umwandlungscode Java für das FODS-Format in eine XLSB-Datei. Programmierer können diesen Beispielcode verwenden, um Excel- und OpenOffice-Tabellen in XLSB innerhalb einer beliebigen Web- oder Desktop-Java-basierten Anwendung zu exportieren.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie FODS über Java in XLSB" h2="Konvertierung von FODS in XLSB Java zum Konvertieren einzelner oder mehrerer Seiten in XLSB mithilfe der lokalen Java-Bibliothek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie FODS in XLSB mit Java" %}}

 Um FODS in XLSB zu rendern, verwenden wir
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, einer funktionsreichen, leistungsstarken und benutzerfreundlichen Conversion-API for Java-Plattform. Sie können die neueste Version direkt von herunterladen
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 und installieren Sie es in Ihrem Maven-basierten Projekt, indem Sie der pom.xml die folgenden Konfigurationen hinzufügen.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Abhängigkeit" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von FODS in XLSB über Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-Entwickler können die FODS-Datei in nur wenigen Codezeilen problemlos in XLSB konvertieren.

{{% /blocks/products/pf/agp/text %}}

1. Laden Sie die FODS-Datei mit einer Instanz der Workbook-Klasse1. Rufen Sie die Workbook.save-Methode auf1. Übergeben Sie den Ausgabepfad mit XLSB-Erweiterung und SaveFormat als Parameter1. Überprüfen Sie den angegebenen Pfad für die resultierende XLSB-Datei

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie vor dem Ausführen des Conversion-Quellcodes Java sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Runtime Environment for JSP/JSF Application and Desktop Applications.- Holen Sie sich die neueste Version von Aspose.Cells for Java direkt von Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Konvertierungsquellcode von FODS zu XLSB Java" offSpacer="" %}}

```cs
// Laden Sie die FODS-Datei in eine Instanz von Workbook
Workbook book = new Workbook("template.fods");
// Speichern Sie FODS als XLSB
book.save("output.xlsb", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="FODS-zu-XLSB-Konvertierung Live-Demos" sectionDescription="[Konvertieren Sie FODS in XLSB](https://products.aspose.app/cells/conversion/fods-to-xlsb) jetzt, indem Sie unsere Live-Demo-Website besuchen. Die Live-Demo hat die folgenden Vorteile" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API muss nicht heruntergeladen werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es muss kein Code geschrieben werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre FODS-Datei hoch, sie wird sofort in XLSB konvertiert." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Sie erhalten den Download-Link." >}}

    {{% blocks/products/pf/agp/content h2="Java Tabellenbearbeitungsbibliothek" %}}

 Excel API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FODS" readMoreLink="https://docs.fileformat.com/spreadsheet/fods/" >}}

Eine Datei mit der Erweiterung .fods ist eine Art OpenDocument Spreadsheet-Dokumentformat, das Daten in Zeilen und Spalten speichert. Das Format wird als Teil der ODF 1.2-Spezifikationen spezifiziert, die von OASIS veröffentlicht und gepflegt werden. FODS-Dateien können nicht mit Excel, einer anderen Spreadsheet-Softwareanwendung von Microsoft, geöffnet werden. FODS-Dateien können mit LibreOffice als ODS gespeichert und in andere Formate wie XLS und XLSX konvertiert werden.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

Das XLSB-Dateiformat gibt das Excel-Binärdateiformat an, bei dem es sich um eine Sammlung von Datensätzen und Strukturen handelt, die den Inhalt von Excel-Arbeitsmappen angeben. Der Inhalt kann unstrukturierte oder halbstrukturierte Zahlentabellen, Text oder sowohl Zahlen als auch Text, Formeln, externe Datenverbindungen, Diagramme und Bilder umfassen. Im Gegensatz zu XLSX (das auf dem Open XML-Dateiformat basiert) repräsentiert XLSB eine binäre Excel-Arbeitsmappendatei. XLSB-Dateien können schneller gelesen und geschrieben werden, was sie für die Arbeit mit großen Dateien nützlich macht. XLSB wird selten zum Speichern von Arbeitsmappen verwendet, da XLSX (und früher XLS) die am häufigsten vom Benutzer ausgewählten Dateiformate zum Speichern von Arbeitsmappen sind. Es kann von Microsoft Office 2007 und höher geöffnet werden.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}