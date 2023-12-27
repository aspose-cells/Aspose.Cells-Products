---
title: Vytvářejte grafy Excel a převádějte je na obrázky via Java
description:  Java zdrojový kód pro kreslení a převod grafu nebo diagramu v Microsoft Excelu pomocí knihovny Java.
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Převod a vytváření grafů souborů Excel via Java" h2="Převádějte grafy dokumentů Excel na obrázky a také vytvářejte různé grafy pomocí rozhraní API na straně serveru v aplikacích založených na Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Analýza dat pomocí grafů ukazuje větší obrázek a je snadné činit informovanější rozhodnutí s jasnějšími poznatky.[Java Knihovna Excel](/cells/cs/java/) podporuje kreslení různých vytváření grafů uvedených podle[Typ grafu](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) včetně koláčových, pyramidových, spojnicových a bublinových grafů. Kromě toho také převádí grafy na obrázky. API poskytuje a[Třída grafů](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) pro reprezentaci jednoho excelového grafu.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Převod grafů aplikace Excel na obrázky" %}}

 Proces převodu grafů na obrázky včetně JPG, PNG, TIFF, BMP atd. je, použijte[pracovní sešit](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) třídy k načtení souboru Excel vyberte příslušný[pracovní stůl](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) obsahující grafy nebo procházet každý graf v každém listu. Definovat[ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) a vykreslit výstupní obrázek grafu pomocí[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Kód pro převod grafu Excel na obrázek" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Vytvářejte grafy v souboru aplikace Excel" %}}

Vytváření grafů pomocí Excel API je jednoduché, protože API poskytuje sadu různých tříd, jako je Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection atd. pro různé druhy grafů. Proces je, Vytvořte objekt třídy Workbook a vyberte první list nebo příslušný list poskytnutím jeho indexu. Jako zdroj dat grafu vložte hodnoty do buněk listu pomocí[setValue](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) metoda. Použijte kolekce ChartCollection[přidat metodu](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) pro přidání grafu definujte typ grafu pomocí výčtu ChartType. Přístup k novému objektu Chart z kolekce ChartCollection předáním jeho indexu. Použijte[Řada Kolekce](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) objekt grafu k určení zdroje dat grafu.

{{% blocks/products/pf/feature-page-code h3="Java Kód pro vytváření grafů Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
