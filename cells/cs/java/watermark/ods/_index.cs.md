---
title:  Vodoznak ODS dokument via Java
weight: 1040
description: Java ukázkový kód pro přidání nebo odstranění vodoznaku do souboru ODS v Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.
keywords: [Java Aspose.Cells., Java add watermark to ods file., Java insert watermark to ods file., Java create watermark in ods file., remove watermark from ods file using Java., Java operate watermark in ods file., Java access watermark in ods file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Přidejte textový vodoznak na ODS via Java" h2="Sestavte si své vlastní aplikace Java pro soubory vodoznaku ODS pomocí rozhraní API na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak vytvořit vodoznak ODS pomocí souboru Java" %}}

 Abychom mohli vodoznak ODS souboru, použijeme[Aspose.Cells for Java](https://products.aspose.com/cells/java) API, což je funkčně bohatá, výkonná a snadno použitelná platforma pro vodoznaky API for Java. Jeho nejnovější verzi si můžete stáhnout přímo z[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) a nainstalujte jej do svého projektu založeného na Maven přidáním následujících konfigurací do souboru pom.xml.

{{% blocks/products/pf/agp/code-block title="Úložiště" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Postup přidání vodoznaku na ODS via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Vytvořte nový objekt sešitu
1.  Vyberte List přes jeho index
1.  Vytvořte tvar a použijte jeho funkci addTextEffect
1.  Nastavte barvy, průhlednost a další
1.  Uložte sešit ve formátu ODS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java podporuje všechny hlavní platformy a operační systémy. Ujistěte se prosím, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.
- Získejte nejnovější verzi Aspose.Cells for Java přímo od Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Přidejte vodoznak na ODS - Java" offSpacer="" %}}

```cs

// Instantiate a new Workbook
Workbook workbook = new Workbook();

// Get the first default sheet
Worksheet sheet = workbook.getWorksheets().get(0);

// Add Watermark
Shape wordart = sheet.getShapes().addTextEffect(MsoPresetTextEffect.TEXT_EFFECT_1, "CONFIDENTIAL",
		"Arial Black", 50, false, true, 18, 8, 1, 1, 130, 800);

// Get the fill format of the word art
FillFormat wordArtFormat = wordart.getFill();

// Set the color
wordArtFormat.setOneColorGradient(Color.getRed(), 0.2, GradientStyleType.HORIZONTAL, 2);

// Set the transparency
wordArtFormat.setTransparency(0.9);

// Make the line invisible
LineFormat lineFormat = wordart.getLine();
lineFormat.setWeight(0.0);

// Save the file
workbook.save(dataDir + "AWArtWToWorksheet_out.ods");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for Java API" %}}

 Aspose.Cells API lze použít k vytváření, úpravám, převodu a vykreslování Microsoft formátů Excelu do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelný reporting a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Vodoznak ODS prostřednictvím online aplikace" sectionDescription=" Přidejte vodoznak do dokumentů ODS návštěvou našeho webu[Webová stránka živé ukázky](https://products.aspose.app/cells/watermark). Živé demo má následující výhody" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba nic stahovat ani nastavovat" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Stačí nahrát svůj soubor ODS, nastavit vodoznak a stisknout tlačítko \"Přidat\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Okamžitě získejte odkaz ke stažení výsledného souboru" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Soubory s příponou ODS představují formát OpenDocument Spreadsheet Document, který může uživatel upravovat. Data jsou uložena v souboru ODF do řádků a sloupců. Je to formát založený na XML a je jedním z několika podtypů v rodině Open Document Formats (ODF). Formát je specifikován jako součást specifikací ODF 1.2 publikovaných a spravovaných OASIS. Řada aplikací na Windows i jiných operačních systémech může otevřít soubory ODS pro úpravy a manipulaci, včetně Microsoft Excel, NeoOffice a LibreOffice. Soubory ODS lze také různými aplikacemi převést do jiných tabulkových formátů, stejně jako XLS, XLSX a dalších.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty vodoznaků" subTitle="Pomocí Java lze snadno vodoznak v různých formátech včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xls/" name="XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsb/" name="XLSB" description="Binární soubor sešitu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsm/" name="XLSM" description="Soubor tabulky" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsx/" name="XLSX" description="Soubor Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
