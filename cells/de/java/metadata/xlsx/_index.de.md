---
title:  Bearbeiten oder Anzeigen von XLSX-Dateimetadaten via Java
weight: 1240
description: Java Beispielcode zum Bearbeiten oder Anzeigen von Metadaten im XLSX-Format in der Java-Laufzeitumgebung für JSP/JSF-Anwendungen und Desktop-Anwendungen.
keywords: [Java Aspose.Cells., Java view xlsx metadata., Java add xlsx metadata., Java insert xlsx metadata., Java edit xlsx metadata., Java remove xlsx metadata., Java extract xlsx metadata., Java modify xlsx metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Extrahieren Sie XLSX-Metadaten via Java" h2="Erstellen Sie Ihre eigenen Java-Apps, um mithilfe serverseitiger APIs Metadaten aus XLSX-Dateien hinzuzufügen, zu bearbeiten, zu entfernen oder zu extrahieren." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="So extrahieren Sie XLSX-Metadaten mit Java" %}}

 Um XLSX-Dateimetadaten zu erhalten, verwenden wir
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, eine funktionsreiche, leistungsstarke und benutzerfreundliche Metadatenplattform. Sie können die neueste Version direkt von herunterladen
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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Extrahieren von Metadaten von XLSX via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Greifen Sie auf nützliche Informationen zu, die in der Datei XLSX gespeichert sind, einschließlich wann die Datei XLSX empfangen, verarbeitet, mit einem Zeitstempel versehen usw. wurde.

{{% /blocks/products/pf/agp/text %}}

+ Laden Sie die Datei XLSX in WorkbookMetadata
+ Erstellen Sie ein MetadataOptions-Objekt mit relevanten Optionen
+ Legen Sie die relevanten Eigenschaften fest
+ Speichern Sie die Metadateninformationen XLSX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java unterstützt auf allen wichtigen Plattformen und Betriebssystemen. Bitte stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows oder ein kompatibles Betriebssystem mit Java Laufzeitumgebung für JSP/JSF-Anwendungen und Desktop-Anwendungen.
-  Holen Sie sich die neueste Version von Aspose.Cells for Java direkt von
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extrahieren Sie Metadaten von XLSX - Java" offSpacer="" %}}

```cs

// Open Workbook metadata
MetadataOptions options = new MetadataOptions(MetadataType.DOCUMENT_PROPERTIES);
WorkbookMetadata meta = new WorkbookMetadata("Sample1.xlsx", options);

// Set some properties
meta.getCustomDocumentProperties().add("test", "test");

// Save the metadata info
meta.save("Sample1.out.xlsx");

// Open the workbook
Workbook w = new Workbook("Sample1.out.xlsx");

// Read document property
System.out.println(w.getCustomDocumentProperties().get("test"));  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Über Aspose.Cells for Java API" %}}

 Aspose.Cells API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extrahieren Sie Metadaten von XLSX über die Online-App" sectionDescription=" Anzeigen und Bearbeiten von Metadaten zu XLSX-Dokumenten mithilfe unseres[Live-Demos](https://products.aspose.app/cells/metadata) mit folgenden Vorteilen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Sie müssen nichts herunterladen oder einrichten" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es ist nicht nötig, Code zu schreiben" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre XLSX-Datei hoch und bearbeiten Sie die Dokumenteigenschaften" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Erhalten Sie sofort den Download-Link für die resultierende Datei" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX ist ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Das neue Format basiert auf einer Struktur, die gemäß den Open Packaging Conventions organisiert ist, wie in Teil 2 des OOXML-Standards ECMA-376 beschrieben ein Zip-Paket, das eine Reihe von XML-Dateien enthält. Die zugrunde liegende Struktur und die Dateien können durch einfaches Entpacken der .xlsx-Datei untersucht werden.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Metadatenformate" subTitle="Mit Java kann man auch Metadaten vieler anderer Formate bearbeiten, darunter" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/ods/" name="ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xls/" name="XLS" description="Excel-Binärformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsb/" name="XLSB" description="Binäre Excel-Arbeitsmappendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsm/" name="XLSM" description="Tabellenkalkulationsdatei" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
