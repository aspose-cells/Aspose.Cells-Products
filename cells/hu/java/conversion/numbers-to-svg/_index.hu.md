---
title: "NUMBERS konvertálása SVG-vé a következőn keresztül: Java "
url: /hu/java/conversion/numbers-to-svg/ 
description: Minta Java konverziós kód NUMBERS formátumhoz SVG-fájllá. A programozók ezt a példakódot használhatják Excel és OpenOffice táblázatok exportálására SVG formátumba bármely web- vagy asztali Java alapú alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="NUMBERS konvertálása SVG-vé a következőn keresztül: Java" h2="NUMBERS SVG Java átalakítás egyetlen vagy több oldal SVG formátumba konvertálásához a helyszíni Java könyvtár használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="NUMBERS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="NUMBERS konvertálása SVG-vé a következővel: Java" %}}

 A SZÁMOK SVG formátumban való megjelenítéséhez ezt használjuk
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, amely funkciókban gazdag, hatékony és könnyen használható konverziós API for Java platform. A legújabb verziót közvetlenül a webhelyről töltheti le
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

{{% blocks/products/pf/agp/feature-section-col title="A NUMBERS SVG formátumú konvertálásának lépései a következőn keresztül: Java" %}}

{{% blocks/products/pf/agp/text %}}

 A Java fejlesztői könnyedén konvertálhatnak NUMBERS fájlt SVG formátumba, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltsön be NUMBERS fájlt a munkafüzet egy példányával1. Válassza ki az alapértelmezett vagy bármely munkalapot a gyűjteményből1. Az ImageOrPrintOptions objektum létrehozása és beállítása1. Hozzon létre SheetRender-t Worksheet & ImageOrPrintOptions objektumokkal1. Hívja a SheetRender.toImage metódust az eredmény SVG formátumba mentéséhez

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Java konverziós forráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futásidejű környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.- Szerezze be a(z) Aspose.Cells for Java legújabb verzióját közvetlenül a Maventől.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="NUMBERS SVG Java konverziós forráskódra" offSpacer="" %}}

```cs
// töltse be a megjelenítendő NUMBERS fájlt
Workbook workbook = new Workbook("sourceFile.numbers");
// elérheti az alapértelmezett munkalapot a gyűjteményből
Worksheet worksheet = workbook.getWorksheets().get(0);
// határozza meg az eredményül kapott kép paramétereit
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.SVG);
// munkalapot konvertálni képpé SVG formátumban
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.svg");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="NUMBERS SVG átalakítás élő bemutatók" sectionDescription="[NUMBERS konvertálása SVG formátumba](https://products.aspose.app/cells/conversion/numbers-to-svg) most keresse fel az Élő bemutatók webhelyét.Az élő bemutató a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel NUMBERS fájlját, amely azonnal SVG formátumba konvertálódik." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Megkapod a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="Java Táblázatkezelési könyvtár" %}}

 Az Excel API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="NUMBERS" readMoreLink="https://docs.fileformat.com/spreadsheet/numbers/" >}}

A .numbers kiterjesztésű fájlok hasonlóak az .xlsx fájlokhoz. A Numbers fájlok az Apple iWork Numbers táblázatkezelő szoftverrel jönnek létre. Az Apple iWork Numbers az iWork Productivity Suite egységszoftvere. Az iWork Productivity Suite megegyezik a Windows PC-ken használt Microsoft Office Suite csomaggal.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/page-description-language/svg/" >}}

Az SVG fájlok méretezhető vektorgrafikus fájlok, amelyek XML alapú szövegformátumot használnak a kép megjelenésének leírására. A Scalable szó arra utal, hogy az SVG különböző méretekre méretezhető anélkül, hogy minősége romlana. Az ilyen fájlok szöveges leírása függetlenné teszi őket a felbontástól. Ez az egyik leggyakrabban használt formátum webhelyek és nyomtatott grafikák készítésére a méretezhetőség érdekében. A formátum azonban csak kétdimenziós grafikákhoz használható. Az SVG-fájlok szinte minden modern böngészőben megtekinthetők/megnyithatók, beleértve a Chrome-ot, az Internet Explorert, a Firefoxot és a Safarit.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}