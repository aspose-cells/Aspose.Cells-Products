---
title: Vyhledejte a nahraďte text v dokumentu XLSX prostřednictvím čísla C++
weight: 9570
description: C++ ukázkový kód pro redigování citlivých informací v souboru XLSX v C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ Search and replace text in XLSX file., C++ redact XLSX file., C++ edit XLSX file., C++ XLSX file redaction., C++ Search and replace string in XLSX file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Redigovat XLSX Formáty v C++" h2="Nativní a vysoce výkonné XLSX informace o redigování citlivých na dokumenty pomocí serverových Aspose.Cells for C++ API, bez použití jakéhokoli softwaru, jako je Microsoft nebo Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak upravit soubor XLSX pomocí C++" %}}

 Abychom redigovali soubor XLSX, použijeme[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) API, což je funkčně bohatá, výkonná a snadno použitelná platforma pro úpravu dokumentů API for C++. Jeho nejnovější verzi si můžete stáhnout přímo, stačí otevřít[NuGet](https://www.nuget.org/packages/aspose.cells) správce balíčků, vyhledejte**Aspose.Cells.Cpp** a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky k úpravě souborů XLSX v C++" %}}

{{% blocks/products/pf/agp/text %}}

 Základní vyhledávání a nahrazování textu v obsahu, komentářích nebo metadatech[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) Rozhraní API lze vytvořit pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

+ Načíst soubor XLSX.
+ Definujte možnosti nahrazení.
Nastavte možnost rozlišování malých a velkých písmen.
+ Nastavit možnost shody textu
+ Nahraďte text pomocí metody Nahradit(...).
+ Uložte sešit.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ podporuje všechny hlavní platformy a operační systémy. Ujistěte se prosím, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
-  Přidejte odkaz na Aspose.Cells for C++ DLL ve svém projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Redigovat XLSX Soubory - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Load XLSX file
Workbook wb(u"Input.xlsx");
//Create an instance of the ReplaceOptions class
ReplaceOptions replaceOptions;
// Set text matching option
replaceOptions.SetRegexKey(true);
// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);
// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);
// Replace text
wb.Replace(u"\bKIM\b", u"^^^^^^^^", replaceOptions);
// Save as XLSX file
wb.Save("output.xlsx");

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

    {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSX Živá ukázka redakce" sectionDescription=" Vyhledejte a nahraďte text v obsahu, komentářích nebo metadatech v dokumentech XLSX právě teď, když navštívíte naše[Webová stránka živé ukázky](https://products.aspose.app/cells/redaction). Živé demo má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát své soubory XLSX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Okamžitě bude redigován." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX je dobře známý formát pro dokumenty Excel Microsoft, který byl představen společností Microsoft vydáním Microsoft Office 2007. Na základě struktury organizované podle konvencí otevřeného balení, jak je uvedeno v části 2 standardu OOXML ECMA-376, je nový formát ECMA-376 zip balíček, který obsahuje řadu souborů XML. Základní strukturu a soubory lze prozkoumat jednoduchým rozbalením souboru .xlsx.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované dokumenty redakce" subTitle="Pomocí C++ lze snadno upravovat různé formáty včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/ods/" name="ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xls/" name="XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsb/" name="XLSB" description="Binární soubor sešitu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsm/" name="XLSM" description="Soubor tabulky" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
