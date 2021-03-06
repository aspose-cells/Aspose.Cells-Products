---
title: Vyhledejte a nahraďte text v dokumentu XLSB prostřednictvím C++ 
weight: 6660
url: /cs/cpp/redaction/xlsb/ 
description: C++ ukázkový kód pro redigování citlivých informací v souboru XLSB v C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Upravit formáty XLSB v C++" h2="Nativní a vysoce výkonné XLSB dokumenty citlivé redakční informace pomocí rozhraní API Aspose.Cells na straně serveru pro C++ bez použití jakéhokoli softwaru, jako je Microsoft nebo Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak upravit soubor XLSB pomocí C++" %}}

 Abychom redigovali soubor XLSB, použijeme
 [Aspose.Cells za C++](https://products.aspose.com/cells/cpp) 
 API, což je funkčně bohatá, výkonná a snadno použitelná redakce dokumentů API pro platformu C++. Jeho nejnovější verzi si můžete stáhnout přímo, stačí otevřít
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 správce balíčků, vyhledejte
 **Aspose.Cells.Cpp** 
 a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky k úpravě souborů XLSB v C++" %}}

{{% blocks/products/pf/agp/text %}}

 Základní vyhledávání a nahrazování textu v obsahu, komentářích nebo metadatech
 [Aspose.Cells za C++](https://products.aspose.com/cells/cpp) 
 Rozhraní API lze vytvořit pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

+ Načíst soubor XLSB.
+ Definujte možnosti nahrazení.
+ Nastavte možnost rozlišování malých a velkých písmen.
+ Nastavit možnost shody textu
+ Nahraďte text pomocí metody Nahradit(...).
+ Uložte sešit.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells pro C++ podporuje na všech hlavních platformách a operačních systémech. Ujistěte se prosím, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.- Aspose.Cells pro C++ DLL, na kterou odkazuje váš projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Upravit soubory XLSB – C++" offSpacer="" %}}

```cs
// Cesta ke zdrojovému adresáři.
StringPtr srcDir = new String("SourceFolder\\");

// Cesta výstupního adresáře.
StringPtr outDir = new String("OutputFolder\\");

// Načtěte soubor XLSB
intrusive_ptr<IWorkbook>  workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("book1.xlsb")));

// Vytvořte instanci třídy IReplaceOptions třídy
intrusive_ptr<IReplaceOptions> replaceOptions = Factory::CreateIReplaceOptions();

// Nastavte možnost rozlišování malých a velkých písmen
replaceOptions->SetCaseSensitive(false);

// Nastavit možnost shody textu
replaceOptions->SetMatchEntireCellContents(false);

// Nahradit text
workbook->Replace(new String("Text to find"), new String("Text replacement"), replaceOptions);

// Uložit jako soubor XLSB
workbook->Save(outDir->StringAppend(new String("book1_out.xlsb")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="O Aspose.Cells pro C++ API" %}}

 Aspose.Cells API lze použít k vytváření, úpravám, převodu a vykreslování formátů aplikace Microsoft Excel do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelné výkazy a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online živá ukázka redakce XLSB" sectionDescription="Vyhledejte a nahraďte text v obsahu, komentářích nebo metadatech v dokumentech XLSB právě teď, když navštívíte naše [Web živé ukázky](https://products.aspose.app/cells/redaction). Živé demo má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát soubory XLSB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Okamžitě bude redigován." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Formát souboru XLSB určuje formát binárního souboru aplikace Excel, což je kolekce záznamů a struktur, které určují obsah sešitu aplikace Excel. Obsah může zahrnovat nestrukturované nebo polostrukturované tabulky čísel, text nebo čísla i text, vzorce, externí datová připojení, grafy a obrázky. Na rozdíl od XLSX (který je založen na formátu souboru Open XML), XLSB představuje binární soubor sešitu aplikace Excel. Soubory XLSB lze číst a zapisovat rychleji, což je činí užitečnými pro práci s velkými soubory. XLSB se k ukládání sešitů používá jen zřídka, protože XLSX (a dříve XLS) jsou nejběžnější uživatelsky vybrané formáty souborů pro ukládání sešitů. Lze jej otevřít pomocí sady Microsoft Office 2007 a vyšší. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované dokumenty redakce" subTitle="Pomocí C++ lze snadno upravovat různé formáty včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/ods/" name="ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xls/" name="XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsm/" name="XLSM" description="Soubor tabulky" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}