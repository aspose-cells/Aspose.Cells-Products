---
title: Převeďte XLTX na CSV pomocí aplikace C++ 
url: /cs/cpp/conversion/xltx-to-csv/ 
description: Ukázkový konverzní kód C++ pro dokument XLTX do formátu CSV. Programátoři mohou použít tento zdrojový kód pro dávkový převod XLTX na CSV v jakékoli aplikaci C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést XLTX na CSV přes C++" h2="Vysoce výkonný převod XLTX na CSV pomocí knihovny C++ bez nutnosti instalace Microsoft Excel, OpenOffice nebo Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="CSV" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést XLTX na CSV pomocí C++" %}}

 K převodu XLTX do CSV použijeme
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod XLTX na CSV prostřednictvím C++" %}}

{{% blocks/products/pf/agp/text %}}

 Vývojáři C++ mohou snadno převést soubor XLTX na CSV pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor XLTX pomocí Factory::CreateIWorkbook.1. Zavolejte metodu Save().1. Předejte cestu výstupního souboru s příponou souboru (CSV).1. Soubor CSV bude uložen do zadané cesty.1. Otevřete soubor CSV v kompatibilním programu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním ukázkového kódu konverze C++ se ujistěte, že splňujete následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.- Aspose.Cells pro C++ DLL, na kterou odkazuje váš projekt.
- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.- Aspose.Cells pro C++ DLL, na kterou odkazuje váš projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód konverze XLTX na CSV C++" offSpacer="" %}}

```cs
// Vložte XLTX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltx");

// Uložit ve formátu CSV.
wkb->Save(u"convertedFile.csv", SaveFormat_Csv);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Živá ukázka konverze XLTX na CSV" sectionDescription="[Převést XLTX na CSV](https://products.aspose.app/cells/conversion/xltx-to-csv) právě teď na naší webové stránce s živými ukázkami. Živá ukázka má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát soubor XLTX, bude okamžitě převeden na CSV." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Dostanete odkaz ke stažení." >}}

    {{% blocks/products/pf/agp/content h2="C++ Knihovna manipulace se soubory Excel" %}}

 Excel API lze použít k vytváření, úpravám, převodu a vykreslování formátů Microsoft Excel do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelné výkazy a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTX" readMoreLink="https://docs.fileformat.com/spreadsheet/xltx/" >}}

Soubory s příponou XLTX představují soubory šablon Microsoft Excel, které jsou založeny na specifikacích formátu souborů Office OpenXML. Používá se k vytvoření standardního souboru šablony, který lze použít ke generování souborů XLSX, které vykazují stejná nastavení jako v souboru XLTX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

Soubory s příponou CSV (Comma Separated Values) představují prosté textové soubory, které obsahují záznamy dat s hodnotami oddělenými čárkami. Každý řádek v souboru CSV je nový záznam ze sady záznamů obsažených v souboru. Takové soubory se generují, když je zamýšlený přenos dat z jednoho úložného systému do druhého. Protože všechny aplikace dokážou rozpoznat záznamy oddělené čárkou, import takových datových souborů do databáze se provádí velmi pohodlně. Téměř všechny tabulkové aplikace, jako je Microsoft Excel nebo OpenOffice Calc, dokážou importovat CSV bez velkého úsilí. Data importovaná z takových souborů jsou uspořádána do buněk tabulkového procesoru pro reprezentaci uživateli.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}