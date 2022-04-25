---
title: Sloučení souborů Excel API .NET C#
url: /cs/net/merger/
description: Spojte soubory tabulek Excelu a OpenOffice pomocí několika řádků kódu C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Sloučení souborů Microsoft<sup>&reg;</sup> Excel prostřednictvím .NET" h2="Zkombinujte 2 nebo více souborů aplikace Excel do jedné tabulky pomocí kódu C#" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Knihovna Excel](/cells/net/) poskytuje několik způsobů, jak kombinovat sešity s různými typy obsahu, jako jsou vzorce, data, obrázky, grafy a tak dále, do jednoho tabulkového souboru. Mezi podporované formáty souborů patří XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV a další.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Kombinujte soubory aplikace Excel s obrázky a grafy" %}}
Nejjednodušší způsob, jak zkombinovat 2 soubory Excel s obrázky a grafy, je zavolat [Sešit. Kombinovat](https://apireference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) metoda. Umožňuje sloučit soubory Excel podobného typu do jedné tabulky.
{{% blocks/products/pf/feature-page-code h3="C# Kód pro kombinování souborů aplikace Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Sloučit více souborů aplikace Excel" %}}
[CellsHelper.MergeFiles](https://apireference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) metoda podporuje sloučení dat, stylu a vzorců souboru Excel do nové tabulky stejného formátu. Je to efektivní způsob, jak sloučit několik souborů při použití ukládání do mezipaměti. 
{{% blocks/products/pf/feature-page-code h3="C# Kód pro sloučení několika souborů aplikace Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Sloučení souborů aplikace Excel zkopírováním pracovních listů" %}}
[Pracovní list. Kopírovat](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) lze použít ke kopírování dat a formátování ze zdrojového listu do jiného listu v rámci nebo mezi sešity. Metoda bere jako parametr objekt zdrojového listu.
{{% blocks/products/pf/feature-page-code h3="C# Kód pro kopírování listů v souborech aplikace Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}