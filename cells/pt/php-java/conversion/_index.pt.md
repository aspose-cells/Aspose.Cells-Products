---
title: Microsoft Conversão de arquivo Excel usando PHP via Java
description: Aspose.Cells for PHP via Java biblioteca. Converta EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL e mais formatos com apenas algumas linhas de código PHP.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> Conversão de formato Excel via PHP" h2="Importe e exporte arquivos Excel como planilha, web, imagem e formatos de layout fixo" >}}

{{% blocks/products/pf/feature-page-summary %}}
biblioteca PHP Excel acelera os processos de programação e conversão de planilhas, ao mesmo tempo que suporta formatos populares, incluindo XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Também permite exportar arquivos Excel para PDF, XPS, HTML, MHTML, Simples Formatos de texto e imagem populares, como TIFF, JPG, PNG, BMP e SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converta Excel para XLSX, ODS, SXC e FODS usando PHP" %}}
 A interconversão do formato de planilha requer apenas o carregamento de uma planilha com uma instância de[Pasta de trabalho](https://reference.aspose.com/cells/php/aspose.cells/Workbook) e salvando de volta no formato desejado enquanto seleciona o valor apropriado em[Salvar formato](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) enumeração.
{{% blocks/products/pf/feature-page-code h3="Código PHP para conversão de formato de arquivo Excel" %}}

```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// load the template file
$workbook = new Workbook("input.xlsx");

// save as XLSX, ODS, SXC & FODS formats
$workbook->save("output.xlsx", SaveFormat::Xlsx);
$workbook->save("output.ods", SaveFormat::Ods);
$workbook->save("output.scx", SaveFormat::Sxc);
$workbook->save("output.fods", SaveFormat::Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Converta Excel para PDF, XPS, HTML e MD usando PHP" %}}
 Classes especializadas estão disponíveis para controlar o processo de conversão para formatos de saída específicos, como[Opções de salvamento de PDF](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)para exportar arquivos Excel como PDF,[Opções XpsSave](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) para conversão de Excel para XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) para renderizar o Excel como HTML e[MarkdownSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) para conversão de Excel para Markdown.
{{% blocks/products/pf/feature-page-code h3="Código PHP para Excel para PDF e formatos Web" %}}

```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// load the template file
$workbook = new Workbook("input.xlsx");


// save Excel in PDF_A_1_B format
$pdfOptions = new PdfSaveOptions();
$pdfOptions->setCompliance(PdfCompliance::PDF_A_1_B);
$workbook->save("output.pdf", pdfOptions);

// save Excel in XPS with 1 page per worksheet
$xpsOptions = new XpsSaveOptions();
$xpsOptions->setOnePagePerSheet(true);
$workbook->save("output.xps", xpsOptions);

// save Excel in HTML with images as Base64
$htmlOptions = new HtmlSaveOptions();
$htmlOptions->setExportImagesAsBase64(true);
$workbook->save("output.html", htmlOptions);

// save Excel in Markdown (MD) while retaining cell formatting
$mdOptions = new MarkdownSaveOptions();
$mdOptions->setFormatStrategy(CellValueFormatStrategy::CELL_STYLE);
$workbook->save("output.md", mdOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Converta JSON para Excel e Excel para JSON usando PHP" %}}
Os desenvolvedores PHP podem facilmente carregar e converter arquivos JSON para Excel em apenas algumas linhas de código. Da mesma forma, os dados do Excel podem ser exportados para dados JSON.
{{% blocks/products/pf/feature-page-code h3="Código PHP para conversão JSON para Excel" %}}

```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// Load your source json file
$workbook = new Workbook("Data.json");

//save file to xlsx format
$workbook->save("output.xlsx");
```

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Código PHP para Excel para conversão JSON" %}}

```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// Load your source xlsx file
$workbook = new Workbook("input.xlsx");

// save file to json format
$workbook->save("Data.json");
```

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Converter planilhas do Excel em JPG, BMP, PNG e GIF usando PHP" %}}
 Cada planilha de um arquivo Excel pode ser convertida para diferentes formatos de imagem, ligue[Opções de imagem ou impressão](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat para definir o formato da imagem.
{{% blocks/products/pf/feature-page-code h3="Código PHP para conversão de Excel em imagem" %}}

```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// load template spreadsheet
$workbook = new Workbook("template.xlsx");

// create & set an instance of ImageOrPrintOptions
$options = new ImageOrPrintOptions();
// set output image type
$options->setImageType(ImageType::PNG);
// create SheetRender for first worksheet in the collection
$sheet = $workbook->getWorksheets()->get(0);
$sr = new SheetRender(sheet, options);
// render worksheet to image
$sr->toImage(0, "output.jpg")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Converter Excel para Word e PowerPoint usando PHP" %}}
É possível carregar qualquer planilha e convertê-la para arquivos Word DOCX e PowerPoint PPTX enquanto estiver usando[DocxSaveOptions](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [Opções PptxSave](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) aulas conforme demonstrado abaixo.
{{% blocks/products/pf/feature-page-code h3="Código PHP para Excel para Word e conversão PowerPoint" %}}
```php
require_once("Java.inc"); 
require_once("lib/aspose.cells.php"); 
use aspose\cells;
use aspose\cells\Workbook; 

// load template spreadsheet
$workbook = new Workbook("template.xlsx");

// save spreadsheet as DOCX
$docxOptions = new DocxSaveOptions();
$workbook->save("output.docx", docxOptions);

// save spreadsheet as PPTX
$pptxOptions = new PptxSaveOptions();
$workbook->save("output.pptx", pptxOptions)
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx" >}}
