---
title: Genera rapporti in file XLS tramite Java 
weight: 1090
url: /it/java/assembly/xls/ 
description: Java codice di esempio per creare report in formato XLS su Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Generazione di report in blocco in formato XLS tramite Java" h2="Genera report in formato XLS utilizzando un\'origine dati e un modello." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Come generare rapporti XLS utilizzando Java" %}}

 Per creare report di file XLS, utilizzeremo
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API che è una piattaforma di assemblaggio API for Java ricca di funzionalità, potente e facile da usare. Puoi scaricare la sua ultima versione direttamente da
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per generare rapporti XLS tramite Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Istanziare la classe WorkbookDesigner1. Aggiungi oggetti Datasouce in un ArrayList1. Impostare l'origine dati e il processo per l'oggetto WorkbookDesigner1. Salva il risultato in formato XLS tramite il metodo Worbook.save
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java supporta su tutte le principali piattaforme e sistemi operativi. Assicurati di avere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.- Ottieni l'ultima versione di Aspose.Cells for Java direttamente da Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Genera report Excel in formato XLS - C#" offSpacer="" %}}

```cs
//Crea un designer di cartelle di lavoro
WorkbookDesigner designer = new WorkbookDesigner(workbook);

//Crea oggetti Persone con foto
ArrayList persons = new ArrayList();       
persons.add(new Person("George", "New York", photo1));
persons.add(new Person("George", "New York", photo2));

//Impostare l'origine dati ed elaborare i tag Smart Marker
designer.setDataSource("Person", persons);
designer.process();

//Salva la cartella di lavoro
workbook.save(dataDir + "output.xls", SaveFormat.XLS);
	
System.out.println("File saved");
    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Circa Aspose.Cells for Java API" %}}

 Aspose.Cells API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering di formati Microsoft Excel in formati diversi. Inoltre, può essere utilizzato per grafici completi, report scalabili e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="App gratuita per assemblare XLS" sectionDescription="Controlla le nostre demo dal vivo su [creare file XLS](https://products.aspose.app/cells/assembly/xls) con i seguenti vantaggi." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare o configurare nulla" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere o compilare codice" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il file XLS e premere il pulsante \"Assembla\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Scarica il file XLS risultante dal link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
file con estensione XLS rappresentano il formato file binario di Excel. Tali file possono essere creati da Microsoft Excel e da altri programmi di fogli di calcolo simili come OpenOffice Calc o Apple Numbers. Il file salvato da Excel è noto come cartella di lavoro in cui ogni cartella di lavoro può avere uno o più fogli di lavoro. I dati vengono archiviati e visualizzati agli utenti in formato tabella nel foglio di lavoro e possono comprendere valori numerici, dati di testo, formule, connessioni dati esterne, immagini e grafici. Applicazioni come Microsoft Excel ti consentono di esportare i dati della cartella di lavoro in diversi formati tra cui PDF, CSV, XLSX, TXT, HTML, XPS e molti altri. Il formato di file XLS è stato sostituito con un formato più aperto e strutturato, XLSX, con il rilascio di Microsoft Excel 2007. Le ultime versioni forniscono ancora supporto per la creazione e la lettura di file XLS, sebbene XLSX sia la prima scelta di utilizzo ora.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri formati di generazione di rapporti supportati" subTitle="Utilizzando Java, è possibile generare facilmente rapporti di più formati, tra cui." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/ods/" name="ODS" description="File del foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsb/" name="XLSB" description="File di cartella di lavoro di Excel binario" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsm/" name="XLSM" description="File foglio di lavoro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsx/" name="XLSX" description="File Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}