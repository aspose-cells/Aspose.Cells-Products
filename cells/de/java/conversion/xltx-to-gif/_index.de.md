---
title: Konvertieren Sie XLTX in GIF über Java 
weight: 8640
url: /de/java/conversion/xltx-to-gif/ 
description: Beispiel-Umwandlungscode Java für das XLTX-Format in eine GIF-Datei. Programmierer können diesen Beispielcode zum Exportieren von Excel- und OpenOffice-Tabellen in GIF innerhalb einer beliebigen Web- oder Desktop-Java-basierten Anwendung verwenden.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertieren Sie XLTX in GIF über Java" h2="XLTX-zu-GIF-Java-Konvertierung zum Konvertieren einzelner oder mehrerer Seiten in GIF mithilfe der lokalen Java-Bibliothek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie XLTX in GIF mit Java" %}}

 Um XLTX in GIF zu rendern, verwenden wir
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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von XLTX in GIF über Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-Entwickler können XLTX-Dateien in nur wenigen Codezeilen ganz einfach in GIF konvertieren.

{{% /blocks/products/pf/agp/text %}}

1. XLTX-Datei mit einer Instanz von Workbook laden1. Wählen Sie Standard oder ein beliebiges Arbeitsblatt aus der Sammlung aus1. Erstellen und setzen Sie das Objekt von ImageOrPrintOptions1. Erstellen Sie SheetRender mit Worksheet- und ImageOrPrintOptions-Objekten1. Rufen Sie die SheetRender.toImage-Methode auf, um das Ergebnis im GIF-Format zu speichern
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Stellen Sie vor dem Ausführen des Conversion-Quellcodes Java sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Runtime Environment for JSP/JSF Application and Desktop Applications.- Holen Sie sich die neueste Version von Aspose.Cells for Java direkt von Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTX-zu-GIF-Java-Konvertierungsquellcode" offSpacer="" %}}

```cs
// Laden Sie die zu rendernde XLTX-Datei
Workbook workbook = new Workbook("sourceFile.xltx");
// Greifen Sie auf das Standardarbeitsblatt aus der Sammlung zu
Worksheet worksheet = workbook.getWorksheets().get(0);
// Definieren Sie Parameter für das resultierende Bild
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.GIF);
// Konvertieren Sie das Arbeitsblatt in ein Bild im GIF-Format
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.gif");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLTX-zu-GIF-Konvertierung Live-Demos" sectionDescription="[Konvertieren Sie XLTX in GIF](https://products.aspose.app/cells/conversion/xltx-to-gif) jetzt, indem Sie unsere Live-Demo-Website besuchen. Die Live-Demo hat die folgenden Vorteile" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API muss nicht heruntergeladen werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es muss kein Code geschrieben werden." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre XLTX-Datei hoch, sie wird sofort in GIF konvertiert." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Sie erhalten den Download-Link." >}}

    {{% blocks/products/pf/agp/content h2="Java Tabellenbearbeitungsbibliothek" %}}

 Excel API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTX" readMoreLink="https://docs.fileformat.com/spreadsheet/xltx/" >}}

Dateien mit der Erweiterung XLTX stellen Microsoft Excel-Vorlagendateien dar, die auf den Office OpenXML-Dateiformatspezifikationen basieren. Es wird verwendet, um eine Standardvorlagendatei zu erstellen, die zum Generieren von XLSX-Dateien verwendet werden kann, die dieselben Einstellungen wie in der XLTX-Datei angegeben aufweisen.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

Ein GIF oder Graphical Interchange Format ist eine Art stark komprimiertes Bild. GIF gehört Unisys und verwendet den LZW-Komprimierungsalgorithmus, der die Bildqualität nicht beeinträchtigt. Für jedes Bild sind in GIF normalerweise bis zu 8 Bit pro Pixel und bis zu 256 Farben im gesamten Bild zulässig. Im Gegensatz zu einem JPEG-Bild, das bis zu 16 Millionen Farben darstellen kann und ziemlich an die Grenzen des menschlichen Auges stößt. Als das Internet aufkam, blieben GIFs die beste Wahl, da sie eine geringe Bandbreite erforderten und für die Grafiken kompatibel waren, die Volltonbereiche verbrauchen. Ein animiertes GIF kombiniert zahlreiche Bilder oder Frames in einer einzigen Datei und zeigt sie in einer Sequenz an, um einen animierten Clip oder ein kurzes Video zu erstellen. Die Farbbeschränkungen betragen bis zu 256 für jedes Bild und sind wahrscheinlich am wenigsten geeignet, um andere Bilder und Fotos mit Farbverlauf zu reproduzieren.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können XLTX auch in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-bmp/" name="XLTX ZU BMP" description="Bitmap-Bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-csv/" name="XLTX ZU CSV" description="Komma-getrennte Werte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-dif/" name="XLTX ZU DIF" description="Datenaustauschformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-emf/" name="XLTX ZU EMF" description="Verbessertes Metafile-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-html/" name="XLTX ZU HTML" description="Hypertext-Auszeichnungssprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-jpeg/" name="XLTX ZU JPEG" description="JPEG-Bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-mhtml/" name="XLTX ZU MHTML" description="Archivformat für Webseiten" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-ods/" name="XLTX ZU ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-pdf/" name="XLTX ZU PDF" description="Portables Dokumentenformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-png/" name="XLTX ZU PNG" description="Portable Netzwerkgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-svg/" name="XLTX ZU SVG" description="Skalierbare Vektorgrafiken" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-tiff/" name="XLTX ZU TIFF" description="Markiertes Bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-tsv/" name="XLTX ZU TSV" description="Tabulatorgetrennte Werte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-txt/" name="XLTX ZU TXT" description="Text dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlm/" name="XLTX ZU XLM" description="Excel-Makrodatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xls/" name="XLTX ZU XLS" description="Excel-Binärformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlsb/" name="XLTX ZU XLSB" description="Binäre Excel-Arbeitsmappendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlsx/" name="XLTX ZU XLSX" description="OOXML-Excel-Datei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xlt/" name="XLTX ZU XLT" description="Microsoft Excel-Vorlage" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xltm/" name="XLTX ZU XLTM" description="Makrofähige Excel-Vorlage" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-xps/" name="XLTX ZU XPS" description="XML-Papierspezifikationen" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xltx-to-json/" name="XLTX ZU JSON" description="JavaScript-Objekt-Notation" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}