---
title: Excel-fájljegyzetek hozzáadása vagy eltávolítása a Go segítségével a C++-es telefonszámon
description: Adatmegjegyzések hozzáadása vagy eltávolítása Excel és OpenOffice táblázatokból a Go segítségével a C++ könyvtáron keresztül.
keywords: [Go via C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=" Microsoft<sup>&reg;</sup> Excel fájljegyzetek kezelése Go-val a C++-en keresztül" h2="Egyszerű jegyzetek hozzáadása vagy eltávolítása jegyzetekhez vagy megjegyzésekhez a Go via C++ alapú alkalmazásokban." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Menj a C++-es számon Excelben API](/cells/hu/go-cpp/) támogatást nyújt a cellaszintű annotációk kezeléséhez megjegyzések hozzáadásával, elérésével és eltávolításával. A API biztosítja[Megjegyzés](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/) és[Hozzászólásgyűjtemény](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/)valamint[GetComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/getcomments/) a megjegyzések minden aspektusának kezelésére. A támogatott Excel-formátumok a következők: ODS, XLS, XLSX, XLSB és XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel fájlok adatjegyzetei" %}}
 Munkalapokon található megjegyzések kezelése - Az MS Excelben nincs korlátozva, hogy egy munkalap hány megjegyzést tartalmazhat. Annyit beilleszthet, amennyire az alkalmazásnak szüksége van. A megjegyzések beszúrásának folyamata a következő: hozzon létre[Munkafüzet](https://reference.aspose.com/cells/go-cpp/aspose.cells/workbook/) osztályú objektumot egy meglévő fájl betöltéséhez és annak a munkalapnak a kiválasztásához, amelyhez a megjegyzést hozzá szeretnéd adni. Az összes megjegyzést a getComments() használatával szerezheted be. A megjegyzést a következővel adhatod hozzá:[Add(const char16_t* cellaNeve)](https://reference.aspose.com/cells/go-cpp/aspose.cells/commentcollection/add/) metódus. Szerezd meg a cellaindexet és használd a[Megjegyzés beállítása](https://reference.aspose.com/cells/go-cpp/aspose.cells/comment/setnote/) megjegyzések beszúrásához. Továbbá a API képes az összes megjegyzés eltávolítására. Néhány metódus[ClearComments()](https://reference.aspose.com/cells/go-cpp/aspose.cells/worksheet/clearcomments/) az összes megjegyzés törlése a tervezői táblázatból. Továbbá,***Eltávolítás*** metódus a megadott indexű vagy megadott nevű elem eltávolítására.

{{% blocks/products/pf/feature-page-code h3="Menj végig a C++ kódon, hogy megjegyzéseket adj hozzá az Excel fájlhoz" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-comment-in-excel.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}

{{< /blocks/products/pf/feature-page-wrap >}}
