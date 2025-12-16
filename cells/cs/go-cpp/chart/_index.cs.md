---
title: Vytvářejte grafy v Excelu a převádějte je do obrázků pomocí Go přes C++
description: Pro kreslení a převod grafu nebo diagramu v Excelu pomocí knihovny Go přes zdrojový kód C++ použijte zdrojový kód Microsoft.
keywords: [Go via C++ Aspose.Cells., Go via C++ Convert chart to image., Go via C++ Save chart to image., Go via C++ chart to image., create charts in Go via C++., insert charts in Go via C++., manage charts in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořte Microsoft<sup>&reg;</sup> grafy v Excelu a převeďte je do obrázků pomocí Go přes C++" h2="Převádějte grafy z dokumentů Excelu na obrázky a vytvářejte grafy včetně koláčových, pyramidových, spojnicových a bublinových grafů v aplikaci Go prostřednictvím aplikací založených na kódu C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Pomocí excelových grafů lze získat širší obraz a snadno analyzovat data pro správné rozhodování.[Přejděte přes C++ Knihovna Excelu](/cells/cs/go-cpp/) podporuje vytváření různých grafů uvedených podle[výčet Aspose::Cells::Grafy::TypGrafu
](https://reference.aspose.com/cells/go-cpp/charttype/) včetně plošných, sloupcových, koláčových, pyramidových, spojnicových a bublinových grafů. Pro převod grafů do obrázků navíc poskytuje API[ToImage](https://reference.aspose.com/cells/go-cpp/chart/toimage_string/) metod do požadovaného obrazového formátu.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Vytváření grafů v Excelu" %}}

 Proces vytváření grafu v Excelu spočívá v vytvoření instance[Třída pracovního sešitu](https://reference.aspose.com/cells/go-cpp/workbook/) a vyberte požadovanou[Pracovní list](https://reference.aspose.com/cells/go-cpp/worksheet/) Přidejte graf pomocí[Přidat metodu](https://reference.aspose.com/cells/go-cpp/chartcollection/addfloatingchart/) s příslušnými parametry včetně typu grafu. Přístup k grafu přes index a[Přidat](https://reference.aspose.com/cells/go-cpp/seriescollection/add_string_bool_bool/)zdroj dat pro graf.

{{% blocks/products/pf/feature-page-code h3="Pro vytvoření grafů v Excelu přejděte přes kód C++" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "create-excel-chart.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Převod grafů na obrázky" %}}


Pro převod grafů je nejprve nutné vytvořit graf příslušného typu pomocí výše uvedeného kódu nebo k němu přistupovat z příslušného listu. Definovat cestu pro uložení výstupního obrázku a pro převod použít metodu ToImage.


{{% blocks/products/pf/feature-page-code h3="Pro převod grafů v Excelu přejděte přes kód C++" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "convert-excel-chart-to-image.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{< /blocks/products/pf/feature-page-wrap >}}