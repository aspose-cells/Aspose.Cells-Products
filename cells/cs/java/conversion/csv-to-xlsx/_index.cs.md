---
title: Převést CSV na XLSX prostřednictvím Java 
weight: 5180
url: /cs/java/conversion/csv-to-xlsx/ 
description: Ukázkový konverzní kód Java pro formát CSV na soubor XLSX. Programátoři mohou použít tento příklad kódu k exportu tabulek Excelu a OpenOffice do XLSX v jakékoli webové nebo desktopové aplikaci založené na Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést CSV na XLSX prostřednictvím Java" h2="Převod CSV na XLSX Java pro převod jedné nebo více stránek na XLSX pomocí místní knihovny Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak převést CSV na XLSX pomocí Java" %}}

 vykreslení CSV do XLSX použijeme
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, což je funkčně bohatá, výkonná a snadno použitelná konverzní API for Java platforma. Jeho nejnovější verzi si můžete stáhnout přímo z
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky k převodu CSV na XLSX prostřednictvím Java" %}}

{{% blocks/products/pf/agp/text %}}

 Vývojáři Java mohou snadno převést soubor CSV na XLSX pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor CSV s instancí třídy Workbook1. Zavolejte metodu Workbook.save1. Předejte výstupní cestu s rozšířením XLSX a SaveFormat jako parametry1. Zkontrolujte zadanou cestu pro výsledný soubor XLSX
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním zdrojového kódu konverze Java se ujistěte, že splňujete následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.- Získejte nejnovější verzi Aspose.Cells for Java přímo od společnosti Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód konverze CSV na XLSX Java" offSpacer="" %}}

```cs
// načíst soubor CSV v instanci sešitu
Workbook book = new Workbook("template.csv");
// uložit CSV jako XLSX
book.save("output.xlsx", SaveFormat.AUTO);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Živá ukázka konverze CSV na XLSX" sectionDescription="[Převést CSV na XLSX](https://products.aspose.app/cells/conversion/csv-to-xlsx) právě teď na naší webové stránce s živými ukázkami. Živá ukázka má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát svůj soubor CSV a bude okamžitě převeden na XLSX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Dostanete odkaz ke stažení." >}}

    {{% blocks/products/pf/agp/content h2="Java Knihovna manipulace s tabulkami" %}}

 Excel API lze použít k vytváření, úpravám, převodu a vykreslování formátů Microsoft Excel do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelné výkazy a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

Soubory s příponou CSV (Comma Separated Values) představují prosté textové soubory, které obsahují záznamy dat s hodnotami oddělenými čárkami. Každý řádek v souboru CSV je nový záznam ze sady záznamů obsažených v souboru. Takové soubory se generují, když je zamýšlený přenos dat z jednoho úložného systému do druhého. Protože všechny aplikace dokážou rozpoznat záznamy oddělené čárkou, import takových datových souborů do databáze se provádí velmi pohodlně. Téměř všechny tabulkové aplikace, jako je Microsoft Excel nebo OpenOffice Calc, dokážou importovat CSV bez velkého úsilí. Data importovaná z takových souborů jsou uspořádána do buněk tabulkového procesoru pro reprezentaci uživateli.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}

XLSX je dobře známý formát pro dokumenty Microsoft Excel, který byl představen společností Microsoft s vydáním Microsoft Office 2007. Na základě struktury organizované podle Open Packaging Conventions, jak je uvedeno v části 2 standardu OOXML ECMA-376, je nový formát zip balíček, který obsahuje řadu souborů XML. Základní strukturu a soubory lze prozkoumat jednoduchým rozbalením souboru .xlsx.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="Můžete také převést CSV do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-bmp/" name="CSV DO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-dif/" name="CSV DO DIF" description="Formát výměny dat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-emf/" name="CSV DO EMF" description="Vylepšený formát metasouborů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-gif/" name="CSV NA GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-html/" name="CSV DO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-jpeg/" name="CSV DO JPEG" description="Obrázek JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-mhtml/" name="CSV DO MHTML" description="Formát archivu webové stránky" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-ods/" name="CSV DO ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-pdf/" name="CSV DO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-png/" name="CSV DO PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-svg/" name="CSV DO SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-tiff/" name="CSV NA TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-tsv/" name="CSV DO TSV" description="Hodnoty oddělené tabulátory" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-txt/" name="CSV DO TXT" description="Textový dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlm/" name="CSV DO XLM" description="Soubor makra Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xls/" name="CSV DO XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlsb/" name="CSV DO XLSB" description="Binární soubor sešitu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xlt/" name="CSV DO XLT" description="Šablona aplikace Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xltm/" name="CSV DO XLTM" description="Šablona s podporou maker aplikace Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xltx/" name="CSV DO XLTX" description="Šablona Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-xps/" name="CSV DO XPS" description="Specifikace papíru XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/csv-to-json/" name="CSV TO JSON" description="Zápis objektů JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}