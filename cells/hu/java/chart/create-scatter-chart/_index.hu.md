---
title: Hozzon létre szóródási diagramokat a Java-ben
description: Aspose Excel. Java Hozzon létre szóródiagramokat. Szórványdiagramok létrehozása Java. Szórványdiagramok Java létrehozása. Szórásdiagramok létrehozása a Java használatával.
keywords: [Aspose Excel., Java Aspose.Cells., Create Scatter Charts Java., Create Scatter Charts in Java., Generate Scatter Charts in Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Hozzon létre szóródási diagramokat a Java-ben" h2="Nagy sebességű Java könyvtár szóródási diagramok létrehozásához. Ez egy professzionális szoftvermegoldás a XLSX, PDF és sok más formátum importálásához és exportálásához a Java használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hozzon létre szóródiagramokat a Java használatával" %}}

 Hogyan készítsünk szóródiagramokat? A Aspose.Cells for Java könyvtárral egyszerűen, néhány soros kóddal programozottan szórhatja szét a diagramokat.[Aspose.Cells for Java](https://products.aspose.com/cells/java)képes többplatformos alkalmazásokat létrehozni, módosítani, konvertálni, renderelni és kinyomtatni az összes Excel fájlt. Java Az Excel API nemcsak a táblázatformátumok között konvertál, hanem Excel-fájlokat is képes megjeleníteni képként, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT és egyebekként, így tökéletes választás a szabványos formátumú dokumentumok cseréjéhez. A legújabb verziót közvetlenül a webhelyről töltheti le[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) és telepítse a Maven alapú projekten belül a következő konfigurációk hozzáadásával a pom.xml fájlhoz.

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



{{% blocks/products/pf/agp/content h2="Szórványdiagramok létrehozása a Java számon" %}}

{{% blocks/products/pf/agp/text %}}

Programozottan kell szóródiagramokat létrehozni? Java A fejlesztők egyszerűen hozhatnak létre szóródási diagramokat néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Szerelje be a névteret az osztályfájlba
1.  Teremt[**Munkafüzet**](https://reference.aspose.com/cells/java/com.aspose.cells/workbook/) osztály példány.
1.  Adjon hozzá néhány adatot a munkalap celláihoz a[**Cell**](https://reference.aspose.com/cells/java/com.aspose.cells/cell/) tárgyat[**putValue**](https://reference.aspose.com/cells/java/com.aspose.cells/cell/#putValue-int-)módszer.
1.  Add hozzá a[**SCATTER**](https://reference.aspose.com/cells/java/com.aspose.cells/charttype/) Diagram a munkalaphoz hívásával a[**Diagramok**](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection/) gyűjteményét[**add hozzá**](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection/#add-int-int-int-int-int-) módszerrel, a[**Munkalap**](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/)tárgy.
1.  Hozzáférés az újhoz[**Diagram**](https://reference.aspose.com/cells/java/com.aspose.cells/chart/)objektumot a Charts gyűjteményből indexének átadásával.
1.  Állítsa be a diagram adatforrását a következővel:[**Chart.setChartDataRange**](https://reference.aspose.com/cells/java/com.aspose.cells/chart/#setChartDataRange-java.lang.String-boolean-) módszer.
1. Mentés Excel vagy ODS fájlként.

{{% blocks/products/pf/agp/code-block title="A mintakód bemutatja, hogyan lehet szóródiagramokat létrehozni a Java-ben." offSpacer="" %}}

```cs

// Instantiating a Workbook object
Workbook workbook = new Workbook();
// Obtaining the reference of the first worksheet
Worksheet worksheet = workbook.getWorksheets().get(0);

// Adding sample values to cells
Cells cells = worksheet.getCells();
cells.get("A2").putValue("Category1");
cells.get("A3").putValue("Category2");
cells.get("A4").putValue("Category3");

cells.get("B1").putValue("Scatter");
cells.get("B2").putValue(324);
cells.get("B3").putValue(200);
cells.get("B4").putValue(450);

// Adding a Scatter chart to the worksheet
int chartIndex = worksheet.getCharts().add(ChartType.SCATTER, 6, 2, 20, 10);

// Accessing the instance of the newly added chart
Chart chart = worksheet.getCharts().get(chartIndex);

// Setting chart data source as the range "A1:B4"
chart.setChartDataRange("A1:B4", true);

// Save the Workbook as .xlsx file.
workbook.save("output.xlsx");

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Java könyvtárat szóródiagramok létrehozásához" %}}
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


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
