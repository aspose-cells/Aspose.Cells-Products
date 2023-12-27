---
title: Vytváření grafů Excel a převod na obrázky via .NET
description:  C# zdrojový kód pro kreslení a převod grafu nebo diagramu v Microsoft Excelu pomocí knihovny .NET.
keywords: [C# Aspose.Cells., c# Convert chart to image., c# Save chart to image., c# chart to image., create charts in c#., insert charts in c#., manage charts in c#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Vytváření a převod grafů souborů Excel via .NET" h2="Vytvářejte grafy dokumentů aplikace Excel a převádějte je na obrázky pomocí rozhraní API na straně serveru v aplikacích založených na .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Kreslení grafů je umění zobrazovat data graficky pro snadnou analýzu.[.NET Knihovna Excel](/cells/cs/net/) podporuje kreslení grafů v souborech aplikace Excel. API podporuje vytváření různých grafů uvedených v[Výčet typu ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) včetně koláčových, pyramidových, spojnicových a bublinových grafů. Kromě toho také převádí grafy na obrázky. API poskytuje a[Třída grafů](https://reference.aspose.com/cells/net/aspose.cells.charts) pro stavební bloky grafu.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Vytvářejte grafy v souboru aplikace Excel" %}}

 Vytváření grafů pomocí Excelu API je jednoduché. Proces je, vytvořit[Třída sešitu](https://reference.aspose.com/cells/net/aspose.cells/workbook)objekt a vyberte první list nebo příslušný list zadáním jeho indexu. Vložte požadovaná data buněk pomocí[Metoda PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Přidejte graf do listu pomocí kolekce Charts[Přidat metodu](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Zadejte[Typ grafu](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) z výčtu ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Kód pro vytváření grafů Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Převod grafů aplikace Excel na obrázky" %}}

 Proces převodu grafů na obrázky je: Použijte třídu Workbook k načtení souboru Excel, vyberte příslušnou pracovní sadu obsahující grafy a zavolejte[Metoda ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) pro konverzi.

{{% blocks/products/pf/feature-page-code h3="C# Kód pro převod grafu Excel na obrázek" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
