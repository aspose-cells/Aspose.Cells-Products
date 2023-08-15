---
title:  Microsoft Conversión de archivos de Excel via Java
description: Convertir Excel XLS, XLSX, ODS, CSV a PDF, XPS, HTML, JPEG, HTML y muchos otros formatos populares con solo pocas líneas de 07619341 Código.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversión de archivos de Excel via Java" h2="Guarde Microsoft documentos de Excel como hojas de cálculo, web, imágenes y formatos de diseño fijo" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Para cualquier**convertidor de Excel**aplicación o solución, Java Excel Library acelera la programación de hojas de cálculo y los procesos de conversión mientras maneja múltiples formatos, incluidos XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 076 193481. También permite *convertir archivos de Excel a PDF**, XPS, HTML, MHTML, texto sin formato y formatos de imagen populares como TIFF, JPG, PNG, BMP y SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversión de Microsoft Formatos de Excel" %}}
 La interconversión del formato de hoja de cálculo solo requiere cargar una hoja de cálculo con una instancia de[Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) y guardar de nuevo en el formato deseado mientras selecciona el valor apropiado de[Guardar formato](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) enumeración.
{{% blocks/products/pf/feature-page-code h3="Java Código de ejemplo para conversión de formato de archivo de Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Convierta Excel a PDF, XPS, HTML y MD" %}}
 Hay clases especializadas disponibles para controlar el proceso de conversión para formatos de salida específicos como[PdfGuardarOpciones](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) para convertir archivos de Excel como PDF,[XpsSaveOpciones](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) para exportar Excel como XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) para representar Excel como HTML y[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) para la conversión de Excel a Markdown.
{{% blocks/products/pf/feature-page-code h3="Java Código de muestra para Excel a PDF y formatos web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Convierta JSON a Excel y Excel a JSON" %}}
 Los datos JSON se pueden importar a una instancia de la clase Workbook con la ayuda de[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) para su posterior procesamiento o simple conversión a cualquiera de los formatos admitidos. De manera similar, los datos de la hoja de trabajo se pueden exportar como JSON creando un[Rango](https://reference.aspose.com/cells/java/com.aspose.cells/range) o celdas y llamando al[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) método.
{{% blocks/products/pf/feature-page-code h3="Java Código para la conversión JSON a Excel" %}}
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

{{% blocks/products/pf/feature-page-code h3="Java Código fuente para Excel a JSON Conversión" %}}
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

{{% blocks/products/pf/feature-page-section h2="Guardar hojas de cálculo de Excel en imágenes" %}}
 Cada hoja de trabajo se puede convertir a diferentes formatos de imagen, incluidos JPG, BMP, PNG y GIF, establecidos por la propiedad ImageType. Para cualquier**Convertir Excel a Imágenes** caso, seleccione el caso relevante de los enlaces.
{{% blocks/products/pf/feature-page-code h3="Java Código para conversión de Excel a imagen" %}}
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

{{% blocks/products/pf/feature-page-section h2="Convierta Microsoft Excel a Word y PowerPoint" %}}
 Es posible cargar cualquier hoja de cálculo y convertirla a archivos de Word DOCX y PowerPoint PPTX mientras se usa[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxGuardarOpciones](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions)clases como se muestra a continuación.
{{% blocks/products/pf/feature-page-code h3="Java Código para Excel a Word y PowerPoint Conversión" %}}
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
