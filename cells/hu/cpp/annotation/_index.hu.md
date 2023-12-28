---
title: Excel-fájl megjegyzések hozzáadása vagy eltávolítása a C++ számon keresztül
description: Adja hozzá vagy távolítsa el a C++ könyvtárral rendelkező Excel és OpenOffice táblázatok adatannotációinak megjegyzéseit.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A Microsoft<sup>&reg;</sup> Excel-fájl megjegyzéseinek kezelése a C++-es számon keresztül" h2="Adjon hozzá vagy távolítson el egyszerű megjegyzéseket a megjegyzésekhez vagy megjegyzésekhez a C++ alapú alkalmazásokon belül." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/hu/cpp/) támogatást nyújt a megjegyzések cellaszintű kezeléséhez, megjegyzések hozzáadásával, elérésével és eltávolításával. API rendelkezik[Megjegyzés](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) és[CommentCollection](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) szintén[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/) hozzászólások minden szempontból történő kezelésére. A támogatott Excel formátumok közé tartozik a ODS, XLS, XLSX, XLSB és XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel fájlok adatjegyzetek" %}}
 Megjegyzések manipulálása munkalapokon – Nincs korlátozva, hogy egy munkalap hány megjegyzést tartalmazzon az MS Excelben. Annyi beszúrható, amennyit az alkalmazásnak szüksége van. A megjegyzések beszúrásának folyamata a létrehozás[Munkafüzet](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) osztály objektumot egy meglévő fájl betöltéséhez, és válassza ki azt a munkalapot, amelyhez hozzá szeretné adni a megjegyzést. Az összes megjegyzés lekérése a getComments() segítségével. Adja hozzá a megjegyzést a használatával[Add(const char16_t* cellName)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) módszer. Szerezze be a cella indexét és használja[SetNote](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) megjegyzések beszúrásához. Ezenkívül a API képes eltávolítani az összes megjegyzést. A módszerek közül néhány az[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) to Törli az összes megjegyzést a tervezői táblázatban. Ráadásul,***RemoveAt*** metódussal eltávolítja az elemet egy megadott indexen vagy megadott néven.

{{% blocks/products/pf/feature-page-code h3="C++ Kód megjegyzések hozzáadásához az Excel-fájlban" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
