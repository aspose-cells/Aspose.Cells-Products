---
title:  Generieren Sie Berichte in XLS-Dateien via Java
weight: 1090
description: Java Beispielcode zum Erstellen von Berichten im XLS-Format zur Java-Laufzeitumgebung für JSP/JSF-Anwendungen und Desktop-Anwendungen.
keywords: [Java Aspose.Cells., Java Create XLS Reports Based on Predesigned Excel Template., Java Generate XLS Reports Based on Predesigned Excel Template., Java Create XLS Reports Based on Excel Template., Java Generate XLS Reports Based on Excel Template., Java Create XLS files Based on Excel Template., Java Generate XLS files Based on Excel Template]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Massenberichterstellung im XLS-Format via Java" h2="Erstellen Sie Berichte im Format XLS mithilfe einer Datenquelle und einer Vorlage." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="So erstellen Sie XLS-Berichte mit Java" %}}

 Um XLS-Dateiberichte zu erstellen, verwenden wir
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, eine funktionsreiche, leistungsstarke und benutzerfreundliche Baugruppenplattform. Sie können die neueste Version direkt von herunterladen
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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Generieren von XLS-Berichten via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Instanziieren Sie die WorkbookDesigner-Klasse
1. Fügen Sie Datenquellenobjekte in einer ArrayList hinzu
1.  Legen Sie die Datenquelle und den Prozess für das WorkbookDesigner-Objekt fest
1.  Speichern Sie das Ergebnis im Format XLS über die Methode Worbook.save

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java unterstützt auf allen wichtigen Plattformen und Betriebssystemen. Bitte stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Laufzeitumgebung für JSP/JSF-Anwendungen und Desktop-Anwendungen.
- Holen Sie sich die neueste Version von Aspose.Cells for Java direkt von Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Generieren Sie Excel-Berichte im Format XLS – Java" offSpacer="" %}}

```java
//Create a workbook designer
WorkbookDesigner designer = new WorkbookDesigner(workbook);

//Create Persons objects with photos
ArrayList persons = new ArrayList();       
persons.add(new Person("George", "New York", photo1));
persons.add(new Person("George", "New York", photo2));

//Set the data source and process smart marker tags
designer.setDataSource("Person", persons);
designer.process();

//Save the workbook
workbook.save(dataDir + "output.xls", SaveFormat.XLS);
	
System.out.println("File saved");
    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Über Aspose.Cells for Java API" %}}

 Aspose.Cells API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Kostenlose App zum Zusammenbauen von XLS" sectionDescription=" Schauen Sie sich unsere Live-Demos an[Erstellen Sie XLS-Dateien](https://products.aspose.app/cells/assembly/xls) mit folgenden Vorteilen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Sie müssen nichts herunterladen oder einrichten" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es ist nicht erforderlich, Code zu schreiben oder zu kompilieren" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach die Datei XLS hoch und klicken Sie auf die Schaltfläche „Assemble“." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Laden Sie die resultierende Datei XLS über den Link herunter" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Dateien mit der Erweiterung XLS repräsentieren das Excel-Binärdateiformat. Solche Dateien können mit Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Die von Excel gespeicherte Datei wird als Arbeitsmappe bezeichnet, wobei jede Arbeitsmappe ein oder mehrere Arbeitsblätter enthalten kann. Daten werden im Tabellenformat im Arbeitsblatt gespeichert und den Benutzern angezeigt und können numerische Werte, Textdaten, Formeln, externe Datenverbindungen, Bilder und Diagramme umfassen. Mit Anwendungen wie Microsoft Excel können Sie Arbeitsmappendaten in verschiedene Formate exportieren, darunter PDF, CSV, XLSX, TXT, HTML, XPS und mehrere andere. Das Dateiformat XLS wurde mit der Veröffentlichung von Microsoft Excel 2007 durch ein offeneres und strukturierteres Format, XLSX, ersetzt. Die neuesten Versionen unterstützen weiterhin das Erstellen und Lesen von XLS-Dateien, obwohl XLSX jetzt die erste Wahl ist.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Berichtserstellungsformate" subTitle="Mit Java können problemlos Berichte in mehreren Formaten erstellt werden, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/ods/" name="ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsb/" name="XLSB" description="Binäre Excel-Arbeitsmappendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsm/" name="XLSM" description="Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsx/" name="XLSX" description="OOXML-Excel-Datei" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
