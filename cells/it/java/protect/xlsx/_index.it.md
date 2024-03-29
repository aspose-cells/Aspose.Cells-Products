---
title:  Proteggi e blocca il documento XLSX via Java
weight: 1870
description: Codice di esempio Java per bloccare il file XLSX utilizzando la password sull'ambiente runtime Java per applicazioni JSP/JSF e applicazioni desktop.
keywords: [Java Aspose.Cells., Java Lock XLSX files., Java How to Protect and lock XLSX document., Java Protect XLSX files., Encrypt XLSX Files using Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Crittografa XLSX file via Java" h2="Fogli di calcolo Excel protetti da password incluso il formato XLSX utilizzando la libreria .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java/" installationsDocsLink="https://docs.aspose.com/cells/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Come proteggere il file XLSX utilizzando Java" %}}

 Per proteggere il file XLSX, utilizzeremo
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API che è una piattaforma di crittografia API for Java ricca di funzionalità, potente e facile da usare. Puoi scaricare la versione più recente direttamente da
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 e installalo nel tuo progetto basato su Maven aggiungendo le seguenti configurazioni a pom.xml.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Deposito" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per proteggere i file XLSX via Java" %}}

{{% blocks/products/pf/agp/text %}}

 La protezione dei documenti utilizzando le API Aspose.Cells può essere eseguita con poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1.  Carica il file XLSX istanziando la classe Workbook
1.  Utilizzare il metodo Protect(..) con ProtectionType e Password
1.  Salvare il file protetto XLSX con il metodo save()

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java supporta tutte le principali piattaforme e sistemi operativi. Assicurati di possedere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows o un sistema operativo compatibile con Java Ambiente runtime per applicazioni JSP/JSF e applicazioni desktop.
-  Ottieni l'ultima versione di Aspose.Cells for Java direttamente da
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dipendenza" offSpacer="" %}}

```cs

// Open the XLSX file
Workbook wkb = new Workbook("sourceFile.xlsx");

// Protect workbook by specifying protection type
wkb.protect(ProtectionType.ALL, "12345");

// Save the XLSX file
wkb.save("lockedFile.xlsx");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Informazioni su Aspose.Cells for Java API" %}}

 Aspose.Cells API può essere utilizzato per creare, modificare, convertire ed eseguire il rendering dei formati Excel Microsoft in diversi formati. Inoltre, può essere utilizzato per grafici completi, reporting scalabile e calcoli affidabili all'interno di applicazioni software. Aspose.Cells è un API autonomo e non richiede alcun software come Microsoft o OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="App gratuita per proteggere XLSX" sectionDescription=" Controlla le nostre demo dal vivo per[crittografare i file XLSX](https://products.aspose.app/cells/protect/xlsx) con i seguenti vantaggi." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare o configurare nulla" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non è necessario scrivere o compilare codice" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il file XLSX e premere il pulsante \"Sblocca\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Scaricare il file XLSX risultante dal collegamento" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX è un formato noto per i documenti Excel Microsoft introdotto da Microsoft con il rilascio di Microsoft Office 2007. Basato sulla struttura organizzata secondo le convenzioni Open Packaging come delineato nella Parte 2 dello standard OOXML ECMA-376, il nuovo formato è un pacchetto zip che contiene una serie di file XML. La struttura e i file sottostanti possono essere esaminati semplicemente decomprimendo il file .xlsx.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altri documenti di protezione supportati" subTitle="Utilizzando Java, è possibile proteggere altri file inclusi." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/ods/" name="ODS" description="File di foglio di calcolo OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xls/" name="XLS" description="Formato binario Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsb/" name="XLSB" description="File binario della cartella di lavoro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsm/" name="XLSM" description="File di foglio di calcolo" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
