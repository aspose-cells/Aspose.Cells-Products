---
title: Scal różne pliki Excela w jeden w Java

description: Scal pliki Excel za pomocą Java w wiele arkuszy lub jeden arkusz. Łącz, łącz lub łącz dokumenty Excela z plikami PDF, obrazami i HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Scalanie plików Excela przez Java" h2="Połącz dwa lub więcej plików Excela w jednym arkuszu kalkulacyjnym, używając kodu Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Biblioteka Excela](/cells/java/) zapewnia wiele sposobów łączenia skoroszytów z różnymi rodzajami treści, takimi jak formuły, obrazy, dane, wykresy itp., w jeden dokument arkusza kalkulacyjnego. Obsługiwane formaty plików to XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV i inne.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Połącz pliki Excela z obrazami i wykresami" %}}
Najprostszym sposobem połączenia dwóch plików Excela zawierających obrazy i wykresy jest wywołanie [Skoroszyt.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) metoda. Pozwala łączyć pliki Excel podobnego typu w jeden arkusz kalkulacyjny.
{{% blocks/products/pf/feature-page-code h3="Java Kod do łączenia plików Excel" %}}

```cs
// załaduj pierwszy plik Excel
var book1 = new Workbook("with-charts.xlsx");
// załaduj drugi plik Excela do osobnej instancji
var book2 = new Workbook("with-images.xlsx");

// połącz dwa skoroszyty
book1.combine(book2);
// zapisz skoroszyt docelowy 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Scal wiele plików Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) Metoda obsługuje łączenie danych, stylów i formuł pliku Excel w nowy arkusz kalkulacyjny o tym samym formacie. Jest to wydajny sposób łączenia kilku plików podczas korzystania z pamięci podręcznej. 
{{% blocks/products/pf/feature-page-code h3="Java Kod do łączenia kilku plików Excel" %}}

```cs
// utwórz tablicę (długość=2)
String[] files = new String[2];
// określ ścieżki plików do scalenia
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// scal pliki, aby zapisać wynik
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Scal pliki Excela, kopiując arkusze robocze" %}}
[Arkusz.kopia](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)może służyć do kopiowania danych i formatowania z arkusza źródłowego do innego arkusza w obrębie skoroszytów lub między nimi. Metoda przyjmuje źródłowy obiekt arkusza jako parametr.
{{% blocks/products/pf/feature-page-code h3="Java Kod do kopiowania arkuszy roboczych między skoroszytami" %}}

```cs
// Utwórz skoroszyt.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Utwórz kolejny skoroszyt.
Workbook excelWorkbook1 = new Workbook();

// Skopiuj pierwszy arkusz pierwszej książki do drugiej książki.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Zapisz plik.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
