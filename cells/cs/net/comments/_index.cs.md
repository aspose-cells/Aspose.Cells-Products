---
title: Vložit komentáře do Excelu přes .NET

description: C# zdrojové kódy, které umožňují vložit komentář do souborů Microsoft Excel pomocí knihovny .NET. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vkládání komentářů Microsoft<sup>&reg;</sup> Excel prostřednictvím .NET" h2="Vytvářejte dokumenty aplikace Excel a vkládejte komentáře pomocí rozhraní API na straně serveru v aplikacích založených na .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

K buňkám můžete přidávat komentáře. Když má buňka komentář, zobrazí se v rohu buňky indikátor. Komentáře se zobrazí, když najedete kurzorem na buňku. Tyto komentáře lze použít pro diskusi, speciální pokyny nebo označení obsahu dokumentu. [.NET Knihovna Excel](/cells/net/) podporuje vkládání komentářů do souborů aplikace Excel. K tomu poskytuje API a [Komentář](https://reference.aspose.com/cells/net/aspose.cells/comment) stavební blok třídy pro komentáře.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Vložte komentáře do souboru Excel" %}}

Vkládání komentářů pomocí aplikace Excel API je jednoduché. Proces je, tvořit [Třída sešitu](https://reference.aspose.com/cells/net/aspose.cells/workbook) objekt a vyberte první list nebo příslušný list zadáním jeho indexu. Vložte požadovaná data buněk pomocí [Metoda PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Přidejte komentář do listu pomocí [Sbírka komentářů](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)'s [Přidat metodu](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Kód pro vložení komentáře do Excelu" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
