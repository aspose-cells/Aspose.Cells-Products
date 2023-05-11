---
title: Anotace souboru Excel via Java
description: Přidejte nebo odeberte datovou anotaci tabulek Excelu a OpenOffice s knihovnou Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Spravovat Microsoft<sup>&reg;</sup> Anotace souboru Excel via Java" h2="Vkládejte jednoduché poznámky pro anotaci nebo odstraňte komentáře na úrovni buněk tabulky Excel v aplikacích založených na Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/cs/java/) poskytuje podporu pro správu anotací na úrovni buňky přidáváním, přístupem a mazáním komentářů. API poskytuje[Komentář](https://reference.aspose.com/cells/java/com.aspose.cells/Comment), [Sbírka komentářů](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [ThreadedComment](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) a[ThreadedCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) za zpracování připomínek ve všech aspektech.
Mezi podporované formáty souborů patří ODS, XLS, XLSX, XLSB a XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Anotace dat souborů aplikace Excel" %}}
 Správa komentářů v listech - Neexistuje žádné omezení počtu komentářů v listu v MS Excel. Lze přidat tolik, kolik je požadavků aplikace. Proces přidávání komentářů je, vytvořit[pracovní sešit](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)třídy nebo načtěte existující soubor pomocí třídy Workbook. Získejte přístup ke všem jeho komentářům pomocí getComments(). Získejte index buněk a použijte jej[setNote](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) pro vkládání komentářů. Kromě toho je API schopen odstranit všechny komentáře.

{{% blocks/products/pf/feature-page-code h3="Java Kód pro přidávání komentářů do souboru Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Kód pro odstranění komentářů v souboru aplikace Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
