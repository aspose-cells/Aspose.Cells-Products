---
title:  Cerca il documento TXT senza aprire via Java
weight: 1200
description: Codice di esempio Java per cercare parole con pattern nel file TXT nell'ambiente runtime Java per applicazioni JSP/JSF e applicazioni desktop.
keywords: [Java Aspose.Cells., Java search words with pattern in txt file., Java find words with pattern in txt file., Java search string with pattern in txt file., Java find words with pattern in txt file., Java search words in txt file., Java find words in txt file., Java search string in txt file., Java find string in txt file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Cerca i formati TXT in Java" h2="Ricerca di documenti TXT nativa e ad alte prestazioni utilizzando le API Aspose.Cells for Java lato server, senza l\'uso di software come Microsoft o Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Come cercare il file TXT utilizzando Java" %}}

 Per cercare il file TXT, utilizzeremo
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API che è una piattaforma di ricerca API for Java ricca di funzionalità, potente e facile da usare. Puoi scaricare la versione più recente direttamente da
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 e installalo nel tuo progetto basato su Maven aggiungendo le seguenti configurazioni a pom.xml.

{{% blocks/products/pf/agp/code-block title="Deposito" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per cercare i file TXT in Java" %}}

{{% blocks/products/pf/agp/text %}}

 Una ricerca di documenti di base utilizzando le API Aspose.Cells può essere eseguita con poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

+ Carica il file TXT istanziando un oggetto Workbook.
+ Accedi al primo foglio di lavoro nel file TXT.
+ Trova la cella contenente la formula specificata.
+ Istanzia FindOptions.
+ Trova la cella contenente un valore stringa
Stampa le celle trovate dopo il risultato della ricerca

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java supporta tutte le principali piattaforme e sistemi operativi. Assicurati di possedere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatibile con Java Ambiente runtime per applicazioni JSP/JSF e applicazioni desktop.
-  Ottieni l'ultima versione di Aspose.Cells for Java direttamente da
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cerca file TXT - Java" offSpacer="" %}}

```cs
// Instantiating a Workbook object
Workbook workbook = new Workbook(dataDir + "book1.txt");

// Accessing the first worksheet in the TXT file
Worksheet worksheet = workbook.getWorksheets().get(0);

// Finding the cell containing the specified formula
Cells cells = worksheet.getCells();

// Instantiate FindOptions
FindOptions findOptions = new FindOptions();

// Finding the cell containing a string value that starts with Or
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// Printing the name of the cell found after searching 
System.out.println("Name of the cell containing String: " + cell.getName());  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Informazioni su Aspose.Cells for Java API" %}}

 Aspose.Cells API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering dei formati Excel Microsoft in diversi formati. Inoltre, può essere utilizzato per grafici completi, reporting scalabile e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online TXT Cerca demo live" sectionDescription=" Cerca subito testo, parole e frasi all\'interno dei documenti TXT visitando il nostro[Sito web delle demo dal vivo](https://products.aspose.app/cells/search). La demo live presenta i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non è necessario scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Basta caricare i tuoi file TXT." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Il risultato della ricerca viene visualizzato immediatamente." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT " readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}
Un file con estensione .TXT rappresenta un documento di testo che contiene testo semplice sotto forma di righe. I paragrafi in un documento di testo vengono riconosciuti dai ritorni a capo e vengono utilizzati per una migliore disposizione del contenuto del file. Un documento di testo standard può essere aperto in qualsiasi editor di testo o applicazione di elaborazione testi su diversi sistemi operativi. Tutto il testo contenuto in tale file è in formato leggibile dall'uomo e rappresentato da una sequenza di caratteri.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri documenti di ricerca supportati" subTitle="Utilizzando Java, è possibile cercare anche altri file, inclusi." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/csv/" name="CSV" description="valori separati da virgola" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/ods/" name="ODS" description="File di foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/tsv/" name="TSV" description="Valori separati da tabulazioni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xls/" name="XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsb/" name="XLSB" description="File binario della cartella di lavoro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="File di foglio di calcolo" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
