---
title: Rozdělte tabulku Excelu na listy v Java
description: Java zdrojové kódy, které vysvětlují, jak rozdělit soubory Microsoft Excel do více dokumentů pomocí knihovny Excel Java
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Rozdělení souborů aplikace Excel via Java" h2="Rozdělte tabulku Excelu na listy v rámci aplikací založených na Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Existují různé scénáře, kdy je potřeba rozdělit soubory Excelu jako tabulkový procesor obsahující data studentů s přidělením jednoho listu pro každého studenta. A každý list je potřeba studentsky rozdělit jako samostatný soubor. Pro automatizaci aplikace via Java,[Java Excel API](/cells/cs/java/) slouží k rozdělení dokumentu aplikace Excel na listy. Mezi podporované formáty patří XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Rozdělte dokument Excel do více souborů" %}}

 Nejjednodušší způsob, jak rozdělit soubor Excel na list, je otevřít všechny listy, procházet každý list a ukládat jeden po druhém v požadovaném formátu. Pro načtení listu poskytuje API[pracovní sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) třída.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) metoda získá celkový počet listů. Iterujte každý list a použijte[getWorksheets().get(index listu)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) pro přístup ke konkrétnímu listu. Přesuňte vybraná data listu do nově vytvořeného objektu třídy Sešit pomocí[Metoda kopírování](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Nakonec jej uložte do požadovaného formátu.

{{% blocks/products/pf/feature-page-code h3="Java Kód pro rozdělení souborů aplikace Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Rozdělte pracovní list aplikace Excel na panely" %}}

API také poskytuje funkci rozdělení listu aplikace Excel do různých podoken. Proces je načíst soubor pomocí třídy Workbook. Vyberte první list nebo jakýkoli požadovaný list zadáním jeho rejstříku. Zavolejte setActiveCell s příslušným indexem buňky jako parametrem. A nakonec rozdělte okno listu do různých podoken voláním metody split().

{{% blocks/products/pf/feature-page-code h3="Java Kód pro rozdělení listu aplikace Excel do zobrazení panelu" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
