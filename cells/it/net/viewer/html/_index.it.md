---
title:  Visualizza HTML Formati file via .NET
description: Codice sorgente C# per caricare, eseguire il rendering e visualizzare i documenti HTML su .NET Framework, .NET Core, Windows Azure, Mono o piattaforme Xamarin.
keywords: [C# Aspose.Cells., c# view HTML files., c# how to render HTML document., c# load and display HTML files., HTML File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="HTML Visualizzatore File for .NET" h2="Visualizza fogli di calcolo Excel e OpenOffice come HTML senza richiedere Microsoft Excel o Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come visualizzare il file HTML utilizzando C#" %}}

 Per visualizzare il file HTML, utilizzeremo<a href="https://products.aspose.com/cells/net">Aspose.Cells for .NET</a>API che è una piattaforma API per C# ricca di funzionalità, potente e facile da usare con qualsiasi visualizzatore. Aprire<a href="https://www.nuget.org/packages/aspose.cells">NuGet</a> gestore pacchetti, cerca<b>Aspose.Cells</b> e installare. Puoi anche utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di Gestione pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per visualizzare HTML tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells consente agli sviluppatori di visualizzare facilmente il file HTML con solo poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file HTML in un'istanza di Workbook
1. Crea un'istanza di HtmlSaveOptions e imposta la proprietà ExportHeadings su true
1. Salva il file HTML nel formato HTML utilizzando il metodo Workbook.Save
1. Carica il risultante HTML nel browser predefinito con Process.Start


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET è supportato su tutti i principali sistemi operativi. Assicurati solo di avere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatibile con .NET Framework, .NET Core, Windows Azure, Mono o piattaforme Xamarin
-  Ambiente di sviluppo come Microsoft Visual Studio
-  Aggiungi riferimento alla DLL Aspose.Cells for .NET nel tuo progetto

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice di esempio C# per visualizzare il file HTML" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the HTML file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.html");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the HTML file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Cells API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering dei formati Excel Microsoft in diversi formati. Inoltre, può essere utilizzato per grafici completi, reporting scalabile e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="App gratuita per visualizzare HTML" sectionDescription=" Controlla le nostre demo dal vivo per[Visualizza HTML](https://products.aspose.app/cells/viewer/html) con i seguenti vantaggi." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare o configurare nulla" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non è necessario scrivere o compilare codice" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il file HTML e premere il pulsante \"Visualizza\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Scaricare il file HTML dal collegamento, se richiesto" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (Hyper Text Markup Language) è l'estensione per le pagine web creata per la visualizzazione nei browser. Conosciuto come linguaggio del web, HTML si è evoluto con i requisiti di nuove informazioni da visualizzare come parte delle pagine web. L'ultima variante è nota come HTML 5 che offre molta flessibilità per lavorare con la lingua. HTML le pagine vengono ricevute dal server, dove sono ospitate, oppure possono essere caricate anche dal sistema locale. Ogni pagina HTML è composta da HTML elementi come moduli, testo, immagini, animazioni, collegamenti, ecc. Questi elementi sono rappresentati da tag come img, a, p e molti altri in cui ogni tag ha un inizio e una fine. Può anche incorporare applicazioni scritte in linguaggi di scripting come JavaScript e Fogli di stile (CSS) per la rappresentazione complessiva del layout.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
