---
title:  Microsoft Conversão de arquivo Excel via Java
description: Aspose.Cells for Java biblioteca. Converta EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG e mais formatos com apenas algumas linhas de código Java.
keywords: [Java Aspose.Cells., excel to pdf., excel to json., html to xps., csv to json., json to pdf., xml to excel and Convert files between various formats in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversão de arquivos Excel via Java" h2="Salve documentos Excel Microsoft como planilha, web, imagem e formatos de layout fixo" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Para qualquer**Conversor Excel** aplicativo ou solução, a Biblioteca Excel Java acelera a programação de planilhas e os processos de conversão enquanto lida com vários formatos, incluindo XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 076193 481. Também permite *converter arquivos Excel para PDF**, XPS, HTML, MHTML, texto simples e formatos de imagem populares como TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversão de formatos Excel Microsoft" %}}
 A interconversão do formato de planilha requer apenas o carregamento de uma planilha com uma instância de[Pasta de trabalho](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e salvando de volta no formato desejado enquanto seleciona o valor apropriado em[Salvar formato](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) enumeração.
{{% blocks/products/pf/feature-page-code h3="Java Código de exemplo para conversão de formato de arquivo Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Converter Excel para PDF, XPS, HTML e MD" %}}
 Classes especializadas estão disponíveis para controlar o processo de conversão para formatos de saída específicos, como[Opções de salvamento de PDF](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) para converter arquivos Excel como PDF,[Opções XpsSave](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) para exportar Excel como XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) para renderizar o Excel como HTML e[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) para conversão de Excel para Markdown.
{{% blocks/products/pf/feature-page-code h3="Java Código de exemplo para Excel para PDF e formatos da Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Converta JSON para Excel e Excel para JSON" %}}
 Os dados JSON podem ser importados para uma instância da classe Workbook com a ajuda de[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) para processamento posterior ou conversão simples para qualquer um dos formatos suportados. Da mesma forma, os dados da planilha podem ser exportados como JSON criando um[Faixa](https://reference.aspose.com/cells/java/com.aspose.cells/range) ou células e ligando para o[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) método.
{{% blocks/products/pf/feature-page-code h3="Java Código para conversão JSON para Excel" %}}
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

{{% blocks/products/pf/feature-page-code h3="Código-fonte Java para Excel para conversão JSON" %}}
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

{{% blocks/products/pf/feature-page-section h2="Salvar planilhas do Excel em imagens" %}}
 Cada planilha pode ser convertida em diferentes formatos de imagem, incluindo JPG, BMP, PNG e GIF, definidos pela propriedade ImageType. Para qualquer**Converter Excel em imagens** caso, selecione o caso relevante nos links.
{{% blocks/products/pf/feature-page-code h3="Java Código para conversão de Excel em imagem" %}}
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

{{% blocks/products/pf/feature-page-section h2="Converter Microsoft Excel para Word e PowerPoint" %}}
É possível carregar qualquer planilha e convertê-la para arquivos Word DOCX e PowerPoint PPTX enquanto estiver usando[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [Opções PptxSave](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) aulas conforme demonstrado abaixo.
{{% blocks/products/pf/feature-page-code h3="Código Java para Excel para Word e conversão PowerPoint" %}}
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
