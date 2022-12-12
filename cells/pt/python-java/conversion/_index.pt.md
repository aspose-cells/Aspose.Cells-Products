---
title: Conversão de arquivo do Microsoft Excel via Python 

description: Converta Excel XLS, XLSX, ODS, CSV para PDF, XPS, HTML, JPEG, HTML e muitos outros formatos populares com apenas algumas linhas de código Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversão de Formato Excel via Python" h2="Importe e exporte arquivos do Excel como planilha, web, imagem e formatos de layout fixo" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python A Biblioteca do Excel acelera a programação de planilhas e os processos de conversão ao mesmo tempo em que oferece suporte a formatos populares, incluindo XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Também permite exportar arquivos do Excel para PDF, XPS, HTML, MHTML, Texto Simples e formatos de imagem populares como TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converter Excel para XLSX, ODS, SXC e FODS" %}}
A interconversão do formato da planilha requer apenas o carregamento de uma planilha com uma instância de [Pasta de trabalho](https://reference.aspose.com/cells/python/asposecells.api/Workbook) e salvando de volta no formato desejado enquanto seleciona o valor apropriado de [Salvar formato](https://reference.aspose.com/cells/python/asposecells.api/saveformat) enumeração.
{{% blocks/products/pf/feature-page-code h3="Python Código para conversão de formato de arquivo do Excel" %}}

```cs
// carregue o arquivo de modelo
workbook = Workbook("Book1.xls")
  
// salvar nos formatos XLSX, ODS, SXC e FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converter Excel para PDF, XPS, HTML e MD" %}}
Classes especializadas estão disponíveis para controlar o processo de conversão para formatos de saída específicos, como [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) para exportar arquivos do Excel como PDF, [XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) para conversão de Excel para XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) para renderizar o Excel como HTML e [MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) para conversão de Excel para Markdown. 
{{% blocks/products/pf/feature-page-code h3="Python Código para Excel para PDF e Formatos da Web" %}}

```cs
// carregar arquivo de modelo do Excel do disco
book = Workbook("template.xlsx")

// salvar Excel no formato PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// salve o Excel em XPS com 1 página por planilha
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// salve o Excel em HTML com imagens como Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// salve o Excel em Markdown (MD) enquanto mantém a formatação da célula
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converter JSON para Excel e Excel para JSON" %}}
Python os desenvolvedores podem facilmente carregar e converter arquivos JSON para Excel em apenas algumas linhas de código. Da mesma forma, os dados do Excel podem ser exportados para dados JSON.
{{% blocks/products/pf/feature-page-code h3="Python Código para conversão de JSON para Excel" %}}
```cs
//Carregue seu arquivo json de origem
workbook = Workbook("Data.json")
//salvar arquivo no formato xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Código para conversão de Excel para JSON" %}}
```cs
//Carregue seu arquivo xlsx de origem
workbook = Workbook("input.xlsx")
//salvar arquivo no formato json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Converter planilhas do Excel para JPG, BMP, PNG e GIF" %}}
Cada planilha de um arquivo Excel pode ser convertida para diferentes formatos de imagem, chame [ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat para definir o formato da imagem. 
{{% blocks/products/pf/feature-page-code h3="Python Código para conversão de Excel em imagem" %}}
```cs
// carregar planilha modelo
workbook = Workbook("template.xlsx")
// crie e defina uma instância de ImageOrPrintOptions
options = ImageOrPrintOptions()
// definir o formato da imagem de saída
options.setImageFormat(ImageFormat.getPng())
// crie SheetRender para a primeira planilha na coleção
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// renderizar planilha para imagem
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converter Excel para Word e PowerPoint" %}}
É possível carregar qualquer planilha e convertê-la em arquivos Word DOCX e PowerPoint PPTX enquanto estiver usando [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) classes, conforme demonstrado abaixo.
{{% blocks/products/pf/feature-page-code h3="Python código para conversão de Excel para Word e PowerPoint" %}}
```cs
// carregue o arquivo de modelo
workbook = Workbook("template.xlsx")

// salvar planilha como DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// salvar planilha como PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
