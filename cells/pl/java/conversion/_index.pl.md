---
title:  Microsoft Konwersja pliku Excel via Java
description: Aspose.Cells for Java biblioteka. Konwertuj formaty EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG i więcej za pomocą zaledwie kilku linii kodu Java.
keywords: [Java Aspose.Cells., excel to pdf., excel to json., html to xps., csv to json., json to pdf., xml to excel and Convert files between various formats in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konwersja plików Excel via Java" h2="Zapisz Microsoft dokumenty Excel w formacie arkusza kalkulacyjnego, Internetu, obrazu i formatu o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Dla każdego**Konwerter Excela** aplikacja lub rozwiązanie, Java Biblioteka Excel przyspiesza programowanie arkuszy kalkulacyjnych i procesy konwersji podczas obsługi wielu formatów, w tym XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07619 3481. Umożliwia także *konwersję plików Excel do PDF**, XPS, HTML, MHTML, zwykły tekst i popularne formaty obrazów, takie jak TIFF, JPG, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Wzajemna konwersja formatów Excel Microsoft" %}}
 Wzajemna konwersja formatu arkusza kalkulacyjnego wymaga jedynie załadowania arkusza kalkulacyjnego z instancją[zeszyt ćwiczeń](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) i zapisz ponownie w żądanym formacie, wybierając odpowiednią wartość z[ZapiszFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) wyliczenie.
{{% blocks/products/pf/feature-page-code h3="Java Przykładowy kod konwersji formatu pliku Excel" %}}

```cs
// load the source file
var wkb = new Workbook("sourceFile.xls");
// save as XLSX, ODS, SXC & FODS formats
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na PDF, XPS, HTML i MD" %}}
 Dostępne są wyspecjalizowane klasy kontrolujące proces konwersji dla określonych formatów wyjściowych, takich jak[Opcje zapisywania PDF](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) do konwersji plików Excel jako PDF,[Opcje XpsSave](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) aby wyeksportować Excela jako XPS,[Opcje HTMLSave](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) aby renderować Excel jako HTML i[Opcje zapisywania Markdown](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) do konwersji Excela na Markdown.
{{% blocks/products/pf/feature-page-code h3="Java Przykładowy kod dla programu Excel do PDF i formatów internetowych" %}}

```cs
// load template Excel file from disc
var bk = new Workbook("source-file.xlsx");

// convert Excel to PDF using Java
// Create PDF options
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// save Excel in XPS
bk.save("output.xps", new XpsSaveOptions());
// save Excel in HTML
bk.save("output.html", new HtmlSaveOptions());
// save Excel in Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// one can set relevant save options as of his choice before saving into relevant format
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj JSON na Excel i Excel na JSON" %}}
 Dane JSON można zaimportować do instancji klasy Workbook za pomocą[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) do dalszego przetwarzania lub prostej konwersji do dowolnego obsługiwanego formatu. Podobnie dane arkusza można wyeksportować jako JSON, tworząc plik[Zakres](https://reference.aspose.com/cells/java/com.aspose.cells/range) lub komórek i wywołanie[eksportujRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) metoda.
{{% blocks/products/pf/feature-page-code h3="Java Kod do konwersji JSON na Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Read File
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Set JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Import JSON Data
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Save Excel file
workbook.save(path + "excel-to-json.out.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Kod źródłowy programu Excel do konwersji JSON" %}}
```cs
// load XLSX file with an instance of Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// access CellsCollection of the worksheet containing data to be converted
Cells cells = workbook.getWorksheets().get(0).getCells();
// create & set ExportRangeToJsonOptions for advanced options
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// export range as JSON data
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// write data to disc in JSON format
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Zapisz arkusze programu Excel w obrazach" %}}
 Każdy arkusz można przekonwertować na różne formaty obrazów, w tym JPG, BMP, PNG i GIF, ustawiane przez właściwość ImageType. Dla każdego**Konwertuj program Excel na obrazy** przypadku wybierz odpowiedni przypadek z łączy.
{{% blocks/products/pf/feature-page-code h3="Java Kod do konwersji programu Excel na obraz" %}}
```cs
// load template spreadsheet
var wkb = new Workbook("template.xlsx");

// Create an object for ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Set the image type
imgOptions.setImageType(ImageType.PNG);

// Get the first worksheet.
Worksheet sheet = wkb.getWorksheets().get(0);

// Create a SheetRender object for the target sheet
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Generate an image for the worksheet
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj Microsoft Excel na Word i PowerPoint" %}}
Możliwe jest załadowanie dowolnego arkusza kalkulacyjnego i konwersja go do plików Word DOCX i PowerPoint PPTX podczas korzystania[Opcje DocxSave](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [Opcje PptxSave](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) klas, jak pokazano poniżej.
{{% blocks/products/pf/feature-page-code h3="Java Kod dla Excela do Worda i PowerPoint Konwersja" %}}
```cs
// load the template file
var wkb = new Workbook("template.xlsx");
// save spreadsheet as DOCX
wkb.save("output.docx", new DocxSaveOptions());
// save spreadsheet as PPTX
wkb.save("output.pptx", new PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
