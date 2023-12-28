---
title: Scal różne pliki Excel w jeden w Java
description: Scal pliki Excel za pomocą numeru Java w wiele arkuszy lub pojedynczy arkusz. Scalaj, łącz lub łącz dokumenty Excel z numerami PDF, obrazami i HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Łączenie plików Excel via Java" h2="Połącz dwa lub więcej plików Excel w jednym arkuszu kalkulacyjnym, używając kodu Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Biblioteka Excela](/cells/pl/java/)zapewnia wiele sposobów łączenia skoroszytów z różnymi typami treści, takimi jak formuły, obrazy, dane, wykresy itp., W jednym dokumencie arkusza kalkulacyjnego. Obsługiwane formaty plików to XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV i więcej.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Łącz pliki Excel z obrazami i wykresami" %}}
 Najprostszym sposobem połączenia dwóch plików Excel zawierających obrazy i wykresy jest wywołanie metody[Skoroszyt.połącz](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) metoda. Umożliwia łączenie plików Excel podobnego typu w jeden arkusz kalkulacyjny.
{{% blocks/products/pf/feature-page-code h3="Java Kod do łączenia plików Excel" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Scal wiele plików Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) Metoda obsługuje łączenie danych, stylu i formuł pliku Excel z nowym arkuszem kalkulacyjnym o tym samym formacie. Jest to skuteczny sposób łączenia kilku plików podczas korzystania z pamięci podręcznej.
{{% blocks/products/pf/feature-page-code h3="Java Kod umożliwiający połączenie kilku plików Excel" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Scal pliki Excel, kopiując arkusze" %}}
[Arkusz.kopia](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)może służyć do kopiowania danych i formatowania z arkusza źródłowego do innego arkusza w obrębie skoroszytów lub pomiędzy nimi. Metoda przyjmuje obiekt arkusza źródłowego jako parametr.
{{% blocks/products/pf/feature-page-code h3="Java Kod umożliwiający kopiowanie arkuszy między skoroszytami" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty scalania" subTitle="Za pomocą numeru Java można także łączyć wiele innych formatów plików, w tym..." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Wartości oddzielone przecinkami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="hipertekstowy język znaczników" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Format archiwum stron internetowych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Plik arkusza kalkulacyjnego OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Wartości rozdzielone tabulatorami" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Dokument tekstowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Format binarny Excela" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Binarny plik skoroszytu programu Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Plik arkusza kalkulacyjnego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Plik Excela OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Szablon Excela" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Szablon programu Excel z obsługą makr" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
