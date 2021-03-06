---
title: "FODS konvertálása BMP-vé a következőn keresztül: Java "
url: /hu/java/conversion/fods-to-bmp/ 
description: Minta Java konverziós kód FODS-formátumhoz BMP-fájllá. A programozók ezt a példakódot használhatják Excel- és OpenOffice-táblázatok exportálására BMP-be bármely web- vagy asztali Java-alapú alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="FODS konvertálása BMP-vé a következőn keresztül: Java" h2="A FODS-ból BMP-be Java konvertálhat egyetlen vagy több oldalt BMP-vé a Helyszíni Java könyvtár használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="FODS konvertálása BMP-vé a Java használatával" %}}

 Ahhoz, hogy a FODS-t BMP-be rendereljük, használjuk
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

{{% blocks/products/pf/agp/feature-section-col title="FODS BMP-vé konvertálásának lépései a következőn keresztül: Java" %}}

{{% blocks/products/pf/agp/text %}}

 A Java fejlesztői könnyedén konvertálhatják a FODS-fájlt BMP-vé, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be a FODS-fájlt a munkafüzet egy példányával1. Válassza ki az alapértelmezett vagy bármely munkalapot a gyűjteményből1. Az ImageOrPrintOptions objektum létrehozása és beállítása1. Hozzon létre SheetRender-t Worksheet & ImageOrPrintOptions objektumokkal1. Hívja a SheetRender.toImage metódust az eredmény BMP formátumba mentéséhez

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Java konverziós forráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futásidejű környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.- Szerezze be a(z) Aspose.Cells for Java legújabb verzióját közvetlenül a Maventől.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="FODS-ból BMP-be Java konverziós forráskód" offSpacer="" %}}

```cs
// töltse be a renderelni kívánt FODS fájlt
Workbook workbook = new Workbook("sourceFile.fods");
// elérheti az alapértelmezett munkalapot a gyűjteményből
Worksheet worksheet = workbook.getWorksheets().get(0);
// határozza meg az eredményül kapott kép paramétereit
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.BMP);
// munkalapot konvertálni képpé BMP formátumban
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.bmp");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="FODS-ból BMP-be konvertáló élő bemutatók" sectionDescription="[Konvertálja a FODS-t BMP-vé](https://products.aspose.app/cells/conversion/fods-to-bmp) most keresse fel az Élő bemutatók webhelyét.Az élő bemutató a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel a FODS-fájlt, és azonnal BMP-re konvertálódik." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Megkapod a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="Java Táblázatkezelési könyvtár" %}}

 Az Excel API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FODS" readMoreLink="https://docs.fileformat.com/spreadsheet/fods/" >}}

A .fods kiterjesztésű fájl az OpenDocument Spreadsheet dokumentumformátum egyik típusa, amely sorokban és oszlopokban tárolja az adatokat. A formátumot az OASIS által közzétett és karbantartott ODF 1.2 specifikáció részeként határozták meg. A FODS fájlok nem nyithatók meg a Microsoft másik táblázatkezelő szoftverével, az Excellel. A FODS fájlok ODS-ként menthetők a LibreOffice segítségével, és konvertálhatók más formátumokba, például XLS és XLSX formátumba.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" >}}

.BMP kiterjesztésű fájlok olyan bittérképes képfájlokat képviselnek, amelyeket bittérképes digitális képek tárolására használnak. Ezek a képek függetlenek a grafikus adaptertől, és eszközfüggetlen bittérkép (DIB) fájlformátumnak is nevezik őket. Ez a függetlenség azt a célt szolgálja, hogy a fájlt több platformon, például Microsoft Windowson és Macen is megnyissa. A BMP fájlformátum kétdimenziós digitális képként képes tárolni az adatokat mind monokróm, mind színes formátumban, különböző színmélységgel.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}