---
title: Converti XLSX in JPG tramite l'applicazione C++ 
url: /it/cpp/conversion/xlsx-to-jpg/ 
description: Esempio di codice di conversione C++ per il documento XLSX in formato JPG. I programmatori possono utilizzare questo codice sorgente per la conversione batch da XLSX a JPG all'interno di qualsiasi applicazione C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti XLSX in JPG tramite C++" h2="Conversione da XLSX a JPG ad alte prestazioni utilizzando la libreria C++ senza la necessità di installare Microsoft Excel, OpenOffice o Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come convertire XLSX in JPG usando C++" %}}

 Per convertire XLSX in JPG, useremo
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire XLSX in JPG tramite C++" %}}

{{% blocks/products/pf/agp/text %}}

 C++ gli sviluppatori possono convertire facilmente file XLSX in JPG in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file XLSX usando Factory::CreateIWorkbook.1. Chiama il metodo Save().1. Passa il percorso del file di output con l'estensione del file (JPG).1. Il file JPG verrà salvato nel percorso specificato.1. Apri il file JPG in un programma compatibile.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di esempio di conversione C++, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows a 32 bit, Windows a 64 bit e Linux a 64 bit.- Aspose.Cells per C++ DLL a cui si fa riferimento nel tuo progetto.
- Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows a 32 bit, Windows a 64 bit e Linux a 64 bit.- Aspose.Cells per C++ DLL a cui si fa riferimento nel tuo progetto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice sorgente di conversione da XLSX a JPG C++" offSpacer="" %}}

```cs
// Carica l'XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsx");

// Salva in formato JPG.
wkb->Save(u"convertedFile.jpg", SaveFormat_Jpg);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Dimostrazioni live di conversione da XLSX a JPG" sectionDescription="[Converti XLSX in JPG](https://products.aspose.app/cells/conversion/xlsx-to-jpg) in questo momento visitando il nostro sito Web di demo dal vivo. La demo dal vivo ha i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il tuo file XLSX, verrà convertito istantaneamente in JPG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai il link per il download." >}}

    {{% blocks/products/pf/agp/content h2="C++ Libreria di manipolazione dei file di Excel" %}}

 Excel API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering di formati Microsoft Excel in formati diversi. Inoltre, può essere utilizzato per grafici completi, report scalabili e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}

XLSX è un formato noto per i documenti Microsoft Excel che è stato introdotto da Microsoft con il rilascio di Microsoft Office 2007. Basato su una struttura organizzata secondo le Open Packaging Conventions come delineato nella Parte 2 dello standard OOXML ECMA-376, il nuovo formato è un pacchetto zip che contiene un numero di file XML. La struttura ei file sottostanti possono essere esaminati semplicemente decomprimendo il file .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

Un JPEG è un tipo di formato immagine che viene salvato utilizzando il metodo di compressione con perdita di dati. L'immagine di output, come risultato della compressione, è un compromesso tra la dimensione della memoria e la qualità dell'immagine. Gli utenti possono regolare il livello di compressione per ottenere il livello di qualità desiderato riducendo allo stesso tempo le dimensioni dello storage. La qualità dell'immagine viene influenzata in modo trascurabile se all'immagine viene applicata la compressione 10:1. Maggiore è il valore di compressione, maggiore è il degrado della qualità dell'immagine.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire XLSX in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-bmp/" name="XLSX A BMP" description="Immagine bitmap" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-csv/" name="XLSX IN CSV" description="valori separati da virgola" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-dif/" name="XLSX A DIF" description="Formato di scambio dati" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-emf/" name="XLSX A EMF" description="Formato Metafile migliorato" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-gif/" name="XLSX IN GIF" description="Formato di scambio grafico" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-html/" name="XLSX IN HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-jpeg/" name="XLSX IN JPEG" description="Immagine JPEG" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-mhtml/" name="XLSX IN MHTML" description="Formato di archivio della pagina web" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-ods/" name="XLSX A ODS" description="File del foglio di calcolo OpenDocument" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-pdf/" name="XLSX IN PDF" description="Formato documento portatile" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-png/" name="XLSX IN PNG" description="Grafica di rete portatile" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-svg/" name="XLSX IN SVG" description="Grafica vettoriale scalabile" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-tiff/" name="XLSX IN TIFF" description="Formato immagine contrassegnato" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-tsv/" name="XLSX A TSV" description="Valori separati da tabulazioni" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xls/" name="XLSX A XLS" description="Formato binario Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xlsb/" name="XLSX A XLSB" description="File di cartella di lavoro di Excel binario" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xlsm/" name="XLSX A XLSM" description="File foglio di lavoro" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xltm/" name="XLSX A XLTM" description="Modello abilitato alle macro di Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xltx/" name="XLSX A XLTX" description="Modello di Office OpenXML Excel" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xps/" name="XLSX A XPS" description="Specifiche della carta XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}