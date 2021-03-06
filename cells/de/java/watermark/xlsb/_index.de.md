---
title: XLSB-Dokument mit Wasserzeichen über Java 
weight: 5900
url: /de/java/watermark/xlsb/ 
description: Java Beispielcode zum Hinzufügen oder Entfernen von Wasserzeichen zur XLSB-Datei in Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Textwasserzeichen zu XLSB über Java hinzufügen" h2="Erstellen Sie mithilfe serverseitiger APIs Ihre eigenen Java-Apps, um XLSB-Dateien mit Wasserzeichen zu versehen." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="So versehen Sie XLSB-Dateien mit Java mit einem Wasserzeichen" %}}

 Um XLSB-Dateien mit Wasserzeichen zu versehen, verwenden wir
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, eine funktionsreiche, leistungsstarke und benutzerfreundliche Wasserzeichen-API for Java-Plattform. Sie können die neueste Version direkt von herunterladen
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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Hinzufügen von Wasserzeichen zu XLSB über Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Erstellen Sie ein neues Workbook-Objekt1. Wählen Sie das Arbeitsblatt über seinen Index aus1. Erstellen Sie eine Form und verwenden Sie ihre addTextEffect-Funktion1. Stellen Sie Farben, Transparenz und mehr ein1. Arbeitsmappe im XLSB-Format speichern
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java wird auf allen wichtigen Plattformen und Betriebssystemen unterstützt. Bitte stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Runtime Environment for JSP/JSF Application and Desktop Applications.- Holen Sie sich die neueste Version von Aspose.Cells for Java direkt von Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Wasserzeichen zu XLSB hinzufügen - Java" offSpacer="" %}}

```cs

// Instanziieren Sie eine neue Arbeitsmappe
Workbook workbook = new Workbook();

// Holen Sie sich das erste Standardblatt
Worksheet sheet = workbook.getWorksheets().get(0);

// Wasserzeichen hinzufügen
Shape wordart = sheet.getShapes().addTextEffect(MsoPresetTextEffect.TEXT_EFFECT_1, "CONFIDENTIAL",
		"Arial Black", 50, false, true, 18, 8, 1, 1, 130, 800);

// Holen Sie sich das Füllformat der Wortkunst
FillFormat wordArtFormat = wordart.getFill();

// Stellen Sie die Farbe ein
wordArtFormat.setOneColorGradient(Color.getRed(), 0.2, GradientStyleType.HORIZONTAL, 2);

// Legen Sie die Transparenz fest
wordArtFormat.setTransparency(0.9);

// Machen Sie die Linie unsichtbar
LineFormat lineFormat = wordart.getLine();
lineFormat.setWeight(0.0);

// Speicher die Datei
workbook.save(dataDir + "AWArtWToWorksheet_out.xlsb");  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Über Aspose.Cells for Java API" %}}

 Aspose.Cells API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Wasserzeichen XLSB über Online-App" sectionDescription="Fügen Sie XLSB-Dokumenten Wasserzeichen hinzu, indem Sie unsere besuchen [Live-Demos-Website](https://products.aspose.app/cells/watermark). Die Live-Demo hat die folgenden Vorteile" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Sie müssen nichts herunterladen oder einrichten" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es muss kein Code geschrieben werden" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Laden Sie einfach Ihre XLSB-Datei hoch, setzen Sie Ihr Wasserzeichen und klicken Sie auf die Schaltfläche \"Hinzufügen\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Erhalten Sie sofort den Download-Link für die resultierende Datei" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Das XLSB-Dateiformat gibt das Excel-Binärdateiformat an, bei dem es sich um eine Sammlung von Datensätzen und Strukturen handelt, die den Inhalt von Excel-Arbeitsmappen angeben. Der Inhalt kann unstrukturierte oder halbstrukturierte Zahlentabellen, Text oder sowohl Zahlen als auch Text, Formeln, externe Datenverbindungen, Diagramme und Bilder umfassen. Im Gegensatz zu XLSX (das auf dem Open XML-Dateiformat basiert) repräsentiert XLSB eine binäre Excel-Arbeitsmappendatei. XLSB-Dateien können schneller gelesen und geschrieben werden, was sie für die Arbeit mit großen Dateien nützlich macht. XLSB wird selten zum Speichern von Arbeitsmappen verwendet, da XLSX (und früher XLS) die am häufigsten vom Benutzer ausgewählten Dateiformate zum Speichern von Arbeitsmappen sind. Es kann von Microsoft Office 2007 und höher geöffnet werden.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Wasserzeichenformate" subTitle="Mit Java kann man problemlos verschiedene Formate mit Wasserzeichen versehen, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/ods/" name="ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xls/" name="XLS" description="Excel-Binärformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsm/" name="XLSM" description="Tabellenkalkulationsdatei" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}