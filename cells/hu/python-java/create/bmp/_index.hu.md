---
title: BMP létrehozása – BMP fájl létrehozása a Python-ben
description: Aspose Excel. Python Excel. Python Hozzon létre BMP Fájlokat gyorsan és egyszerűen a Aspose.Cells segítségével. Hozzon létre BMP fájlt a Python Excel Library használatával. Hozzon létre BMP-et a Python Excel-könyvtárban. Python BMP Alkotó.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create BMP file., Generate BMP file in Python Excel Library., Create BMP file using Python Excel Library., Write data to BMP file via Python Excel Library., Create a BMP file in Python Excel Library., Python Generate a BMP file., Python BMP Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Hozzon létre BMP fájlt a Python Excel könyvtárban" h2="Nagy sebességű Python Excel könyvtár a BMP fájl létrehozásához. Ez egy professzionális szoftvermegoldás a XLSX, PDF és sok más formátum importálásához és exportálásához a Python használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hozzon létre BMP fájlt a Python Excel könyvtár használatával" %}}

 Hogyan lehet létrehozni a BMP fájlt? A Aspose.Cells for Python via Java excel könyvtárral könnyedén létrehozhat BMP fájlt programozottan néhány sornyi kóddal.[Aspose.Cells for Python](https://pypi.org/project/aspose-cells)képes többplatformos alkalmazások létrehozására, amelyek képesek az összes Excel fájl generálására, módosítására, konvertálására, renderelésére és nyomtatására. Python Az Excel API nemcsak a táblázatformátumok között konvertál, hanem Excel-fájlokat is képes megjeleníteni képként, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT és egyebekként, így tökéletes választás a szabványos formátumú dokumentumok cseréjéhez.

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="A BMP létrehozása a Python Excel-könyvtárban" %}}

{{% blocks/products/pf/agp/text %}}

 A fejlesztők egyszerűen hozhatnak létre, tölthetnek be, módosíthatnak és konvertálhatnak BMP fájlokat a futó különböző jelentéskészítő alkalmazásokon belül, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1.  Importálja az asposecellákat a kódfájlba.
1.  Munkafüzet osztálypéldány létrehozása.
1.  Nyissa meg a munkafüzet első munkalapját.
1. Szerezze meg a munkalap kívánt celláit, és írja be az értéket a cellákba.
1.  A Mentés módszerrel mentheti a munkafüzetet BMP fájlként.

{{% blocks/products/pf/agp/code-block title="A mintakód bemutatja, hogyan hozhat létre BMP fájlt a Python Excel könyvtárban." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

# Create Workbook object.
workbook = Workbook(FileFormatType.BMP)

# Access the first worksheet of the workbook.
worksheet = workbook.getWorksheets().get(0)

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

# Save the workbook as BMP file.
workbook.save("output.bmp")

jpype.shutdownJVM()

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python Excel-könyvtár a BMP-es fájl létrehozásához" %}}

{{% blocks/products/pf/agp/text %}}

Három lehetőség közül választhat a „Aspose.Cells for Python via Java” telepítéséhez a rendszerre. Kérjük, válasszon egyet, amely megfelel az Ön igényeinek, és kövesse a lépésről lépésre található utasításokat:

{{% /blocks/products/pf/agp/text %}}

1.  Telepítse a Aspose.Cells for Python via Java-et a Windows-be. Lásd[Dokumentáció](https://docs.aspose.com/cells/python-java/getting-started/#windows)
1.  Telepítse a Aspose.Cells for Python via Java-et Linux rendszeren. Lát[Dokumentáció](https://docs.aspose.com/cells/python-java/getting-started/#linux)
1.  Telepítse a Aspose.Cells for Python via Java számot macOS rendszerben. Lát[Dokumentáció](https://docs.aspose.com/cells/python-java/getting-started/#macos)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Python via Java platformfüggetlen API, és bármilyen platformon használható (Windows, Linux és MacOS), csak győződjön meg arról, hogy a rendszer Java 1.8 vagy újabb[Python](https://www.python.org/downloads/) 3,5 vagy magasabb.

{{% /blocks/products/pf/agp/text %}}

-  Telepítse a Java-et, és adja hozzá a PATH környezeti változóhoz, például:<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  Telepítés: Aspose.Cells for Python via Java innen<a href="https://pypi.org/project/aspose-cells/">pypi</a> , használja a parancsot a következőképpen:<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" >}}.BMP kiterjesztésű fájlok olyan bittérképes képfájlokat jelentenek, amelyeket bittérképes digitális képek tárolására használnak. Ezek a képek függetlenek a grafikus adaptertől, és eszközfüggetlen bittérkép (DIB) fájlformátumnak is nevezik őket. Ez a függetlenség azt a célt szolgálja, hogy a fájlt több platformon is megnyissa, mint például a Microsoft Windows és a Mac. A BMP fájlformátum kétdimenziós digitális képként képes tárolni az adatokat mind monokróm, mind színes formátumban, különböző színmélységgel.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott táblázatgenerálás" subTitle="Létrehozhat más Microsoft Excel formátumokat is, köztük néhányat az alábbiakban felsorolva." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xls/" name="XLS" description="Microsoft Excel-táblázat (örökölt)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsx/" name="XLSX" description="Nyissa meg az XML-munkafüzetet" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsb/" name="XLSB" description="Excel bináris munkafüzet" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsm/" name="XLSM" description="Makró-kompatibilis táblázat" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlt/" name="XLT" description="Excel 97 - 2003 sablon" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltx/" name="XLTX" description="Excel sablon" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltm/" name="XLTM" description="Excel makró-engedélyezett sablon" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/csv/" name="CSV" description="Vesszővel elválasztott értékek" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/tsv/" name="TSV" description="Tabulátorral elválasztott értékek" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/ods/" name="ODS" description="OpenDocument Spreadsheet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/pdf/" name="PDF" description="Hordozható dokumentum formátum" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/html/" name="HTML" description="Hyper Text Markup Language" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
