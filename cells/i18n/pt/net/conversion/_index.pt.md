---
title: Conversão de arquivo do Microsoft Excel via C# 
url: /pt/net/conversion/
description: Converta Excel XLS, XLSX, ODS, CSV para PDF, XPS, HTML, JPEG, HTML e muitos outros formatos populares com apenas algumas linhas de código C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversão de Formato Excel via .NET" h2="Importe e exporte arquivos do Excel como planilha, web, imagem e formatos de layout fixo" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET A Biblioteca do Excel acelera a programação de planilhas e os processos de conversão ao mesmo tempo em que oferece suporte a formatos populares, incluindo XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Também permite exportar arquivos do Excel para PDF, XPS, HTML, MHTML, Texto Simples e formatos de imagem populares como TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converter Excel para XLSX, ODS, SXC e FODS" %}}
A interconversão do formato da planilha requer apenas o carregamento de uma planilha com uma instância de [Pasta de trabalho](https://apireference.aspose.com/cells/net/aspose.cells/workbook) e salvando de volta no formato desejado enquanto seleciona o valor apropriado de [Salvar formato](https://apireference.aspose.com/cells/net/aspose.cells/saveformat) enumeração.
{{% blocks/products/pf/feature-page-code h3="C# Código para conversão de formato de arquivo do Excel" %}}

```cs
// carregue o arquivo de modelo
var workbook = new Aspose.Cells.Workbook("template.xls");
// salvar nos formatos XLSX, ODS, SXC e FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converter Excel para PDF, XPS, HTML e MD" %}}
Classes especializadas estão disponíveis para controlar o processo de conversão para formatos de saída específicos, como [PdfSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) para exportar arquivos do Excel como PDF, [XpsSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/xpssaveoptions) para conversão de Excel para XPS, [HtmlSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) para renderizar o Excel como HTML e [MarkdownSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) para conversão de Excel para Markdown. 
{{% blocks/products/pf/feature-page-code h3="C# Código para Excel para PDF e Formatos da Web" %}}

```cs
// carregar arquivo de modelo do Excel do disco
var book = new Aspose.Cells.Workbook("template.xlsx");
// salve o Excel no formato PDF/A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// salve o Excel em XPS com 1 página por planilha
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// salve o Excel em HTML com imagens como Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// salve o Excel em Markdown (MD) enquanto mantém a formatação da célula
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converter JSON para Excel e Excel para JSON" %}}
Os dados JSON podem ser importados para uma instância de [Cells](https://apireference.aspose.com/cells/net/aspose.cells/cells) aula com a ajuda de [JsonUtility.ImportData](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) para processamento adicional ou conversão simples para qualquer um dos formatos suportados. De forma similar, [Planilha](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) os dados podem ser exportados como JSON criando um [Alcance](https://apireference.aspose.com/cells/net/aspose.cells/range) ou células e chamando o [JsonUtility.ExportRangeToJson](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) método.
{{% blocks/products/pf/feature-page-code h3="C# Código para conversão de JSON para Excel" %}}
```cs
// criar um objeto Workbook
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// ler dados JSON do arquivo
string jsonInput = File.ReadAllText("Data.json");
// defina JsonLayoutOptions para tratar Arrays como Tabela
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// importar dados JSON para a planilha começando na célula A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// salve o arquivo resultante no formato XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para conversão de Excel para JSON" %}}
```cs
// carregar o arquivo XLSX com uma instância da pasta de trabalho
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// acessar CellsCollection da planilha contendo os dados a serem convertidos
var cells = workbook.Worksheets[0].Cells;
// crie e defina ExportRangeToJsonOptions para opções avançadas
var exportOptions = new Utility.ExportRangeToJsonOptions();
// crie um intervalo de células contendo dados a serem exportados
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// exportar intervalo como dados JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// gravar arquivo de dados em disco no formato JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Converter planilhas do Excel para JPG, BMP, PNG e GIF" %}}
Cada planilha de um arquivo Excel pode ser convertida em diferentes formatos de imagem definidos pelo [ImageOrPrintOptions.ImageType](https://apireference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) propriedade. O valor padrão é `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Código para conversão de Excel em imagem" %}}
```cs
// carregar planilha modelo
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// crie e defina uma instância de ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// definir o formato da imagem de saída
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// crie SheetRender para a primeira planilha na coleção
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// renderizar planilha para imagem
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converter Excel para Word e PowerPoint" %}}
É possível carregar qualquer planilha e convertê-la em arquivos Word DOCX e PowerPoint PPTX enquanto estiver usando [DocxSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) classes, conforme demonstrado abaixo.
{{% blocks/products/pf/feature-page-code h3="C# código para conversão de Excel para Word e PowerPoint" %}}
```cs
// carregue o arquivo de modelo
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// salvar planilha como DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// salvar planilha como PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}