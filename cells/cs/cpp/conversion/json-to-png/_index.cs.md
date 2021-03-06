---
title: Převeďte JSON na PNG pomocí aplikace C++ 
url: /cs/cpp/conversion/json-to-png/ 
description: Ukázkový konverzní kód C++ pro dokument JSON do formátu PNG. Programátoři mohou tento zdrojový kód použít pro dávkový převod JSON na PNG v jakékoli aplikaci C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést JSON na PNG přes C++" h2="Vysoce výkonný převod JSON na PNG pomocí knihovny C++ bez nutnosti instalace Microsoft Excel, OpenOffice nebo Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JSON" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést JSON na PNG pomocí C++" %}}

 Abychom převedli JSON na PNG, použijeme
 [Aspose.Cells za C++](https://products.aspose.com/cells/cpp) 
 API, což je funkčně bohatý, výkonný a snadno použitelný nástroj pro manipulaci a konverzi dokumentů API pro platformu C++. Jeho nejnovější verzi si můžete stáhnout přímo, stačí otevřít
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 správce balíčků, vyhledejte
 Aspose.Cells.Cpp 
 a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky k převodu JSON na PNG prostřednictvím C++" %}}

{{% blocks/products/pf/agp/text %}}

 Vývojáři C++ mohou snadno převést soubor JSON na PNG pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor JSON pomocí Factory::CreateIWorkbook.1. Vyberte první list.1. Nastavit možnosti (PNG).1. Iterujte každou stránku listu a vykreslete.1. Otevřete soubor PNG v kompatibilním programu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním ukázkového kódu konverze C++ se ujistěte, že splňujete následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.- Aspose.Cells pro C++ DLL, na kterou odkazuje váš projekt.
- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.- Aspose.Cells pro C++ DLL, na kterou odkazuje váš projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód převodu JSON na PNG C++" offSpacer="" %}}

```cs
// Cesta výstupního adresáře.
StringPtr outDir = new String("OutputDirectoryPath");

// Načtěte JSON.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.json");

// Přístup k prvnímu listu.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Vytvořte objekt možností obrázku nebo tisku.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Určete formát obrázku.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetPng());

// Určete horizontální a vertikální rozlišení
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Vykreslete list s ohledem na zadané možnosti obrázku nebo tisku.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Získejte počet stránek.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Vytvořte objekt pro vytváření řetězců pro zřetězení řetězců.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Vykreslete každou stránku na obrázek png jednu po druhé.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImagePNG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".png"));

	// Získejte cestu k výstupnímu obrazu.
	StringPtr outputPNG = sb->ToString();

	// Převést pracovní list na obrázek png.
	sr->ToImage(i, outputPNG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Živá ukázka převodu JSON na PNG" sectionDescription="[Převést JSON na PNG](https://products.aspose.app/cells/conversion/json-to-png) právě teď na naší webové stránce s živými ukázkami. Živá ukázka má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát svůj soubor JSON, bude okamžitě převeden na PNG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Dostanete odkaz ke stažení." >}}

    {{% blocks/products/pf/agp/content h2="C++ Knihovna manipulace se soubory Excel" %}}

 Excel API lze použít k vytváření, úpravám, převodu a vykreslování formátů Microsoft Excel do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelné výkazy a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (JavaScript Object Notation) je otevřený standardní formát souboru pro sdílení dat, který k ukládání a přenosu dat používá text čitelný člověkem. Soubory JSON jsou uloženy s příponou .json. JSON vyžaduje méně formátování a je dobrou alternativou pro XML. JSON je odvozen z JavaScriptu, ale je to datový formát nezávislý na jazyce. Generování a parsování JSON je podporováno mnoha moderními programovacími jazyky. application/json je typ média používaný pro JSON.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" >}}

PNG, Portable Network Graphics, označuje typ formátu rastrového obrázku, který používá bezztrátovou kompresi. Tento formát souboru byl vytvořen jako náhrada za Graphics Interchange Format (GIF) a nemá žádná omezení autorských práv. Formát souboru PNG však nepodporuje animace. Formát souboru PNG podporuje bezztrátovou kompresi obrázků, díky čemuž je mezi uživateli oblíbený. Postupem času se PNG vyvinul jako jeden z nejčastěji používaných formátů obrazových souborů. Téměř všechny operační systémy podporují otevírání souborů PNG. Například prohlížeč Microsoft Windows má schopnost otevírat soubory PNG, protože OS má standardně podporu dostupnou jako součást instalace.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}