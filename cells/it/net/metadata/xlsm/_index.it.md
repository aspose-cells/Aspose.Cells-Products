---
title:  Visualizza o modifica i metadati dei file XLSM via .NET
weight: 5590
description: Codice sorgente C# per modificare o visualizzare i metadati del formato XLSM sulle piattaforme .NET Framework, .NET Core, Mono o Xamarin.
keywords: [C# Aspose.Cells., c# view xlsm metadata., c# add xlsm metadata., c# insert xlsm metadata., c# edit xlsm metadata., c# remove xlsm metadata., c# extract xlsm metadata., c# modify xlsm metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Estratto XLSM Metadati via .NET" h2="Crea le tue app .NET per aggiungere, modificare, rimuovere o estrarre metadati dai file XLSM utilizzando API lato server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come estrarre i metadati XLSM utilizzando C#" %}}

Per estrarre i metadati XLSM, utilizzeremo
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API che è un metadata di documento ricco di funzionalità, potente e facile da usare API per la piattaforma C#. Aprire
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 gestore pacchetti, cerca
 **Aspose.Cells** 
 e installare. Puoi anche utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per estrarre i metadati di XLSM tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

 Accedi a informazioni utili memorizzate nel file XLSM, incluso quando il file XLSM è stato ricevuto, elaborato, timestamp e così via.

{{% /blocks/products/pf/agp/text %}}

+ Carica XLSM con un'istanza di Workbook
+ Ottieni la raccolta BuiltInDocumentProperties dell'oggetto Workbook
+ Itera sulla raccolta
+ Visualizza nome, tipo e valore della proprietà

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET è supportato su tutti i principali sistemi operativi. Assicurati solo di avere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con .NET Framework, .NET Core, Mono o piattaforme Xamarin.
-  Ambiente di sviluppo come Microsoft Visual Studio.
-  Aggiungi il riferimento alla DLL Aspose.Cells for .NET nel tuo progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Estrai metadati di XLSM - C#" offSpacer="" %}}

```cs

// load the XLSM with an instance of Workbook
var book = new Aspose.Cells.Workbook("template.xlsm");
// iterate over the BuiltInDocumentProperties collection
foreach (Aspose.Cells.Properties.DocumentProperty property in book.Worksheets.BuiltInDocumentProperties)
{
    Console.WriteLine($"\tType:\t{property.Type}");

    // Some properties may store multiple values
    if (property.Value is Array)
    {
        foreach (object value in property.Value as Array)
            Console.WriteLine($"\tValue:\t\"{value}\"");
    }
    else
    {
        Console.WriteLine($"\tValue:\t\"{property.Value}\"");
    }
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Informazioni su Aspose.Cells for .NET API" %}}

 Aspose.Cells API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering dei formati Excel Microsoft in diversi formati. Inoltre, può essere utilizzato per grafici completi, reporting scalabile e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Estrai i metadati di XLSM tramite l\'app online" sectionDescription=" Visualizza e modifica i metadati nei documenti XLSM utilizzando il nostro[Demo dal vivo](https://products.aspose.app/cells/metadata) con i seguenti vantaggi." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare o configurare nulla" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non è necessario scrivere alcun codice" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il file XLSM e modificare le proprietà del documento" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ottieni immediatamente il collegamento per il download del file risultante" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
file con estensione XLSM sono un tipo di file di foglio di calcolo che supportano le macro. Dal punto di vista applicativo, una Macro è un insieme di istruzioni utilizzate per automatizzare i processi. Una macro viene utilizzata per registrare i passaggi eseguiti ripetutamente e facilita l'esecuzione delle azioni eseguendo nuovamente la macro. Le macro vengono programmate con Visual Basic for Applications (VBA) di Microsoft dalla cartella di lavoro di Excel utilizzando l'editor di Visual Basic e possono essere eseguite/debug direttamente da lì.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di metadati supportati" subTitle="Utilizzando C#, è anche possibile manipolare metadati di molti altri formati, inclusi." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/ods/" name="ODS" description="File di foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xls/" name="XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsb/" name="XLSB" description="File binario della cartella di lavoro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/metadata/xlsx/" name="XLSX" description="File Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
