---
title:  Entsperren Sie das Dokument XLSM über C++
weight: 6070
description: C++ Beispielcode zum Entsperren der passwortgeschützten XLSM-Datei in der C++-Laufzeitumgebung für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.
keywords: [C++ Aspose.Cells., C++ unlock XLSM files., C++ how to unlock XLSM document., C++ unprotect XLSM files., remove protection from XLSM files., decrypt XLSM Files using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Entsperren Sie XLSM-Dateien über C++" h2="Entfernen Sie den Schutz von Excel-Tabellen einschließlich der Datei XLSM mithilfe der Bibliothek C++." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So entfernen Sie den Schutz der Datei XLSM mit C++" %}}

 Um die Datei XLSM zu entsperren, verwenden wir
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API, eine funktionsreiche, leistungsstarke und benutzerfreundliche Plattform für den Dokumentenschutz. Sie können die neueste Version direkt herunterladen, indem Sie sie einfach öffnen
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 Paketmanager, suchen Sie nach
 **Aspose.Cells.Cpp** 
 und installieren. Sie können auch den folgenden Befehl über die Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schalten Sie XLSM über C++ frei" %}}

{{% blocks/products/pf/agp/text %}}

 Du brauchst
 [aspose.cells.dll](https://downloads.aspose.com/cells/cpp) 
 in Ihrem Projekt referenziert, um den folgenden Workflow auszuführen.

{{% /blocks/products/pf/agp/text %}}

1.  Instanziieren Sie die Arbeitsmappenklasse mit dem Pfad zur geschützten Datei XLSM
1.  Rufen Sie das Standard- oder ein beliebiges Arbeitsblatt ab, um den Schutz zu entfernen
1.  Entfernen Sie den Arbeitsblattschutz mit der Worksheet.Unprotect-Methode
1.  Entfernen Sie den Arbeitsmappenschutz mit der Methode Workbook.Unprotect
1.  Ergebnis im Format XLSM speichern

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ unterstützt auf allen wichtigen Plattformen und Betriebssystemen. Bitte stellen Sie sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows oder ein kompatibles Betriebssystem mit C++ Laufzeitumgebung für Windows 32 Bit, Windows 64 Bit und Linux 64 Bit.
-  Fügen Sie in Ihrem Projekt einen Verweis auf die DLL Aspose.Cells for C++ hinzu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Befehl" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// instantiate a Workbook object with protected XLSM file
Workbook workbook(u"protected.xlsm");

// access the default worksheet in the Excel file
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in XLSM format
workbook.Save("unprotected.xlsm", SaveFormat::Auto);

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Über Aspose.Cells for C++ API" %}}

 Aspose.Cells API kann zum Erstellen, Bearbeiten, Konvertieren und Rendern von Microsoft Excel-Formaten in verschiedene Formate verwendet werden. Darüber hinaus kann es für umfassende Diagramme, skalierbare Berichte und zuverlässige Berechnungen innerhalb von Softwareanwendungen verwendet werden. Aspose.Cells ist ein eigenständiges API und erfordert keine Software wie Microsoft oder OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Kostenlose App zum Entsperren von XLSM" sectionDescription=" Schauen Sie sich unsere Live-Demos an[XLSM-Dateien entsperren](https://products.aspose.app/cells/unlock/xlsm) mit folgenden Vorteilen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Sie müssen nichts herunterladen oder einrichten" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es ist nicht erforderlich, Code zu schreiben oder zu kompilieren" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach die Datei XLSM hoch und klicken Sie auf die Schaltfläche „Entsperren“." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Laden Sie die resultierende Datei XLSM über den Link herunter" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Dateien mit der Erweiterung XLSM sind Tabellenkalkulationsdateien, die Makros unterstützen. Aus Anwendungssicht handelt es sich bei einem Makro um eine Reihe von Anweisungen, die zur Automatisierung von Prozessen verwendet werden. Ein Makro wird verwendet, um die Schritte aufzuzeichnen, die wiederholt ausgeführt werden, und erleichtert die Ausführung der Aktionen durch erneutes Ausführen des Makros. Makros werden mit Visual Basic for Applications (VBA) von Microsoft aus der Excel-Arbeitsmappe heraus mit dem Visual Basic-Editor programmiert und können direkt von dort aus ausgeführt/debuggt werden.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Entsperrformate" subTitle="Mit C++ kann man den Schutz/die Entsperrung verschiedener Formate problemlos aufheben, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/ods/" name="ODS" description="OpenDocument-Tabellenkalkulationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xls/" name="XLS" description="Excel-Binärformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsb/" name="XLSB" description="Binäre Excel-Arbeitsmappendatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsx/" name="XLSX" description="OOXML-Excel-Datei" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
