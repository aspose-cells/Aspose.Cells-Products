---
title: Converti XLSB in JSON tramite Java 
weight: 9970
url: /it/java/conversion/xlsb-to-json/ 
description: Esempio di codice di conversione Java per il formato XLSB in file JSON. I programmatori possono utilizzare questo codice di esempio per esportare fogli di calcolo Excel e OpenOffice in JSON all'interno di qualsiasi applicazione basata su Web o desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti XLSB in JSON tramite Java" h2="Conversione da XLSB a JSON Java per convertire pagine singole o multiple in JSON utilizzando la libreria Java on-premise." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Come convertire XLSB in JSON usando Java" %}}

 Per rendere XLSB in JSON, useremo
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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire XLSB in JSON tramite Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java gli sviluppatori possono convertire facilmente file XLSB in JSON in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica il file XLSB con un'istanza della classe Workbook1. Crea un intervallo di dati da esportare utilizzando il metodo Cells.createRange1. Chiama il metodo JsonUtility.exportRangeToJson con riferimenti a Range & ExportRangeToJsonOptions1. Scrivi i dati JSON della stringa su file tramite il metodo BufferedWriter.write
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice sorgente di conversione Java, assicurati di disporre dei seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con Java Runtime Environment per applicazioni JSP/JSF e applicazioni desktop.- Ottieni l'ultima versione di Aspose.Cells for Java direttamente da Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice sorgente di conversione da XLSB a JSON Java" offSpacer="" %}}

```cs
// carica il file XLSX con un'istanza di Workbook
Workbook workbook = new Workbook("template.xlsx");
// accedere a CellsCollection del foglio di lavoro contenente i dati da convertire
Cells cells = workbook.getWorksheets().get(0).getCells();
// crea e imposta ExportRangeToJsonOptions per opzioni avanzate
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// creare un intervallo di celle contenenti dati da esportare
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// intervallo di esportazione come dati JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// scrivere i dati su disco in formato JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Dimostrazioni live di conversione da XLSB a JSON" sectionDescription="[Converti XLSB in JSON](https://products.aspose.app/cells/conversion/xlsb-to-json) in questo momento visitando il nostro sito Web di demo dal vivo. La demo dal vivo ha i seguenti vantaggi" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il tuo file XLSB, verrà convertito istantaneamente in JSON." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai il link per il download." >}}

    {{% blocks/products/pf/agp/content h2="Java Libreria di manipolazione del foglio di lavoro" %}}

 Excel API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering di formati Microsoft Excel in formati diversi. Inoltre, può essere utilizzato per grafici completi, report scalabili e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

Il formato file XLSB specifica il formato file binario di Excel, che è una raccolta di record e strutture che specificano il contenuto della cartella di lavoro di Excel. Il contenuto può includere tabelle di numeri non strutturate o semi-strutturate, testo o sia numeri che testo, formule, connessioni dati esterne, grafici e immagini. A differenza di XLSX (che si basa sul formato di file Open XML), XLSB rappresenta il file binario della cartella di lavoro di Excel. I file XLSB possono essere letti e scritti più velocemente, il che li rende utili per lavorare con file di grandi dimensioni. XLSB viene utilizzato raramente per archiviare cartelle di lavoro poiché XLSX (e in precedenza XLS) sono i formati di file selezionati dall'utente più comuni per il salvataggio delle cartelle di lavoro. Può essere aperto da Microsoft Office 2007 e versioni successive.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (JavaScript Object Notation) è un formato di file standard aperto per la condivisione di dati che utilizza testo leggibile per archiviare e trasmettere dati. I file JSON vengono archiviati con l'estensione .json. JSON richiede meno formattazione ed è una buona alternativa per XML. JSON è derivato da JavaScript ma è un formato di dati indipendente dalla lingua. La generazione e l'analisi di JSON è supportata da molti linguaggi di programmazione moderni. application/json è il tipo di supporto utilizzato per JSON.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire XLSB in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-bmp/" name="XLSB A BMP" description="Immagine bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-csv/" name="XLSB IN CSV" description="valori separati da virgola" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-dif/" name="XLSB A DIF" description="Formato di scambio dati" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-emf/" name="XLSB A EMF" description="Formato Metafile migliorato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-gif/" name="XLSB IN GIF" description="Formato di scambio grafico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-html/" name="XLSB IN HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-jpeg/" name="XLSB IN JPEG" description="Immagine JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-mhtml/" name="XLSB IN MHTML" description="Formato di archivio della pagina web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-ods/" name="XLSB A ODS" description="File del foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-pdf/" name="XLSB IN PDF" description="Formato documento portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-png/" name="XLSB IN PNG" description="Grafica di rete portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-svg/" name="XLSB IN SVG" description="Grafica vettoriale scalabile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-tiff/" name="XLSB IN TIFF" description="Formato immagine contrassegnato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-tsv/" name="XLSB A TSV" description="Valori separati da tabulazioni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-txt/" name="XLSB IN TXT" description="Documento di testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xls/" name="XLSB A XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlsm/" name="XLSB A XLSM" description="File foglio di lavoro" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlsx/" name="XLSB A XLSX" description="File Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlt/" name="XLSB A XLT" description="Modello Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xltm/" name="XLSB A XLTM" description="Modello abilitato alle macro di Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xltx/" name="XLSB A XLTX" description="Modello di Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xps/" name="XLSB A XPS" description="Specifiche della carta XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}