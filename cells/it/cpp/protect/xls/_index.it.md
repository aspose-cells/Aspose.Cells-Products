---
title: Proteggi e blocca il documento XLS tramite C++ 
weight: 8760
url: /it/cpp/protect/xls/ 
description: C++ codice di esempio per bloccare il file XLS utilizzando la password in C++ Runtime Environment per Windows a 32 bit, Windows a 64 bit e Linux a 64 bit.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Crittografa i file XLS tramite C++" h2="Proteggi con password i fogli di lavoro Excel, incluso il formato XLS, utilizzando .NET Libreria." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp/" installationsDocsLink="https://docs.aspose.com/cells/cpp/" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come proteggere il file XLS utilizzando C++" %}}

 Per proteggere il file XLS, useremo
 [Aspose.Cells per C++](https://products.aspose.com/cells/cpp) 
 API che è una crittografia dei documenti API ricca di funzionalità, potente e facile da usare per la piattaforma C++. Puoi scaricare direttamente la sua ultima versione, basta aprire
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 gestore pacchetti, cerca
 **Aspose.Cells.Cpp** 
 e installa. È inoltre possibile utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per proteggere i file XLS tramite C++" %}}

{{% blocks/products/pf/agp/text %}}

 La protezione dei documenti utilizzando Aspose.Cells API può essere eseguita con poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file XLS usando la classe IWorkbook1. Utilizzare il metodo Protect(..) con ProtectionType e Password1. Salva il file XLS protetto con il metodo Save()
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells per C++ supporta su tutte le principali piattaforme e sistemi operativi. Assicurati di avere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con C++ Runtime Environment per Windows a 32 bit, Windows a 64 bit e Linux a 64 bit.- Aspose.Cells per C++ DLL a cui si fa riferimento nel tuo progetto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="" %}}

```cs

// Percorso di origine.
StringPtr srcDir = new String("SourcePath\");

// Percorso di uscita.
StringPtr outDir = new String("OutputPath\");

// Carica file XLS
intrusive_ptr<IWorkbook> workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sourceFile.xls")));

// Proteggi la cartella di lavoro specificando il tipo di protezione
workbook->Protect(ProtectionType::ProtectionType_All, new String("12345"));

// Salva il file XLS
workbook->Save(outDir->StringAppend(new String("output.xls")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Circa Aspose.Cells per C++ API" %}}

 Aspose.Cells API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering di formati Microsoft Excel in formati diversi. Inoltre, può essere utilizzato per grafici completi, report scalabili e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="App gratuita per proteggere XLS" sectionDescription="Controlla le nostre demo dal vivo su [crittografare i file XLS](https://products.aspose.app/cells/protect/xls) con i seguenti vantaggi." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare o configurare nulla" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere o compilare codice" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il file XLS e premere il pulsante \"Sblocca\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Scarica il file XLS risultante dal link" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
file con estensione XLS rappresentano il formato file binario di Excel. Tali file possono essere creati da Microsoft Excel e da altri programmi di fogli di calcolo simili come OpenOffice Calc o Apple Numbers. Il file salvato da Excel è noto come cartella di lavoro in cui ogni cartella di lavoro può avere uno o più fogli di lavoro. I dati vengono archiviati e visualizzati agli utenti in formato tabella nel foglio di lavoro e possono comprendere valori numerici, dati di testo, formule, connessioni dati esterne, immagini e grafici. Applicazioni come Microsoft Excel ti consentono di esportare i dati della cartella di lavoro in diversi formati tra cui PDF, CSV, XLSX, TXT, HTML, XPS e molti altri. Il formato di file XLS è stato sostituito con un formato più aperto e strutturato, XLSX, con il rilascio di Microsoft Excel 2007. Le ultime versioni forniscono ancora supporto per la creazione e la lettura di file XLS, sebbene XLSX sia la prima scelta di utilizzo ora.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri documenti di protezione supportati" subTitle="Utilizzando C++, è possibile proteggere altri file tra cui." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/ods/" name="ODS" description="File del foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsb/" name="XLSB" description="File di cartella di lavoro di Excel binario" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsm/" name="XLSM" description="File foglio di lavoro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsx/" name="XLSX" description="File Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}