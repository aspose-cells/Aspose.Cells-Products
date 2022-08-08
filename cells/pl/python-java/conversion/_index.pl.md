---
title: Konwersja plików Microsoft Excel przez Python 
url: /pl/python/conversion/
description: Konwertuj Excel XLS, XLSX, ODS, CSV do PDF, XPS, HTML, JPEG, HTML i wielu innych popularnych formatów za pomocą zaledwie kilku linijek kodu Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwersja formatu Microsoft<sup>&reg;</sup> Excel przez Python" h2="Importuj i eksportuj pliki Excel jako arkusze kalkulacyjne, strony internetowe, obrazy i formaty o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Biblioteka Excela przyspiesza proces programowania i konwersji arkuszy kalkulacyjnych, jednocześnie obsługując popularne formaty, w tym XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Pozwala także eksportować pliki Excel do PDF, XPS, HTML, MHTML, Plain Text i popularnych formatów graficznych, takich jak TIFF, JPG, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na XLSX, ODS, SXC i FODS" %}}
Konwersja między formatami arkusza kalkulacyjnego wymaga tylko załadowania arkusza kalkulacyjnego z wystąpieniem [zeszyt ćwiczeń](https://reference.aspose.com/cells/python/asposecells.api/Workbook) i zapisywanie z powrotem w żądanym formacie przy wyborze odpowiedniej wartości z [Zapisz format](https://reference.aspose.com/cells/python/asposecells.api/saveformat) wyliczenie.
{{% blocks/products/pf/feature-page-code h3="Python Kod konwersji formatu pliku Excel" %}}

```cs
// załaduj plik szablonu
workbook = Workbook("Book1.xls")
  
// zapisz jako formaty XLSX, ODS, SXC i FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na PDF, XPS, HTML i MD" %}}
Dostępne są specjalistyczne klasy do kontrolowania procesu konwersji dla określonych formatów wyjściowych, takich jak [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) eksportować pliki Excel jako PDF, [XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) do konwersji programu Excel do XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) renderować Excel jako HTML i [MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) do konwersji programu Excel do Markdown. 
{{% blocks/products/pf/feature-page-code h3="Python Kod programu Excel do formatu PDF i internetowego" %}}

```cs
// wczytaj szablon pliku Excel z dysku
book = Workbook("template.xlsx")

// zapisz Excel w formacie PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// zapisz Excel w XPS z 1 stroną na arkusz
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// zapisz Excel w HTML z obrazami jako Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// zapisz Excel w Markdown (MD), zachowując formatowanie komórek
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj JSON na Excel i Excel na JSON" %}}
Python programiści mogą łatwo ładować i konwertować pliki JSON do programu Excel w zaledwie kilku wierszach kodu. Podobnie dane z Excela można wyeksportować do danych JSON.
{{% blocks/products/pf/feature-page-code h3="Python Kod konwersji JSON na Excel" %}}
```cs
//Załaduj swój źródłowy plik json
workbook = Workbook("Data.json")
//zapisz plik w formacie xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kod konwersji programu Excel do formatu JSON" %}}
```cs
//Załaduj źródłowy plik xlsx
workbook = Workbook("input.xlsx")
//zapisz plik w formacie json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj arkusze Excela na JPG, BMP, PNG i GIF" %}}
Każdy arkusz roboczy pliku Excel można przekonwertować na różne formaty obrazu, zadzwoń [Opcje obrazu lub wydruku](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat, aby ustawić format obrazu. 
{{% blocks/products/pf/feature-page-code h3="Python Kod programu Excel do konwersji obrazu" %}}
```cs
// załaduj arkusz kalkulacyjny szablonu
workbook = Workbook("template.xlsx")
// utwórz i ustaw instancję ImageOrPrintOptions
options = ImageOrPrintOptions()
// ustaw format obrazu wyjściowego
options.setImageFormat(ImageFormat.getPng())
// utwórz SheetRender dla pierwszego arkusza w kolekcji
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// wyrenderuj arkusz do obrazu
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na Word i PowerPoint" %}}
Podczas używania można załadować dowolny arkusz kalkulacyjny i przekonwertować go na pliki Word DOCX i PowerPoint PPTX [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [Opcje zapisu Pptx](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) klasy, jak pokazano poniżej.
{{% blocks/products/pf/feature-page-code h3="Python kod konwersji z programu Excel do programu Word i PowerPoint" %}}
```cs
// załaduj plik szablonu
workbook = Workbook("template.xlsx")

// zapisz arkusz kalkulacyjny jako DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// zapisz arkusz kalkulacyjny jako PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}