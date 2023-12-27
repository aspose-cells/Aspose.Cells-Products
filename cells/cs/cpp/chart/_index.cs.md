---
title: Vytvářejte grafy Excel a převádějte je na obrázky prostřednictvím C++
description: C++ zdrojový kód pro kreslení a převod grafu nebo diagramu v Microsoft Excel pomocí knihovny C++
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořte Microsoft<sup>&reg;</sup> Excelové grafy a převeďte je na obrázky přes C++" h2="Převádějte grafy dokumentů Excel na obrázky a vytvářejte grafy včetně výsečových, pyramidových, spojnicových a bublinových grafů v aplikacích založených na C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Pomocí grafů v Excelu lze získat větší obrázek a snadno analyzovat data pro přijímání správných rozhodnutí.[C++ Knihovna Excel](/cells/cs/cpp/) podporuje vytváření různých grafů uvedených podle[enum Aspose::Cells::Grafy::ChartType
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/) včetně plošných, sloupcových, koláčových, pyramidových, spojnicových a bublinových grafů. Kromě toho pro převod grafů na obrázky poskytuje API a[ToImage](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/) mehtod do požadovaného formátu obrázku.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Vytvářejte grafy Excel" %}}

 Proces vytváření grafu aplikace Excel je vytvoření instance souboru[Třída sešitu](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) a vyberte požadované[Pracovní list](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/) . Přidejte graf pomocí[Přidat metodu](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/) příslušnými parametry včetně typu grafu. Přístup k grafu přes index a[Přidat](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/) zdroj dat pro graf.

{{% blocks/products/pf/feature-page-code h3="C++ Kód pro vytváření grafů Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Převést grafy na obrázky" %}}


Proces převodu grafů spočívá v tom, že nejprve vytvořte graf příslušného typu pomocí výše uvedeného kódu nebo jej otevřete z příslušného listu. Definujte cestu uložení výstupu pro obrázek a pro převod použijte metodu ToImage.

 
{{% blocks/products/pf/feature-page-code h3="C++ Kód pro převod grafů Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
