---
title: Přidat nebo odebrat anotace souboru Excel prostřednictvím C++
description: Přidejte nebo odeberte komentáře datových anotací tabulek Excelu a OpenOffice s knihovnou C++.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Spravovat Microsoft<sup>&reg;</sup> Anotace souboru Excel prostřednictvím C++" h2="Přidejte nebo odeberte jednoduché poznámky pro anotace nebo komentáře v aplikacích založených na C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cs/cpp/) poskytuje podporu pro správu anotací na úrovni buňky přidáváním, přístupem a odebíráním komentářů. API poskytuje[Komentář](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) a[Sbírka komentářů](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) jakož i[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)za zpracování připomínek ve všech aspektech. Mezi podporované formáty Excelu patří ODS, XLS, XLSX, XLSB a XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotace dat souborů aplikace Excel" %}}
 Manipulace s komentáři v pracovních listech - Není omezeno, kolik komentářů má list v MS Excel. Lze vložit tolik, kolik aplikace potřebuje. Proces vkládání komentářů je, vytvořit[pracovní sešit](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) class objekt načíst existující soubor a vybrat list, kam chcete přidat komentář. Získejte všechny jeho komentáře pomocí getComments(). Přidejte komentář pomocí[Add(const char16_t* cellName)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) metoda. Získejte index buněk a použijte jej[SetNote](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) pro vkládání komentářů. Kromě toho je API schopen odstranit všechny komentáře. Jen málo metod je[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) to Vymaže všechny komentáře v návrhářské tabulce. Navíc,***RemoveAt*** metoda k odstranění prvku na zadaném indexu nebo se zadaným názvem.

{{% blocks/products/pf/feature-page-code h3="C++ Kód pro přidávání komentářů do souboru Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
