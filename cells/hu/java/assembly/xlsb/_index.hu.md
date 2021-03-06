---
title: "Jelentések létrehozása XLSB-fájlokban a következőn keresztül: Java "
weight: 3560
url: /hu/java/assembly/xlsb/ 
description: Java mintakód XLSB formátumú jelentések létrehozásához a Java Futókörnyezetben JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Tömeges jelentéskészítés XLSB formátumban a következőn keresztül: Java" h2="Készítsen jelentéseket XLSB formátumban adatforrás és sablon használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="XLSB-jelentések létrehozása a következővel: Java" %}}

 Az XLSB fájl jelentések létrehozásához használjuk
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, amely funkciókban gazdag, hatékony és könnyen használható összeszerelési API for Java platform. A legújabb verziót közvetlenül a webhelyről töltheti le
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

{{% blocks/products/pf/agp/feature-section-col title="Az XLSB-jelentések létrehozásának lépései a következőn keresztül: Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Példányos munkafüzettervező osztály1. Adjon hozzá Datasouce objektumokat egy ArrayList-hez1. Állítsa be az adatforrást és a folyamatot a WorkbookDesigner objektumhoz1. Mentse el az eredményt XLSB formátumban a Worbook.save metódussal
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A Aspose.Cells for Java minden nagyobb platformon és operációs rendszeren támogatja. Kérjük, győződjön meg arról, hogy rendelkezik az alábbi előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futásidejű környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.- Szerezze be a(z) Aspose.Cells for Java legújabb verzióját közvetlenül a Maventől.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Excel-jelentések létrehozása XLSB formátumban – C#" offSpacer="" %}}

```cs
//Hozzon létre egy munkafüzet-tervezőt
WorkbookDesigner designer = new WorkbookDesigner(workbook);

//Hozzon létre Személyes objektumokat fényképekkel
ArrayList persons = new ArrayList();       
persons.add(new Person("George", "New York", photo1));
persons.add(new Person("George", "New York", photo2));

//Állítsa be az adatforrást és dolgozza fel az intelligens jelölőcímkéket
designer.setDataSource("Person", persons);
designer.process();

//Mentse el a munkafüzetet
workbook.save(dataDir + "output.xlsb", SaveFormat.XLSB);
	
System.out.println("File saved");
    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Körülbelül Aspose.Cells for Java API" %}}

 A Aspose.Cells API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Ingyenes alkalmazás az XLSB összeállításához" sectionDescription="Tekintse meg élő bemutatóinkat [XLSB fájlok létrehozása](https://products.aspose.app/cells/assembly/xlsb) a következő előnyökkel." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni vagy beállítani semmit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni vagy fordítani" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel az XLSB fájlt, és nyomja meg az \"Összeállítás\" gombot" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Töltse le az eredményül kapott XLSB fájlt a hivatkozásról" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Az XLSB fájlformátum az Excel bináris fájlformátumát határozza meg, amely az Excel-munkafüzet tartalmát meghatározó rekordok és struktúrák gyűjteménye. A tartalom tartalmazhat strukturálatlan vagy félig strukturált számtáblázatokat, szöveget, vagy számokat és szöveget egyaránt, képleteket, külső adatkapcsolatokat, diagramokat és képeket. Az XLSX-től eltérően (amely Open XML fájlformátumon alapul), az XLSB bináris Excel-munkafüzetfájlt jelent. Az XLSB fájlok gyorsabban olvashatók és írhatók, ami hasznossá teszi őket a nagy fájlokkal való munkavégzéshez. Az XLSB-t ritkán használják munkafüzetek tárolására, mivel az XLSX (és korábban az XLS) a felhasználók által leggyakrabban kiválasztott fájlformátum a munkafüzetek mentésére. Megnyitható a Microsoft Office 2007 és újabb verzióival.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott jelentéskészítési formátumok" subTitle="A(z) Java használatával egyszerűen hozhat létre jelentéseket többféle formátumban, beleértve a következőket:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/ods/" name="ODS" description="OpenDocument táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xls/" name="XLS" description="Excel bináris formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsm/" name="XLSM" description="Táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsx/" name="XLSX" description="OOXML Excel fájl" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}