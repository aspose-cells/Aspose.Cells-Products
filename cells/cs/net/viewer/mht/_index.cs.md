---
title:  Zobrazit formáty souborů MHT via .NET
description: C# zdrojový kód pro načtení, vykreslení a zobrazení dokumentů MHT na platformách .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin.
keywords: [C# Aspose.Cells., c# view MHT files., c# how to render MHT document., c# load and display MHT files., MHT File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Prohlížeč souborů MHT for .NET" h2="Prohlížejte si tabulky Excelu a OpenOffice, jako je MHT, aniž byste potřebovali Microsoft Excel nebo Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak zobrazit soubor MHT pomocí C#" %}}

 K zobrazení souboru MHT použijeme<a href="https://products.aspose.com/cells/net">Aspose.Cells for .NET</a>API, což je funkčně bohatá, výkonná a snadno použitelná platforma API pro C#, kterou lze použít s jakýmkoli prohlížečem. OTEVŘENO<a href="https://www.nuget.org/packages/aspose.cells">NuGet</a> správce balíčků, vyhledejte<b>Aspose.Cells</b> a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly Správce balíčků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky k zobrazení MHT přes C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells usnadňuje vývojářům zobrazení souboru MHT pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor MHT v instanci sešitu
1. Vytvořte instanci HtmlSaveOptions a nastavte vlastnost ExportHeadings na true
1. Uložte soubor MHT ve formátu HTML pomocí metody Workbook.Save
1. Načtěte výsledný HTML ve výchozím prohlížeči pomocí Process.Start


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET je podporován na všech hlavních operačních systémech. Jen se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows nebo kompatibilní OS s platformami .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin
-  Vývojové prostředí jako Microsoft Visual Studio
-  Přidejte odkaz na Aspose.Cells for .NET DLL ve vašem projektu

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# příklad kódu pro zobrazení souboru MHT" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the MHT file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.mht");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the MHT file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Cells API lze použít k vytváření, úpravám, převodu a vykreslování Microsoft formátů Excelu do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelný reporting a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Bezplatná aplikace pro zobrazení MHT" sectionDescription=" Podívejte se na naše živé ukázky[Zobrazit MHT](https://products.aspose.app/cells/viewer/mht) s následujícími výhodami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba nic stahovat ani nastavovat" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát nebo kompilovat kód" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát soubor MHT a stisknout tlačítko \"Zobrazit\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" V případě potřeby stáhněte soubor MHT z odkazu" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHT" readMoreLink="https://docs.fileformat.com/web/mht/" >}}
Soubor s příponou .mht je formát archivačního souboru s povoleným MIME, který obsahuje různé typy dat do jednoho souboru. Může ukládat data jako text, obrázky, styly stránek ve formě souborů CSS, JavaScript a další zdroje jako vložené prostředky. Soubory MHT, které mají typ MIME message/rfc822, zapouzdřují veškerý obsah souboru HTML jako jeden archivní soubor pro uložení při archivaci na úložných zařízeních. Softwarové aplikace, jako je Microsoft Word, vám umožní převést vaše dokumenty WORD na MHT exportem jako soubor MHT. Soubory MHT lze otevřít pomocí oblíbených prohlížečů, jako je Microsoft Internet Explore a Google Chrome.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
