---
title: Vytvářejte soubory Excel prostřednictvím Java

description: Generujte tabulky Microsoft Excel ze šablony pomocí knihovny tabulek Java
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Vytváření přehledů na základě šablony Excelu prostřednictvím Java" h2="Vytvářejte hromadné sestavy souborů Excel na základě předdefinované šablony v aplikacích založených na Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Knihovna Excel](/cells/java/) podporuje generování souborů Excel založených na šablonách pro hromadné generování sestav. Je potřeba pro většinu případů, jako je vytváření fee challans, výsledkových karet a záznamů pacientů atd. Šablony jsou předdefinované vzory. Pod kódem Java se vygenerují hromadné soubory Excel stejné jako šablona dokumentu, která je naplněna daty. Mezi podporované formáty souborů patří XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Vytvářejte sestavy na základě předem navržené šablony aplikace Excel" %}}

Pomocí JavasestaveníAPI mohou vývojáři snadno naprogramovat kód pro generování hromadných sestav tím, že zahrnou níže uvedené úryvky kódu. API poskytuje [importovat data](https://docs.aspose.com/cells/java/import-and-export-data/) funkce z různých zdrojů a vytvářet dokumenty Excel v závislosti na těchto datech. Pro vzory založené na šablonách poskytuje API a [WorkbookDesigner třída](https://reference.aspose.com/cells/java/com.aspose.cells/WorkbookDesigner) reprezentovat pracovní list návrháře. Proces je, vytvořte jeho objekt a použijte jej k otevření souboru šablony. Nastavte zdroj dat, což může být Array, DataTable, Json atd. Zpracujte jej pro import dat a uložte soubor v požadovaném formátu. Programátoři mohou sestavovat data do zpráv v jiných formátech souborů včetně XLS, XLSX, XLSB, XLSM, ODS podle níže uvedených odkazů.



{{% blocks/products/pf/feature-page-code h3="Java Kód pro vytváření sestav Excel" %}}

{{< gist "aspose-com-gists" "d9948743348f4393d12d5a09ac5aec4f" "create-excel-reports.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Create" afterslug="Reports" >}}
