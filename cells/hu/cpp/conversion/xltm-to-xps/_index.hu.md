---
title: Konvertálja az XLTM-et XPS-re a(z) C++ alkalmazáson keresztül 
url: /hu/cpp/conversion/xltm-to-xps/ 
description: Minta C++ konverziós kód XLTM dokumentumhoz XPS formátumba. A programozók ezt a forráskódot használhatják az XLTM-ből XPS-be kötegelt konvertáláshoz bármely C++ alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLTM konvertálása XPS-re a következőn keresztül: C++" h2="Nagy teljesítményű XLTM–XPS konvertálás a C++ könyvtár használatával, Microsoft Excel, OpenOffice vagy Adobe Acrobat telepítése nélkül." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XPS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="XLTM konvertálása XPS-re a következővel: C++" %}}

 Az XLTM XPS-re konvertálásához használjuk
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

{{% blocks/products/pf/agp/feature-section-col title="Az XLTM XPS-re konvertálásának lépései a következőn keresztül: C++" %}}

{{% blocks/products/pf/agp/text %}}

 A C++ fejlesztői könnyedén konvertálhatnak XLTM fájlt XPS-re, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be az XLTM fájlt a Factory::CreateIWorkbook segítségével.1. Hívja a Save() metódust.1. Adja meg a kimeneti fájl elérési útját (XPS) fájlkiterjesztéssel.1. Az XPS fájl a megadott elérési útra kerül mentésre.1. Nyissa meg az XPS fájlt egy kompatibilis programban.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A C++ konverziós mintakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer C++ Runtime Environment for Windows 32 bit, Windows 64 bit és Linux 64 bit.- Aspose.Cells a projektben hivatkozott C++ DLL-hez.
- Microsoft Windows vagy kompatibilis operációs rendszer C++ Runtime Environment for Windows 32 bit, Windows 64 bit és Linux 64 bit.- Aspose.Cells a projektben hivatkozott C++ DLL-hez.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTM-ből XPS-be C++ konverziós forráskód" offSpacer="" %}}

```cs
// Töltse be az XLTM-et.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltm");

// Mentse XPS formátumban.
wkb->Save(u"convertedFile.xps", SaveFormat_Xps);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLTM–XPS konverziós élő bemutatók" sectionDescription="[Az XLTM konvertálása XPS-re](https://products.aspose.app/cells/conversion/xltm-to-xps) most keresse fel az Élő bemutatók webhelyét.Az élő bemutató a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel XLTM-fájlját, és azonnal XPS-re konvertálódik." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Megkapod a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel fájlkezelési könyvtár" %}}

 Az Excel API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTM" readMoreLink="https://docs.fileformat.com/spreadsheet/xltm/" >}}

Az XLTM fájlkiterjesztés azokat a fájlokat jelöli, amelyeket a Microsoft Excel hoz létre makró-kompatibilis sablonfájlként. Az XLTM-fájlok szerkezetükben hasonlóak az XLTX-hez, kivéve, hogy a későbbiek nem támogatják a makrókat tartalmazó sablonfájlok létrehozását. Az ilyen sablonfájlokat az elrendezés, a formázás és egyéb beállítások generálására és beállítására használják a makrók mellett, hogy megkönnyítsék a hasonló XLSX-fájlok létrehozását.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XPS" readMoreLink="https://docs.fileformat.com/page-description-language/xps/" >}}

Az XPS-fájlok olyan oldalelrendezési fájlok, amelyek a Microsoft által létrehozott XML-papírspecifikációkon alapulnak. Ezt a formátumot a Microsoft fejlesztette ki az EMF fájlformátum helyettesítésére, és hasonló a PDF fájlformátumhoz, de XML-t használ a dokumentum elrendezésében, megjelenésében és nyomtatási információiban. Valójában indokoltabb azt állítani, hogy az XPS egy kísérlet a PDF-re, de több okból sem tudott elég népszerűségre szert tenni a PDF tulajdonában. A Microsoft alapértelmezés szerint XPS Document Writert biztosít a Windows 7-től kezdve az XPS-fájlok létrehozásához. XPS-fájlok generálhatók a „Microsoft XPS Document Writer” nyomtató kiválasztásával a dokumentum nyomtatása közben.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}