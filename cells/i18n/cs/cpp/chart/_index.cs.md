---
title: Vytvářejte grafy Excel a převádějte je na obrázky prostřednictvím C++
url: /cs/cpp/chart/
description: Zdrojový kód C++ pro kreslení a převod grafu nebo diagramu v aplikaci Microsoft Excel pomocí knihovny C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvářejte grafy Microsoft<sup>&reg;</sup> Excel a převádějte je na obrázky prostřednictvím C++" h2="Převádějte grafy dokumentů Excel na obrázky a také vytvářejte grafy včetně výsečových, pyramidových, spojnicových a bublinových grafů v aplikacích založených na C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pomocí grafů v Excelu lze získat větší obrázek a snadno analyzovat data pro přijímání správných rozhodnutí. [C++ Knihovna Excel](/cells/cpp/) podporuje vytváření různých grafů uvedených podle [výčet Aspose::Cells::Charts::ChartType
](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) včetně plošných, sloupcových, koláčových, pyramidových, spojnicových a bublinových grafů. Kromě toho pro převod grafů na obrázky poskytuje API a [ToImage mehtod](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) do požadovaného formátu obrázku.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Vytvářejte grafy Excel" %}}

Proces vytváření grafu aplikace Excel je vytvoření instance souboru [Třída sešitu](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) a vyberte požadované [Pracovní list](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Přidejte graf pomocí [Přidat metodu](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) příslušnými parametry včetně typu grafu. Přístup k grafu přes index a [Přidat](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) zdroj dat pro graf.

{{% blocks/products/pf/feature-page-code h3="C++ Kód pro vytváření grafů Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Převést grafy na obrázky" %}}


Proces převodu grafů spočívá v tom, že nejprve vytvořte graf příslušného typu pomocí výše uvedeného kódu nebo jej otevřete z příslušného listu. Definujte cestu uložení výstupu pro obrázek a pro převod použijte metodu ToImage.

 
{{% blocks/products/pf/feature-page-code h3="C++ Kód pro převod grafů Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}