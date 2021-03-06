---
title: Převést ODS na JPEG prostřednictvím Java 
weight: 3640
url: /cs/java/conversion/ods-to-jpeg/ 
description: Ukázka převodního kódu Java pro formát ODS na soubor JPEG. Programátoři mohou tento příklad kódu použít k exportu tabulek Excelu a OpenOffice do formátu JPEG v jakékoli webové nebo desktopové aplikaci založené na Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést ODS na JPEG prostřednictvím Java" h2="Převod ODS na JPEG Java pro převod jedné nebo více stránek na JPEG pomocí místní knihovny Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak převést ODS na JPEG pomocí Java" %}}

 K vykreslení ODS do JPEG použijeme
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod ODS na JPEG prostřednictvím Java" %}}

{{% blocks/products/pf/agp/text %}}

 Vývojáři Java mohou snadno převést soubor ODS na JPEG pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor ODS s instancí Workbook1. Vyberte výchozí nebo libovolný pracovní list z kolekce1. Vytvořte a nastavte objekt ImageOrPrintOptions1. Vytvořte SheetRender s objekty Worksheet & ImageOrPrintOptions1. Voláním metody SheetRender.toImage uložíte výsledek ve formátu JPEG
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním zdrojového kódu konverze Java se ujistěte, že splňujete následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.- Získejte nejnovější verzi Aspose.Cells for Java přímo od společnosti Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód převodu ODS na JPEG Java" offSpacer="" %}}

```cs
// načtěte soubor ODS, který se má vykreslit
Workbook workbook = new Workbook("sourceFile.ods");
// přístup k výchozímu listu z kolekce
Worksheet worksheet = workbook.getWorksheets().get(0);
// definovat parametry pro výsledný obrázek
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.JPEG);
// převést pracovní list na obrázek ve formátu JPEG
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.jpeg");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Živá ukázka konverze ODS na JPEG" sectionDescription="[Převést ODS na JPEG](https://products.aspose.app/cells/conversion/ods-to-jpeg) právě teď na naší webové stránce s živými ukázkami. Živá ukázka má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát váš soubor ODS, bude okamžitě převeden do formátu JPEG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Dostanete odkaz ke stažení." >}}

    {{% blocks/products/pf/agp/content h2="Java Knihovna manipulace s tabulkami" %}}

 Excel API lze použít k vytváření, úpravám, převodu a vykreslování formátů Microsoft Excel do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelné výkazy a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}

Soubory s příponou ODS představují formát OpenDocument Spreadsheet Document, který může uživatel upravovat. Data jsou uložena v souboru ODF do řádků a sloupců. Je to formát založený na XML a je jedním z několika podtypů v rodině Open Document Formats (ODF). Formát je specifikován jako součást specifikací ODF 1.2 publikovaných a spravovaných OASIS. Soubory ODS pro úpravy a manipulaci může otevřít řada aplikací v systému Windows a také v jiných operačních systémech, včetně aplikací Microsoft Excel, NeoOffice a LibreOffice. Soubory ODS lze také různými aplikacemi převádět do jiných tabulkových formátů, jako jsou XLS, XLSX a další.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

JPEG je typ obrazového formátu, který se ukládá pomocí metody ztrátové komprese. Výstupní obraz, jako výsledek komprese, je kompromisem mezi velikostí úložiště a kvalitou obrazu. Uživatelé mohou upravit úroveň komprese tak, aby dosáhli požadované úrovně kvality a zároveň snížili velikost úložiště. Kvalita obrazu je zanedbatelně ovlivněna, pokud je na obraz aplikována komprese 10:1. Čím vyšší je hodnota komprese, tím vyšší je zhoršení kvality obrazu. Formát obrazového souboru JPEG byl standardizován skupinou Joint Photographic Experts Group a odtud název JPEG. Formát byl zvolen pro ukládání a přenos fotografických obrázků na webu. Téměř všechny operační systémy nyní mají prohlížeče, které podporují vizualizaci obrázků JPEG, které jsou často uloženy také s příponou JPG. Dokonce i webové prohlížeče podporují vizualizaci obrázků JPEG.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="ODS můžete také převést do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-bmp/" name="ODS DO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-csv/" name="ODS DO ČSV" description="hodnoty oddělené čárkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-dif/" name="ODS TO DIF" description="Formát výměny dat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-emf/" name="ODS K EMF" description="Vylepšený formát metasouborů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-gif/" name="ODS NA GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-html/" name="ODS TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-mhtml/" name="ODS TO MHTML" description="Formát archivu webové stránky" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-pdf/" name="ODS DO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-png/" name="ODS NA PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-svg/" name="ODS NA SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-tiff/" name="ODS TO TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-tsv/" name="ODS TO TSV" description="Hodnoty oddělené tabulátory" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-txt/" name="ODS TO TXT" description="Textový dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xlm/" name="ODS TO XLM" description="Soubor makra Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xls/" name="ODS NA XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xlsb/" name="ODS NA XLSB" description="Binární soubor sešitu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xlsx/" name="ODS NA XLSX" description="Soubor Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xlt/" name="ODS TO XLT" description="Šablona aplikace Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xltm/" name="ODS TO XLTM" description="Šablona s podporou maker aplikace Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xltx/" name="ODS NA XLTX" description="Šablona Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-xps/" name="ODS NA XPS" description="Specifikace papíru XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/ods-to-json/" name="ODS TO JSON" description="Zápis objektů JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}