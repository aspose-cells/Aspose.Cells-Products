---
title: "Excel-fájl megjegyzések a következőn keresztül: C++"

description: Adja hozzá vagy távolítsa el a(z) C++ könyvtárral rendelkező Excel- és OpenOffice-táblázatok adatjegyzet-megjegyzéseit.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="A Microsoft<sup>&reg;</sup> Excel-fájl megjegyzéseinek kezelése a következőn keresztül: C++" h2="Egyszerű megjegyzések hozzáadása vagy eltávolítása a megjegyzésekhez vagy megjegyzésekhez a C++ alapú alkalmazásokban." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) támogatást nyújt a megjegyzések cellaszintű kezeléséhez megjegyzések hozzáadásával, elérésével és eltávolításával. API biztosítja [IComment](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) és [ICommentCollection](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) szintén [GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) a megjegyzések minden szempontból történő kezelésére. A támogatott Excel formátumok közé tartozik az ODS, XLS, XLSX, XLSB és XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel fájlok adatjegyzetek" %}}
Megjegyzések manipulálása munkalapokon – Nincs korlátozva, hogy egy munkalap hány megjegyzést tartalmazzon az MS Excelben. Annyi beszúrható, amennyit az alkalmazásnak szüksége van. A megjegyzések beszúrásának folyamata a létrehozás [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) osztály objektumot egy meglévő fájl betöltéséhez, és válassza ki a munkalapot, ahová a megjegyzést hozzá kívánja adni. Az összes megjegyzés lekérése a getComments() segítségével. Adja hozzá a megjegyzést a használatával [Hozzáadás](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusive_ptr < Aspose::Cells::Systems::String > cellName) módszerrel. Szerezze be a cella indexét és használja [setNote](https://reference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) megjegyzések beszúrásához. Ezenkívül a API képes eltávolítani az összes megjegyzést. A módszerek közül néhány az [Megjegyzések törlése()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) to Törli az összes megjegyzést a tervezői táblázatban. Ráadásul, [RemoveAt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) módszerrel eltávolítja az elemet egy megadott indexen vagy megadott néven.

{{% blocks/products/pf/feature-page-code h3="C++ Kód megjegyzések hozzáadásához az Excel-fájlban" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
