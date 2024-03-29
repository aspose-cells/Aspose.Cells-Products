---
title:  Cerca il documento XLSX senza aprire via .NET
weight: 4880
description: Codice sorgente C# per cercare parole con pattern nel file XLSX su .NET Framework, .NET Core, Mono o piattaforme Xamarin.
keywords: [C# Aspose.Cells., c# search words with pattern in XLSX file., c# find words with pattern in XLSX file., c# search string with pattern in XLSX file., c# find words with pattern in XLSX file., c# search words in excel file., c# find words in excel file., c# search string in excel file., c# find string in excel file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Cerca i formati XLSX in C#" h2="Ricerca di documenti XLSX nativa e ad alte prestazioni utilizzando le API Aspose.Cells for .NET lato server, senza l\'uso di software come Microsoft o Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come cercare il file XLSX utilizzando C#" %}}

 Per cercare il file XLSX, utilizzeremo
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API che è un documento ricco di funzionalità, potente e facile da usare per la ricerca di documenti API per la piattaforma C#. Aprire
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per cercare i file XLSX in C#" %}}

{{% blocks/products/pf/agp/text %}}

 Una ricerca di documenti di base con
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 Le API possono essere eseguite con poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

+ Carica il file XLSX utilizzando la classe Workbook.
+ Ottieni le celle nel foglio pertinente.
+ Cerca Numbers, data e testo utilizzando il metodo Trova

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Le nostre API sono supportate su tutte le principali piattaforme e sistemi operativi. Prima di eseguire il codice seguente, assicurati di avere i seguenti prerequisiti sul tuo sistema.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatibile con .NET Framework, .NET Core, Mono o piattaforme Xamarin
-  Ambiente di sviluppo come Microsoft Visual Studio
-  Aggiungi riferimento alla DLL Aspose.Cells for .NET nel tuo progetto - Installa da NuGet utilizzando il pulsante Download in alto

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cerca file XLSX - C#" offSpacer="" %}}

```cs
// searching cells containing specified string value or number
Workbook workbook = new Workbook("book1.xlsx");

// get cells collection
Cells cells = workbook.Worksheets[0].Cells;

FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.EntireContent;

// find the cell with the input integer or double
Cell cell1 = cells.Find(205, null, opts);

if (cell1 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell1.Name);
}else{
    Console.WriteLine("Record not found ");
}

// find the cell with the input string
Aspose.Cells.Cell cell2 = cells.Find("Items A", null, opts);

if (cell2 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell2.Name);
}else{
    Console.WriteLine("Record not found ");
}

// find the cell containing with the input string
opts.LookAtType = LookAtType.Contains;
Cell cell3 = cells.Find("Data", null, opts);

if (cell3 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell3.Name);
}else{
    Console.WriteLine("Record not found ");
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

        {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSX Cerca demo live" sectionDescription=" Cerca subito testo, parole e frasi all\'interno dei documenti XLSX visitando il nostro[Sito web delle demo dal vivo](https://products.aspose.app/cells/search). La demo live presenta i seguenti vantaggi" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non è necessario scrivere alcun codice." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Basta caricare i tuoi file XLSX." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Il risultato della ricerca viene visualizzato immediatamente." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX " readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX è un formato noto per i documenti Excel Microsoft introdotto da Microsoft con il rilascio di Microsoft Office 2007. Basato sulla struttura organizzata secondo le convenzioni Open Packaging come delineato nella Parte 2 dello standard OOXML ECMA-376, il nuovo formato è un pacchetto zip che contiene una serie di file XML. La struttura e i file sottostanti possono essere esaminati semplicemente decomprimendo il file .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di ricerca supportati" subTitle="Utilizzando C#, è possibile cercare anche altri formati, inclusi." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/csv/" name="CSV" description="valori separati da virgola" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/ods/" name="ODS" description="File di foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/tsv/" name="TSV" description="Valori separati da tabulazioni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/txt/" name="TXT" description="Documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xls/" name="XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsb/" name="XLSB" description="File binario della cartella di lavoro Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
