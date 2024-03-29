---
title:  Odemkněte dokument XLS přes C++
weight: 2380
description: C++ ukázkový kód pro odemknutí heslem chráněného souboru XLS na C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
keywords: [C++ Aspose.Cells., C++ unlock XLS files., C++ how to unlock XLS document., C++ unprotect XLS files., remove protection from XLS files., decrypt XLS Files using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Odemkněte soubory XLS přes C++" h2="Odstraňte ochranu z tabulek aplikace Excel včetně souboru XLS pomocí knihovny C++." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak odstranit ochranu souboru XLS pomocí C++" %}}

 K odemknutí souboru XLS použijeme
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API, což je funkčně bohatá, výkonná a snadno použitelná platforma pro ochranu dokumentů API for C++. Jeho nejnovější verzi si můžete stáhnout přímo, stačí otevřít
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

{{% blocks/products/pf/agp/feature-section-col title="Odemkněte XLS přes C++" %}}

{{% blocks/products/pf/agp/text %}}

 Potřebuješ
 [aspose.cells.dll](https://downloads.aspose.com/cells/cpp) 
 odkazovaný ve vašem projektu k provedení následujícího pracovního postupu.

{{% /blocks/products/pf/agp/text %}}

1.  Okamžitá třída sešitu s cestou k chráněnému souboru XLS
1.  Získejte výchozí nebo jakýkoli pracovní list pro odstranění ochrany
1.  Odstraňte ochranu listu pomocí metody Worksheet.Unprotect
1.  Odstraňte ochranu sešitu pomocí metody Workbook.Unprotect
1.  Uložte výsledek ve formátu XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ podporuje všechny hlavní platformy a operační systémy. Ujistěte se prosím, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
-  Přidejte odkaz na Aspose.Cells for C++ DLL ve svém projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Příkaz" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// instantiate a Workbook object with protected XLS file
Workbook workbook(u"protected.xls");

// access the default worksheet in the Excel file
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in XLS format
workbook.Save("unprotected.xls", SaveFormat::Auto);

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

        {{< blocks/products/pf/agp/demobox sectionTitle="Bezplatná aplikace k odemknutí XLS" sectionDescription=" Podívejte se na naše živé ukázky[odemknout XLS soubory](https://products.aspose.app/cells/unlock/xls) s následujícími výhodami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba nic stahovat ani nastavovat" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát nebo kompilovat kód" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát soubor XLS a stisknout tlačítko „Odemknout“." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Stáhněte si výsledný soubor XLS z odkazu" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Soubory s příponou XLS představují binární formát souboru Excel. Takové soubory mohou být vytvořeny aplikací Excel Microsoft i jinými podobnými tabulkovými programy, jako je OpenOffice Calc nebo Apple Numbers. Soubor uložený aplikací Excel je známý jako Workbook, kde každý sešit může mít jeden nebo více listů. Data se ukládají a zobrazují uživatelům ve formátu tabulky v listu a mohou zahrnovat číselné hodnoty, textová data, vzorce, externí datová připojení, obrázky a grafy. Aplikace jako Microsoft Excel vám umožňují exportovat data sešitu do několika různých formátů včetně PDF, CSV, XLSX, TXT, HTML, XPS a několika dalších. Formát souboru XLS byl nahrazen otevřenějším a strukturovanějším formátem XLSX s vydáním Microsoft Excel 2007. Nejnovější verze stále poskytují podporu pro vytváření a čtení souborů XLS, i když XLSX je nyní první volbou použití.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty odemykání" subTitle="Pomocí C++ lze snadno odstranit ochranu / odemknutí různých formátů včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/ods/" name="ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsb/" name="XLSB" description="Binární soubor sešitu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsm/" name="XLSM" description="Soubor tabulky" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsx/" name="XLSX" description="Soubor Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
