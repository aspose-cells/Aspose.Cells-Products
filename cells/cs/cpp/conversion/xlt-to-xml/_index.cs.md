---
title: Převeďte XLT na XML pomocí aplikace C++ 
url: /cs/cpp/conversion/xlt-to-xml/ 
description: Ukázka převodního kódu C++ pro dokument XLT do formátu XML. Programátoři mohou použít tento zdrojový kód pro dávkovou konverzi XLT do XML v jakékoli aplikaci C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést XLT na XML prostřednictvím C++" h2="Vysoce výkonný převod XLT na XML pomocí knihovny C++ bez nutnosti instalace Microsoft Excel, OpenOffice nebo Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést XLT na XML pomocí C++" %}}

 K převodu XLT na XML použijeme
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod XLT na XML prostřednictvím C++" %}}

{{% blocks/products/pf/agp/text %}}

 Vývojáři C++ mohou snadno převést soubor XLT na XML pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor XLT pomocí Factory::CreateIWorkbook.1. Zavolejte metodu Save().1. Předejte cestu výstupního souboru s příponou (XML).1. Soubor XML bude uložen do zadané cesty.1. Otevřete soubor XML v kompatibilním programu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním ukázkového kódu konverze C++ se ujistěte, že splňujete následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.- Aspose.Cells pro C++ DLL, na kterou odkazuje váš projekt.
- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.- Aspose.Cells pro C++ DLL, na kterou odkazuje váš projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód konverze XLT na XML C++" offSpacer="" %}}

```cs
// Vložte XLT.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlt");

// Uložit ve formátu XML.
wkb->Save(u"convertedFile.xml", SaveFormat_Xml);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Živá ukázka konverze XLT na XML" sectionDescription="[Převést XLT na XML](https://products.aspose.app/cells/conversion/xlt-to-xml) právě teď na naší webové stránce s živými ukázkami. Živá ukázka má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát váš soubor XLT, bude okamžitě převeden do XML." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Dostanete odkaz ke stažení." >}}

    {{% blocks/products/pf/agp/content h2="C++ Knihovna manipulace se soubory Excel" %}}

 Excel API lze použít k vytváření, úpravám, převodu a vykreslování formátů Microsoft Excel do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelné výkazy a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}

Soubory s příponou .XLT jsou soubory šablon vytvořené pomocí Microsoft Excel, což je tabulkový procesor, který je součástí sady Microsoft Office. Microsoft Office 97-2003 podporoval vytváření nových souborů XLT a také jejich otevírání. Nejnovější verze aplikace Excel je stále schopna otevřít soubory šablon tohoto starého formátu. Takový soubor šablony se používá k rychlému vytvoření nových souborů aplikace Excel s výchozími daty a nastaveními, jako je formátování stránky, velikost písma, okraje, grafy atd., které lze dále uložit jako nové soubory .XLS.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" >}}

XML je zkratka pro Extensible Markup Language, který je podobný HTML, ale liší se v používání značek pro definování objektů. Celá myšlenka za vytvořením formátu souboru XML byla ukládat a přenášet data bez závislosti na softwarových nebo hardwarových nástrojích. Jeho popularita je způsobena tím, že je čitelný člověkem i strojově. To umožňuje vytvářet společné datové protokoly ve formě objektů, které mají být uloženy a sdíleny po síti, jako je World Wide Web (WWW). "X" v XML je pro rozšiřitelnost, což znamená, že jazyk lze rozšířit na libovolný počet symbolů podle požadavků uživatele. Právě pro tyto funkce jej využívá mnoho standardních formátů souborů, jako je Microsoft Open XML, LibreOffice OpenDocument, XHTML a SVG.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}