---
title: "Excel-fájl megjegyzések a következőn keresztül: Java"
url: /hu/java/annotation/
description: Adja hozzá vagy távolítsa el a(z) Java könyvtárral rendelkező Excel és OpenOffice táblázatok adatfeljegyzéseit.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A Microsoft<sup>&reg;</sup> Excel-fájl megjegyzéseinek kezelése a következőn keresztül: Java" h2="Szúrjon be egyszerű megjegyzéseket a megjegyzésekhez, vagy törölje az Excel-táblázat cellaszintű megjegyzéseit a Java alapú alkalmazásokban." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) támogatást nyújt a megjegyzések cellaszintű kezeléséhez, megjegyzések hozzáadásával, elérésével és törlésével. API biztosítja [Megjegyzés](https://apireference.aspose.com/cells/java/com.aspose.cells/Comment), [CommentCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [ThreadedComment](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) és [ThreadedCommentCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) a megjegyzések minden szempontból történő kezelésére.
A támogatott fájlformátumok közé tartozik az ODS, XLS, XLSX, XLSB és XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel fájlok adatjegyzetek" %}}
Megjegyzések kezelése munkalapokon – Az MS Excelben nincs korlátozva egy lapon található megjegyzések száma. Annyi hozzáadható, amennyi az alkalmazási követelményhez szükséges. A megjegyzések hozzáadásának folyamata a létrehozás [Munkafüzet](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály objektumot, vagy töltsön be egy meglévő fájlt a Workbook osztály segítségével. Hozzáférés az összes megjegyzéséhez a getComments() segítségével. Szerezze be a cella indexét és használja [setNote](https://apireference.aspose.com/cells/java/com.aspose.cells/comment#Note) megjegyzések beszúrásához. Ezenkívül a API képes eltávolítani az összes megjegyzést. 

{{% blocks/products/pf/feature-page-code h3="Java Kód megjegyzések hozzáadásához az Excel-fájlban" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Kód a megjegyzések eltávolításához az Excel-fájlból" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}