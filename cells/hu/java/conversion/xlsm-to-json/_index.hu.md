---
title: "XLSM konvertálása JSON-ra a következőn keresztül: Java "
weight: 1640
url: /hu/java/conversion/xlsm-to-json/ 
description: Minta Java konverziós kód az XLSM formátumhoz JSON-fájllá. A programozók ezt a példakódot használhatják Excel- és OpenOffice-táblázatok exportálására JSON-ba bármely web- vagy asztali Java-alapú alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSM konvertálása JSON-ra a következőn keresztül: Java" h2="XLSM–JSON Java konverzió, amellyel egyetlen vagy több oldalt konvertálhat JSON-ba a helyszíni Java könyvtár használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Az XLSM konvertálása JSON-ba a következővel: Java" %}}

 Ahhoz, hogy az XLSM-et JSON-ba rendereljük, ezt használjuk
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

{{% blocks/products/pf/agp/feature-section-col title="Az XLSM konvertálása JSON-ra a következőn keresztül: Java" %}}

{{% blocks/products/pf/agp/text %}}

 A Java fejlesztői könnyedén konvertálhatják az XLSM fájlt JSON formátumba, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be az XLSM-fájlt a Workbook osztály egy példányával1. Hozzon létre egy exportálandó adattartományt a Cells.createRange metódussal1. Hívja a JsonUtility.exportRangeToJson metódust a Range és az ExportRangeToJsonOptions hivatkozásokkal1. Írja be a karakterlánc JSON-adatait a fájlba a BufferedWriter.write metódussal
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Java konverziós forráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futásidejű környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.- Szerezze be a(z) Aspose.Cells for Java legújabb verzióját közvetlenül a Maventől.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Az XLSM-ből JSON-ba Java konverziós forráskód" offSpacer="" %}}

```cs
// töltse be az XLSX fájlt a munkafüzet egy példányával
Workbook workbook = new Workbook("template.xlsx");
// access CellsA konvertálandó adatokat tartalmazó munkalap gyűjteménye
Cells cells = workbook.getWorksheets().get(0).getCells();
// Hozzon létre és állítson be ExportRangeToJsonOptions-t a speciális beállításokhoz
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// hozzon létre egy cellatartományt, amely exportálandó adatokat tartalmaz
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// tartomány exportálása JSON-adatokként
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// írjon adatokat a lemezre JSON formátumban
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLSM-ből JSON-ba konvertáló élő bemutatók" sectionDescription="[Konvertálja az XLSM-et JSON-ba](https://products.aspose.app/cells/conversion/xlsm-to-json) most keresse fel az Élő bemutatók webhelyét.Az élő bemutató a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel XLSM-fájlját, amely azonnal JSON-ba konvertálódik." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Megkapod a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="Java Táblázatkezelési könyvtár" %}}

 Az Excel API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}

Az XLSM kiterjesztésű fájlok olyan táblázatkezelő fájlok, amelyek támogatják a makrókat. Alkalmazási szempontból a makró a folyamatok automatizálására használt utasítások halmaza. A makró rögzíti az ismételten végrehajtott lépéseket, és megkönnyíti a műveletek végrehajtását a makró ismételt futtatásával. A makrók a Microsoft Visual Basic for Applications (VBA) programmal programozhatók az Excel-munkafüzetből a Visual Basic Editor segítségével, és onnan közvetlenül futtathatók/hibakereshetők.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

A JSON (JavaScript Object Notation) egy nyílt szabványos fájlformátum az adatok megosztására, amely ember által olvasható szöveget használ az adatok tárolására és továbbítására. A JSON-fájlok tárolása .json kiterjesztéssel történik. A JSON kevesebb formázást igényel, és jó alternatíva az XML számára. A JSON a JavaScriptből származik, de nyelvtől független adatformátum. A JSON generálását és elemzését számos modern programozási nyelv támogatja. Az application/json a JSON-hoz használt médiatípus.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="Az XLSM-et sok más fájlformátumra is konvertálhatja, köztük néhány alább felsorolt fájlformátumra." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-bmp/" name="XLSM A BMP-re" description="Bittérképes kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-csv/" name="XLSM-ből CSV-be" description="Vesszővel elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-dif/" name="XLSM TO DIF" description="Adatcsere formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-emf/" name="XLSM TO EMF" description="Továbbfejlesztett metafájl formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-gif/" name="XLSM GIF-RE" description="Grafikus csereformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-html/" name="XLSM-ből HTML-be" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-jpeg/" name="XLSM - JPEG" description="JPEG kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-mhtml/" name="XLSM-ről MHTML-re" description="Weboldal archív formátuma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-ods/" name="XLSM TO ODS" description="OpenDocument táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-pdf/" name="XLSM-ből PDF-be" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-png/" name="XLSM-ről PNG-re" description="Hordozható hálózati grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-svg/" name="XLSM – SVG" description="Skálázható vektorgrafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-tiff/" name="XLSM TIFF-RE" description="Címkézett képformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-tsv/" name="XLSM TSV-RE" description="Tabulátorral elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-txt/" name="XLSM - TXT" description="Szöveges dokumentum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xls/" name="XLSM - XLS" description="Excel bináris formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xlsb/" name="XLSM - XLSB" description="Bináris Excel munkafüzet fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xlsx/" name="XLSM - XLSX" description="OOXML Excel fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xlt/" name="XLSM - XLT" description="Microsoft Excel sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xltm/" name="XLSM - XLTM" description="Excel makró-kompatibilis sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xltx/" name="XLSM - XLTX" description="Office OpenXML Excel sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xlsm-to-xps/" name="XLSM-től XPS-ig" description="XML papírspecifikációk" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}