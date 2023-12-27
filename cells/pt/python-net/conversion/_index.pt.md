---
title: Microsoft Conversão de arquivo Excel usando Python via NET
description: Aspose.Cells for Python através da biblioteca NET. Converta EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL e mais formatos com apenas algumas linhas de código Python.
keywords: [Python Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Python]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversão de formato Excel via Python" h2="Importe e exporte arquivos Excel como planilha, web, imagem e formatos de layout fixo" >}}

{{% blocks/products/pf/feature-page-summary %}}
A Biblioteca Excel Python acelera a programação de planilhas e os processos de conversão, ao mesmo tempo em que oferece suporte a formatos populares, incluindo XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Também permite exportar arquivos Excel para PDF, XPS, HTML, MHTML, Simples Formatos de texto e imagem populares, como TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converter Excel em XLSX, ODS, SXC e FODS" %}}
 A interconversão do formato de planilha requer apenas o carregamento de uma planilha com uma instância de[Pasta de trabalho](https://reference.aspose.com/cells/python-net/aspose.cells/workbook/) e salvando de volta no formato desejado enquanto seleciona o valor apropriado em[Salvar formato](https://reference.aspose.com/cells/python-net/aspose.cells/saveformat/) enumeração.
{{% blocks/products/pf/feature-page-code h3="Código Python para conversão de formato de arquivo Excel" %}}

```cs
// load the template file
workbook = Workbook("Book1.xls")
  
// save as XLSX, ODS, SXC & FODS formats
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.sxc", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converter Excel para PDF, XPS, HTML e MD" %}}
 Classes especializadas estão disponíveis para controlar o processo de conversão para formatos de saída específicos, como[Opções de salvamento de PDF](https://reference.aspose.com/cells/python-net/aspose.cells/pdfsaveoptions/) para exportar arquivos Excel como PDF,[Opções XpsSave](https://reference.aspose.com/cells/python-net/aspose.cells/xpssaveoptions/) para conversão de Excel para XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/htmlsaveoptions/) para renderizar o Excel como HTML e[MarkdownSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/markdownsaveoptions/) para conversão de Excel para Markdown.
{{% blocks/products/pf/feature-page-code h3="Python Código para Excel para PDF e formatos Web" %}}

```cs
// load template Excel file from disc
book = Workbook("template.xlsx")

// save Excel in PDF_A_1_B format
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// save Excel in XPS with 1 page per worksheet
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// save Excel in HTML with images as Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// save Excel in Markdown (MD) while retaining cell formatting
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converta JSON para Excel e Excel para JSON" %}}
Os desenvolvedores do Python podem facilmente carregar e converter arquivos JSON para Excel em apenas algumas linhas de código. Da mesma forma, os dados do Excel podem ser exportados para dados JSON.
{{% blocks/products/pf/feature-page-code h3="Python Código para conversão JSON para Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Código Python para Excel para conversão JSON" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Converter planilhas do Excel em JPG, BMP, PNG e GIF" %}}
 Cada planilha de um arquivo Excel pode ser convertida para diferentes formatos de imagem, ligue[Opções de imagem ou impressão](https://reference.aspose.com/cells/python-net/aspose.cells.rendering/imageorprintoptions/).setImageFormat para definir o formato da imagem.
{{% blocks/products/pf/feature-page-code h3="Python Código para conversão de Excel em imagem" %}}
```cs
// load template spreadsheet
workbook = Workbook("template.xlsx")
// create & set an instance of ImageOrPrintOptions
options = ImageOrPrintOptions()
// set output image format
options.setImageFormat(ImageFormat.getPng())
// create SheetRender for first worksheet in the collection
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// render worksheet to image
sr.toImage(0, "output.jpg")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converter Excel para Word e PowerPoint" %}}
É possível carregar qualquer planilha e convertê-la para arquivos Word DOCX e PowerPoint PPTX enquanto estiver usando[DocxSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/docxsaveoptions/) & [Opções PptxSave](https://reference.aspose.com/cells/python-net/aspose.cells/pptxsaveoptions/) aulas conforme demonstrado abaixo.
{{% blocks/products/pf/feature-page-code h3="Código Python para Excel para Word e conversão PowerPoint" %}}
```cs
// load the template file
workbook = Workbook("template.xlsx")

// save spreadsheet as DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// save spreadsheet as PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx" >}}
