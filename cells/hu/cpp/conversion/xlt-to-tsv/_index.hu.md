---
title: Konvertálja az XLT-t TSV-vé a C++ alkalmazáson keresztül 
url: /hu/cpp/conversion/xlt-to-tsv/ 
description: Minta C++ konverziós kód az XLT dokumentumhoz TSV formátumba. A programozók ezt a forráskódot használhatják kötegelt XLT-ből TSV-vé konvertálásához bármely C++-alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLT konvertálása TSV-vé a következőn keresztül: C++" h2="Nagy teljesítményű XLT-TSV konvertálás a C++ könyvtár használatával, Microsoft Excel, OpenOffice vagy Adobe Acrobat telepítése nélkül." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="TSV" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Az XLT konvertálása TSV-vé a következővel: C++" %}}

 Az XLT TSV-vé konvertálásához használjuk
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

{{% blocks/products/pf/agp/feature-section-col title="Az XLT TSV-vé konvertálásának lépései a következőn keresztül: C++" %}}

{{% blocks/products/pf/agp/text %}}

 A C++ fejlesztői könnyedén konvertálhatnak XLT fájlt TSV-vé, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be az XLT fájlt a Factory::CreateIWorkbook segítségével.1. Hívja a Save() metódust.1. Adja meg a kimeneti fájl elérési útját (TSV) fájlkiterjesztéssel.1. A TSV fájl a megadott elérési útra kerül mentésre.1. Nyissa meg a TSV fájlt egy kompatibilis programban.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A C++ konverziós mintakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer C++ Runtime Environment for Windows 32 bit, Windows 64 bit és Linux 64 bit.- Aspose.Cells a projektben hivatkozott C++ DLL-hez.
- Microsoft Windows vagy kompatibilis operációs rendszer C++ Runtime Environment for Windows 32 bit, Windows 64 bit és Linux 64 bit.- Aspose.Cells a projektben hivatkozott C++ DLL-hez.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLT-től TSV-vé C++ konverziós forráskód" offSpacer="" %}}

```cs
// Töltse be az XLT-t.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlt");

// Mentés TSV formátumban.
wkb->Save(u"convertedFile.tsv", SaveFormat_Tsv);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLT-ből TSV-be konvertáló élő bemutatók" sectionDescription="[Konvertálja az XLT-t TSV-vé](https://products.aspose.app/cells/conversion/xlt-to-tsv) most keresse fel az Élő bemutatók webhelyét.Az élő bemutató a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel XLT fájlját, és azonnal TSV formátumba konvertálódik." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Megkapod a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel fájlkezelési könyvtár" %}}

 Az Excel API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}

Az .XLT kiterjesztésű fájlok olyan sablonfájlok, amelyeket a Microsoft Excel programmal hoztak létre, amely egy táblázatkezelő alkalmazás, amely a Microsoft Office programcsomag része. A Microsoft Office 97-2003 támogatta az új XLT-fájlok létrehozását és megnyitását. Az Excel legújabb verziója továbbra is képes megnyitni a régi formátumú sablonfájlokat. Egy ilyen sablonfájl segítségével gyorsan hozhatók létre új Excel-fájlok alapértelmezett adatokkal és beállításokkal, például oldalformázással, betűmérettel, margókkal, diagramokkal stb., amelyek tovább menthetők új .XLS fájlként.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}

A tabulátorral elválasztott értékek (TSV) fájlformátum a tabulátorokkal elválasztott adatokat egyszerű szöveges formátumban jelenti. A CSV-hez hasonló fájlformátumot az adatok strukturált rendszerezésére használják a különböző alkalmazások közötti importálás és exportálás érdekében. A formátumot elsősorban adatimportálására/exportálására és adatcseréjére használják táblázatkezelő alkalmazásokban és adatbázisokban. A TSV-fájl minden rekordja egyetlen sor szövegfájlban található, ahol minden mezőértéket tabulátor karakter választ el. A TSV fájlformátum médiatípusa: szöveg/tabulátorral elválasztott értékek.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}