---
title:  Generujte sestavy v souborech XLSB via Java
weight: 3560
description: Java ukázkový kód pro vytvoření sestav formátu XLSB na Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.
keywords: [Java Aspose.Cells., Java Create XLSB Reports Based on Predesigned Excel Template., Java Generate XLSB Reports Based on Predesigned Excel Template., Java Create XLSB Reports Based on Excel Template., Java Generate XLSB Reports Based on Excel Template., Java Create XLSB files Based on Excel Template., Java Generate XLSB files Based on Excel Template]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Generování hromadné sestavy ve formátu XLSB Formát via Java" h2="Generujte zprávy ve formátu XLSB pomocí zdroje dat a šablony." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Jak generovat sestavy XLSB pomocí Java" %}}

 K vytvoření XLSB souborových sestav použijeme
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, což je funkčně bohatá, výkonná a snadno použitelná montážní platforma API for Java. Jeho nejnovější verzi si můžete stáhnout přímo z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 a nainstalujte jej do svého projektu založeného na Maven přidáním následujících konfigurací do souboru pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Kroky k generování XLSB sestav via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Okamžitá třída WorkbookDesigner
1. Přidejte objekty Datasouce do ArrayList
1.  Nastavte zdroj dat a proces pro objekt WorkbookDesigner
1.  Uložte výsledek ve formátu XLSB pomocí metody Worbook.save

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java podporuje všechny hlavní platformy a operační systémy. Ujistěte se prosím, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s Java Runtime Environment pro JSP/JSF aplikace a desktopové aplikace.
- Získejte nejnovější verzi Aspose.Cells for Java přímo od Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Generujte sestavy Excel ve formátu XLSB – Java" offSpacer="" %}}

```java
//Create a workbook designer
WorkbookDesigner designer = new WorkbookDesigner(workbook);

//Create Persons objects with photos
ArrayList persons = new ArrayList();       
persons.add(new Person("George", "New York", photo1));
persons.add(new Person("George", "New York", photo2));

//Set the data source and process smart marker tags
designer.setDataSource("Person", persons);
designer.process();

//Save the workbook
workbook.save(dataDir + "output.xlsb", SaveFormat.XLSB);
	
System.out.println("File saved");
    

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for Java API" %}}

 Aspose.Cells API lze použít k vytváření, úpravám, převodu a vykreslování Microsoft formátů Excelu do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelný reporting a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Bezplatná aplikace k sestavení XLSB" sectionDescription=" Podívejte se na naše živé ukázky[vytvořit XLSB souborů](https://products.aspose.app/cells/assembly/xlsb) s následujícími výhodami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba nic stahovat ani nastavovat" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát nebo kompilovat kód" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát soubor XLSB a stisknout tlačítko \"Sestavit\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Stáhněte si výsledný soubor XLSB z odkazu" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Formát souboru XLSB určuje formát binárního souboru aplikace Excel, což je kolekce záznamů a struktur, které určují obsah sešitu aplikace Excel. Obsah může zahrnovat nestrukturované nebo polostrukturované tabulky čísel, text nebo čísla i text, vzorce, externí datová připojení, grafy a obrázky. Na rozdíl od XLSX (který je založen na formátu souboru Open XML), XLSB představuje binární soubor sešitu aplikace Excel. XLSB soubory lze číst a zapisovat rychleji, což je činí užitečnými pro práci s velkými soubory. XLSB se zřídka používá k ukládání sešitů, protože XLSX (a dříve XLS) jsou nejběžnější uživatelem vybrané formáty souborů pro ukládání sešitů. Lze jej otevřít na čísle Microsoft Office 2007 a vyšším.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty generování sestav" subTitle="Pomocí Java lze snadno generovat zprávy v různých formátech včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/ods/" name="ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xls/" name="XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsm/" name="XLSM" description="Soubor tabulky" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsx/" name="XLSX" description="Soubor Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
