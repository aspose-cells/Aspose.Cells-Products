---
title:  Wasserzeichen XLS Dokument via Java
weight: 2210
description: Java Beispielcode zum Hinzufügen oder Entfernen eines Wasserzeichens zur Datei XLS in der Laufzeitumgebung Java für JSP/JSF-Anwendungen und Desktopanwendungen.
keywords: [Java Aspose.Cells., Java add watermark to xls file., Java insert watermark to xls file., Java create watermark in xls file., remove watermark from xls file using Java., Java operate watermark in xls file., Java access watermark in xls file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Text-Wasserzeichen zu XLS via Java hinzufügen" h2="Erstellen Sie Ihre eigenen Java-Apps, um XLS-Dateien mithilfe serverseitiger APIs mit einem Wasserzeichen zu versehen." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="So versehen Sie die Datei XLS mit einem Wasserzeichen unter Verwendung von Java" %}}

 Um die Datei XLS mit einem Wasserzeichen zu versehen, verwenden wir[Aspose.Cells for Java](https://products.aspose.com/cells/java) API ist eine funktionsreiche, leistungsstarke und einfach zu bedienende Wasserzeichenplattform API for Java. Sie können die neueste Version direkt von herunterladen[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) und installieren Sie es in Ihrem auf Maven basierenden Projekt, indem Sie die folgenden Konfigurationen zur pom.xml hinzufügen.

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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Hinzufügen eines Wasserzeichens zu XLS via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Erstellen eines neuen Workbook-Objekts
1.  Wählen Sie das Arbeitsblatt über seinen Index aus
1.  Erstellen Sie eine Form und verwenden Sie deren Funktion addTextEffect
1.  Festlegen von Farben, Transparenz und mehr
1.  Arbeitsmappe im Format XLS speichern

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java wird auf allen wichtigen Plattformen und Betriebssystemen unterstützt. Bitte stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Laufzeitumgebung für JSP/JSF-Anwendungen und Desktop-Anwendungen.
- Holen Sie sich die neueste Version von Aspose.Cells for Java direkt von Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Wasserzeichen hinzufügen zu XLS - Java" offSpacer="" %}}

```cs

// Instantiate a new Workbook
Workbook workbook = new Workbook();

// Get the first default sheet
Worksheet sheet = workbook.getWorksheets().get(0);

// Add Watermark
Shape wordart = sheet.getShapes().addTextEffect(MsoPresetTextEffect.TEXT_EFFECT_1, "CONFIDENTIAL",
		"Arial Black", 50, false, true, 18, 8, 1, 1, 130, 800);

// Get the fill format of the word art
FillFormat wordArtFormat = wordart.getFill();

// Set the color
wordArtFormat.setOneColorGradient(Color.getRed(), 0.2, GradientStyleType.HORIZONTAL, 2);

// Set the transparency
wordArtFormat.setTransparency(0.9);

// Make the line invisible
LineFormat lineFormat = wordart.getLine();
lineFormat.setWeight(0.0);

// Save the file
workbook.save(dataDir + "AWArtWToWorksheet_out.xls");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Über Aspose.Cells for Java API" %}}

 Aspose.Cells API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagrammerstellung, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Wasserzeichen XLS per Online-App" sectionDescription=" Fügen Sie Wasserzeichen zu XLS Dokumenten hinzu, indem Sie unsere[Live-Demos-Website](https://products.aspose.app/cells/watermark)Die Live-Demo bietet folgende Vorteile" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Sie müssen nichts herunterladen oder einrichten" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Sie müssen keinen Code schreiben" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Laden Sie einfach Ihre XLS-Datei hoch, setzen Sie Ihr Wasserzeichen und klicken Sie auf die Schaltfläche \"Hinzufügen\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Erhalten Sie sofort den Download-Link für die resultierende Datei" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Dateien mit der Erweiterung XLS repräsentieren das Excel-Binärdateiformat. Solche Dateien können von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Eine von Excel gespeicherte Datei wird als Arbeitsmappe bezeichnet, wobei jede Arbeitsmappe ein oder mehrere Arbeitsblätter enthalten kann. Daten werden gespeichert und Benutzern im Tabellenformat im Arbeitsblatt angezeigt und können numerische Werte, Textdaten, Formeln, externe Datenverbindungen, Bilder und Diagramme umfassen. Anwendungen wie Microsoft Excel ermöglichen Ihnen den Export von Arbeitsmappendaten in verschiedene Formate, darunter PDF, CSV, XLSX, TXT, HTML, XPS und mehrere andere. Das Dateiformat XLS wurde mit der Veröffentlichung von Microsoft Excel 2007 durch ein offeneres und strukturierteres Format, XLSX, ersetzt. Die neuesten Versionen unterstützen weiterhin das Erstellen und Lesen von XLS-Dateien, obwohl XLSX jetzt die erste Wahl ist.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Wasserzeichenformate" subTitle="Mit Java können Sie problemlos verschiedene Formate mit Wasserzeichen versehen, darunter." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/ods/" name="ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsb/" name="XLSB" description="Binäre Excel-Arbeitsmappendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsm/" name="XLSM" description="Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsx/" name="XLSX" description="OOXML-Excel-Datei" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
