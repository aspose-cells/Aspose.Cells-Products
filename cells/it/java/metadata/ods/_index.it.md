---
title:  Modifica o visualizza i metadati dei file ODS via Java
weight: 2080
description: Codice di esempio Java per modificare o visualizzare i metadati del formato ODS sull'ambiente runtime Java per applicazioni JSP/JSF e applicazioni desktop.
keywords: [Java Aspose.Cells., Java view ods metadata., Java add ods metadata., Java insert ods metadata., Java edit ods metadata., Java remove ods metadata., Java extract ods metadata., Java modify ods metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Estratto ODS Metadati via Java" h2="Crea le tue app Java per aggiungere, modificare, rimuovere o estrarre metadati dai file ODS utilizzando API lato server." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Come estrarre i metadati ODS utilizzando Java" %}}

 Per ottenere i metadati del file ODS, utilizzeremo
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API che è una piattaforma di metadati API for Java ricca di funzionalità, potente e facile da usare. Puoi scaricare la versione più recente direttamente da
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per estrarre i metadati di ODS via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Accedi a informazioni utili memorizzate nel file ODS, incluso quando il file ODS è stato ricevuto, elaborato, timestamp e così via.

{{% /blocks/products/pf/agp/text %}}

+ Carica il file ODS all'interno di WorkbookMetadata
+ Crea oggetto MetadataOptions con opzioni pertinenti
+ Imposta le proprietà rilevanti
+ Salva le informazioni sui metadati ODS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java supporta tutte le principali piattaforme e sistemi operativi. Assicurati di possedere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatibile con Java Ambiente runtime per applicazioni JSP/JSF e applicazioni desktop.
-  Ottieni l'ultima versione di Aspose.Cells for Java direttamente da
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Estrai metadati di ODS - Java" offSpacer="" %}}

```cs

// Open Workbook metadata
MetadataOptions options = new MetadataOptions(MetadataType.DOCUMENT_PROPERTIES);
WorkbookMetadata meta = new WorkbookMetadata("Sample1.ods", options);

// Set some properties
meta.getCustomDocumentProperties().add("test", "test");

// Save the metadata info
meta.save("Sample1.out.ods");

// Open the workbook
Workbook w = new Workbook("Sample1.out.ods");

// Read document property
System.out.println(w.getCustomDocumentProperties().get("test"));  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Informazioni su Aspose.Cells for Java API" %}}

 Aspose.Cells API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering dei formati Excel Microsoft in diversi formati. Inoltre, può essere utilizzato per grafici completi, reporting scalabile e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Estrai i metadati di ODS tramite l\'app online" sectionDescription=" Visualizza e modifica i metadati nei documenti ODS utilizzando il nostro[Demo dal vivo](https://products.aspose.app/cells/metadata) con i seguenti vantaggi." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare o configurare nulla" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non è necessario scrivere alcun codice" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il file ODS e modificare le proprietà del documento" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ottieni immediatamente il collegamento per il download del file risultante" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
file con estensione ODS indicano il formato del documento OpenDocument Spreadsheet modificabile dall'utente. I dati vengono archiviati nel file ODF in righe e colonne. È un formato basato su XML ed è uno dei numerosi sottotipi della famiglia Open Document Formats (ODF). Il formato è specificato come parte delle specifiche ODF 1.2 pubblicate e mantenute da OASIS. Numerose applicazioni su Windows e altri sistemi operativi possono aprire file ODS per la modifica e la manipolazione, inclusi Microsoft Excel, NeoOffice e LibreOffice. I file ODS possono anche essere convertiti in altri formati di fogli di calcolo come XLS, XLSX e altri da diverse applicazioni.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di metadati supportati" subTitle="Utilizzando Java, è anche possibile manipolare metadati di molti altri formati, inclusi" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xls/" name="XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsb/" name="XLSB" description="File binario della cartella di lavoro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsm/" name="XLSM" description="File di foglio di calcolo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsx/" name="XLSX" description="File Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
