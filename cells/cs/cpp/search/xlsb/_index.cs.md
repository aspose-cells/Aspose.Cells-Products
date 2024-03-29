---
title:  Vyhledejte dokument XLSB bez otevření přes C++
weight: 7020
description: C++ ukázkový kód pro vyhledávání slov se vzorem v souboru XLSB na C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ search words with pattern in xlsb file., C++ find words with pattern in xlsb file., C++ search string with pattern in xlsb file., C++ find words with pattern in xlsb file., C++ search words in xlsb file., C++ find words in xlsb file., C++ search string in xlsb file., C++ find string in xlsb file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Hledejte XLSB Formáty v C++" h2="Nativní a vysoce výkonné XLSB prohledávání dokumentů pomocí serverových Aspose.Cells for C++ API, bez použití jakéhokoli softwaru, jako je Microsoft nebo Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak hledat soubor XLSB pomocí C++" %}}

 K vyhledání souboru XLSB použijeme
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
API, což je funkčně bohatá, výkonná a snadno použitelná platforma pro vyhledávání dokumentů API for C++. Jeho nejnovější verzi si můžete stáhnout přímo, stačí otevřít
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky k hledání XLSB Soubory v C++" %}}

{{% blocks/products/pf/agp/text %}}

 Základní vyhledávání dokumentů pomocí Aspose.Cells API lze provést pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

+ Načtěte soubor XLSB vytvořením instance třídy Workbook.
+ Instantiate třídy ReplaceOptions.
+ Nastavte požadovaný vzor jako SetCaseSensitive (hodnota bool), SetMatchEntireCellContents (hodnota bool) .
Použijte metodu Workbook::Replace(...) s příslušnými možnostmi.
+ Uložte soubor XLSB pomocí metody Workbook::Save(...).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ podporuje všechny hlavní platformy a operační systémy. Ujistěte se prosím, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
-  Přidejte odkaz na Aspose.Cells for C++ DLL ve svém projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Hledat XLSB Soubory - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Source directory path.
U16String srcDir(u"SourcePath\\");

// Output directory path.
U16String outDir(u"OutputPath\\");

// Load XLSB file
Workbook  wkb(srcDir + u"sourceFile.xlsb");

// Create an instance of the IReplaceOptions class
ReplaceOptions replaceOptions;

// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);

// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);

// Replace text
wkb.Replace(u"Text to find", u"Text replacement", replaceOptions);

// Save as XLSB file
wkb.Save(outDir + u"outputFile.xlsb");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="O Aspose.Cells for C++ API" %}}

 Aspose.Cells API lze použít k vytváření, úpravám, převodu a vykreslování Microsoft formátů Excelu do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelný reporting a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSB Hledejte živé ukázky" sectionDescription=" Hledejte text, slova, fráze v XLSB dokumentech právě teď, když navštívíte naše[Webová stránka živé ukázky](https://products.aspose.app/cells/search). Živé demo má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Stačí nahrát své soubory XLSB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Výsledek hledání se zobrazí okamžitě." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB " readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Formát souboru XLSB určuje formát binárního souboru aplikace Excel, což je kolekce záznamů a struktur, které určují obsah sešitu aplikace Excel. Obsah může zahrnovat nestrukturované nebo polostrukturované tabulky čísel, text nebo čísla i text, vzorce, externí datová připojení, grafy a obrázky. Na rozdíl od XLSX (který je založen na formátu souboru Open XML), XLSB představuje binární soubor sešitu aplikace Excel. XLSB soubory lze číst a zapisovat rychleji, což je činí užitečnými pro práci s velkými soubory. XLSB se zřídka používá k ukládání sešitů, protože XLSX (a dříve XLS) jsou nejběžnější uživatelem vybrané formáty souborů pro ukládání sešitů. Lze jej otevřít na čísle Microsoft Office 2007 a vyšším.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované vyhledávací dokumenty" subTitle="Pomocí C++ lze také vyhledávat další soubory včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/csv/" name="CSV" description="hodnoty oddělené čárkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/ods/" name="ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/tsv/" name="TSV" description="Hodnoty oddělené tabulátory" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/txt/" name="TXT" description="Textový dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xls/" name="XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/search/xlsm/" name="XLSM" description="Soubor tabulky" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
