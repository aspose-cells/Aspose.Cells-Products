---
title: Microsoft Excel-filkonvertering via Java 
url: /sv/java/conversion/
description: Konvertera Excel XLS, XLSX, ODS, CSV till PDF, XPS, HTML, JPEG, HTML och många andra populära format med bara några rader med Java-kod.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-filkonvertering via Java" h2="Spara Microsoft Excel-dokument som kalkylblad, webb, bild och format med fast layout" >}}

{{% blocks/products/pf/feature-page-summary %}}
För alla **Excel-omvandlare**-applikationer eller -lösningar snabbar Java Excel Library upp kalkylbladsprogrammering och konverteringsprocesser samtidigt som de hanterar flera format inklusive XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Det gör det också möjligt att **konvertera Excel-filer till PDF**, XPS, HTML, MHTML, vanlig text och populära bildformat som TIFF, JPG, PNG, BMP och SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interkonvertering av Microsoft Excel-format" %}}
Interkonvertering av kalkylarksformat kräver bara att ett kalkylblad laddas med en instans av [Arbetsbok](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) och spara tillbaka i önskat format samtidigt som du väljer lämpligt värde från [SaveFormat](https://apireference.aspose.com/cells/java/com.aspose.cells/SaveFormat) uppräkning.
{{% blocks/products/pf/feature-page-code h3="Java Exempelkod för konvertering av Excel-filformat" %}}

```cs
// ladda källfilen
var wkb = new Workbook("sourceFile.xls");
// spara som XLSX-, ODS-, SXC- och FODS-format
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till PDF, XPS, HTML och MD" %}}
Specialiserade klasser finns tillgängliga för att styra konverteringsprocessen för specifika utdataformat som t.ex [PdfSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) för att konvertera Excel-filer som PDF, [XpsSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) för att exportera Excel som XPS, [HtmlSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) att rendera Excel som HTML och [MarkdownSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) för Excel till Markdown-konvertering. 
{{% blocks/products/pf/feature-page-code h3="Java Exempelkod för Excel till PDF- och webbformat" %}}

```cs
// ladda mall Excel-fil från skiva
var bk = new Workbook("source-file.xlsx");

// konvertera Excel till PDF med Java
// Skapa PDF-alternativ
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// spara Excel i XPS
bk.save("output.xps", new XpsSaveOptions());
// spara Excel i HTML
bk.save("output.html", new HtmlSaveOptions());
// spara Excel i Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// man kan ställa in relevanta sparalternativ efter eget val innan man sparar till relevant format

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera JSON till Excel och Excel till JSON" %}}
JSON-data kan importeras till en instans av Workbook-klassen med hjälp av [JSONUtility.importData](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) för vidare bearbetning eller enkel konvertering till något av de format som stöds. På liknande sätt kan kalkylbladsdata exporteras som JSON genom att skapa en [Räckvidd](https://apireference.aspose.com/cells/java/com.aspose.cells/range) eller celler och ringer till [exportRangeToJson](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility) metod.
{{% blocks/products/pf/feature-page-code h3="Java Kod för JSON till Excel-konvertering" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Läs fil
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Ställ in JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Importera JSON-data
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Spara Excel-fil
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Källkod för Excel till JSON-konvertering" %}}
```cs
// ladda XLSX-fil med en instans av Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// få tillgång till CellsCollection av kalkylbladet som innehåller data som ska konverteras
Cells cells = workbook.getWorksheets().get(0).getCells();
// skapa & ställ in ExportRangeToJsonOptions för avancerade alternativ
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// skapa ett intervall av celler som innehåller data som ska exporteras
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// exportera intervall som JSON-data
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// skriva data till skivan i JSON-format
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Spara Excel-kalkylblad till bilder" %}}
Varje kalkylblad kan konverteras till olika bildformat inklusive JPG, BMP, PNG och GIF, som ställs in av egenskapen ImageType. För alla fall av **Konvertera Excel till bilder**, välj relevant fall från länkarna.
{{% blocks/products/pf/feature-page-code h3="Java Kod för konvertering av Excel till bild" %}}
```cs
// ladda mallkalkylblad
var wkb = new Workbook("template.xlsx");

// Skapa ett objekt för ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Ställ in bildtyp
imgOptions.setImageType(ImageType.PNG);

// Skaffa det första arbetsbladet.
Worksheet sheet = wkb.getWorksheets().get(0);

// Skapa ett SheetRender-objekt för målarket
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Skapa en bild för kalkylbladet
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera Microsoft Excel till Word och PowerPoint" %}}
Det är möjligt att ladda vilket kalkylblad som helst och konvertera det till Word DOCX- och PowerPoint PPTX-filer medan du använder det [DocxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) klasser som visas nedan.
{{% blocks/products/pf/feature-page-code h3="Java Kod för konvertering av Excel till Word och PowerPoint" %}}
```cs
// ladda mallfilen
var wkb = new Workbook("template.xlsx");
// spara kalkylblad som DOCX
wkb.save("output.docx", new DocxSaveOptions());
// spara kalkylblad som PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}