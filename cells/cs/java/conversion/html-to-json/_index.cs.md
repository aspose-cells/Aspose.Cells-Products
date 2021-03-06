---
title: Převést HTML na JSON prostřednictvím Java 
weight: 9560
url: /cs/java/conversion/html-to-json/ 
description: Ukázkový konverzní kód Java pro formát HTML na soubor JSON. Programátoři mohou tento příklad kódu použít k exportu tabulek Excelu a OpenOffice do formátu JSON v jakékoli webové nebo desktopové aplikaci založené na Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést HTML na JSON prostřednictvím Java" h2="Převod HTML na JSON Java pro převod jedné nebo více stránek na JSON pomocí místní knihovny Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak převést HTML na JSON pomocí Java" %}}

 K vykreslení HTML do JSON použijeme
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky k převodu HTML na JSON prostřednictvím Java" %}}

{{% blocks/products/pf/agp/text %}}

 Vývojáři Java mohou snadno převést soubor HTML na JSON pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor HTML s instancí třídy Workbook1. Vytvořte rozsah dat k exportu pomocí metody Cells.createRange1. Volání metody JsonUtility.exportRangeToJson s odkazy na Range & ExportRangeToJsonOptions1. Zápis dat String JSON do souboru pomocí metody BufferedWriter.write
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním ukázkového zdrojového kódu se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.- Získejte nejnovější verzi Aspose.Cells for Java přímo od společnosti Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód převodu HTML na JSON Java" offSpacer="" %}}

```cs
// načíst soubor XLSX s instancí sešitu
Workbook workbook = new Workbook("template.xlsx");
// přístup k CellsCollection listu obsahujícího data, která mají být převedena
Cells cells = workbook.getWorksheets().get(0).getCells();
// vytvořit a nastavit ExportRangeToJsonOptions pro pokročilé možnosti
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// vytvořit oblast buněk obsahujících data k exportu
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// exportovat rozsah jako data JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// zapisovat data na disk ve formátu JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Živá ukázka konverze HTML na JSON" sectionDescription="[Převést HTML na JSON](https://products.aspose.app/cells/conversion/html-to-json) právě teď na naší webové stránce s živými ukázkami. Živá ukázka má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát svůj soubor HTML, bude okamžitě převeden na JSON." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Dostanete odkaz ke stažení." >}}

    {{% blocks/products/pf/agp/content h2="Java Knihovna manipulace s tabulkami" %}}

 Excel API lze použít k vytváření, úpravám, převodu a vykreslování formátů Microsoft Excel do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelné výkazy a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language) je rozšíření pro webové stránky vytvořené pro zobrazení v prohlížečích. HTML, známé jako jazyk webu, se vyvinulo s požadavky na nové informace, které mají být zobrazeny jako součást webových stránek. Nejnovější varianta je známá jako HTML 5, která poskytuje velkou flexibilitu pro práci s jazykem. HTML stránky jsou buď přijímány ze serveru, kde jsou umístěny, nebo mohou být načteny z lokálního systému. Každá stránka HTML se skládá z prvků HTML, jako jsou formuláře, text, obrázky, animace, odkazy atd. Tyto prvky jsou reprezentovány značkami jako img, a, p a několika dalšími, kde každá značka má začátek a konec. Může také vkládat aplikace napsané ve skriptovacích jazycích, jako je JavaScript a styly (CSS), pro celkovou reprezentaci rozvržení.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (JavaScript Object Notation) je otevřený standardní formát souboru pro sdílení dat, který k ukládání a přenosu dat používá text čitelný člověkem. Soubory JSON jsou uloženy s příponou .json. JSON vyžaduje méně formátování a je dobrou alternativou pro XML. JSON je odvozen z JavaScriptu, ale je to datový formát nezávislý na jazyce. Generování a parsování JSON je podporováno mnoha moderními programovacími jazyky. application/json je typ média používaný pro JSON.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="HTML můžete také převést do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-bmp/" name="HTML DO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-csv/" name="HTML DO CSV" description="hodnoty oddělené čárkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-dif/" name="HTML DO DIF" description="Formát výměny dat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-emf/" name="HTML DO EMF" description="Vylepšený formát metasouborů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-gif/" name="Z HTML DO GIFu" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-jpeg/" name="HTML DO JPEG" description="Obrázek JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-mhtml/" name="HTML DO MHTML" description="Formát archivu webové stránky" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-ods/" name="HTML TO ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-pdf/" name="HTML DO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-png/" name="HTML DO PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-svg/" name="HTML DO SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-tiff/" name="HTML DO TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-tsv/" name="HTML DO TSV" description="Hodnoty oddělené tabulátory" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-txt/" name="HTML DO TXT" description="Textový dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xlm/" name="HTML DO XLM" description="Soubor makra Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xls/" name="HTML DO XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xlsb/" name="HTML DO XLSB" description="Binární soubor sešitu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xlsx/" name="HTML DO XLSX" description="Soubor Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xlt/" name="HTML DO XLT" description="Šablona aplikace Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xltm/" name="HTML TO XLTM" description="Šablona s podporou maker aplikace Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xltx/" name="HTML DO XLTX" description="Šablona Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/html-to-xps/" name="HTML NA XPS" description="Specifikace papíru XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}