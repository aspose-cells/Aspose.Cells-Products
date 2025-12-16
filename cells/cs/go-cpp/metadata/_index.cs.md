---
title: Správa metadat souborů Excel pomocí Go přes C++
description: Zobrazení, přidání, úprava, odebrání nebo extrahování metadat souborů Excelu pomocí knihovny Go přes C++
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Spravovat Microsoft<sup>&reg;</sup> metadata dokumentů Excel přes Go přes C++" h2="Zobrazujte, vkládejte, aktualizujte, odebírejte nebo extrahujte vlastní a vestavěné vlastnosti dokumentů aplikace Excel v aplikacích C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadata v Excelu - Jak zobrazit, vložit a odebrat metadata souboru Excel.[Přejděte přes C++ Knihovna Excelu](/cells/cs/go-cpp/)Faclitates je snadno dostupný díky podpoře vestavěných/systémem definovaných vlastností, jako je jméno autora, název, statistiky dokumentu atd., které jsou někdy potřeba ke kontrole poslední úpravy nebo uložení souboru, spolu s vlastními/uživatelem definovanými vlastnostmi ve formě párů název/hodnota. Pro automatizaci procesu knihovna podporuje vytváření a údržbu velkých souborů metadat v Excelu.[pracovní sešit](https://reference.aspose.com/cells/go-cpp/workbook/) Třída otevírá sešit podle cesty, streamu a speciálního FileFormatType. Soubor se tedy načítá vhodnou metodou pro další zpracování. Níže uvedené možnosti umožňují vývojářům snadno vylepšit svůj kód podle požadavků aplikace.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Čtení a aktualizace vestavěných vlastností" %}}

 Pro automatizaci vestavěných vlastností poskytuje API[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Metoda, která vrací kolekci DocumentProperties reprezentující všechny vestavěné vlastnosti dokumentu tabulky. Po přístupu ke všem vestavěným vlastnostem se k příslušným vlastnostem přistupuje pomocí příslušné metody, jako je GetTitle(), GetSubject() atd. Pro aktualizaci vlastností poskytuje API metody, jako je SetTitle, SetSubject, SetAuthor, SetComments atd. Zobrazit[vestavěná kolekce vlastností dokumentů](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) pro požadovanou funkci.

{{% blocks/products/pf/feature-page-code h3="Pro čtení systémem definovaných vlastností přejděte přes kód C++." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Pro aktualizaci vestavěných vlastností přejděte přes kód C++" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Zobrazení a přidání vlastních definovaných vlastností" %}}

 Pro zpracování vlastních vlastností poskytuje API[Sešit::GetCustomDocumentProperties](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)která vrací veškerou kolekci vlastních vlastností dokumentů v tabulce. Nejprve přistupují k vlastním vlastnostem pomocí této metody a vývojáři mohou pomocí příslušných metod přidat vlastnosti, jako je AddIDocumentProperty, AddLinkToContentProperty, a podobně pomocí metod UpdateLinkedPropertyValue a UpdateLinkedRange aktualizovat hodnotu vlastní vlastnosti dokumentu, která odkazuje na obsah, respektive na propojený rozsah. Vývojáři mohou pomocí příslušných metod z[kolekce vlastních vlastností dokumentů](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Pro zobrazení vlastních vlastností přejděte přes kód C++" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Pro přidání metadat do souboru aplikace Excel přejděte přes kód C++" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}