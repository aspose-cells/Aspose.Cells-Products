---
title: Chránit a uzamknout dokument XLSB prostřednictvím C++ 
weight: 4860
url: /cs/cpp/protect/xlsb/ 
description: C++ ukázkový kód pro uzamčení souboru XLSB pomocí hesla v C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Šifrovat soubory XLSB přes C++" h2="Chraňte heslem tabulky aplikace Excel včetně formátu XLSB pomocí knihovny .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp/" installationsDocsLink="https://docs.aspose.com/cells/cpp/" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak zabezpečit soubor XLSB pomocí C++" %}}

 Za účelem ochrany souboru XLSB použijeme
 [Aspose.Cells za C++](https://products.aspose.com/cells/cpp) 
 API, což je funkčně bohaté, výkonné a snadno použitelné šifrování dokumentů API pro platformu C++. Jeho nejnovější verzi si můžete stáhnout přímo, stačí otevřít
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 správce balíčků, vyhledejte
 **Aspose.Cells.Cpp** 
 a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky k ochraně souborů XLSB prostřednictvím C++" %}}

{{% blocks/products/pf/agp/text %}}

 Ochranu dokumentů pomocí rozhraní API Aspose.Cells lze provést pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor XLSB pomocí třídy IWorkbook1. Použijte metodu Protect(..) s ProtectionType a Password1. Uložte chráněný soubor XLSB metodou Save().
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells pro C++ podporuje na všech hlavních platformách a operačních systémech. Ujistěte se prosím, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.- Aspose.Cells pro C++ DLL, na kterou odkazuje váš projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Příkaz" offSpacer="" %}}

```cs

// Zdrojová cesta.
StringPtr srcDir = new String("SourcePath\");

// Výstupní cesta.
StringPtr outDir = new String("OutputPath\");

// Načtěte soubor XLSB
intrusive_ptr<IWorkbook> workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sourceFile.xlsb")));

// Chraňte sešit zadáním typu ochrany
workbook->Protect(ProtectionType::ProtectionType_All, new String("12345"));

// Uložte soubor XLSB
workbook->Save(outDir->StringAppend(new String("output.xlsb")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="O Aspose.Cells pro C++ API" %}}

 Aspose.Cells API lze použít k vytváření, úpravám, převodu a vykreslování formátů aplikace Microsoft Excel do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelné výkazy a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Bezplatná aplikace pro ochranu XLSB" sectionDescription="Podívejte se na naše živé ukázky [šifrovat soubory XLSB](https://products.aspose.app/cells/protect/xlsb) s následujícími výhodami." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není potřeba nic stahovat ani nastavovat" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát nebo kompilovat kód" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát soubor XLSB a stisknout tlačítko „Odemknout“." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Stáhněte si výsledný soubor XLSB z odkazu" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Formát souboru XLSB určuje formát binárního souboru aplikace Excel, což je kolekce záznamů a struktur, které určují obsah sešitu aplikace Excel. Obsah může zahrnovat nestrukturované nebo polostrukturované tabulky čísel, text nebo čísla i text, vzorce, externí datová připojení, grafy a obrázky. Na rozdíl od XLSX (který je založen na formátu souboru Open XML), XLSB představuje binární soubor sešitu aplikace Excel. Soubory XLSB lze číst a zapisovat rychleji, což je činí užitečnými pro práci s velkými soubory. XLSB se k ukládání sešitů používá jen zřídka, protože XLSX (a dříve XLS) jsou nejběžnější uživatelsky vybrané formáty souborů pro ukládání sešitů. Lze jej otevřít pomocí sady Microsoft Office 2007 a vyšší.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované ochranné dokumenty" subTitle="Pomocí C++ lze chránit další soubory včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/ods/" name="ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xls/" name="XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsm/" name="XLSM" description="Soubor tabulky" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsx/" name="XLSX" description="Soubor Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}