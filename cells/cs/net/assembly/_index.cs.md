---
title: Vygenerujte soubory Excel přes C#
description: Vygenerujte Microsoft Excel tabulky ze šablony pomocí kódu C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Vytvoření souborů podle šablony aplikace Excel via .NET" h2="Vytvářejte sestavy souborů Excel na základě předdefinované šablony v aplikacích založených na .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Knihovna Excel](/cells/cs/net/) podporuje generování souborů Excel založených na šablonách pro hromadné generování sestav. Šablony jsou předem navržené formáty, které se používají k vytváření zpráv se stejným vzorem. .NET kód vytvoří nový excelový soubor stejný jako šablonový dokument, který je vyplněn daty. Mezi podporované formáty souborů patří XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Vytvářejte sestavy na základě předem navržené šablony aplikace Excel" %}}

Automatizaci procesu vytváření stejných souborů vzorů je snadné pomocí .NET Sestavení API. Existují různé způsoby, jak[importovat data](https://docs.aspose.com/cells/net/import-data-into-worksheet/#importing-data-from-json) a generovat soubory Excel. API poskytuje a[WorkbookDesigner třída](https://reference.aspose.com/cells/net/aspose.cells/workbookdesigner) reprezentovat pracovní list návrháře. Vytvořte jeho objekt a použijte jej k otevření souboru šablony. Nastavte zdroj dat, kterým může být DataTable, Array, soubor Json atd. Zpracujte jej pro import dat a uložte soubor s daty v požadovaném formátu. Programátoři mohou sestavovat data do zpráv v jiných formátech souborů podle níže uvedených odkazů.



{{% blocks/products/pf/feature-page-code h3="C# Kód pro generování sestav aplikace Excel" %}}

{{< gist "aspose-com-gists" "5c193070f1b6acdc3eed001f52eadbc2" "generate-excel-reports.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Generate" afterslug="Reports" >}}
