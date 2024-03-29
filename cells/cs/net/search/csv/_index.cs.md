---
title:  Vyhledejte dokument CSV bez otevření via .NET
weight: 7510
description: C# zdrojový kód pro vyhledávání slov se vzorem v souboru CSV na platformách .NET Framework, .NET Core, Mono nebo Xamarin.
keywords: [C# Aspose.Cells., c# search words with pattern in csv file., c# find words with pattern in csv file., c# search string with pattern in csv file., c# find words with pattern in csv file., c# search words in csv file., c# find words in csv file., c# search string in csv file., c# find string in csv file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Hledejte CSV Formáty v C#" h2="Nativní a vysoce výkonné CSV prohledávání dokumentů pomocí serverových Aspose.Cells for .NET API, bez použití jakéhokoli softwaru, jako je Microsoft nebo Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak hledat soubor CSV pomocí C#" %}}

 K vyhledání souboru CSV použijeme
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, což je funkčně bohatá, výkonná a snadno použitelná platforma pro vyhledávání dokumentů API pro C#. OTEVŘENO
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 správce balíčků, vyhledejte
 **Aspose.Cells** 
 a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky k hledání CSV Soubory v C#" %}}

{{% blocks/products/pf/agp/text %}}

 Základní vyhledávání dokumentů s
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 Rozhraní API lze vytvořit pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

+ Načtěte soubor CSV pomocí třídy Workbook.
+ Získejte buňky v příslušném listu.
+ Hledat Numbers, Datum a text pomocí metody Najít

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Naše API jsou podporována na všech hlavních platformách a operačních systémech. Před spuštěním níže uvedeného kódu se prosím ujistěte, že máte ve svém systému následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows nebo kompatibilní OS s .NET Framework, .NET Core, Mono nebo Xamarin Platforms
-  Vývojové prostředí jako Microsoft Visual Studio
-  Přidejte odkaz na Aspose.Cells for .NET DLL do vašeho projektu – Nainstalujte z NuGet pomocí tlačítka Stáhnout výše

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Hledat CSV Soubory - C#" offSpacer="" %}}

```cs
// searching cells containing specified string value or number
Workbook workbook = new Workbook("book1.csv");

// get cells collection
Cells cells = workbook.Worksheets[0].Cells;

FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.EntireContent;

// find the cell with the input integer or double
Cell cell1 = cells.Find(205, null, opts);

if (cell1 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell1.Name);
}else{
    Console.WriteLine("Record not found ");
}

// find the cell with the input string
Aspose.Cells.Cell cell2 = cells.Find("Items A", null, opts);

if (cell2 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell2.Name);
}else{
    Console.WriteLine("Record not found ");
}

// find the cell containing with the input string
opts.LookAtType = LookAtType.Contains;
Cell cell3 = cells.Find("Data", null, opts);

if (cell3 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell3.Name);
}else{
    Console.WriteLine("Record not found ");
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="O Aspose.Cells for .NET API" %}}

 Aspose.Cells API lze použít k vytváření, úpravám, převodu a vykreslování Microsoft formátů Excelu do různých formátů. Kromě toho jej lze použít pro komplexní vytváření grafů, škálovatelný reporting a spolehlivé výpočty v rámci softwarových aplikací. Aspose.Cells je samostatný API a nevyžaduje žádný software jako Microsoft nebo OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online CSV Hledejte živé ukázky" sectionDescription=" Hledejte text, slova, fráze v CSV dokumentech právě teď, když navštívíte naše[Webová stránka živé ukázky](https://products.aspose.app/cells/search). Živé demo má následující výhody" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stahovat Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba psát žádný kód." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Stačí nahrát své soubory CSV." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Výsledek hledání se zobrazí okamžitě." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV " readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}
Soubory s příponou CSV (Comma Separated Values) představují soubory ve formátu prostého textu, které obsahují záznamy dat s hodnotami oddělenými čárkami. Každý řádek v souboru CSV je nový záznam ze sady záznamů obsažených v souboru. Takové soubory jsou generovány, když je zamýšlen přenos dat z jednoho úložného systému do druhého. Protože všechny aplikace dokážou rozpoznat záznamy oddělené čárkou, import takových datových souborů do databáze se provádí velmi pohodlně. Téměř všechny tabulkové aplikace, jako je Microsoft Excel nebo OpenOffice Calc, dokážou importovat CSV bez velkého úsilí. Data importovaná z takových souborů jsou uspořádána do buněk tabulky pro reprezentaci uživateli.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované formáty vyhledávání" subTitle="Pomocí C# lze vyhledávat i jiné formáty včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/ods/" name="ODS" description="Soubor tabulkového procesoru OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/tsv/" name="TSV" description="Hodnoty oddělené tabulátory" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/txt/" name="TXT" description="Textový dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xls/" name="XLS" description="Binární formát Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsb/" name="XLSB" description="Binární soubor sešitu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsm/" name="XLSM" description="Soubor tabulky" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
