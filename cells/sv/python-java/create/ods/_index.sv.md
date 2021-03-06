---
title: Skapa ODS-filer (Openoffice / Lbreoffice) via Python 
url: /sv/python-java/create-ods/ 
description: Python Exempelkod för att generera ODS-dokument. Använd den här koden för att skapa ODS-filer (Openoffice / Lbreoffice) i programmet Python.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Skapa ODS-dokument via Python" h2="Inbyggt och högpresterande ODS (Openoffice / Lbreoffice) kalkylark skapade programmatiskt med hjälp av Python API:er." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/python" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Att generera ODS (Openoffice / Lbreoffice) fil dynamiskt inom ett program som körs är enkelt. För att skapa ODS-dokument från grunden utan att behöva MS Office kommer vi att använda
 [Aspose.Cells för Python](https://pypi.org/project/aspose-cells) 
 API som erbjuder olika funktioner för att skapa, manipulera och konvertera kalkylark med hjälp av Python-plattformen. Utvecklare kan enkelt förbättra kod för att skriva data, generera diagram eller grafer samt skapa tabeller i kalkylblad.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Så här skapar du ODS via Python" %}}

{{% blocks/products/pf/agp/text %}}

 Det är lätt för utvecklarna att skapa, ladda, modifiera och konvertera ODS (Openoffice / Lbreoffice) kalkylblad inom att köra olika rapporteringsapplikationer för databehandling på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Importera asposeceller i din kodfil.1. Skapa Workbook-klassinstans.1. Öppna det första kalkylbladet i arbetsboken.1. Hämta önskad cell(er) i kalkylbladet och mata in värdet i cellen(erna).1. Använd metoden Spara för att spara arbetsboken som ODS-fil.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells för Python via Java är plattformsoberoende API och kan användas på alla plattformar (Windows, Linux och MacOS), se bara till att systemet har Java 1.8 eller högre, [Python](https://www.python.org/downloads/) 3,5 eller högre. 

{{% /blocks/products/pf/agp/text %}}

- Installera Java och lägg till den i PATH-miljövariabeln, till exempel: <code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.- Installera Aspose.Cells för Python via Java från <a href="https://pypi.org/project/aspose-cells/">pypi</a>, använd kommandot som: <code>$ pip install aspose-cells</code>.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Följande källkod visar hur du skapar en ODS-fil (Openoffice / Lbreoffice) med Python." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

// Skapa arbetsboksobjekt.
workbook = Workbook(FileFormatType.ODS)

// Öppna det första kalkylbladet i arbetsboken.
worksheet = workbook.getWorksheets().get(0)

// Hämta önskad cell(er) i kalkylbladet och mata in värdet i cellen(erna).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Spara arbetsboken som ODS-fil.
workbook.save("output.ods")

jpype.shutdownJVM()


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Ett Excel Spreadsheet Programming Library som kan bygga plattformsoberoende applikationer med förmågan att generera, modifiera, konvertera, rendera och skriva ut ODS (Openoffice / Lbreoffice) filer. Python API konverterar inte bara mellan kalkylarksformat, den kan också återge Excel-filer som bilder, PDF, HTML, ODS och mer, vilket gör det till ett perfekt val att utbyta dokument i branschstandardformat.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Filer med filtillägget .ods står för OpenDocument Spreadsheet Document-format som kan redigeras av användaren. Data lagras i ODF-filen i rader och kolumner. Det är XML-baserat format och är en av flera undertyper i familjen Open Document Formats (ODF). Formatet specificeras som en del av ODF 1.2-specifikationerna som publiceras och underhålls av OASIS. Ett antal applikationer på Windows såväl som andra operativsystem kan öppna ODS-filer för redigering och manipulering, inklusive Microsoft Excel, NeoOffice och LibreOffice. ODS-filer kan också konverteras till andra kalkylbladsformat som XLS, XLSX och andra av olika applikationer.
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}   

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Annan kalkylarksgenerering som stöds" subTitle="Du kan också skapa andra Microsoft Excel-format inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xls/" name="XLS" description="Microsoft Excel-kalkylblad (legacy)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsx/" name="XLSX" description="Öppna XML-arbetsbok" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsb/" name="XLSB" description="Excel binär arbetsbok" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsm/" name="XLSM" description="Makroaktiverat kalkylblad" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlt/" name="XLT" description="Excel 97 - 2003 mall" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltx/" name="XLTX" description="Excel-mall" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltm/" name="XLTM" description="Excel-makroaktiverad mall" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-csv/" name="CSV" description="Kommaseparerade värden" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-tsv/" name="TSV" description="Flikseparerade värden" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-ods/" name="ODS" description="OpenDocument Kalkylblad" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
