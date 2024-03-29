---
title: Vytvořit XLTM - Vytvořit soubor XLTM v C#
description: Aspose Excel. C# Vytvořte XLTM Soubor rychle a snadno pomocí Aspose.Cells. Vygenerujte soubor XLTM pomocí C#. Vytvořte XLTM v C#. 0761831981 0761831983
keywords: [Aspose Excel., C# Aspose.Cells., C# Create XLTM file., Generate XLTM file in C#., Create XLTM file using C#., Write data to XLTM file via C#., Create a XLTM file in C#., C# Generate a XLTM file., C# XLTM Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Vytvořte soubor XLTM v C#" h2="Vysokorychlostní knihovna C# pro vytváření XLTM. Jedná se o profesionální softwarové řešení pro import a export XLSX, PDF a mnoha dalších formátů na platformách .NET Framework, .NET Core nebo .NET Platforms." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLTM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Vytvořte soubor XLTM pomocí C#" %}}
 Jak vytvořit soubor XLTM? S knihovnou Aspose.Cells for .NET můžete snadno vytvořit soubor XLTM programově pomocí několika řádků kódu.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)je schopen vytvářet multiplatformní aplikace se schopností generovat, upravovat, konvertovat, vykreslovat a tisknout všechny soubory aplikace Excel. .NET Excel API nejen převádí mezi tabulkovými formáty, ale umí také vykreslovat soubory Excel jako obrázky, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT a další, takže je perfektní volbou pro výměnu dokumentů ve standardních průmyslových formátech. OTEVŘENO[NuGet](https://www.nuget.org/packages/aspose.cells) správce balíčků, vyhledejte Aspose.Cells a nainstalujte. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly Správce balíčků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}
 
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="Jak vytvořit XLTM v C#" %}}

{{% blocks/products/pf/agp/text %}}

 Pro vývojáře je snadné vytvářet, načítat, upravovat a převádět soubory XLTM v rámci různých aplikací pro vytváření sestav pro zpracování dat v několika řádcích kódu.

{{% /blocks/products/pf/agp/text %}}

1.  Zahrňte jmenný prostor do souboru třídy
1.  Vytvořte instanci třídy Sešit.
1.  Otevřete první list sešitu.
1.  Získejte požadovanou buňku (buňky) listu a zadejte hodnotu do buněk.
1.  Pomocí metody Uložit uložte sešit jako soubor XLTM.

{{% blocks/products/pf/agp/code-block title="Ukázkový kód ukazuje, jak vytvořit soubor XLTM v C#." offSpacer="" %}}

```cs

// Create Workbook class instance.
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet sht = wkb.Worksheets[0];

// Get the desired cell(s) of the worksheet.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// input the value into the cell(s).
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Save the Workbook as .xltm file.
wkb.Save("created_one.xltm");

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="Knihovna C# pro vytvoření souboru XLTM" %}}

{{% blocks/products/pf/agp/text %}}

Existují dvě alternativní možnosti instalace „Aspose.Cells for .NET“ do vašeho systému. Vyberte si prosím ten, který odpovídá vašim potřebám, a postupujte podle pokynů krok za krokem:

{{% /blocks/products/pf/agp/text %}}

1.  Nainstalujte a[NuGet Balíček](https://www.nuget.org/packages/Aspose.Cells/) . Vidět[Dokumentace](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Nainstalujte knihovnu pomocí[Konzole správce balíčků](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) v rámci Visual Studio IDE

{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním ukázkového kódu konverze .NET se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows nebo kompatibilní OS s platformami .NET, .NET Core, Windows Azure nebo Mono.
-  Vývojové prostředí jako Microsoft Visual Studio.
-  Přidejte odkaz na Aspose.Cells for .NET DLL ve svém projektu.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTM" readMoreLink="https://docs.fileformat.com/spreadsheet/xltm/" >}}Přípona souboru XLTM představuje soubory, které generuje aplikace Excel Microsoft jako soubory šablon s podporou maker. Soubory XLTM jsou podobné souborům XLTX v jiné struktuře než ta, která nepodporuje vytváření souborů šablon s makry. Tyto soubory šablon se používají ke generování a nastavení rozvržení, formátování a dalších nastavení spolu s makry, aby se pak usnadnilo vytváření podobných souborů XLSX.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované generování tabulek" subTitle="Můžete také vytvořit další Microsoft formáty Excelu, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xls/" name="XLS" description="Microsoft Excelová tabulka (starší)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsx/" name="XLSX" description="Otevřete sešit XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsb/" name="XLSB" description="Binární sešit Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsm/" name="XLSM" description="Tabulka s podporou maker" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlt/" name="XLT" description="Šablona Excel 97 - 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltx/" name="XLTX" description="Excel šablona" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltm/" name="XLTM" description="Šablona s podporou maker aplikace Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/csv/" name="CSV" description="hodnoty oddělené čárkami" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/tsv/" name="TSV" description="Hodnoty oddělené záložkou" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/ods/" name="ODS" description="Tabulka OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/pdf/" name="PDF" description="Přenosný formát dokumentu" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/html/" name="HTML" description="Hyper Text Markup Language" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
