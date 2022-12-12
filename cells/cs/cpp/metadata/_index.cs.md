---
title: Spravujte metadata souboru Excel prostřednictvím C++

description: Zobrazte, přidejte, upravte, odeberte nebo extrahujte metadata souborů Excel pomocí knihovny C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Spravujte metadata dokumentu Microsoft<sup>&reg;</sup> Excel prostřednictvím C++" h2="Zobrazte, vkládejte, aktualizujte, odeberte nebo extrahujte vlastní a vestavěné vlastnosti dokumentu aplikace Excel v aplikacích C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
Metadata v Excelu - Jak zobrazit, vložit a odstranit metadata souboru Excel. [C++ Knihovna Excel](/cells/cpp/) faclitates je jednoduchým způsobem podporováním vestavěných / systémem definovaných vlastností, jako je jméno autora, název, statistika dokumentu atd., které někdy potřebujete zkontrolovat, kdy je naposledy soubor upraven nebo uložen spolu s vlastními / uživatelem definovanými vlastnostmi ve formě dvojice název/hodnota. Pro automatizaci procesu knihovna podporuje vytváření a údržbu velkých metadatových souborů Excel. [Metoda CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) z [Tovární třída](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Otevřete sešit podle cesty, proudu a speciálního FileFormatType. Načtěte soubor vhodnou metodou pro další zpracování. Několik z níže uvedených možností a vývojáři mohou snadno vylepšit svůj kód podle požadavků aplikace. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Číst a aktualizovat vlastnosti Builtin" %}}

Pro automatizaci vestavěných vlastností poskytuje API [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) metoda, která vrací kolekci DocumentProperties představující všechny vestavěné vlastnosti dokumentu tabulky. Po přístupu ke všem integrovaným vlastnostem přistupte k relevantním vlastnostem pomocí příslušné metody, jako je GetTitle(), GetSubject() atd. Chcete-li aktualizovat vlastnosti, API poskytuje metodu, jako je SetTitle, SetSubject, SetAuthor, SetComments atd. Zobrazit [vestavěná sbírka majetku dokumentů](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) pro požadovanou funkci.

{{% blocks/products/pf/feature-page-code h3="C++ Kód pro čtení vlastností definovaných systémem" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Kód pro aktualizaci vestavěných vlastností" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Zobrazit a přidat vlastní definované vlastnosti" %}}

Pro zpracování vlastních vlastností poskytuje API [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) který vrátí všechny vlastní kolekce vlastností dokumentu tabulky. Nejprve při přístupu k uživatelským vlastnostem prostřednictvím této metody mohou vývojáři použít příslušné metody k přidání vlastností, jako je AddIDocumentProperty, AddLinkToContentProperty, a podobně použít UpdateLinkedPropertyValue, UpdateLinkedRange k aktualizaci hodnoty vlastní vlastnosti dokumentu, která odkazuje na obsah a na propojený rozsah. Vývojáři mohou použít příslušnou metodu z [kolekce vlastních vlastností dokumentu](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Kód pro zobrazení uživatelských vlastností" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Kód pro přidání metadat do souboru Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
