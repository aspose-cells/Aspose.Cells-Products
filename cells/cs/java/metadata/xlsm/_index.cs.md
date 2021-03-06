---
title: Upravit nebo zobrazit metadata souborů XLSM prostřednictvím Java 
weight: 9030
url: /cs/java/metadata/xlsm/ 
description: Java ukázkový kód pro úpravu nebo zobrazení metadat ve formátu XLSM v Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Extrahovat XLSM metadata prostřednictvím Java" h2="Sestavte si své vlastní aplikace Java a přidávejte, upravujte, odebírejte nebo extrahujte metadata ze souborů XLSM pomocí rozhraní API na straně serveru." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak extrahovat XLSM metadata pomocí Java" %}}

 Abychom získali metadata souboru XLSM, použijeme
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, což je funkčně bohatá, výkonná a snadno použitelná platforma metadat API for Java. Jeho nejnovější verzi si můžete stáhnout přímo z
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky k extrahování metadat XLSM prostřednictvím Java" %}}

{{% blocks/products/pf/agp/text %}}

 Získejte přístup k užitečným informacím uloženým v souboru XLSM včetně toho, kdy byl soubor XLSM přijat, zpracován, označen časovým razítkem atd.

{{% /blocks/products/pf/agp/text %}}

+ Načíst soubor XLSM v rámci WorkbookMetadata
+ Vytvořte objekt MetadataOptions s příslušnými možnostmi
+ Nastavte příslušné vlastnosti
+ Uložte informace o metadatech XLSM

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java podporuje na všech hlavních platformách a operačních systémech. Ujistěte se prosím, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.- Získejte nejnovější verzi Aspose.Cells for Java přímo od [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extrahovat metadata XLSM – Java" offSpacer="" %}}

```cs

// Otevřete metadata sešitu
MetadataOptions options = new MetadataOptions(MetadataType.DOCUMENT_PROPERTIES);
WorkbookMetadata meta = new WorkbookMetadata("Sample1.xlsm", options);

// Nastavte některé vlastnosti
meta.getCustomDocumentProperties().add("test", "test");

// Uložte informace o metadatech
meta.save("Sample1.out.xlsm");

// Otevřete sešit
Workbook w = new Workbook("Sample1.out.xlsm");

// Číst vlastnost dokumentu
System.out.println(w.getCustomDocumentProperties().get("test"));  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for Java API" %}}

 Aspose.Cells API lze použít k vytváření, úpravám, převodu a vykreslování formátů aplikace Microsoft Excel do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelné výkazy a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extrahujte metadata XLSM prostřednictvím online aplikace" sectionDescription="Prohlížejte a upravujte metadata k dokumentům XLSM pomocí našeho [Živá ukázka](https://products.aspose.app/cells/metadata) s následujícími výhodami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není potřeba nic stahovat ani nastavovat" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát soubor XLSM a upravit vlastnosti dokumentu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Okamžitě získejte odkaz ke stažení výsledného souboru" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Soubory s příponou XLSM jsou typem souborů tabulky, které podporují makra. Z aplikačního hlediska je makro sada instrukcí, které se používají pro automatizaci procesů. Makro se používá k zaznamenání kroků, které jsou prováděny opakovaně, a usnadňuje provádění akcí opětovným spuštěním makra. Makra se programují pomocí jazyka Microsoft Visual Basic for Applications (VBA) ze sešitu aplikace Excel pomocí editoru jazyka Visual Basic a lze je spouštět/ladit přímo odtud.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty metadat" subTitle="Pomocí Java lze také manipulovat s metadaty mnoha dalších formátů, včetně" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/ods/" name="ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xls/" name="XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsb/" name="XLSB" description="Binární soubor sešitu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/metadata/xlsx/" name="XLSX" description="Soubor Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}