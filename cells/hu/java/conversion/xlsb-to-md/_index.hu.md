---
title: "Konvertálja az XLSB-t MD-vé a következőn keresztül: Java "
url: /hu/java/conversion/xlsb-to-md/ 
description: Minta Java konverziós kód az XLSB formátumhoz MD fájllá. A programozók ezt a példakódot használhatják Excel- és OpenOffice-táblázatok exportálására MD-re bármely web- vagy asztali Java-alapú alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertálja az XLSB-t MD-vé a következőn keresztül: Java" h2="XLSB-ből MD-vé Java konverzió egyetlen vagy több oldal konvertálásához MD-vé az On-premise Java könyvtár használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="MD" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="XLSB konvertálása MD-vé a Java használatával" %}}

 Ahhoz, hogy az XLSB-t MD-re rendereljük, használjuk
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

{{% blocks/products/pf/agp/feature-section-col title="Az XLSB MD-vé konvertálásának lépései a következőn keresztül: Java" %}}

{{% blocks/products/pf/agp/text %}}

 A Java fejlesztői könnyedén konvertálhatnak XLSB-fájlt MD-re, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be az XLSB-fájlt a Workbook osztály egy példányával1. Hívja a Workbook.save metódust1. Adja meg a kimeneti útvonalat MD kiterjesztéssel és SaveFormat paraméterekkel1. Ellenőrizze az eredményül kapott MD-fájl megadott elérési útját

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Java konverziós forráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futásidejű környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.- Szerezze be a(z) Aspose.Cells for Java legújabb verzióját közvetlenül a Maventől.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSB-ből MD-be Java konverziós forráskód" offSpacer="" %}}

```cs
// töltse be az XLSB fájlt a munkafüzet egy példányába
Workbook book = new Workbook("template.xlsb");
// mentse az XLSB-t MD-ként
book.save("output.md", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLSB-ről MD-re konvertáló élő demók" sectionDescription="[Konvertálja az XLSB-t MD-re](https://products.aspose.app/cells/conversion/xlsb-to-md) most keresse fel az Élő bemutatók webhelyét.Az élő bemutató a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel XLSB fájlját, és azonnal MD formátumba konvertálódik." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Megkapod a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="Java Táblázatkezelési könyvtár" %}}

 Az Excel API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

Az XLSB fájlformátum az Excel bináris fájlformátumát határozza meg, amely az Excel-munkafüzet tartalmát meghatározó rekordok és struktúrák gyűjteménye. A tartalom tartalmazhat strukturálatlan vagy félig strukturált számtáblázatokat, szöveget, vagy számokat és szöveget egyaránt, képleteket, külső adatkapcsolatokat, diagramokat és képeket. Az XLSX-től eltérően (amely Open XML fájlformátumon alapul), az XLSB bináris Excel-munkafüzetfájlt jelent. Az XLSB fájlok gyorsabban olvashatók és írhatók, ami hasznossá teszi őket a nagy fájlokkal való munkavégzéshez. Az XLSB-t ritkán használják munkafüzetek tárolására, mivel az XLSX (és korábban az XLS) a felhasználók által leggyakrabban kiválasztott fájlformátum a munkafüzetek mentésére. Megnyitható a Microsoft Office 2007 és újabb verzióival.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MD" readMoreLink="https://docs.fileformat.com/word-processing/md/" >}}

Markdown nyelvi dialektusokkal létrehozott szöveges fájlok .MD vagy .MARKDOWN fájlkiterjesztéssel kerülnek mentésre. Az MD-fájlok egyszerű szöveges formátumban kerülnek mentésre, amely Markdown nyelvet használ, amely szövegközi szimbólumokat is tartalmaz, amelyek meghatározzák a szöveg formázhatóságát, például behúzásokat, táblázatformázást, betűtípusokat és fejléceket. Az MD fájlok a Markdown nevű programmal HTML-be konvertálhatók. A Markdown nyelvet John Gruber adta ki.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="Az XLSB-t számos más fájlformátumra is konvertálhatja, beleértve az alábbiakban felsorolt néhányat." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-bmp/" name="XLSB A BMP-re" description="Bittérképes kép" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-csv/" name="XLSB – CSV" description="Vesszővel elválasztott értékek" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-dif/" name="XLSB TO DIF" description="Adatcsere formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-emf/" name="XLSB TO EMF" description="Továbbfejlesztett metafájl formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-gif/" name="XLSB-ről GIF-re" description="Grafikus csereformátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-html/" name="XLSB-ből HTML-be" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-jpeg/" name="XLSB - JPEG" description="JPEG kép" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-mhtml/" name="XLSB - MHTML" description="Weboldal archív formátuma" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-ods/" name="XLSB TO ODS" description="OpenDocument táblázatfájl" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-pdf/" name="XLSB-ből PDF-be" description="Hordozható dokumentum formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-png/" name="XLSB - PNG" description="Hordozható hálózati grafika" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-svg/" name="XLSB - SVG" description="Skálázható vektorgrafika" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-tiff/" name="XLSB-től TIFF-hez" description="Címkézett képformátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-tsv/" name="XLSB – TSV" description="Tabulátorral elválasztott értékek" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-txt/" name="XLSB - TXT" description="Szöveges dokumentum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xls/" name="XLSB - XLS" description="Excel bináris formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlsm/" name="XLSB - XLSM" description="Táblázatfájl" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlsx/" name="XLSB - XLSX" description="OOXML Excel fájl" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xlt/" name="XLSB - XLT" description="Microsoft Excel sablon" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xltm/" name="XLSB - XLTM" description="Excel makró-kompatibilis sablon" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xltx/" name="XLSB - XLTX" description="Office OpenXML Excel sablon" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-xps/" name="XLSB-től XPS-ig" description="XML papírspecifikációk" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsb-to-json/" name="XLSB – JSON" description="JavaScript objektum jelölés" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}