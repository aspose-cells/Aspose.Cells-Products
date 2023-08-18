---
title:  Microsoft Excel-filkonvertering via Java
description: Konvertera Excel XLS, XLSX, ODS, CSV till PDF, XPS, HTML, JPEG, JPEG, 076183, 076183, 8 och bara 1 164 format med 8 andra 4 format kod.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konvertering av Excel-filer via Java" h2="Spara Microsoft Excel-dokument som kalkylblad, webb, bild och format med fast layout" >}}

{{% blocks/products/pf/feature-page-summary %}}
 För alla**Excel-konverterare**applikation eller lösning, Java Excel Library snabbar upp kalkylbladsprogrammering och konverteringsprocesser samtidigt som den hanterar flera format inklusive XLS, XLSX, XLSM, XLSB, XLTX, 07616 18, 07616 18, 07616 18481, 07616 180 , ODS. Det gör det också möjligt att *konvertera Excel-filer till PDF**, XPS, HTML, MHTML, vanlig text och populära bildformat som TIFF, JPG, PNG, BMP och SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interkonvertering av Microsoft Excel-format" %}}
 Interkonvertering av kalkylarksformat kräver bara att ett kalkylblad laddas med en instans av[Arbetsbok](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) och spara tillbaka i önskat format samtidigt som du väljer lämpligt värde från[SaveFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) uppräkning.
{{% blocks/products/pf/feature-page-code h3="Java Exempelkod för konvertering av Excel-filformat" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till PDF, XPS, HTML & MD" %}}
 Specialiserade klasser finns tillgängliga för att styra konverteringsprocessen för specifika utdataformat som t.ex[PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) för att konvertera Excel-filer som PDF,[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) för att exportera Excel som XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) för att återge Excel som HTML och[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) för konvertering från Excel till Markdown.
{{% blocks/products/pf/feature-page-code h3="Java Exempelkod för Excel till PDF och webbformat" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konvertera JSON till Excel och Excel till JSON" %}}
 JSON data kan importeras till en instans av Workbook-klassen med hjälp av[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) för vidare bearbetning eller enkel konvertering till något av de format som stöds. På samma sätt kan kalkylbladsdata exporteras som JSON genom att skapa en[Räckvidd](https://reference.aspose.com/cells/java/com.aspose.cells/range) eller celler och ringer till[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) metod.
{{% blocks/products/pf/feature-page-code h3="Java Kod för JSON till Excel-konvertering" %}}
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

{{% blocks/products/pf/feature-page-code h3="Java Källkod för Excel till JSON konvertering" %}}
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

{{% blocks/products/pf/feature-page-section h2="Spara Excel-kalkylblad till bilder" %}}
 Varje kalkylblad kan konverteras till olika bildformat inklusive JPG, BMP, PNG och GIF, inställda av egenskapen ImageType. För alla**Konvertera Excel till bilder** ärende, välj relevant ärende från länkar.
{{% blocks/products/pf/feature-page-code h3="Java Kod för konvertering av Excel till bild" %}}
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

{{% blocks/products/pf/feature-page-section h2="Konvertera Microsoft Excel till Word och PowerPoint" %}}
 Det är möjligt att ladda vilket kalkylblad som helst och konvertera det till Word DOCX- och PowerPoint PPTX-filer medan du använder[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions)klasser som visas nedan.
{{% blocks/products/pf/feature-page-code h3="Java Kod för Excel till Word & PowerPoint konvertering" %}}
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
