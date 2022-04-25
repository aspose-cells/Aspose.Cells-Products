---
title: Conversión de archivos de Microsoft Excel a través de Java 
url: /es/java/conversion/
description: Convierta Excel XLS, XLSX, ODS, CSV a PDF, XPS, HTML, JPEG, HTML y muchos otros formatos populares con solo unas pocas líneas de código Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversión de archivos de Microsoft<sup>&reg;</sup> Excel a través de Java" h2="Guarde documentos de Microsoft Excel como hojas de cálculo, web, imágenes y formatos de diseño fijo" >}}

{{% blocks/products/pf/feature-page-summary %}}
Para cualquier aplicación o solución de **conversor de Excel**, Java Biblioteca de Excel acelera la programación de hojas de cálculo y los procesos de conversión mientras maneja múltiples formatos, incluidos XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. También permite **convertir archivos de Excel a PDF**, XPS, HTML, MHTML, texto sin formato y formatos de imagen populares como TIFF, JPG, PNG, BMP y SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversión de formatos de Microsoft Excel" %}}
La interconversión del formato de hoja de cálculo solo requiere cargar una hoja de cálculo con una instancia de [Libro de trabajo](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) y guardar de nuevo en el formato deseado mientras selecciona el valor apropiado de [Guardar formato](https://apireference.aspose.com/cells/java/com.aspose.cells/SaveFormat) enumeración.
{{% blocks/products/pf/feature-page-code h3="Java Código de ejemplo para conversión de formato de archivo de Excel" %}}

```cs
// cargar el archivo fuente
var wkb = new Workbook("sourceFile.xls");
// guardar como formatos XLSX, ODS, SXC y FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Convierta Excel a PDF, XPS, HTML y MD" %}}
Hay clases especializadas disponibles para controlar el proceso de conversión para formatos de salida específicos como [PdfGuardarOpciones](https://apireference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) para convertir archivos de Excel a PDF, [XpsSaveOpciones](https://apireference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) para exportar Excel como XPS, [HtmlSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) para renderizar Excel como HTML y [MarkdownSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) para la conversión de Excel a Markdown. 
{{% blocks/products/pf/feature-page-code h3="Java Código de muestra para formatos de Excel a PDF y Web" %}}

```cs
// cargar el archivo Excel de la plantilla desde el disco
var bk = new Workbook("source-file.xlsx");

// convertir Excel a PDF usando Java
// Crear opciones de PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// guardar Excel en XPS
bk.save("output.xps", new XpsSaveOptions());
// guardar Excel en HTML
bk.save("output.html", new HtmlSaveOptions());
// guardar Excel en Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// uno puede establecer opciones de guardado relevantes a su elección antes de guardar en el formato relevante

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Convierta JSON a Excel y Excel a JSON" %}}
Los datos JSON se pueden importar a una instancia de la clase Workbook con la ayuda de [JSONUtility.importData](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) para su posterior procesamiento o simple conversión a cualquiera de los formatos admitidos. De manera similar, los datos de la hoja de trabajo se pueden exportar como JSON creando un [Distancia](https://apireference.aspose.com/cells/java/com.aspose.cells/range) o celdas y llamando al [exportRangeToJson](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonutility) método.
{{% blocks/products/pf/feature-page-code h3="Java Código para la conversión de JSON a Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Leer archivo
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Establecer JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Importar datos JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Guardar archivo de Excel
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java código fuente para la conversión de Excel a JSON" %}}
```cs
// cargue el archivo XLSX con una instancia de Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// acceda a CellsCollection de la hoja de cálculo que contiene los datos que se van a convertir
Cells cells = workbook.getWorksheets().get(0).getCells();
// crear y configurar ExportRangeToJsonOptions para opciones avanzadas
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// crear un rango de celdas que contengan datos para exportar
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// rango de exportación como datos JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// escribir datos en el disco en formato JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Guardar hojas de cálculo de Excel en imágenes" %}}
Cada hoja de trabajo se puede convertir a diferentes formatos de imagen, incluidos JPG, BMP, PNG y GIF, establecidos por la propiedad ImageType. Para cualquier caso de **Convertir Excel a Imágenes**, seleccione el caso relevante de los enlaces.
{{% blocks/products/pf/feature-page-code h3="Java Código para conversión de Excel a imagen" %}}
```cs
// cargar plantilla de hoja de cálculo
var wkb = new Workbook("template.xlsx");

// Crear un objeto para ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Establecer el tipo de imagen
imgOptions.setImageType(ImageType.PNG);

// Obtenga la primera hoja de trabajo.
Worksheet sheet = wkb.getWorksheets().get(0);

// Cree un objeto SheetRender para la hoja de destino
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Generar una imagen para la hoja de trabajo
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir Microsoft Excel a Word y PowerPoint" %}}
Es posible cargar cualquier hoja de cálculo y convertirla a archivos Word DOCX y PowerPoint PPTX mientras se usa [DocxSaveOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxGuardarOpciones](https://apireference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) clases como se muestra a continuación.
{{% blocks/products/pf/feature-page-code h3="Java Código para la conversión de Excel a Word y PowerPoint" %}}
```cs
// cargar el archivo de plantilla
var wkb = new Workbook("template.xlsx");
// guardar hoja de cálculo como DOCX
wkb.save("output.docx", new DocxSaveOptions());
// guardar hoja de cálculo como PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}