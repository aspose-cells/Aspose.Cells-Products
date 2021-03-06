---
title: "Hozzon létre MS Excel XLT fájlokat a következőn keresztül: Python "
url: /hu/python-java/create-xlt/ 
description: Python Mintakód XLT-dokumentumok generálásához. Ezzel a kóddal MS Excel XLT fájlokat hozhat létre a(z) Python alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLT-dokumentumok létrehozása a következőn keresztül: Python" h2="Natív és nagy teljesítményű MS Excel XLT táblázatkészítés programozottan, Python API-k használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/python" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Az MS Excel XLT fájl dinamikus generálása futó alkalmazáson belül egyszerű. Annak érdekében, hogy az XLT dokumentumokat a semmiből hozzuk létre, MS Office nélkül, ezt használjuk
 [Aspose.Cells – Python](https://pypi.org/project/aspose-cells) 
 API, amely különböző funkciókat kínál a táblázatok létrehozásához, kezeléséhez és konvertálásához a Python platformon. A fejlesztők egyszerűen javíthatják a kódot az adatok írásához, diagramok vagy grafikonok generálásához, valamint táblázatok készítéséhez.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLT létrehozása a következőn keresztül: Python" %}}

{{% blocks/products/pf/agp/text %}}

 fejlesztők könnyen létrehozhatják, betölthetik, módosíthatják és konvertálhatják az MS Excel XLT táblázatokat a különböző adatfeldolgozási alkalmazásokon belül, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Importálja az asposecellákat a kódfájlba.1. Munkafüzet osztálypéldány létrehozása.1. Nyissa meg a munkafüzet első munkalapját.1. Szerezze meg a munkalap kívánt celláit, és írja be az értéket a cellákba.1. A Mentés módszerrel mentheti a munkafüzetet XLT-fájlként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A(z) Aspose.Cells for Python via Java platformfüggetlen API, és bármilyen platformon használható (Windows, Linux és MacOS), csak győződjön meg arról, hogy a rendszer Java 1.8 vagy újabb verzióval rendelkezik, [Python](https://www.python.org/downloads/) 3,5 vagy magasabb. 

{{% /blocks/products/pf/agp/text %}}

- Telepítse a(z) Java fájlt, és adja hozzá a PATH környezeti változóhoz, például: <code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.- A(z) Aspose.Cells telepítése a(z) Python számára a következőn keresztül: Java innen <a href="https://pypi.org/project/aspose-cells/">pypi</a>, használja a parancsot a következőképpen: <code>$ pip install aspose-cells</code>.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="A következő forráskód bemutatja, hogyan hozhat létre MS Excel XLT fájlt a Python használatával." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

// Munkafüzet objektum létrehozása.
workbook = Workbook(FileFormatType.XLT)

// Nyissa meg a munkafüzet első munkalapját.
worksheet = workbook.getWorksheets().get(0)

// Szerezze meg a munkalap kívánt celláit, és írja be az értéket a cellákba.
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Mentse el a munkafüzetet XLT fájlként.
workbook.save("output.xlt")

jpype.shutdownJVM()


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Egy Excel táblázatkezelő programkönyvtár, amely képes többplatformos alkalmazások létrehozására, amelyek képesek MS Excel XLT fájlok generálására, módosítására, konvertálására, renderelésére és nyomtatására. Python API nem csak konvertál a táblázatformátumok között, hanem Excel-fájlokat is képes megjeleníteni képként, PDF-ként, HTML-ként, ODS-ként és sok másként, így tökéletes választás a szabványos formátumú dokumentumok cseréjéhez.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
Az .xlt kiterjesztésű fájlok olyan sablonfájlok, amelyeket a Microsoft Excel programmal hoztak létre, amely egy táblázatkezelő alkalmazás, amely a Microsoft Office programcsomag része. A Microsoft Office 97-2003 támogatta az új XLT-fájlok létrehozását és megnyitását. Az Excel legújabb verziója továbbra is képes megnyitni a régi formátumú sablonfájlokat. Egy ilyen sablonfájl segítségével gyorsan hozhatók létre új Excel-fájlok alapértelmezett adatokkal és beállításokkal, például oldalformázással, betűmérettel, margókkal, diagramokkal stb., amelyek tovább menthetők új .xls fájlként.
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}   

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott táblázatgenerálás" subTitle="Létrehozhat más Microsoft Excel formátumokat is, köztük néhányat az alábbiakban." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xls/" name="XLS" description="Microsoft Excel táblázat (örökölt)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsx/" name="XLSX" description="Nyissa meg az XML-munkafüzetet" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsb/" name="XLSB" description="Excel bináris munkafüzet" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlsm/" name="XLSM" description="Makró-kompatibilis táblázat" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xlt/" name="XLT" description="Excel 97 - 2003 sablon" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltx/" name="XLTX" description="Excel sablon" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-xltm/" name="XLTM" description="Excel makró-engedélyezett sablon" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-csv/" name="CSV" description="Vesszővel elválasztott értékek" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-tsv/" name="TSV" description="Tabulátorral elválasztott értékek" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create-ods/" name="ODS" description="OpenDocument Spreadsheet" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
