---
title: Converti ODS in TXT tramite l'applicazione C++ 
url: /it/cpp/conversion/ods-to-txt/ 
description: Esempio di codice di conversione C++ per il documento ODS in formato TXT. I programmatori possono utilizzare questo codice sorgente per la conversione batch da ODS a TXT all'interno di qualsiasi applicazione C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti ODS in TXT tramite C++" h2="Conversione da ODS a TXT ad alte prestazioni utilizzando la libreria C++ senza la necessità di installare Microsoft Excel, OpenOffice o Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="TXT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come convertire ODS in TXT utilizzando C++" %}}

 Per convertire ODS in TXT, useremo
 [Aspose.Cells per C++](https://products.aspose.com/cells/cpp) 
 API che è una piattaforma di manipolazione e conversione di documenti API ricca di funzionalità, potente e facile da usare per C++. Puoi scaricare direttamente la sua ultima versione, basta aprire
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 gestore pacchetti, cerca
 Aspose.Cells.Cpp 
 e installa. È inoltre possibile utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire ODS in TXT tramite C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ gli sviluppatori possono convertire facilmente i file ODS in TXT in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file ODS usando Factory::CreateIWorkbook.1. Chiama il metodo Save().1. Passa il percorso del file di output con l'estensione del file (TXT).1. Il file TXT verrà salvato nel percorso specificato.1. Apri il file TXT nel programma compatibile.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di esempio di conversione C++, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows a 32 bit, Windows a 64 bit e Linux a 64 bit.- Aspose.Cells per C++ DLL a cui si fa riferimento nel tuo progetto.
- Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows a 32 bit, Windows a 64 bit e Linux a 64 bit.- Aspose.Cells per C++ DLL a cui si fa riferimento nel tuo progetto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice sorgente di conversione da ODS a TXT C++" offSpacer="" %}}

```cs
// Carica l'ODS.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.ods");

// Salva in formato TXT.
wkb->Save(u"convertedFile.txt", SaveFormat_Txt);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demo live di conversione da ODS a TXT" sectionDescription="[Converti ODS in TXT](https://products.aspose.app/cells/conversion/ods-to-txt) in questo momento visitando il nostro sito Web di demo dal vivo. La demo dal vivo ha i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il tuo file ODS, verrà convertito istantaneamente in TXT." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai il link per il download." >}}

    {{% blocks/products/pf/agp/content h2="C++ Libreria di manipolazione dei file di Excel" %}}

 Excel API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering di formati Microsoft Excel in formati diversi. Inoltre, può essere utilizzato per grafici completi, report scalabili e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}

I file con estensione ODS stanno per il formato OpenDocument Spreadsheet Document che sono modificabili dall'utente. I dati vengono archiviati all'interno del file ODF in righe e colonne. È un formato basato su XML ed è uno dei numerosi sottotipi della famiglia Open Document Formats (ODF). Il formato è specificato come parte delle specifiche ODF 1.2 pubblicate e mantenute da OASIS. Numerose applicazioni su Windows e altri sistemi operativi possono aprire file ODS per la modifica e la manipolazione, inclusi Microsoft Excel, NeoOffice e LibreOffice. I file ODS possono anche essere convertiti in altri formati di fogli di calcolo, come XLS, XLSX e altri da diverse applicazioni.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}

Un file con estensione .TXT rappresenta un documento di testo che contiene testo normale sotto forma di righe. I paragrafi in un documento di testo sono riconosciuti dai ritorni a capo e sono utilizzati per una migliore disposizione del contenuto del file. Un documento di testo standard può essere aperto in qualsiasi editor di testo o applicazione di elaborazione testi su diversi sistemi operativi. Tutto il testo contenuto in tale file è in formato leggibile e rappresentato da una sequenza di caratteri.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire ODS in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-bmp/" name="ODS A BMP" description="Immagine bitmap" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-csv/" name="ODS A CSV" description="valori separati da virgola" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-dif/" name="ODS A DIF" description="Formato di scambio dati" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-emf/" name="ODS A EMF" description="Formato Metafile migliorato" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-gif/" name="ODS DA GIF" description="Formato di scambio grafico" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-html/" name="ODS IN HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-jpeg/" name="ODS IN JPEG" description="Immagine JPEG" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-mhtml/" name="ODS A MHTML" description="Formato di archivio della pagina web" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-pdf/" name="ODS IN PDF" description="Formato documento portatile" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-png/" name="ODS A PNG" description="Grafica di rete portatile" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-svg/" name="ODS A SVG" description="Grafica vettoriale scalabile" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-tiff/" name="ODS A TIFF" description="Formato immagine contrassegnato" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-tsv/" name="ODS AL TSV" description="Valori separati da tabulazioni" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xls/" name="ODS A XLS" description="Formato binario Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xlsb/" name="ODS A XLSB" description="File di cartella di lavoro di Excel binario" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xlsm/" name="ODS A XLSM" description="File foglio di lavoro" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xlsx/" name="ODS A XLSX" description="File Excel OOXML" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xltm/" name="ODS A XLTM" description="Modello abilitato alle macro di Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xltx/" name="ODS A XLTX" description="Modello di Office OpenXML Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/ods-to-xps/" name="ODS A XPS" description="Specifiche della carta XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}