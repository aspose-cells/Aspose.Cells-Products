---
title: Spravujte metadata souboru Excel přes C++
description: Zobrazte, přidejte, upravte, odeberte nebo extrahujte metadata souborů aplikace Excel pomocí knihovny C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Spravovat Microsoft<sup>&reg;</sup> metadata dokumentu Excel prostřednictvím C++" h2="Prohlížejte, vkládejte, aktualizujte, odebírejte nebo extrahujte vlastní a vestavěné vlastnosti dokumentu aplikace Excel v aplikacích C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Metadata v Excelu - Jak zobrazit, vložit a odstranit metadata souboru Excel.[C++ Knihovna Excel](/cells/cs/cpp/) faclitates je jednoduchým způsobem podporováním vestavěných / systémem definovaných vlastností, jako je jméno autora, titul, statistika dokumentu atd., které někdy potřebujete zkontrolovat, kdy je naposledy soubor upraven nebo uložen spolu s vlastními / uživatelem definovanými vlastnostmi ve formě dvojice název/hodnota. Pro automatizaci procesu knihovna podporuje vytváření a údržbu velkých metadatových souborů Excel.[pracovní sešit](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class Otevře sešit podle cesty, proudu a speciálního FileFormatType. Načtěte soubor vhodnou metodou pro další zpracování. Několik z níže uvedených možností a vývojáři mohou snadno vylepšit svůj kód podle požadavků aplikace.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Číst a aktualizovat vlastnosti Builtin" %}}

 Pro automatizaci vestavěných vlastností poskytuje API[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) metoda, která vrací kolekci DocumentProperties představující všechny vestavěné vlastnosti dokumentu tabulky. Po přístupu ke všem vestavěným vlastnostem přistupte k příslušným vlastnostem pomocí příslušné metody, jako je GetTitle(), GetSubject() atd. Chcete-li aktualizovat vlastnosti, API poskytuje metodu jako SetTitle, SetSubject, SetAuthor, SetComments atd. Zobrazit[vestavěná sbírka majetku dokumentů](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) pro požadovanou funkci.

{{% blocks/products/pf/feature-page-code h3="C++ Kód pro čtení vlastností definovaných systémem" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Kód pro aktualizaci vestavěných vlastností" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Zobrazit a přidat vlastní definované vlastnosti" %}}

Pro manipulaci s uživatelskými vlastnostmi poskytuje API[Sešit::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) který vrátí všechny vlastní kolekce vlastností dokumentu tabulky. Nejprve při přístupu k uživatelským vlastnostem prostřednictvím této metody mohou vývojáři použít příslušné metody k přidání vlastností, jako je AddIDocumentProperty, AddLinkToContentProperty, a podobně použít UpdateLinkedPropertyValue, UpdateLinkedRange k aktualizaci hodnoty vlastní vlastnosti dokumentu, která odkazuje na obsah a na propojený rozsah. Vývojáři mohou použít příslušnou metodu z[kolekce vlastních vlastností dokumentu](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Kód pro zobrazení uživatelských vlastností" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Kód pro přidání metadat do souboru aplikace Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
