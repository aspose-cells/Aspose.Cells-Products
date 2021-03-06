---
title: Konvertálja az XLS-t TXT-re a C++ alkalmazással 
url: /hu/cpp/conversion/xls-to-txt/ 
description: Minta C++ konverziós kód az XLS dokumentumhoz TXT formátumba. A programozók ezt a forráskódot használhatják az XLS-ből TXT-be történő kötegelt konvertáláshoz bármely C++-alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLS konvertálása TXT-re a következőn keresztül: C++" h2="Nagy teljesítményű XLS-TXT konvertálás a C++ könyvtár használatával Microsoft Excel, OpenOffice vagy Adobe Acrobat telepítése nélkül." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="TXT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="XLS konvertálása TXT-re a következővel: C++" %}}

 Az XLS TXT-re konvertálásához használjuk
 [Aspose.Cells – C++](https://products.aspose.com/cells/cpp) 
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési és -konverziós API a C++ platformhoz. A legújabb verziót közvetlenül letöltheti, csak nyissa meg
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 csomagkezelő, keressen
 Aspose.Cells.Cpp 
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Parancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Az XLS-ből TXT-vé konvertálás lépései a következőn keresztül: C++" %}}

{{% blocks/products/pf/agp/text %}}

 A C++ fejlesztői könnyedén konvertálhatnak XLS fájlt TXT formátumba, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be az XLS fájlt a Factory::CreateIWorkbook segítségével.1. Hívja a Save() metódust.1. Adja meg a kimeneti fájl elérési útját (TXT) fájlkiterjesztéssel.1. A TXT fájl a megadott elérési útra kerül mentésre.1. Nyissa meg a TXT fájlt egy kompatibilis programban.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A C++ konverziós mintakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer C++ Runtime Environment for Windows 32 bit, Windows 64 bit és Linux 64 bit.- Aspose.Cells a projektben hivatkozott C++ DLL-hez.
- Microsoft Windows vagy kompatibilis operációs rendszer C++ Runtime Environment for Windows 32 bit, Windows 64 bit és Linux 64 bit.- Aspose.Cells a projektben hivatkozott C++ DLL-hez.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS-ből TXT-be C++ konverziós forráskód" offSpacer="" %}}

```cs
// Töltse be az XLS-t.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xls");

// Mentés TXT formátumban.
wkb->Save(u"convertedFile.txt", SaveFormat_Txt);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLS-ből TXT-be konvertáló élő bemutatók" sectionDescription="[Konvertálja az XLS-t TXT-re](https://products.aspose.app/cells/conversion/xls-to-txt) most keresse fel az Élő bemutatók webhelyét.Az élő bemutató a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel XLS fájlját, és azonnal TXT formátumba konvertálódik." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Megkapod a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel fájlkezelési könyvtár" %}}

 Az Excel API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

Az XLS kiterjesztésű fájlok Excel bináris fájlformátumot képviselnek. Ilyen fájlokat létrehozhat a Microsoft Excel, valamint más hasonló táblázatkezelő programok, például az OpenOffice Calc vagy az Apple Numbers. Az Excel által mentett fájl munkafüzetként ismert, ahol minden munkafüzet egy vagy több munkalappal rendelkezhet. Az adatok tárolása és megjelenítése a felhasználók számára táblázat formátumban, munkalapon történik, és kiterjedhetnek számértékekre, szöveges adatokra, képletekre, külső adatkapcsolatokra, képekre és diagramokra. Az olyan alkalmazások, mint a Microsoft Excel, lehetővé teszik a munkafüzet adatainak több különböző formátumba, köztük PDF, CSV, XLSX, TXT, HTML, XPS és sok más formátumba történő exportálását. Az XLS fájlformátumot egy nyitottabb és strukturáltabb formátum, az XLSX váltotta fel a Microsoft Excel 2007 kiadásával. A legújabb verziók továbbra is támogatják az XLS fájlok létrehozását és olvasását, bár most az XLSX az első számú választás.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}

A .TXT kiterjesztésű fájl olyan szöveges dokumentumot jelent, amely egyszerű szöveget tartalmaz sorok formájában. A szöveges dokumentum bekezdéseit a kocsivisszaadások felismerik, és a fájltartalom jobb elrendezésére használják. A szabványos szöveges dokumentum bármely szövegszerkesztőben vagy szövegszerkesztő alkalmazásban megnyitható különböző operációs rendszereken. Az ilyen fájlokban található összes szöveg ember által olvasható formátumban van, és karakterek sorozata ábrázolja.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="Az XLS-t sok más fájlformátumra is konvertálhatja, beleértve az alábbiakban felsorolt néhányat." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-bmp/" name="XLS A BMP-re" description="Bittérképes kép" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-csv/" name="XLS-ből CSV-be" description="Vesszővel elválasztott értékek" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-dif/" name="XLS TO DIF" description="Adatcsere formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-emf/" name="XLS TO EMF" description="Továbbfejlesztett metafájl formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-gif/" name="XLS-ből GIF-be" description="Grafikus csereformátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-html/" name="XLS-ből HTML-be" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-jpeg/" name="XLS - JPEG" description="JPEG kép" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-mhtml/" name="XLS-ről MHTML-re" description="Weboldal archív formátuma" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-ods/" name="XLS TO ODS" description="OpenDocument táblázatfájl" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-pdf/" name="XLS-ből PDF-be" description="Hordozható dokumentum formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-png/" name="XLS-től PNG-ig" description="Hordozható hálózati grafika" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-svg/" name="XLS - SVG" description="Skálázható vektorgrafika" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tiff/" name="XLS-től TIFF-ig" description="Címkézett képformátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tsv/" name="XLS TO TSV" description="Tabulátorral elválasztott értékek" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsb/" name="XLS - XLSB" description="Bináris Excel munkafüzet fájl" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsm/" name="XLS-től XLSM-ig" description="Táblázatfájl" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsx/" name="XLS - XLSX" description="OOXML Excel fájl" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltm/" name="XLS - XLTM" description="Excel makró-kompatibilis sablon" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltx/" name="XLS - XLTX" description="Office OpenXML Excel sablon" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xps/" name="XLS-től XPS-ig" description="XML papírspecifikációk" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}