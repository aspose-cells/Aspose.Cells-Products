---
title: Converti TABDELIMITED in EMF tramite Java 
url: /it/java/conversion/tabdelimited-to-emf/ 
description: Esempio di codice di conversione Java per il formato TABDELIMITED in file EMF. I programmatori possono utilizzare questo codice di esempio per esportare fogli di calcolo Excel e OpenOffice in EMF all'interno di qualsiasi applicazione basata su Web o desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti TABDELIMITED in EMF tramite Java" h2="Conversione da TABDELIMITED a EMF Java per convertire pagine singole o multiple in EMF utilizzando la libreria Java on-premise." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TABDELIMITED" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Come convertire TABDELIMITED in EMF utilizzando Java" %}}

 Per rendere TABDELIMITED a EMF, useremo
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API che è una piattaforma di conversione API for Java ricca di funzionalità, potente e facile da usare. Puoi scaricare la sua ultima versione direttamente da
 [Esperto di](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 e installalo all'interno del tuo progetto basato su Maven aggiungendo le seguenti configurazioni a pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dipendenza" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire TABDELIMITED in EMF tramite Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java gli sviluppatori possono convertire facilmente il file TABDELIMITED in EMF in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file TABDELIMITED con un'istanza di Workbook1. Seleziona l'impostazione predefinita o qualsiasi foglio di lavoro dalla raccolta1. Crea e imposta l'oggetto di ImageOrPrintOptions1. Crea SheetRender con Foglio di lavoro e oggetti ImageOrPrintOptions1. Chiama il metodo SheetRender.toImage per salvare il risultato in formato EMF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice sorgente di conversione Java, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.- Ottieni l'ultima versione di Aspose.Cells for Java direttamente da Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TABDELIMITED a EMF Java codice sorgente di conversione" offSpacer="" %}}

```cs
// caricare il file TABDELIMITED di cui eseguire il rendering
Workbook workbook = new Workbook("sourceFile.tabdelimited");
// accedere al foglio di lavoro predefinito dalla raccolta
Worksheet worksheet = workbook.getWorksheets().get(0);
// definire i parametri per l'immagine risultante
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.EMF);
// converti foglio di lavoro in immagine in formato EMF
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.emf");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demo dal vivo di conversione da TABDELIMITED a EMF" sectionDescription="[Converti TABDELIMITED in EMF](https://products.aspose.app/cells/conversion/tabdelimited-to-emf) in questo momento visitando il nostro sito Web di demo dal vivo. La demo dal vivo ha i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il tuo file TABDELIMITED, verrà convertito istantaneamente in EMF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai il link per il download." >}}

    {{% blocks/products/pf/agp/content h2="Java Libreria di manipolazione del foglio di lavoro" %}}

 Excel API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering di formati Microsoft Excel in formati diversi. Inoltre, può essere utilizzato per grafici completi, report scalabili e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" >}}

Il formato metafile avanzato (EMF) memorizza le immagini grafiche indipendentemente dal dispositivo. I metafile di EMF comprendono record di lunghezza variabile in ordine cronologico che possono eseguire il rendering dell'immagine archiviata dopo l'analisi su qualsiasi dispositivo di output. Questi record a lunghezza variabile possono essere definizioni di oggetti racchiusi, comandi per il disegno e proprietà grafiche fondamentali per il rendering accurato dell'immagine. Quando un dispositivo apre un metafile EMF utilizzando il proprio ambiente grafico, le proporzioni, le dimensioni, i colori e altre proprietà grafiche dell'immagine originale rimangono le stesse indipendentemente dalla piattaforma del dispositivo di apertura.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}