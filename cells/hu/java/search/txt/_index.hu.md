---
title: "TXT-dokumentum keresése megnyitás nélkül a következőn keresztül: Java "
weight: 1200
url: /hu/java/search/txt/ 
description: Java mintakód a mintával rendelkező szavak kereséséhez a TXT-fájlban a Java Futókörnyezetben JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TXT formátumok keresése itt: Java" h2="Natív és nagy teljesítményű TXT-dokumentumkeresés szerveroldali Aspose.Cells for Java API-kkal, olyan szoftverek használata nélkül, mint a Microsoft vagy az Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="TXT-fájl keresése a következővel: Java" %}}

 A TXT fájl kereséséhez használjuk
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, amely funkciókban gazdag, hatékony és könnyen használható Keresési API for Java platform. A legújabb verziót közvetlenül a webhelyről töltheti le
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 és telepítse a Maven-alapú projekten belül a következő konfigurációk hozzáadásával a pom.xml fájlhoz.

{{% blocks/products/pf/agp/code-block title="Adattár" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Függőség" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Lépések a TXT-fájlok kereséséhez itt: Java" %}}

{{% blocks/products/pf/agp/text %}}

 A Aspose.Cells API-kat használó alapvető dokumentumkeresés néhány kódsorral elvégezhető.

{{% /blocks/products/pf/agp/text %}}

+ TXT fájl betöltése munkafüzet objektum létrehozásával.
+ A TXT fájl első munkalapjának elérése.
+ Keresse meg a megadott képletet tartalmazó cellát.
+ Példányos keresési opciók.
+ Keresse meg a karakterlánc értéket tartalmazó cellát
+ Nyomtassa ki a keresési eredmény után talált cellákat

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Aspose.Cells for Java minden nagyobb platformon és operációs rendszeren támogatja. Kérjük, győződjön meg arról, hogy rendelkezik az alábbi előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futásidejű környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.- Szerezze be a(z) Aspose.Cells for Java legújabb verzióját közvetlenül innen [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TXT fájlok keresése – Java" offSpacer="" %}}

```cs
// Munkafüzet objektum példányosítása
Workbook workbook = new Workbook(dataDir + "book1.txt");

// A TXT fájl első munkalapjának elérése
Worksheet worksheet = workbook.getWorksheets().get(0);

// A megadott képletet tartalmazó cella megkeresése
Cells cells = worksheet.getCells();

// Példányos keresési opciók
FindOptions findOptions = new FindOptions();

// Az Or karakterrel kezdődő karakterlánc-értéket tartalmazó cella megkeresése
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// A keresés után talált cella nevének kinyomtatása 
System.out.println("Name of the cell containing String: " + cell.getName());  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Körülbelül Aspose.Cells for Java API" %}}

 A Aspose.Cells API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online TXT élő bemutatók keresése" sectionDescription="Keressen szöveget, szavakat, kifejezéseket a TXT-dokumentumokban most, látogassa meg webhelyünket [Élő bemutatók weboldala](https://products.aspose.app/cells/search). Az élő demónak a következő előnyei vannak" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Csak töltse fel TXT fájljait." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" A keresés eredménye azonnal megjelenik." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT " readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}
A .TXT kiterjesztésű fájl olyan szöveges dokumentumot jelent, amely egyszerű szöveget tartalmaz sorok formájában. A szöveges dokumentum bekezdéseit a kocsivisszaadások felismerik, és a fájltartalom jobb elrendezésére használják. A szabványos szöveges dokumentum bármely szövegszerkesztőben vagy szövegszerkesztő alkalmazásban megnyitható különböző operációs rendszereken. Az ilyen fájlokban található összes szöveg ember által olvasható formátumban van, és karakterek sorozata ábrázolja. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott keresési dokumentumok" subTitle="A Java használatával más fájlokban is kereshet, beleértve a." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/csv/" name="CSV" description="Vesszővel elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/ods/" name="ODS" description="OpenDocument táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/tsv/" name="TSV" description="Tabulátorral elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xls/" name="XLS" description="Excel bináris formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsb/" name="XLSB" description="Bináris Excel munkafüzet fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="Táblázatfájl" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}