---
title: Crea JPEG - Crea file JPEG in C#
description: Aspose Excel. C# Crea il file JPEG in modo semplice e veloce con Aspose.Cells. Genera il file JPEG utilizzando C#. Crea JPEG in C#. C# JPEG Creatore.
keywords: [Aspose Excel., C# Aspose.Cells., C# Create JPEG file., Generate JPEG file in C#., Create JPEG file using C#., Write data to JPEG file via C#., Create a JPEG file in C#., C# Generate a JPEG file., C# JPEG Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Crea il file JPEG in C#" h2="Libreria C# ad alta velocità per la creazione di JPEG. Si tratta di una soluzione software professionale per importare ed esportare XLSX, PDF e molti altri formati sulle piattaforme .NET Framework, .NET Core o Mono." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Crea il file JPEG utilizzando C#" %}}
 Come creare il file JPEG? Con la libreria Aspose.Cells for .NET, puoi creare facilmente il file JPEG a livello di codice con poche righe di codice.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)è in grado di creare applicazioni multipiattaforma con la capacità di generare, modificare, convertire, eseguire il rendering e stampare tutti i file Excel. .NET Excel API non solo converte tra formati di foglio di calcolo, ma può anche eseguire il rendering di file Excel come immagini, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT e altro, rendendolo quindi una scelta perfetta per scambiare documenti in formati standard del settore. Aprire[NuGet](https://www.nuget.org/packages/aspose.cells) gestore pacchetti, cerca Aspose.Cells e installa. Puoi anche utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di Gestione pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}
 
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="Come creare JPEG in C#" %}}

{{% blocks/products/pf/agp/text %}}

 È facile per gli sviluppatori creare, caricare, modificare e convertire i file JPEG eseguendo diverse applicazioni di reporting per l'elaborazione dei dati in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1.  Includi lo spazio dei nomi nel file della classe
1.  Crea un'istanza della classe Workbook.
1.  Accedi al primo foglio di lavoro della cartella di lavoro.
1.  Ottieni le celle desiderate del foglio di lavoro e inserisci il valore nelle celle.
1.  Utilizzare il metodo Salva per salvare la cartella di lavoro come file JPEG.

{{% blocks/products/pf/agp/code-block title="Il codice di esempio mostra come creare il file JPEG in C#." offSpacer="" %}}

```cs

// Create Workbook class instance.
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet sht = wkb.Worksheets[0];

// Get the desired cell(s) of the worksheet.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// input the value into the cell(s).
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Save the Workbook as .jpg file.
wkb.Save("created_one.jpg");

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="Libreria C# per creare il file JPEG" %}}

{{% blocks/products/pf/agp/text %}}

Esistono due opzioni alternative per installare "Aspose.Cells for .NET" sul tuo sistema. Scegline uno che soddisfi le tue esigenze e segui le istruzioni passo passo:

{{% /blocks/products/pf/agp/text %}}

1.  Installa un[NuGet Pacchetto](https://www.nuget.org/packages/Aspose.Cells/) . Vedere[Documentazione](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Installa la libreria utilizzando[Console di gestione pacchetti](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) all'interno dell'IDE di Visual Studio

{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di esempio di conversione .NET, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatibile con le piattaforme .NET, .NET Core, Windows Azure o Mono.
-  Ambiente di sviluppo come Microsoft Visual Studio.
-  Aggiungi il riferimento alla DLL Aspose.Cells for .NET nel tuo progetto.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpg/" >}}A JPEG è un tipo di formato immagine che viene salvato utilizzando il metodo di compressione con perdita. L'immagine di output, come risultato della compressione, è un compromesso tra le dimensioni di archiviazione e la qualità dell'immagine. Gli utenti possono regolare il livello di compressione per ottenere il livello di qualità desiderato e allo stesso tempo ridurre le dimensioni di archiviazione. La qualità dell'immagine viene influenzata in modo trascurabile se all'immagine viene applicata la compressione 10:1. Maggiore è il valore di compressione, maggiore sarà il degrado della qualità dell'immagine.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altra generazione di fogli di calcolo supportata" subTitle="Puoi anche creare altri formati Excel Microsoft inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xls/" name="XLS" description="Microsoft Foglio di calcolo Excel (precedente)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsx/" name="XLSX" description="Apri la cartella di lavoro XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsb/" name="XLSB" description="Cartella di lavoro binaria di Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsm/" name="XLSM" description="Foglio di calcolo abilitato per le macro" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlt/" name="XLT" description="Modello Excel 97-2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltx/" name="XLTX" description="Modello Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltm/" name="XLTM" description="Modello con attivazione macro di Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/csv/" name="CSV" description="valori separati da virgola" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/tsv/" name="TSV" description="Valori separati da tabulazioni" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/ods/" name="ODS" description="Foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/pdf/" name="PDF" description="Formato documento portatile" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/html/" name="HTML" description="Hyper Text Markup Language" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
