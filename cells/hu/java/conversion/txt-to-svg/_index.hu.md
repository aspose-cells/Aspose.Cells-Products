---
title: "TXT konvertálása SVG-vé a következőn keresztül: Java "
weight: 9880
url: /hu/java/conversion/txt-to-svg/ 
description: Minta Java konverziós kód a TXT formátumhoz SVG fájllá. A programozók ezt a példakódot használhatják Excel és OpenOffice táblázatok exportálására SVG formátumba bármely web- vagy asztali Java alapú alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TXT konvertálása SVG-vé a következőn keresztül: Java" h2="TXT-ből SVG-vé Java konverzió egyetlen vagy több oldal konvertálásához SVG-vé a helyszíni Java könyvtár használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="TXT konvertálása SVG-vé a következővel: Java" %}}

 A TXT SVG formátumba való rendereléséhez használjuk
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

{{% blocks/products/pf/agp/feature-section-col title="A TXT SVG-vé konvertálásának lépései a következőn keresztül: Java" %}}

{{% blocks/products/pf/agp/text %}}

 A Java fejlesztői könnyedén konvertálhatják a TXT fájlt SVG formátumba, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltsön be TXT-fájlt a munkafüzet egy példányával1. Válassza ki az alapértelmezett vagy bármely munkalapot a gyűjteményből1. Az ImageOrPrintOptions objektum létrehozása és beállítása1. Hozzon létre SheetRender-t Worksheet & ImageOrPrintOptions objektumokkal1. Hívja a SheetRender.toImage metódust az eredmény SVG formátumba mentéséhez
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Java konverziós forráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futásidejű környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.- Szerezze be a(z) Aspose.Cells for Java legújabb verzióját közvetlenül a Maventől.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TXT-ből SVG-be Java Konverziós forráskód" offSpacer="" %}}

```cs
// töltse be a renderelni kívánt TXT fájlt
Workbook workbook = new Workbook("sourceFile.txt");
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

{{< blocks/products/pf/agp/demobox sectionTitle="TXT-ből SVG-be konvertáló élő bemutatók" sectionDescription="[Konvertálja a TXT-t SVG-vé](https://products.aspose.app/cells/conversion/txt-to-svg) most keresse fel az Élő bemutatók webhelyét.Az élő bemutató a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel TXT fájlját, és azonnal SVG formátumba konvertálódik." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Megkapod a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="Java Táblázatkezelési könyvtár" %}}

 Az Excel API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}

A .TXT kiterjesztésű fájl olyan szöveges dokumentumot jelent, amely egyszerű szöveget tartalmaz sorok formájában. A szöveges dokumentum bekezdéseit a kocsivisszaadások felismerik, és a fájltartalom jobb elrendezésére használják. A szabványos szöveges dokumentum bármely szövegszerkesztőben vagy szövegszerkesztő alkalmazásban megnyitható különböző operációs rendszereken. Az ilyen fájlokban található összes szöveg ember által olvasható formátumban van, és karakterek sorozata ábrázolja.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/page-description-language/svg/" >}}

Az SVG fájlok méretezhető vektorgrafikus fájlok, amelyek XML alapú szövegformátumot használnak a kép megjelenésének leírására. A Scalable szó arra utal, hogy az SVG különböző méretekre méretezhető anélkül, hogy minősége romlana. Az ilyen fájlok szöveges leírása függetlenné teszi őket a felbontástól. Ez az egyik leggyakrabban használt formátum webhelyek és nyomtatott grafikák készítésére a méretezhetőség érdekében. A formátum azonban csak kétdimenziós grafikákhoz használható. Az SVG-fájlok szinte minden modern böngészőben megtekinthetők/megnyithatók, beleértve a Chrome-ot, az Internet Explorert, a Firefoxot és a Safarit.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A TXT-t sok más fájlformátumra is konvertálhatja, beleértve az alábbiakban felsorolt néhányat." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-bmp/" name="TXT BMP-RE" description="Bittérképes kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-csv/" name="TXT CSV-BA" description="Vesszővel elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-dif/" name="TXT TO DIF" description="Adatcsere formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-emf/" name="TXT EMF-RE" description="Továbbfejlesztett metafájl formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-gif/" name="TXT GIF-RE" description="Grafikus csereformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-html/" name="TXT HTML-BE" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-jpeg/" name="TXT JPEG formátumba" description="JPEG kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-mhtml/" name="TXT MHTML-RE" description="Weboldal archív formátuma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-ods/" name="TXT TO ODS" description="OpenDocument táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-pdf/" name="TXT PDF-BE" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-png/" name="TXT PNG-RE" description="Hordozható hálózati grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-tiff/" name="TXT TIFF-RE" description="Címkézett képformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-tsv/" name="TXT TSV-RE" description="Tabulátorral elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xlm/" name="TXT - XLM" description="Excel makrófájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xls/" name="TXT - XLS" description="Excel bináris formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xlsb/" name="TXT - XLSB" description="Bináris Excel munkafüzet fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xlsx/" name="TXT - XLSX" description="OOXML Excel fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xlt/" name="TXT - XLT" description="Microsoft Excel sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xltm/" name="TXT - XLTM" description="Excel makró-kompatibilis sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xltx/" name="TXT - XLTX" description="Office OpenXML Excel sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xps/" name="TXT XPS-RE" description="XML papírspecifikációk" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-json/" name="TXT JSON-RA" description="JavaScript objektum jelölés" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}