---
title: Estrai testo e immagini dal documento ODS tramite C++
weight: 9130
description: C++ codice di esempio per estrarre testo e immagini dal file ODS su C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ Extract text and images from ODS file., C++ How to Parse ODS File., C++ Extract text from ODS file., Extract images from ODS file using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Analizza i formati ODS in C++" h2="Analisi dei documenti ODS nativa e ad alte prestazioni utilizzando le API Aspose.Cells for C++ lato server, senza l\'uso di software come Microsoft o Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come analizzare il file ODS utilizzando C++" %}}

 Per analizzare il file ODS, utilizzeremo[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) API che è una piattaforma di analisi dei documenti API for C++ ricca di funzionalità, potente e facile da usare. Puoi scaricare direttamente la sua ultima versione, basta aprirla[NuGet](https://www.nuget.org/packages/aspose.cells) gestore pacchetti, cerca**Aspose.Cells.Cpp** e installare. Puoi anche utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per analizzare i file ODS in C++" %}}

{{% blocks/products/pf/agp/text %}}

 Un documento di base con cui eseguire l'analisi[Aspose.Cells for C++](https://products.aspose.com/cells/cpp)Le API possono essere eseguite con poche righe di codice. Analizza testo e immagini dai file Microsoft Excel XLS, XLSX, XLSM, XLSB e OpenDocument ODS.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ supporta tutte le principali piattaforme e sistemi operativi. Assicurati di possedere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
-  Aggiungi il riferimento alla DLL Aspose.Cells for C++ nel tuo progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Analizza i file ODS - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// extract images from Worksheets 
// open a template Excel file
Workbook workbook(u"sampleExtractImagesFromWorksheets.ods");

// get the first worksheet
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// get the first Picture in the first worksheet
Picture pic = worksheet.GetPictures().Get(0);

// Note: you may evaluate the image format before specifying the image path
// define ImageOrPrintOptions
ImageOrPrintOptions printoption;

// specify the image format
printoption.SetImageType(ImageType::Jpeg);

// save the image
pic.ToImage(u"outputExtractImagesFromWorksheets.jpg", printoption);

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Informazioni su Aspose.Cells for C++ API" %}}

 Aspose.Cells API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering dei formati Excel Microsoft in diversi formati. Inoltre, può essere utilizzato per grafici completi, reporting scalabile e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online ODS Demo live del parser" sectionDescription="Estrai testo e immagini dai documenti ODS adesso visitando il nostro[Sito web delle demo dal vivo](https://products.aspose.app/cells/parser). La demo live presenta i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non è necessario scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare i tuoi file ODS." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Verrà analizzato immediatamente." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
 I file con estensione ODS indicano il formato del documento OpenDocument Spreadsheet modificabile dall'utente. I dati vengono archiviati nel file ODF in righe e colonne. È un formato basato su XML ed è uno dei numerosi sottotipi della famiglia Open Document Formats (ODF). Il formato è specificato come parte delle specifiche ODF 1.2 pubblicate e mantenute da OASIS. Numerose applicazioni su Windows e altri sistemi operativi possono aprire file ODS per la modifica e la manipolazione, inclusi Microsoft Excel, NeoOffice e LibreOffice. I file ODS possono anche essere convertiti in altri formati di fogli di calcolo come XLS, XLSX e altri da diverse applicazioni.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri documenti di analisi supportati" subTitle="Utilizzando C++, è possibile analizzare facilmente altri formati, inclusi." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xls/" name="XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsb/" name="XLSB" description="File binario della cartella di lavoro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsm/" name="XLSM" description="File di foglio di calcolo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/parser/xlsx/" name="XLSX" description="File Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
