---
title:  Cerca il documento XLSB senza aprire tramite C++
weight: 7020
description: C++ codice di esempio per cercare parole con pattern nel file XLSB su C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ search words with pattern in xlsb file., C++ find words with pattern in xlsb file., C++ search string with pattern in xlsb file., C++ find words with pattern in xlsb file., C++ search words in xlsb file., C++ find words in xlsb file., C++ search string in xlsb file., C++ find string in xlsb file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Cerca i formati XLSB in C++" h2="Ricerca di documenti XLSB nativa e ad alte prestazioni utilizzando le API Aspose.Cells for C++ lato server, senza l\'uso di software come Microsoft o Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come cercare il file XLSB utilizzando C++" %}}

 Per cercare il file XLSB, utilizzeremo
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per cercare i file XLSB in C++" %}}

{{% blocks/products/pf/agp/text %}}

 Una ricerca di documenti di base utilizzando le API Aspose.Cells può essere eseguita con poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

+ Carica il file XLSB istanziando una classe Workbook.
+ Istanzia la classe replaceOptions.
+ Imposta il modello richiesto come SetCaseSensitive(valore bool), SetMatchEntireCellContents(valore bool) .
Utilizza il metodo Workbook::Replace(...) con le opzioni pertinenti.
+ Salva il file XLSB utilizzando il metodo Workbook::Save(...).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ supporta tutte le principali piattaforme e sistemi operativi. Assicurati di possedere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
-  Aggiungi il riferimento alla DLL Aspose.Cells for C++ nel tuo progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cerca file XLSB - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load XLSB file
Workbook  wkb(srcDir + u"sourceFile.xlsb");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as XLSB file
wkb.Save(outDir + u"outputFile.xlsb");

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

    {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSB Cerca demo live" sectionDescription=" Cerca subito testo, parole e frasi all\'interno dei documenti XLSB visitando il nostro[Sito web delle demo dal vivo](https://products.aspose.app/cells/search). La demo live presenta i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non è necessario scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Basta caricare i tuoi file XLSB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Il risultato della ricerca viene visualizzato immediatamente." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB " readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Il formato file XLSB specifica il formato file binario di Excel, ovvero una raccolta di record e strutture che specificano il contenuto della cartella di lavoro di Excel. Il contenuto può includere tabelle di numeri non strutturate o semistrutturate, testo o sia numeri che testo, formule, connessioni dati esterne, grafici e immagini. A differenza di XLSX (che si basa sul formato file Open XML), XLSB rappresenta un file binario della cartella di lavoro di Excel. I file XLSB possono essere letti e scritti più velocemente, il che li rende utili per lavorare con file di grandi dimensioni. XLSB viene utilizzato raramente per archiviare le cartelle di lavoro poiché XLSX (e in precedenza XLS) sono i formati di file selezionati dall'utente più comuni per il salvataggio delle cartelle di lavoro. Può essere aperto da Microsoft Office 2007 e versioni successive.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri documenti di ricerca supportati" subTitle="Utilizzando C++, è possibile cercare anche altri file, inclusi." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="valori separati da virgola" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="File di foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="Valori separati da tabulazioni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="Documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="File di foglio di calcolo" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
