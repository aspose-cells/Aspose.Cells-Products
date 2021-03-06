---
title: JSON konvertálása PNG-re a(z) C++ alkalmazáson keresztül 
url: /hu/cpp/conversion/json-to-png/ 
description: Minta C++ konverziós kód a JSON-dokumentumhoz PNG formátumba. A programozók ezt a forráskódot használhatják a JSON-ból PNG-be kötegelt konvertálásához bármely C++-alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="JSON konvertálása PNG-re a következőn keresztül: C++" h2="Nagy teljesítményű JSON-ból PNG konvertálás a C++ könyvtár használatával, Microsoft Excel, OpenOffice vagy Adobe Acrobat telepítése nélkül." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JSON" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="JSON konvertálása PNG-re a következővel: C++" %}}

 A JSON PNG-re konvertálásához használjuk
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

{{% blocks/products/pf/agp/feature-section-col title="A JSON konvertálása PNG-re a következőn keresztül: C++" %}}

{{% blocks/products/pf/agp/text %}}

 A C++ fejlesztői könnyedén konvertálhatnak JSON-fájlt PNG-formátumba, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be a JSON-fájlt a Factory::CreateIWorkbook használatával.1. Válassza ki az első munkalapot.1. Állítsa be a (PNG) opciókat.1. Ismételje meg a lap minden oldalát, és jelenítse meg.1. Nyissa meg a PNG fájlt egy kompatibilis programban.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A C++ konverziós mintakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer C++ Runtime Environment for Windows 32 bit, Windows 64 bit és Linux 64 bit.- Aspose.Cells a projektben hivatkozott C++ DLL-hez.
- Microsoft Windows vagy kompatibilis operációs rendszer C++ Runtime Environment for Windows 32 bit, Windows 64 bit és Linux 64 bit.- Aspose.Cells a projektben hivatkozott C++ DLL-hez.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="JSON-ból PNG-be C++ konverziós forráskód" offSpacer="" %}}

```cs
// Kimeneti könyvtár elérési útja.
StringPtr outDir = new String("OutputDirectoryPath");

// Töltse be a JSON-t.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.json");

// Az első munkalap elérése.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Kép vagy nyomtatási beállítások objektum létrehozása.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Adja meg a képformátumot.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetPng());

// Adja meg a vízszintes és függőleges felbontást
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Renderje le a lapot a megadott kép- vagy nyomtatási beállításoknak megfelelően.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Oldalszám lekérése.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Hozzon létre karakterlánc-építő objektumot a karakterlánc-összefűzéshez.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Az egyes oldalakat egyenként jelenítse meg png képpé.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImagePNG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".png"));

	// Szerezze meg a kimeneti kép elérési útját.
	StringPtr outputPNG = sb->ToString();

	// Konvertálja a munkalapot png képpé.
	sr->ToImage(i, outputPNG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="JSON-ból PNG-be konvertáló élő bemutatók" sectionDescription="[Konvertálja a JSON-t PNG-re](https://products.aspose.app/cells/conversion/json-to-png) most keresse fel az Élő bemutatók webhelyét.Az élő bemutató a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel a JSON-fájlt, és azonnal PNG-re konvertálódik." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Megkapod a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel fájlkezelési könyvtár" %}}

 Az Excel API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

A JSON (JavaScript Object Notation) egy nyílt szabványos fájlformátum az adatok megosztására, amely ember által olvasható szöveget használ az adatok tárolására és továbbítására. A JSON-fájlok tárolása .json kiterjesztéssel történik. A JSON kevesebb formázást igényel, és jó alternatíva az XML számára. A JSON a JavaScriptből származik, de nyelvtől független adatformátum. A JSON generálását és elemzését számos modern programozási nyelv támogatja. Az application/json a JSON-hoz használt médiatípus.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" >}}

A PNG, a Portable Network Graphics egy olyan típusú raszteres képfájlformátumra utal, amely veszteségmentes tömörítést használ. Ezt a fájlformátumot a Graphics Interchange Format (GIF) helyettesítésére hozták létre, és nincs szerzői jogi korlátozása. A PNG fájlformátum azonban nem támogatja az animációkat. A PNG fájlformátum támogatja a veszteséges képtömörítést, amely népszerűvé teszi a felhasználók körében. Az idő múlásával a PNG az egyik leggyakrabban használt képfájlformátummá fejlődött. Szinte minden operációs rendszer támogatja a PNG fájlok megnyitását. Például a Microsoft Windows Viewer képes PNG-fájlok megnyitására, mivel az operációs rendszer alapértelmezés szerint rendelkezik a telepítés részeként elérhető támogatással.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}