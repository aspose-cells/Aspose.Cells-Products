---
title: Microsoft Excel File Conversion via Java 
url: /java/conversion/
description: Convert Excel XLS, XLSX, ODS, CSV to PDF, XPS, HTML, JPEG, HTML and many other popular formats with just few lines of Java code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Files Conversion via Java" h2="Save Microsoft Excel documents as spreadsheet, web, image and fixed-layout formats" >}}

{{% blocks/products/pf/feature-page-summary %}}
For any **Excel converter** application or solution, Java Excel Library speeds up spreadsheet programming and conversion processes while handling multiple formats including XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. It also allows to **convert Excel files to PDF**, XPS, HTML, MHTML, Plain Text and popular image formats such as TIFF, JPG, PNG, BMP and SVG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter-conversion of Microsoft Excel Formats" %}}
Inter-conversion of spreadsheet format only requires loading a spreadsheet with an instance of [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) and saving back in the desired format while selecting appropriate value from [SaveFormat](https://apireference.aspose.com/cells/java/com.aspose.cells/SaveFormat) enumeration.
{{% blocks/products/pf/feature-page-code h3="Java Example Code for Excel File Format Conversion" %}}

```cs
// load the source file
var wkb = new Workbook("sourceFile.xls");
// save as XLSX, ODS, SXC & FODS formats
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section  h2="Convert Excel to PDF, XPS, HTML & MD" %}}
Specialized classes are available to control the conversion process for specific output formats such as [PdfSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) to convert Excel files as PDF, [XpsSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) to export Excel as XPS, [HtmlSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) to render Excel as HTML and [MarkdownSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) for Excel to Markdown conversion. 
{{% blocks/products/pf/feature-page-code h3="Java Sample Code for Excel to PDF and Web Formats" %}}

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
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert">}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON to Excel and Excel to JSON" %}}
JSON data can be imported into an instance of Workbook class with the help of [JSONUtility.importData](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) for further processing or simple conversion to any of the supported formats. Similarly, Worksheet data can be exported as JSON by creating a [Range](https://apireference.aspose.com/cells/java/com.aspose.cells/range) or cells and calling the [exportRangeToJson](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility) method.
{{% blocks/products/pf/feature-page-code h3="Java Code for JSON to Excel Conversion" %}}
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

{{% blocks/products/pf/feature-page-code h3="Java Source Code for Excel to JSON Conversion" %}}
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

{{% blocks/products/pf/feature-page-section  h2="Save Excel Worksheets to Images" %}}
Each worksheet can be converted to different image formats including JPG, BMP, PNG & GIF, set by the ImageType property. For any **Convert Excel to Images** case, select the relevant case from links.
{{% blocks/products/pf/feature-page-code h3="Java Code for Excel to Image Conversion" %}}
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

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering">}}

{{% blocks/products/pf/feature-page-section  h2="Convert Microsoft Excel to Word and PowerPoint" %}}
It is possible to load any spreadsheet and convert it to Word DOCX & PowerPoint PPTX files while using [DocxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) classes as demonstrated below.
{{% blocks/products/pf/feature-page-code h3="Java Code for Excel to Word & PowerPoint Conversion" %}}
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