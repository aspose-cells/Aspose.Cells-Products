---
title:  Cerca il documento ODS senza aprire tramite C++
weight: 3300
description: C++ codice di esempio per cercare parole con pattern nel file ODS su C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ search words with pattern in ods file., C++ find words with pattern in ods file., C++ search string with pattern in ods file., C++ find words with pattern in ods file., C++ search words in ods file., C++ find words in ods file., C++ search string in ods file., C++ find string in ods file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Cerca i formati ODS in C++" h2="Ricerca di documenti ODS nativa e ad alte prestazioni utilizzando le API Aspose.Cells for C++ lato server, senza l\'uso di software come Microsoft o Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come cercare il file ODS utilizzando C++" %}}

 Per cercare il file ODS, utilizzeremo
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API che è una piattaforma di ricerca di documenti ricca di funzionalità, potente e facile da usare API for C++. Puoi scaricare direttamente la sua ultima versione, basta aprirla
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 gestore pacchetti, cerca
 **Aspose.Cells.Cpp** 
 e installare. Puoi anche utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per cercare i file ODS in C++" %}}

{{% blocks/products/pf/agp/text %}}

 Una ricerca di documenti di base utilizzando le API Aspose.Cells può essere eseguita con poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

+ Carica il file ODS istanziando una classe Workbook.
+ Istanzia la classe replaceOptions.
+ Imposta il modello richiesto come SetCaseSensitive(valore bool), SetMatchEntireCellContents(valore bool) .
Utilizza il metodo Workbook::Replace(...) con le opzioni pertinenti.
+ Salva il file ODS utilizzando il metodo Workbook::Save(...).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ supporta tutte le principali piattaforme e sistemi operativi. Assicurati di possedere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
-  Aggiungi il riferimento alla DLL Aspose.Cells for C++ nel tuo progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cerca file ODS - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load ODS file
Workbook  wkb(srcDir + u"sourceFile.ods");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as ODS file
wkb.Save(outDir + u"outputFile.ods");

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

    {{< blocks/products/pf/agp/demobox sectionTitle="Online ODS Cerca demo live" sectionDescription=" Cerca subito testo, parole e frasi all\'interno dei documenti ODS visitando il nostro[Sito web delle demo dal vivo](https://products.aspose.app/cells/search). La demo live presenta i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non è necessario scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Basta caricare i tuoi file ODS." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Il risultato della ricerca viene visualizzato immediatamente." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS " readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
 file con estensione ODS indicano il formato del documento OpenDocument Spreadsheet modificabile dall'utente. I dati vengono archiviati nel file ODF in righe e colonne. È un formato basato su XML ed è uno dei numerosi sottotipi della famiglia Open Document Formats (ODF). Il formato è specificato come parte delle specifiche ODF 1.2 pubblicate e mantenute da OASIS. Numerose applicazioni su Windows e altri sistemi operativi possono aprire file ODS per la modifica e la manipolazione, inclusi Microsoft Excel, NeoOffice e LibreOffice. I file ODS possono anche essere convertiti in altri formati di fogli di calcolo come XLS, XLSX e altri da diverse applicazioni.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri documenti di ricerca supportati" subTitle="Utilizzando C++, è possibile cercare anche altri file, inclusi." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="valori separati da virgola" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="Valori separati da tabulazioni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="Documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsb/" name="XLSB" description="File binario della cartella di lavoro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="File di foglio di calcolo" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
