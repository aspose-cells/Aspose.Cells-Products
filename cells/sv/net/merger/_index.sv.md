---
title: Excel-filsammanslagning API .NET C#

description: Sammanfoga Excel- och OpenOffice-kalkylbladsfiler med bara några rader med C#-kod.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-filsammanslagning via .NET" h2="Kombinera 2 eller fler Excel-filer i ett enda kalkylblad med C#-koden" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel-bibliotek](/cells/net/) ger flera sätt att kombinera arbetsböcker med olika typer av innehåll som formler, data, bilder, diagram och så vidare till en enda kalkylarksfil. Filformat som stöds inkluderar XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV och mer.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinera Excel-filer med bilder och diagram" %}}
Det enklaste sättet att kombinera 2 Excel-filer med bilder och diagram är att anropa [Arbetsbok. Kombinera](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) metod. Det gör det möjligt att slå samman Excel-filer av liknande typ till ett enda kalkylblad.
{{% blocks/products/pf/feature-page-code h3="C# Kod för att kombinera Excel-filer" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Slå samman flera Excel-filer" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) Metoden stöder sammanslagning av data, stil och formler för en Excel-fil till ett nytt kalkylblad i samma format. Det är ett effektivt sätt att slå samman flera filer samtidigt som du använder cachning. 
{{% blocks/products/pf/feature-page-code h3="C# Kod för att slå samman flera Excel-filer" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Slå ihop Excel-filer genom att kopiera arbetsblad" %}}
[Arbetsblad.Kopiera](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) kan användas för att kopiera data och formatering från ett källark till ett annat kalkylblad inom eller mellan arbetsböcker. Metoden tar källarksobjektet som en parameter.
{{% blocks/products/pf/feature-page-code h3="C# Kod för att kopiera kalkylblad över Excel-filer" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
