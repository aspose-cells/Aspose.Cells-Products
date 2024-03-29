---
title:  XLS Megjegyzés hozzáadása vagy eltávolítása via Java
weight: 10040
description: Java mintakód a XLS formátumú megjegyzések törléséhez a Java futásidejű környezet JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.
keywords: [Java Aspose.Cells., add xls annotation., insert xls annotation., access xls annotation., remove xls annotation., delete xls annotation., add annotation in xls., insert annotation in xls., access annotation in xls., remove annotation in xls., delete annotation in xls]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Megjegyzés hozzáadása vagy törlése innen: XLS via Java" h2="Készítse el saját Java-es alkalmazásait a dokumentumfájlok megjegyzéseinek és szerzőinek manipulálásához szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="A XLS fájl megjegyzéseinek készítése a Java használatával" %}}

 A XLS fájl megjegyzéseinek rögzítéséhez a következőt használjuk:
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, amely egy funkciókban gazdag, hatékony és könnyen használható megjegyzés API for Java platform. A legújabb verziót közvetlenül a webhelyről töltheti le
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 és telepítse a Maven alapú projekten belül a következő konfigurációk hozzáadásával a pom.xml fájlhoz.

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

{{% blocks/products/pf/agp/feature-section-col title="A megjegyzés hozzáadásának vagy törlésének lépései a XLS via Java számról" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Töltse be a XLS fájlt a munkafüzet osztály használatával
1.  Válassza ki a megfelelő lapot
1.  A CommentCollection összes megjegyzésének megtekintése
1.  Az eltávolításhoz hívja a RemoveAt-t a Cell azonosítóval
1.  Mentse el a munkafüzetet a RemoveAt metódus meghívása előtt és után az összehasonlításhoz

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java támogatja az összes főbb platformot és operációs rendszert. Kérjük, győződjön meg arról, hogy rendelkezik az alábbi előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer Java futásidejű környezettel JSP/JSF alkalmazásokhoz és asztali alkalmazásokhoz.
- Szerezze be a Aspose.Cells for Java legújabb verzióját közvetlenül a Maven számról.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Megjegyzések törlése a XLS - Java számokról" offSpacer="" %}}

```cs
// Instantiating a Workbook object
Workbook workbook = new Workbook(dataDir + "ThreadedCommentsSample.xls");

//Access first worksheet
Worksheet worksheet = workbook.getWorksheets().get(0);

CommentCollection comments = worksheet.getComments();
ThreadedCommentCollection threadedComments = worksheet.getComments().getThreadedComments("I4");
ThreadedCommentAuthor author = threadedComments.get(0).getAuthor();
      
comments.removeAt("I4");
      
ThreadedCommentAuthorCollection authors = workbook.getWorksheets().getThreadedCommentAuthors();

authors.removeAt(authors.indexOf(author));
workbook.save(dataDir + "ThreadedCommentsSample_Out.xls");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Körülbelül Aspose.Cells for Java API" %}}

 Aspose.Cells API használható Microsoft Excel formátumok létrehozására, szerkesztésére, konvertálására és renderelésére különböző formátumokba. Ezen túlmenően használható átfogó diagramok készítésére, skálázható jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Távolítsa el a megjegyzést a XLS számról az online alkalmazáson keresztül" sectionDescription=" Törölje a XLS dokumentumhoz fűzött megjegyzéseket most, látogassa meg webhelyünket[Élő bemutatók weboldala](https://products.aspose.app/cells/annotation). Az élő demónak a következő előnyei vannak" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni vagy beállítani semmit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel a XLS fájlt, és nyomja meg az „Eltávolítás” gombot" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Azonnal megkapja a letöltési linket az eredményül kapott fájlhoz" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
XLS kiterjesztésű fájlok Excel bináris fájlformátumot képviselnek. Az ilyen fájlokat a Microsoft Excel, valamint más hasonló táblázatkezelő programok, például az OpenOffice Calc vagy az Apple Numbers is létrehozhatják. Az Excel által mentett fájlokat munkafüzetnek nevezik, ahol minden munkafüzetnek egy vagy több munkalapja lehet. Az adatok tárolása és megjelenítése táblázatos formában, munkalapon történik a felhasználók számára, és átfoghatnak számértékeket, szöveges adatokat, képleteket, külső adatkapcsolatokat, képeket és diagramokat. Az olyan alkalmazások, mint a Microsoft Excel, lehetővé teszik a munkafüzet adatainak több különböző formátumba történő exportálását, beleértve a PDF, CSV, XLSX, TXT, HTML, XPS és sok más formátumot. A XLS fájlformátumot egy nyitottabb és strukturáltabb formátum, a XLSX váltotta fel a Microsoft Excel 2007 kiadásával. A legújabb verziók továbbra is támogatják a XLS fájlok létrehozását és olvasását, bár most a XLSX az első számú választás.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott megjegyzésformátumok" subTitle="A Java használatával könnyen feljegyezhet más formátumokat, beleértve." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/annotation/ods/" name="ODS" description="OpenDocument táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/annotation/xlsb/" name="XLSB" description="Bináris Excel munkafüzet fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/annotation/xlsm/" name="XLSM" description="Táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/annotation/xlsx/" name="XLSX" description="OOXML Excel fájl" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
