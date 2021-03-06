---
title: Erstellen Sie MS Excel XLSX-Dateien über Java 
url: /de/java/create-xlsx/ 
description: Java Beispielcode zum Generieren von XLSX-Dokumenten. Verwenden Sie diesen Code zum Erstellen von MS Excel XLSX-Dateien in einer Java-basierten Desktop- oder Webanwendung.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Erstellen Sie XLSX-Dokumente über Java" h2="Programmgesteuerte Erstellung nativer und leistungsstarker MS Excel XLSX-Tabellen mithilfe der Java-Bibliothek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Das dynamische Generieren einer MS Excel XLSX-Datei innerhalb einer laufenden Anwendung ist einfach. Um XLSX-Dokumente von Grund auf neu zu erstellen, ohne dass MS Office erforderlich ist, verwenden wir
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, das verschiedene Funktionen zum Erstellen, Bearbeiten und Konvertieren von Tabellenkalkulationen mithilfe der Java-Plattform bietet. Entwickler können Code zum Aktualisieren von Zellendaten, Generieren von Diagrammen oder Grafiken sowie zum Erstellen von Pivot-Tabellen, Hinzufügen von Formeln auf Zellenebene und mehr in Tabellenkalkulationen einfach verbessern.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="So erstellen Sie XLSX über Java" %}}

{{% blocks/products/pf/agp/text %}}

 Für die Entwickler ist es einfach, MS Excel XLSX-Tabellen in nur wenigen Codezeilen zu erstellen, zu laden, zu ändern und zu konvertieren, während verschiedene Berichtsanwendungen für die Datenverarbeitung ausgeführt werden.

{{% /blocks/products/pf/agp/text %}}

1. Erstellen Sie eine Instanz von [Klasse Arbeitsbuch](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).1. Greifen Sie mit der Methode getWorksheets.get() auf das relevante Arbeitsblatt zu.1. Wählen Sie die entsprechende Zelle aus, geben Sie den Wert in die gewünschte Zelle ein, indem Sie den Zellennamen verwenden, z. B. A1, B3 usw.1. Speichern Sie die Arbeitsmappe im XLSX-Format mit der Methode save().
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

Stellen Sie vor dem Ausführen des Beispielquellcodes für die Konvertierung Java sicher, dass Sie die folgenden Voraussetzungen erfüllen.  

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit Java Runtime Environment for JSP/JSF Application and Desktop Applications.- Aspose.Cells for Java unterstützt die folgenden Java Versionen: J2SE 6.0 (1.6), J2SE 7.0 (1.7) oder höher.- [Holen Sie sich die neueste Version von Aspose.Cells for Java direkt von Maven.](https://docs.aspose.com/cells/java/installation/) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Der folgende Quellcode zeigt, wie eine MS Excel XLSX-Datei mit Java erstellt wird." offSpacer="" %}}

```cs

// Erstellen Sie eine neue Arbeitsmappe
Workbook wkb = new Workbook();

// Greifen Sie auf das erste Arbeitsblatt der Arbeitsmappe zu.
Worksheet worksheet = wkb.getWorksheets().get(0);

// Fügen Sie relevante Inhalte in die Zelle ein
worksheet.getCells().get("A1").putValue("ColumnA");
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Speichern Sie die Arbeitsmappe als XLSX-Datei
wkb.save("Excel.xlsx"); 

// Um den Code um weitere Funktionalitäten zu erweitern sind hier weitere Funktionen
// getCells() und setValue zum Ändern des Zellinhalts
// getCharts().add() um Diagramme hinzuzufügen
// getPivotTables().add() zum Erstellen einer Pivot-Tabelle
// getCells().get(int cell id).setFormula zum Hinzufügen einer Formel auf Zellenebene


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Eine Programmierbibliothek für Excel-Tabellenkalkulationen, die plattformübergreifende Anwendungen mit der Fähigkeit zum Generieren, Ändern, Konvertieren, Rendern und Drucken von MS Excel XLSX-Dateien erstellen, erstellen kann. Java Excel API konvertiert nicht nur zwischen Tabellenkalkulationsformaten, sondern kann auch Excel-Dateien als Bilder, PDF, HTML, ODS und mehr wiedergeben und ist somit die perfekte Wahl für den Austausch von Dokumenten in branchenüblichen Formaten.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Spreadsheet-Generierung" subTitle="Sie können auch andere Microsoft Excel-Formate erstellen, einschließlich der unten aufgeführten." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xls/" name="XLS" description="Microsoft Excel-Tabelle (Legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsx/" name="XLSX" description="Öffnen Sie die XML-Arbeitsmappe" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsb/" name="XLSB" description="Excel-Binärarbeitsmappe" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlsm/" name="XLSM" description="Makrofähige Tabellenkalkulation" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xlt/" name="XLT" description="Excel 97-2003-Vorlage" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xltx/" name="XLTX" description="Excel-Vorlage" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-xltm/" name="XLTM" description="Excel-Vorlage mit Makros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-csv/" name="CSV" description="Komma-getrennte Werte" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-tsv/" name="TSV" description="Tabulatorgetrennte Werte" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create-ods/" name="ODS" description="OpenDocument-Tabelle" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
