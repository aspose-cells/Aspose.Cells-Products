---
title: Sloučit soubory CSV přes Java 
weight: 3860
url: /cs/java/merger/csv/ 
description: Java ukázkový kód pro kombinaci dokumentů CSV v Java Runtime Environment pro aplikace JSP/JSF a aplikace pro stolní počítače.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Sloučit formáty CSV v Java" h2="Sloučení nativních dokumentů CSV pomocí rozhraní API Java na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak sloučit soubory CSV pomocí Java" %}}

 Abychom sloučili soubor CSV, použijeme
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, což je funkčně bohatá, výkonná a snadno použitelná platforma pro slučování API for Java. Jeho nejnovější verzi si můžete stáhnout přímo z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 a nainstalujte jej do svého projektu založeného na Maven přidáním následujících konfigurací do souboru pom.xml.

{{% blocks/products/pf/agp/code-block title="úložiště" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Závislost" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro sloučení souborů CSV v Java" %}}

{{% blocks/products/pf/agp/text %}}

 Základní dokument, který se spojuje a spojuje
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 Rozhraní API lze vytvořit pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

Načtěte první soubor CSV s instancí třídy Workbook.
+ Načtěte druhý dokument CSV s instancí třídy Workbook.
+ Sloučit soubory pomocí metody Combined().
+ uložte sloučený soubor CSV do zadané cesty

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java podporuje na všech hlavních platformách a operačních systémech. Ujistěte se prosím, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.- Získejte nejnovější verzi Aspose.Cells for Java přímo od [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Sloučit soubory CSV – Java" offSpacer="" %}}

```cs
// Otevřete první soubor CSV.
Workbook csvFile1 = new Workbook("chartsFileWithPath.csv");

// Definujte druhou zdrojovou knihu.
// Otevřete druhý soubor CSV.
Workbook csvFile2 = new Workbook("pictureFileWithPath.csv");

// Kombinace dvou sešitů
csvFile1.combine(csvFile2);

// Uložte soubor cílové knihy.
csvFile1.save("combinedFileWithPath.csv");  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for Java API" %}}

 Aspose.Cells API lze použít k vytváření, úpravám, převodu a vykreslování formátů aplikace Microsoft Excel do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelné výkazy a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online živé ukázky fúze CSV" sectionDescription="Sloučit dokumenty CSV hned teď, když navštívíte naše [Web živé ukázky](https://products.aspose.app/cells/merger). Živé demo má následující výhody" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Stačí nahrát soubory CSV." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Okamžitě bude sloučen a zřetězen." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}
Soubory s příponou CSV (Comma Separated Values) představují prosté textové soubory, které obsahují záznamy dat s hodnotami oddělenými čárkami. Každý řádek v souboru CSV je nový záznam ze sady záznamů obsažených v souboru. Takové soubory se generují, když je zamýšlený přenos dat z jednoho úložného systému do druhého. Protože všechny aplikace dokážou rozpoznat záznamy oddělené čárkou, import takových datových souborů do databáze se provádí velmi pohodlně. Téměř všechny tabulkové aplikace, jako je Microsoft Excel nebo OpenOffice Calc, dokážou importovat CSV bez velkého úsilí. Data importovaná z takových souborů jsou uspořádána do buněk tabulkového procesoru pro reprezentaci uživateli. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované slučovací formáty" subTitle="Pomocí Java lze také sloučit mnoho dalších formátů souborů, včetně..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Formát archivu webové stránky" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Hodnoty oddělené tabulátory" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Textový dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Binární soubor sešitu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Soubor tabulky" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Soubor Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Šablona aplikace Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Šablona s podporou maker aplikace Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltx/" name="XLTX" description="Šablona Office OpenXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}