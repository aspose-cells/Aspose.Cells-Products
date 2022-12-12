---
title: Konwersja plików Microsoft Excel przez Java 

description: Konwertuj Excel XLS, XLSX, ODS, CSV do PDF, XPS, HTML, JPEG, HTML i wielu innych popularnych formatów za pomocą zaledwie kilku linijek kodu Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwersja plików Microsoft<sup>&reg;</sup> Excel przez Java" h2="Zapisuj dokumenty Microsoft Excel w formacie arkusza kalkulacyjnego, strony internetowej, obrazu i stałego układu" >}}

{{% blocks/products/pf/feature-page-summary %}}
W przypadku dowolnej aplikacji lub rozwiązania **konwertera Excela** JavaBiblioteka Excela przyspiesza proces programowania i konwersji arkuszy kalkulacyjnych, jednocześnie obsługując wiele formatów, w tym XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Pozwala także na **konwertowanie plików Excel do PDF**, XPS, HTML, MHTML, zwykły tekst i popularnych formatów graficznych, takich jak TIFF, JPG, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwersja wzajemna formatów Microsoft Excel" %}}
Konwersja między formatami arkusza kalkulacyjnego wymaga tylko załadowania arkusza kalkulacyjnego z wystąpieniem [zeszyt ćwiczeń](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i zapisywanie z powrotem w żądanym formacie przy wyborze odpowiedniej wartości z [Zapisz format](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) wyliczenie.
{{% blocks/products/pf/feature-page-code h3="Java Przykładowy kod konwersji formatu pliku Excel" %}}

```cs
// załaduj plik źródłowy
var wkb = new Workbook("sourceFile.xls");
// zapisz jako formaty XLSX, ODS, SXC i FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na PDF, XPS, HTML i MD" %}}
Dostępne są specjalistyczne klasy do kontrolowania procesu konwersji dla określonych formatów wyjściowych, takich jak [PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) konwertować pliki Excel do formatu PDF, [XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) wyeksportować Excela jako XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) renderować Excel jako HTML i [MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) do konwersji programu Excel do Markdown. 
{{% blocks/products/pf/feature-page-code h3="Java Przykładowy kod dla formatu Excel do formatu PDF i internetowego" %}}

```cs
// wczytaj szablon pliku Excel z dysku
var bk = new Workbook("source-file.xlsx");

// przekonwertuj Excel na PDF za pomocą Java
// Utwórz opcje PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// zapisz Excela w XPS
bk.save("output.xps", new XpsSaveOptions());
// zapisz Excel w HTML
bk.save("output.html", new HtmlSaveOptions());
// zapisz Excel w Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// można ustawić odpowiednie opcje zapisu według własnego wyboru przed zapisaniem w odpowiednim formacie

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj JSON na Excel i Excel na JSON" %}}
Dane JSON można zaimportować do instancji klasy Workbook za pomocą [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) do dalszego przetwarzania lub prostej konwersji na dowolny z obsługiwanych formatów. Podobnie dane arkusza roboczego można wyeksportować jako JSON, tworząc [Zakres](https://reference.aspose.com/cells/java/com.aspose.cells/range) lub komórki i nazywając [exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) metoda.
{{% blocks/products/pf/feature-page-code h3="Java Kod konwersji JSON na Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Przeczytaj plik
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Ustaw opcje JsonLayout
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Importuj dane JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Zapisz plik Excela
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Kod źródłowy konwersji programu Excel do formatu JSON" %}}
```cs
// załaduj plik XLSX z instancją Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// dostęp do CellsCollection arkusza roboczego zawierającego dane do przekonwertowania
Cells cells = workbook.getWorksheets().get(0).getCells();
// utwórz i ustaw ExportRangeToJsonOptions dla zaawansowanych opcji
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// utwórz zakres komórek zawierających dane do wyeksportowania
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// eksportuj zakres jako dane JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// zapisz dane na dysku w formacie JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Zapisz arkusze Excela w obrazach" %}}
Każdy arkusz roboczy można przekonwertować na różne formaty obrazów, w tym JPG, BMP, PNG i GIF, ustawione we właściwości ImageType. W przypadku dowolnego przypadku **Konwertuj Excel na obrazy** wybierz odpowiednią sprawę z łączy.
{{% blocks/products/pf/feature-page-code h3="Java Kod programu Excel do konwersji obrazu" %}}
```cs
// załaduj arkusz kalkulacyjny szablonu
var wkb = new Workbook("template.xlsx");

// Utwórz obiekt dla ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Ustaw typ obrazu
imgOptions.setImageType(ImageType.PNG);

// Pobierz pierwszy arkusz.
Worksheet sheet = wkb.getWorksheets().get(0);

// Utwórz obiekt SheetRender dla arkusza docelowego
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Wygeneruj obraz do arkusza roboczego
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj Microsoft Excel na Word i PowerPoint" %}}
Podczas używania można załadować dowolny arkusz kalkulacyjny i przekonwertować go na pliki Word DOCX i PowerPoint PPTX [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [Opcje zapisu Pptx](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) klasy, jak pokazano poniżej.
{{% blocks/products/pf/feature-page-code h3="Java Konwersja kodu programu Excel do programu Word i PowerPoint" %}}
```cs
// załaduj plik szablonu
var wkb = new Workbook("template.xlsx");
// zapisz arkusz kalkulacyjny jako DOCX
wkb.save("output.docx", new DocxSaveOptions());
// zapisz arkusz kalkulacyjny jako PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
