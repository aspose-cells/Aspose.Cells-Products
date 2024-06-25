---
title: Microsoft PHP を使用した Excel ファイル変換 via Java
description: Aspose.Cells for PHP via Java ライブラリ。わずか数行の PHP コードで、EXCEL、JSON、PDF、XML、HTML、TXT、TSV、CSV、SQL などの形式を変換します。
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> PHP による Excel 形式の変換" h2="Excel ファイルをスプレッドシート、Web、画像、固定レイアウト形式でインポートおよびエクスポートします。" >}}

{{% blocks/products/pf/feature-page-summary %}}
PHP Excel ライブラリは、XLS、XLSX、XLSM、XLSB、XLTX、XLTM、CSV、SpreadsheetML、ODS などの一般的な形式をサポートしながら、スプレッドシートのプログラミングと変換プロセスを高速化します。また、Excel ファイルを PDF、XPS、HTML、MHTML、プレーン テキスト、および TIFF、JPG、PNG、BMP、SVG などの一般的な画像形式にエクスポートすることもできます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="PHP を使用して Excel を XLSX、ODS、SXC、FODS に変換する" %}}
スプレッドシート形式の相互変換には、次のインスタンスを含むスプレッドシートを読み込むだけで済みます。[ワークブック](https://reference.aspose.com/cells/php/aspose.cells/Workbook)適切な値を選択しながら、希望の形式で保存します。[保存形式](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat)列挙。
{{% blocks/products/pf/feature-page-code h3="Excel ファイル形式変換用の PHP コード" %}}

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


{{% blocks/products/pf/feature-page-section h2="PHP を使用して Excel を PDF、XPS、HTML および MD に変換する" %}}
特定の出力形式の変換プロセスを制御するための専用クラスが用意されています。[Pdf保存オプション](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)ExcelファイルをPDFとしてエクスポートするには、[Xps保存オプション](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/)ExcelからXPSへの変換、[HTML保存オプション](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/)ExcelをHTMLと表示し、[マークダウン保存オプション](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/)Excel から Markdown への変換用。
{{% blocks/products/pf/feature-page-code h3="Excel 用 PHP コード PDF および Web 形式" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP を使用して JSON を Excel に変換し、Excel を JSON に変換する" %}}
PHP 開発者は、わずか数行のコードで JSON ファイルを簡単に読み込み、Excel に変換できます。同様に、Excel データを JSON データにエクスポートすることもできます。
{{% blocks/products/pf/feature-page-code h3="JSON を Excel に変換する PHP コード" %}}

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

{{% blocks/products/pf/feature-page-code h3="Excel から JSON への変換のための PHP コード" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP を使用して Excel ワークシートを JPG、BMP、PNG、GIF に変換する" %}}
Excelファイルの各ワークシートは、異なる画像形式に変換することができます。[画像または印刷オプション](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/).setImageFormat を使用して画像形式を設定します。
{{% blocks/products/pf/feature-page-code h3="Excel から画像への変換のための PHP コード" %}}

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

{{% blocks/products/pf/feature-page-section h2="PHP を使用して Excel を Word および PowerPoint に変換する" %}}
任意のスプレッドシートを読み込み、使用中にWord DOCX & PowerPoint PPTXファイルに変換することが可能です。[Docx保存オプション](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [Pptx保存オプション](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/)以下に示すようにクラスがあります。
{{% blocks/products/pf/feature-page-code h3="Excel から Word への変換と PowerPoint への変換のための PHP コード" %}}
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
