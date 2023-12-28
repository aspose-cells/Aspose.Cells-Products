---
title:  Microsoft Excel-fájl konvertálása via Java
description: Aspose.Cells for Java könyvtár. EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG, PNG és több formátumú 3071 kód1 és több 3071-es formátumok.
keywords: [Java Aspose.Cells., excel to pdf., excel to json., html to xps., csv to json., json to pdf., xml to excel and Convert files between various formats in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-fájlok konvertálása via Java" h2="Microsoft Excel-dokumentumok mentése táblázat, web, kép és rögzített elrendezésű formátumban" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Bármilyen**Excel konverter** alkalmazás vagy megoldás, Java Az Excel Library felgyorsítja a táblázatkezelő programozási és átalakítási folyamatokat, miközben több formátumot is kezel, beleértve a XLS, XLSX, XLSM, XLSB, XLTX, XLTX, XLSB, XLTX, XLSB, XLTX, 071143481, 761,40,8181 ODS. Lehetővé teszi *Excel-fájlok konvertálását PDF-re**, XPS, HTML, MHTML, egyszerű szöveg és népszerű képformátumok, például TIFF, JPG, PNG, BMP és SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="A Microsoft Excel-formátumok interkonverziója" %}}
 A táblázatos formátumok közötti konvertáláshoz csak egy példányt tartalmazó táblázatot kell betölteni[Munkafüzet](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) és visszamenti a kívánt formátumba, miközben kiválasztja a megfelelő értéket[SaveFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) felsorolás.
{{% blocks/products/pf/feature-page-code h3="Java Példakód az Excel fájlformátum konvertálásához" %}}

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


{{% blocks/products/pf/feature-page-section h2="Az Excel konvertálása PDF, XPS, HTML és MD" %}}
 Speciális osztályok állnak rendelkezésre az átalakítási folyamat vezérlésére meghatározott kimeneti formátumokhoz, mint pl[PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) az Excel-fájlok konvertálása PDF-re,[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) az Excel exportálása XPS néven,[HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) hogy az Excel HTML-ként jelenjen meg, és[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) az Excelből Markdown konvertáláshoz.
{{% blocks/products/pf/feature-page-code h3="Java Mintakód az Excelhez a PDF-hez és a webes formátumokhoz" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konvertálja a JSON-et Excel-be, az Excelt pedig JSON-re" %}}
 A JSON adatok a Workbook osztály egy példányába importálhatók a segítségével[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) további feldolgozáshoz vagy egyszerű konvertáláshoz a támogatott formátumok bármelyikére. Hasonlóképpen a munkalapadatok JSON-es számként exportálhatók az a[Hatótávolság](https://reference.aspose.com/cells/java/com.aspose.cells/range) vagy sejtek és hívja a[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) módszer.
{{% blocks/products/pf/feature-page-code h3="Java A JSON kód az Excel konvertáláshoz" %}}
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

{{% blocks/products/pf/feature-page-code h3="Java Forráskód az Excelhez JSON konvertálás" %}}
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

{{% blocks/products/pf/feature-page-section h2="Excel-munkalapok mentése Képek közé" %}}
 Minden munkalap konvertálható különböző képformátumokba, beleértve a JPG, BMP, PNG és GIF formátumokat, amelyeket az ImageType tulajdonság állít be. Bármilyen**Az Excel konvertálása képekké** esetet, válassza ki a megfelelő esetet a hivatkozások közül.
{{% blocks/products/pf/feature-page-code h3="Java Kód az Excel képpé konvertálásához" %}}
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

{{% blocks/products/pf/feature-page-section h2="A Microsoft Excel konvertálása Word-be és PowerPoint" %}}
Lehetőség van bármilyen táblázat betöltésére és Word DOCX és PowerPoint PPTX fájlokká konvertálására használat közben.[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) osztályok alább látható módon.
{{% blocks/products/pf/feature-page-code h3="Java Kód az Excel-hez Word-be és PowerPoint konvertálás" %}}
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
