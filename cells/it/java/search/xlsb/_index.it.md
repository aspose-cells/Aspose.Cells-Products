---
title: Cerca il documento XLSB senza aprire tramite Java 
weight: 9420
url: /it/java/search/xlsb/ 
description: Java codice di esempio per cercare parole con pattern nel file XLSB in Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Cerca formati XLSB in Java" h2="Ricerca di documenti XLSB nativa e ad alte prestazioni utilizzando API Aspose.Cells for Java lato server, senza l\'uso di software come Microsoft o Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Come cercare file XLSB utilizzando Java" %}}

 Per cercare il file XLSB, useremo
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API che è una piattaforma di ricerca API for Java ricca di funzionalità, potente e facile da usare. Puoi scaricare la sua ultima versione direttamente da
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per cercare file XLSB in Java" %}}

{{% blocks/products/pf/agp/text %}}

 È possibile eseguire una ricerca di documenti di base utilizzando Aspose.Cells API con poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

+ Carica il file XLSB istanziando un oggetto Workbook.
+ Accedi al primo foglio di lavoro nel file XLSB.
+ Trova la cella contenente la formula specificata.
+ Istanzia FindOptions.
+ Trova la cella contenente un valore stringa
+ Stampa le celle trovate dopo il risultato della ricerca

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java supporta su tutte le principali piattaforme e sistemi operativi. Assicurati di avere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.- Ottieni l'ultima versione di Aspose.Cells for Java direttamente da [Esperto di](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cerca file XLSB - Java" offSpacer="" %}}

```cs
// Creazione di un'istanza di un oggetto Workbook
Workbook workbook = new Workbook(dataDir + "book1.xlsb");

// Accesso al primo foglio di lavoro nel file XLSB
Worksheet worksheet = workbook.getWorksheets().get(0);

// Trovare la cella contenente la formula specificata
Cells cells = worksheet.getCells();

// Istanziare FindOptions
FindOptions findOptions = new FindOptions();

// Trovare la cella contenente un valore stringa che inizia con Or
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// Stampa del nome della cella trovata dopo la ricerca 
System.out.println("Name of the cell containing String: " + cell.getName());  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Circa Aspose.Cells for Java API" %}}

 Aspose.Cells API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering di formati Microsoft Excel in formati diversi. Inoltre, può essere utilizzato per grafici completi, report scalabili e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="XLSB online Cerca demo dal vivo" sectionDescription="Cerca subito testo, parole, frasi all\'interno dei documenti XLSB visitando il nostro [Sito di demo dal vivo](https://products.aspose.app/cells/search). La demo dal vivo ha i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Carica i tuoi file XLSB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Il risultato della ricerca viene visualizzato immediatamente." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB " readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Il formato file XLSB specifica il formato file binario di Excel, che è una raccolta di record e strutture che specificano il contenuto della cartella di lavoro di Excel. Il contenuto può includere tabelle di numeri non strutturate o semi-strutturate, testo o sia numeri che testo, formule, connessioni dati esterne, grafici e immagini. A differenza di XLSX (che si basa sul formato di file Open XML), XLSB rappresenta il file binario della cartella di lavoro di Excel. I file XLSB possono essere letti e scritti più velocemente, il che li rende utili per lavorare con file di grandi dimensioni. XLSB viene utilizzato raramente per archiviare cartelle di lavoro poiché XLSX (e in precedenza XLS) sono i formati di file selezionati dall'utente più comuni per il salvataggio delle cartelle di lavoro. Può essere aperto da Microsoft Office 2007 e versioni successive. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri documenti di ricerca supportati" subTitle="Usando Java, puoi anche cercare altri file tra cui." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/csv/" name="CSV" description="valori separati da virgola" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/ods/" name="ODS" description="File del foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/tsv/" name="TSV" description="Valori separati da tabulazioni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/txt/" name="TXT" description="Documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xls/" name="XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="File foglio di lavoro" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}