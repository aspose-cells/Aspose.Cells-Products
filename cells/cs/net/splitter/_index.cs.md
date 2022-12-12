---
title: Rozdělit list Excel v C#

description: C# zdrojové kódy, které vysvětlují, jak rozdělit soubory Microsoft Excel do více souborů v aplikacích Visual C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rozdělení souborů Microsoft<sup>&reg;</sup> Excel prostřednictvím .NET" h2="Rozdělte jeden dokument Excel do různých souborů pomocí kódu C# v aplikacích založených na .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Knihovna Excel](/cells/net/) je schopen rozdělit dokument Excel do více tabulek v aplikacích založených na .NET. Mezi podporované formáty souborů patří XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Rozdělte dokument Excel do více souborů" %}}
Nejjednodušší způsob, jak rozdělit soubory aplikace Excel podle listu, je přistupovat ke všem listům pomocí [Pracovní listy](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Iterování přes každý list a volání [kopírovat](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) metoda. Nakonec jej uložte do určené cesty. 

+ Načtěte soubor Excel s úplnou cestou pomocí [Třída sešitu](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Iterujte každý list
+ Vytvořte nový objekt třídy Workbook
+ Zkopírujte list přes [Metoda kopírování](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Zavolejte metodu Save() a předejte název souboru (úplnou cestu) s příslušným SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Kód pro rozdělení souborů aplikace Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Rozdělte pracovní list aplikace Excel na panely" %}}

Pro rozdělení okna listu na panely poskytuje API [Split metoda](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) třídy listu, která poskytuje rozdělené zobrazení listu. Chcete-li odstranit rozdělené zobrazení, API poskytuje [Metoda RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Nakonec jej uložte do určené cesty. 

{{% blocks/products/pf/feature-page-code h3="C# Kód pro rozdělení okna listu Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Kód pro odstranění rozděleného zobrazení" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
