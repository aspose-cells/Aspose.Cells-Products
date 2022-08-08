---
title: Conversão de arquivo do Microsoft Excel via Java 
url: /pt/java/conversion/
description: Converta Excel XLS, XLSX, ODS, CSV para PDF, XPS, HTML, JPEG, HTML e muitos outros formatos populares com apenas algumas linhas de código Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversão de arquivos Excel via Java" h2="Salve documentos do Microsoft Excel como planilha, web, imagem e formatos de layout fixo" >}}

{{% blocks/products/pf/feature-page-summary %}}
Para qualquer aplicativo ou solução **Conversor Excel**, a Java Biblioteca do Excel acelera os processos de programação e conversão de planilhas enquanto lida com vários formatos, incluindo XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Também permite **converter arquivos Excel para PDF**, XPS, HTML, MHTML, Texto simples e formatos de imagem populares como TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Interconversão de formatos do Microsoft Excel" %}}
A interconversão do formato da planilha requer apenas o carregamento de uma planilha com uma instância de [Pasta de trabalho](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e salvando de volta no formato desejado enquanto seleciona o valor apropriado de [Salvar formato](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) enumeração.
{{% blocks/products/pf/feature-page-code h3="Java Código de exemplo para conversão de formato de arquivo do Excel" %}}

```cs
// carregar o arquivo de origem
var wkb = new Workbook("sourceFile.xls");
// salvar nos formatos XLSX, ODS, SXC e FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converter Excel para PDF, XPS, HTML e MD" %}}
Classes especializadas estão disponíveis para controlar o processo de conversão para formatos de saída específicos, como [PdfSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) para converter arquivos do Excel como PDF, [XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) para exportar Excel como XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) para renderizar o Excel como HTML e [MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) para conversão de Excel para Markdown. 
{{% blocks/products/pf/feature-page-code h3="Java Código de exemplo para Excel para PDF e formatos da Web" %}}

```cs
// carregar arquivo de modelo do Excel do disco
var bk = new Workbook("source-file.xlsx");

// converter Excel para PDF usando Java
// Criar opções de PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// salvar Excel em XPS
bk.save("output.xps", new XpsSaveOptions());
// salvar Excel em HTML
bk.save("output.html", new HtmlSaveOptions());
// salvar Excel em Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// pode-se definir as opções de salvamento relevantes à sua escolha antes de salvar no formato relevante

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converter JSON para Excel e Excel para JSON" %}}
Os dados JSON podem ser importados para uma instância da classe Workbook com a ajuda de [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) para processamento adicional ou conversão simples para qualquer um dos formatos suportados. Da mesma forma, os dados da planilha podem ser exportados como JSON criando um [Alcance](https://reference.aspose.com/cells/java/com.aspose.cells/range) ou células e chamando o [exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) método.
{{% blocks/products/pf/feature-page-code h3="Java Código para conversão de JSON para Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Ler arquivo
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Definir JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Importar dados JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Salvar arquivo Excel
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Código-fonte para conversão de Excel para JSON" %}}
```cs
// carregar o arquivo XLSX com uma instância da pasta de trabalho
Workbook workbook = new Workbook("sourceFile.xlsx");
// acessar CellsCollection da planilha contendo os dados a serem convertidos
Cells cells = workbook.getWorksheets().get(0).getCells();
// crie e defina ExportRangeToJsonOptions para opções avançadas
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// crie um intervalo de células contendo dados a serem exportados
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// exportar intervalo como dados JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// gravar dados no disco no formato JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Salvar planilhas do Excel em imagens" %}}
Cada planilha pode ser convertida em diferentes formatos de imagem, incluindo JPG, BMP, PNG e GIF, definidos pela propriedade ImageType. Para qualquer caso de **Converter Excel em Imagens**, selecione o caso relevante nos links.
{{% blocks/products/pf/feature-page-code h3="Java Código para conversão de Excel em imagem" %}}
```cs
// carregar planilha modelo
var wkb = new Workbook("template.xlsx");

// Crie um objeto para ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Defina o tipo de imagem
imgOptions.setImageType(ImageType.PNG);

// Pegue a primeira planilha.
Worksheet sheet = wkb.getWorksheets().get(0);

// Criar um objeto SheetRender para a planilha de destino
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Gerar uma imagem para a planilha
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converter Microsoft Excel para Word e PowerPoint" %}}
É possível carregar qualquer planilha e convertê-la em arquivos Word DOCX e PowerPoint PPTX enquanto estiver usando [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) classes, conforme demonstrado abaixo.
{{% blocks/products/pf/feature-page-code h3="Java Código para conversão de Excel para Word e PowerPoint" %}}
```cs
// carregue o arquivo de modelo
var wkb = new Workbook("template.xlsx");
// salvar planilha como DOCX
wkb.save("output.docx", new DocxSaveOptions());
// salvar planilha como PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}