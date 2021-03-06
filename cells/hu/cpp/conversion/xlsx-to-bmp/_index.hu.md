---
title: Konvertálja az XLSX-et BMP-vé a(z) C++ alkalmazáson keresztül 
weight: 8920
url: /hu/cpp/conversion/xlsx-to-bmp/ 
description: Minta C++ konverziós kód XLSX dokumentumhoz BMP formátumba. A programozók ezt a forráskódot használhatják az XLSX-ből BMP-be kötegelt konvertáláshoz bármely C++-alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSX konvertálása BMP-vé a következőn keresztül: C++" h2="Nagy teljesítményű XLSX-BMP konvertálás a C++ könyvtár használatával, Microsoft Excel, OpenOffice vagy Adobe Acrobat telepítése nélkül." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Az XLSX konvertálása BMP-vé a következővel: C++" %}}

 Az XLSX BMP-vé konvertálásához használjuk
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

{{% blocks/products/pf/agp/feature-section-col title="Az XLSX konvertálása BMP-vé a következőn keresztül: C++" %}}

{{% blocks/products/pf/agp/text %}}

 A C++ fejlesztői könnyedén konvertálhatják az XLSX fájlt BMP-vé, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. Töltse be az XLSX fájlt a Factory::CreateIWorkbook segítségével.1. Válassza ki az első munkalapot.1. Állítsa be a (BMP) opciókat.1. Ismételje meg a lap minden oldalát, és jelenítse meg.1. Nyissa meg a BMP fájlt egy kompatibilis programban.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A C++ konverziós mintakód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer C++ Runtime Environment for Windows 32 bit, Windows 64 bit és Linux 64 bit.- Aspose.Cells a projektben hivatkozott C++ DLL-hez.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSX-ből BMP-be C++ konverziós forráskód" offSpacer="" %}}

```cs
// Kimeneti könyvtár elérési útja.
StringPtr outDir = new String("OutputDirectoryPath");

// Töltse be az XLSX-et.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.xlsx");

// Az első munkalap elérése.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Kép vagy nyomtatási beállítások objektum létrehozása.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Adja meg a képformátumot.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetBmp());

// Adja meg a vízszintes és függőleges felbontást
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Renderje le a lapot a megadott kép- vagy nyomtatási beállításoknak megfelelően.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Oldalszám lekérése.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Hozzon létre karakterlánc-építő objektumot a karakterlánc-összefűzéshez.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Renderelje le az egyes oldalakat bmp képpé egyenként.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageBMP_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".bmp"));

	// Szerezze meg a kimeneti kép elérési útját.
	StringPtr outputBMP = sb->ToString();

	// Konvertálja a munkalapot bmp képpé.
	sr->ToImage(i, outputBMP);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLSX-ből BMP-be konvertáló élő bemutatók" sectionDescription="[Az XLSX konvertálása BMP-re](https://products.aspose.app/cells/conversion/xlsx-to-bmp) most keresse fel az Élő bemutatók webhelyét.Az élő bemutató a következő előnyökkel jár" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nincs szükség a(z) Aspose API letöltésére." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel XLSX fájlját, amely azonnal BMP-re konvertálódik." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Megkapod a letöltési linket." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel fájlkezelési könyvtár" %}}

 Az Excel API segítségével Microsoft Excel formátumokat hozhat létre, szerkeszthet, konvertálhat és renderelhet különböző formátumokká. Ezenkívül használható átfogó diagramok készítésére, méretezhető jelentésekre és megbízható számításokra a szoftveralkalmazásokon belül. A Aspose.Cells egy önálló API, és nem igényel olyan szoftvert, mint a Microsoft vagy az OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}

Az XLSX a Microsoft Excel dokumentumok jól ismert formátuma, amelyet a Microsoft a Microsoft Office 2007 kiadásával vezetett be. Az ECMA-376 OOXML szabvány 2. részében leírt nyílt csomagolási egyezmények szerint szervezett szerkezet alapján az új formátum egy zip-csomag, amely számos XML-fájlt tartalmaz. Az alapul szolgáló struktúra és fájlok az .xlsx fájl egyszerű kicsomagolásával vizsgálhatók.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" >}}

.BMP kiterjesztésű fájlok olyan bittérképes képfájlokat képviselnek, amelyeket bittérképes digitális képek tárolására használnak. Ezek a képek függetlenek a grafikus adaptertől, és eszközfüggetlen bittérkép (DIB) fájlformátumnak is nevezik őket. Ez a függetlenség azt a célt szolgálja, hogy a fájlt több platformon, például Microsoft Windowson és Macen is megnyissa. A BMP fájlformátum kétdimenziós digitális képként képes tárolni az adatokat mind monokróm, mind színes formátumban, különböző színmélységgel.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="Az XLSX-et számos más fájlformátumra is konvertálhatja, köztük néhány alább felsorolt fájlformátumra." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-csv/" name="XLSX A CSV-re" description="Vesszővel elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-dif/" name="XLSX TO DIF" description="Adatcsere formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-emf/" name="XLSX TO EMF" description="Továbbfejlesztett metafájl formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-gif/" name="XLSX GIF-RE" description="Grafikus csereformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-html/" name="XLSX-ből HTML-be" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-jpeg/" name="XLSX - JPEG" description="JPEG kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-mhtml/" name="XLSX-ről MHTML-re" description="Weboldal archív formátuma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-ods/" name="XLSX TO ODS" description="OpenDocument táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-pdf/" name="XLSX-ből PDF-be" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-png/" name="XLSX - PNG" description="Hordozható hálózati grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-svg/" name="XLSX SVG-re" description="Skálázható vektorgrafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-tiff/" name="XLSX-től TIFF-hez" description="Címkézett képformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-tsv/" name="XLSX A TSV-re" description="Tabulátorral elválasztott értékek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xls/" name="XLSX - XLS" description="Excel bináris formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xlsb/" name="XLSX - XLSB" description="Bináris Excel munkafüzet fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xlsm/" name="XLSX - XLSM" description="Táblázatfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xltm/" name="XLSX - XLTM" description="Excel makró-kompatibilis sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xltx/" name="XLSX - XLTX" description="Office OpenXML Excel sablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xlsx-to-xps/" name="XLSX-től XPS-ig" description="XML papírspecifikációk" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}