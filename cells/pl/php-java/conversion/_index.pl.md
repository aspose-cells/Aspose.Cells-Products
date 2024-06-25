---
title: Microsoft Konwersja plików Excel przy użyciu PHP via Java
description: Aspose.Cells for PHP via Java biblioteka. Konwertuj EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL i inne formaty za pomocą zaledwie kilku linii kodu PHP.
keywords: [PHP Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in PHP]
---
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header-php-java h1="Microsoft<sup>&reg;</sup> Konwersja formatu Excel przez PHP" h2="Importuj i eksportuj pliki Excel w formacie arkusza kalkulacyjnego, Internetu, obrazu i formatu o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
Biblioteka PHP Excel przyspiesza procesy programowania i konwersji arkuszy kalkulacyjnych, obsługując popularne formaty, w tym XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Umożliwia także eksport plików Excel do PDF, XPS, HTML, MHTML, zwykły Tekst i popularne formaty obrazów, takie jak TIFF, JPG, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na XLSX, ODS, SXC i FODS za pomocą PHP" %}}
 Wzajemna konwersja formatu arkusza kalkulacyjnego wymaga jedynie załadowania arkusza kalkulacyjnego z instancją[zeszyt ćwiczeń](https://reference.aspose.com/cells/php/aspose.cells/Workbook) i zapisz ponownie w żądanym formacie, wybierając odpowiednią wartość z[ZapiszFormat](https://reference.aspose.com/cells/php/aspose.cells/SaveFormat) wyliczenie.
{{% blocks/products/pf/feature-page-code h3="Kod PHP do konwersji formatu pliku Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na PDF, XPS, HTML i MD za pomocą PHP" %}}
 Dostępne są wyspecjalizowane klasy kontrolujące proces konwersji dla określonych formatów wyjściowych, takich jak[Opcje zapisywania PDF](https://reference.aspose.com/cells/php/aspose.cells/PdfSaveOptions/)aby wyeksportować pliki Excel pod numerem PDF,[Opcje XpsSave](https://reference.aspose.com/cells/php/aspose.cells/XpsSaveOptions/) dla konwersji Excela na XPS,[Opcje HTMLSave](https://reference.aspose.com/cells/php/aspose.cells/HtmlSaveOptions/) aby renderować Excel jako HTML i[Opcje zapisywania Markdown](https://reference.aspose.com/cells/php/aspose.cells/MarkdownSaveOptions/) do konwersji Excela na Markdown.
{{% blocks/products/pf/feature-page-code h3="Kod PHP dla programu Excel do PDF i formatów internetowych" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konwertuj JSON na Excel i Excel na JSON za pomocą PHP" %}}
Programiści PHP mogą z łatwością ładować i konwertować pliki JSON do Excela za pomocą zaledwie kilku linijek kodu. Podobnie dane Excel można wyeksportować do danych JSON.
{{% blocks/products/pf/feature-page-code h3="Kod PHP dla konwersji JSON na Excel" %}}

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

{{% blocks/products/pf/feature-page-code h3="Kod PHP dla programu Excel do konwersji JSON" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konwertuj arkusze programu Excel na JPG, BMP, PNG i GIF za pomocą PHP" %}}
 Każdy arkusz pliku Excel można przekonwertować na różne formaty obrazów, zadzwoń[Opcje obrazu lub wydruku](https://reference.aspose.com/cells/php/aspose.cells/ImageOrPrintOptions/) .setImageFormat, aby ustawić format obrazu.
{{% blocks/products/pf/feature-page-code h3="Kod PHP do konwersji programu Excel na obraz" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na Word i PowerPoint za pomocą PHP" %}}
Możliwe jest załadowanie dowolnego arkusza kalkulacyjnego i konwersja go do plików Word DOCX i PowerPoint PPTX podczas korzystania[Opcje DocxSave](https://reference.aspose.com/cells/php/aspose.cells/DocxSaveOptions/) & [Opcje PptxSave](https://reference.aspose.com/cells/php/aspose.cells/PptxSaveOptions/) klas, jak pokazano poniżej.
{{% blocks/products/pf/feature-page-code h3="Kod PHP dla Excela do Worda i konwersji PowerPoint" %}}
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
