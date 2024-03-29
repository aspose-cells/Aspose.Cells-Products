---
title: OTS létrehozása – OTS-fájl létrehozása a Java-ben
description:  Aspose Excel. Java Hozzon létre OTS-fájlt gyorsan és egyszerűen a Aspose.Cells-es számmal. Hozzon létre OTS-fájlt a Java-es szám használatával. Hozzon létre OTS-fájlt a Java-ben. Java OTS-készítő.
keywords: [Aspose Excel., Java Aspose.Cells., Java Create OTS file., Generate OTS file in Java., Create OTS file using Java., Write data to OTS file via Java., Create a OTS file in Java., Java Generate a OTS file., Java OTS Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Hozzon létre OTS-fájlt a Java-ben" h2="Nagy sebességű Java könyvtár az OTS-fájl létrehozásához. Ez egy professzionális szoftvermegoldás a XLSX, PDF és sok más formátum importálásához és exportálásához a Java használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="OTS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hozzon létre OTS-fájlt a Java használatával" %}}

 Hogyan készítsünk OTS fájlt? A Aspose.Cells for Java könyvtárral egyszerűen hozhat létre OTS-fájlt programozottan néhány sornyi kóddal.[Aspose.Cells for Java](https://products.aspose.com/cells/java)képes többplatformos alkalmazásokat létrehozni, módosítani, konvertálni, renderelni és kinyomtatni az összes Excel fájlt. Java Az Excel API nemcsak a táblázatformátumok között konvertál, hanem Excel-fájlokat is képes megjeleníteni képként, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT és egyebekként, így tökéletes választás a szabványos formátumú dokumentumok cseréjéhez. A legújabb verziót közvetlenül a webhelyről töltheti le[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) és telepítse a Maven alapú projekten belül a következő konfigurációk hozzáadásával a pom.xml fájlhoz.

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



{{% blocks/products/pf/agp/content h2="OTS létrehozása a Java-ben" %}}

{{% blocks/products/pf/agp/text %}}

 fejlesztők egyszerűen hozhatnak létre, tölthetnek be, módosíthatnak és konvertálhatnak OTS-fájlokat a futó különböző jelentéskészítő alkalmazásokon belül adatfeldolgozás céljából, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1.  Hozzon létre egy példányt a[Munkafüzet osztály](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
1.  A megfelelő munkalapot a getWorksheets.get() metódussal érheti el.
1.  Jelölje ki a megfelelő cellát, írja be az értéket a kívánt cellába a cellanév használatával, például A1, B3 stb.
1.  Mentse el a munkafüzetet OTS formátumban a save() metódussal.

{{% blocks/products/pf/agp/code-block title="A mintakód bemutatja, hogyan kell OTS-fájlt létrehozni a Java-ben." offSpacer="" %}}

```cs

// Create a new workbook
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet worksheet = wkb.getWorksheets().get(0);

// Add relevant content in the cell
worksheet.getCells().get("A1").putValue("ColumnA");
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Save the workbook as OTS file
wkb.save("Excel.ots"); 

// To enhance the code for further functionalities here are more functions
// getCells() and setValue for modifying the cell content
// getCharts().add() to add charts
// getPivotTables().add() for creating a Pivot Table
// getCells().get(int cell id).setFormula for adding cell level formula

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Java könyvtár az OTS-fájl létrehozásához" %}}
{{% blocks/products/pf/agp/text %}}

 A Java-es csomagjainkat itt fogadjuk[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) adattárak. A „Aspose.Cells for Java” egy bájtkódot tartalmazó közös JAR-fájl. Kérjük, kövesse a[lépésről lépésre](https://docs.aspose.com/cells/java/installation/) hogyan telepítheti a Java fejlesztői környezetébe.

{{% /blocks/products/pf/agp/text %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Java konverziós mintaforráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futásidejű környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.
- Aspose.Cells for Java a következő Java verziókat támogatja: J2SE 6.0 (1.6), J2SE 7.0 (1.7) vagy újabb.
- [Szerezze be a Aspose.Cells for Java legújabb verzióját közvetlenül a Maven számról.](https://docs.aspose.com/cells/java/installation/) 

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OTS" readMoreLink="https://docs.fileformat.com/spreadsheet/ots/" >}}Az .ots kiterjesztésű fájl egy OpenDocument Spreadsheet Template fájl, amely az Apache OpenOffice-ban található Calc alkalmazással jön létre. A Calc alkalmazásszoftver hasonló a Microsoft Office-ban elérhető Excelhez. Az OTS fájlformátumot olyan sablonok létrehozására használják, amelyek előre meghatározott beállításokat tartalmaznak a stílusokhoz, betűtípusokhoz, adatokhoz, táblázatelrendezéshez és formázáshoz. Az OTF-fájlok mime típusú application/vnd.oasis.opendocument.spreadsheet-template-vel rendelkeznek. Ezek a sablonfájlok kiindulási pontként használhatók a ODS fájlformátumban mentett tényleges adatfájlok létrehozásához és mentéséhez. Az OTS-fájlok olyan alkalmazásokkal használhatók, mint az OpenOffice és a LibreOffice.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott táblázatgenerálás" subTitle="Létrehozhat más Microsoft Excel formátumokat is, köztük néhányat az alábbiakban felsorolva." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xls/" name="XLS" description="Microsoft Excel-táblázat (örökölt)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsx/" name="XLSX" description="Nyissa meg az XML-munkafüzetet" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsb/" name="XLSB" description="Excel bináris munkafüzet" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsm/" name="XLSM" description="Makró-kompatibilis táblázat" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlt/" name="XLT" description="Excel 97 - 2003 sablon" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xltx/" name="XLTX" description="Excel sablon" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xltm/" name="XLTM" description="Excel makró-engedélyezett sablon" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/csv/" name="CSV" description="Vesszővel elválasztott értékek" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/tsv/" name="TSV" description="Tabulátorral elválasztott értékek" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/ods/" name="ODS" description="OpenDocument Spreadsheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/pdf/" name="PDF" description="Hordozható dokumentum formátum" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/html/" name="HTML" description="Hyper Text Markup Language" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
