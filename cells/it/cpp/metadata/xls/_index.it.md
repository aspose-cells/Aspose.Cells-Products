---
title:  Modifica o visualizza i metadati del documento XLS tramite C++
weight: 2150
description: C++ codice di esempio per modificare o visualizzare i metadati del file XLS su C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ view xls metadata., C++ add xls metadata., C++ insert xls metadata., C++ edit xls metadata., C++ remove xls metadata., C++ extract xls metadata., C++ modify xls metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Estrai metadati XLS tramite C++" h2="Crea le tue app C++ per aggiungere, modificare, rimuovere o estrarre metadati dai file XLS utilizzando API lato server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come ottenere i metadati XLS utilizzando C++" %}}

Per estrarre i metadati XLS, utilizzeremo
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API che è una piattaforma di estrazione dei metadati dei documenti ricca di funzionalità, potente e facile da usare API for C++. Puoi scaricare direttamente la sua ultima versione, basta aprirla
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per estrarre i metadati di XLS tramite C++" %}}

{{% blocks/products/pf/agp/text %}}

 Accedi a informazioni utili memorizzate nel file XLS, incluso quando il file XLS è stato ricevuto, elaborato, timestamp e così via.

{{% /blocks/products/pf/agp/text %}}

+ Crea opzioni utilizzando MetadataOptions
+ Carica il file XLS utilizzando WorkbookMetadata
+ Aggiungi nuove proprietà con GetCustomDocumentProperties() e Aggiungi
+ Salva documento XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ supporta tutte le principali piattaforme e sistemi operativi. Assicurati di possedere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows 32 bit, Windows 64 bit e Linux 64 bit.
-  Aggiungi il riferimento alla DLL Aspose.Cells for C++ nel tuo progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Estrai metadati di XLS - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

//Load the sample excel file
MetadataOptions options(MetadataType::Document_Properties);
WorkbookMetadata meta(u"c:\\book1.xls", options);
//Add a new custom property
meta.GetCustomDocumentProperties().Add(u"test", u"test");
//Save the output excel file
meta.Save(u"c:\\book2.xls"); 

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

        {{< blocks/products/pf/agp/demobox sectionTitle="Estrai i metadati di XLS tramite l\'app online" sectionDescription=" Visualizza e modifica i metadati nei documenti XLS utilizzando il nostro[Demo dal vivo](https://products.aspose.app/cells/metadata) con i seguenti vantaggi." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare o configurare nulla" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non è necessario scrivere alcun codice" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il file XLS e modificare le proprietà del documento" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ottieni immediatamente il collegamento per il download del file risultante" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
file con estensione XLS rappresentano il formato file binario di Excel. Tali file possono essere creati da Microsoft Excel così come altri programmi di fogli di calcolo simili come OpenOffice Calc o Apple Numbers. Il file salvato da Excel è noto come cartella di lavoro in cui ciascuna cartella di lavoro può avere uno o più fogli di lavoro. I dati vengono archiviati e visualizzati agli utenti in formato tabella nel foglio di lavoro e possono comprendere valori numerici, dati di testo, formule, connessioni dati esterne, immagini e grafici. Applicazioni come Microsoft Excel ti consentono di esportare i dati della cartella di lavoro in diversi formati tra cui PDF, CSV, XLSX, TXT, HTML, XPS e molti altri. Il formato file XLS è stato sostituito con un formato più aperto e strutturato, XLSX, con il rilascio di Microsoft Excel 2007. Le ultime versioni forniscono ancora supporto per la creazione e la lettura dei file XLS, sebbene XLSX sia ora la prima scelta di utilizzo.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di metadati supportati" subTitle="Utilizzando C++, è anche possibile manipolare metadati di molti altri formati, inclusi" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/ods/" name="ODS" description="File di foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="File binario della cartella di lavoro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsm/" name="XLSM" description="File di foglio di calcolo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsx/" name="XLSX" description="File Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
