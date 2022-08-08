---
title: Anotace souboru Excel prostřednictvím C++
url: /cs/cpp/annotation/
description: Přidejte nebo odeberte komentáře datových poznámek v tabulkách Excel a OpenOffice s knihovnou C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Spravujte anotace souborů Microsoft<sup>&reg;</sup> Excel prostřednictvím C++" h2="Přidejte nebo odeberte jednoduché poznámky pro anotace nebo komentáře v aplikacích založených na C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) poskytuje podporu pro správu anotací na úrovni buňky přidáváním, přístupem a odebíráním komentářů. API poskytuje [IKomentář](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) a [ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) jakož i [GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) za zpracování připomínek ve všech aspektech. Mezi podporované formáty Excelu patří ODS, XLS, XLSX, XLSB a XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotace dat souborů aplikace Excel" %}}
Manipulace s komentáři v pracovních listech - Není omezeno, kolik komentářů má list v MS Excel. Lze vložit tolik, kolik aplikace potřebuje. Proces vkládání komentářů je, vytvořit [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class objekt načíst existující soubor a vybrat list, kam chcete přidat komentář. Získejte všechny jeho komentáře pomocí getComments(). Přidejte komentář pomocí [Přidat](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > cellName) metoda. Získejte index buněk a použijte jej [setNote](https://reference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) pro vkládání komentářů. Kromě toho může API odstranit všechny komentáře. Jen málo metod je [ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) to Vymaže všechny komentáře v návrhářské tabulce. Navíc, [RemoveAt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) metoda k odstranění prvku na zadaném indexu nebo se zadaným názvem.

{{% blocks/products/pf/feature-page-code h3="C++ Kód pro přidávání komentářů do souboru Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}