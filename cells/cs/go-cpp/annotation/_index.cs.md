---
title: Přidání nebo odebrání anotací souborů Excelu pomocí Go přes C++
description: Přidávání nebo odebírání komentářů k datovým anotacím v tabulkách Excelu a OpenOffice pomocí knihovny Go C++.
keywords: [Go via C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Správa anotací souborů Excelu Microsoft<sup>&reg;</sup> pomocí Go přes C++" h2="Přidávání nebo odebírání jednoduchých poznámek k anotacím nebo komentářům v rámci Go přes aplikace založené na čísle C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Jděte přes C++ Excel API](/cells/cs/go-cpp/) poskytuje podporu pro správu anotací na úrovni buněk přidáváním, zpřístupňováním a odebíráním komentářů. API poskytuje[Komentář](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/) a[Kolekce komentářů](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/)stejně jako[GetComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/getcomments/) pro zpracování komentářů ve všech aspektech. Mezi podporované formáty Excelu patří ODS, XLS, XLSX, XLSB a XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotace dat v souborech Excel" %}}
 Manipulace s komentáři v pracovních listech - Počet komentářů na listu v MS Excel není omezen. Lze jich vložit tolik, kolik aplikace potřebuje. Proces vkládání komentářů je následující: vytvoření[pracovní sešit](https://reference.aspose.com/cells/go-cpp/aspose.cells/workbook/) Objekt třídy pro načtení existujícího souboru a výběr listu, kam chcete přidat komentář. Získejte všechny jeho komentáře pomocí getComments(). Komentář přidejte pomocí[Přidat(const char16_t* cellName)](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/add/) metoda. Získejte index buňky a použijte[NastavitPoznámku](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/setnote/) pro vkládání komentářů. Navíc API dokáže odstranit všechny komentáře. Jen málo metod je[ClearComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/clearcomments/) Vymaže všechny komentáře v tabulce návrháře. Navíc,***Odebrat z*** metoda pro odstranění prvku na zadaném indexu nebo se zadaným názvem.

{{% blocks/products/pf/feature-page-code h3="Pro přidání komentářů do souboru Excel přejděte přes kód C++" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-comment-in-excel.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
