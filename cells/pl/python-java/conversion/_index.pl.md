---
title: Microsoft Konwersja pliku programu Excel za pomocą Python via Java
description: Konwertuj Excel XLS, XLSX, ODS, CSV na PDF, XPS, HTML, JPEG, HTML i wiele innych popularnych formatów za pomocą zaledwie kilku linii kodu Python .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konwersja formatu Excel przez Python" h2="Importuj i eksportuj pliki Excel jako formaty arkuszy kalkulacyjnych, stron internetowych, obrazów i o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel Library przyspiesza procesy programowania i konwersji arkuszy kalkulacyjnych, jednocześnie obsługując popularne formaty, w tym XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 0761934 81. Umożliwia także eksport plików Excel na numery PDF, XPS, HTML, MHTML, zwykły Tekst i popularne formaty graficzne, takie jak TIFF, JPG, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na XLSX, ODS, SXC i FODS" %}}
 Wzajemna konwersja formatu arkusza kalkulacyjnego wymaga jedynie załadowania arkusza kalkulacyjnego z instancją[zeszyt ćwiczeń](https://reference.aspose.com/cells/python/asposecells.api/Workbook) i zapisywanie z powrotem w żądanym formacie, wybierając odpowiednią wartość z[ZapiszFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) wyliczenie.
{{% blocks/products/pf/feature-page-code h3="Python Kod do konwersji formatu pliku programu Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na PDF, XPS, HTML & MD" %}}
 Dostępne są wyspecjalizowane klasy do sterowania procesem konwersji dla określonych formatów wyjściowych, takich jak[PdfZapiszOpcje](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) eksportować pliki Excel jako PDF,[XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) do konwersji Excela na XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) renderować program Excel jako HTML i[Opcje zapisu Markdown](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) do konwersji Excela na Markdown.
{{% blocks/products/pf/feature-page-code h3="Python Kod programu Excel na numer PDF i formaty internetowe" %}}

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

{{% blocks/products/pf/feature-page-section h2="Konwertuj JSON na Excel i Excel na JSON" %}}
Programiści Python mogą łatwo ładować i konwertować pliki JSON do programu Excel w zaledwie kilku wierszach kodu. Podobnie dane programu Excel można wyeksportować do danych JSON.
{{% blocks/products/pf/feature-page-code h3="Python Kod do konwersji JSON do programu Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kod programu Excel do konwersji JSON" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj arkusze programu Excel na JPG, BMP, PNG i GIF" %}}
 Każdy arkusz kalkulacyjny pliku Excel można przekonwertować na różne formaty obrazów, zadzwoń[ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions) .setImageFormat, aby ustawić format obrazu.
{{% blocks/products/pf/feature-page-code h3="Python Kod do konwersji programu Excel na obraz" %}}
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

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na Word i PowerPoint" %}}
 Możliwe jest załadowanie dowolnego arkusza kalkulacyjnego i przekonwertowanie go na pliki Word DOCX & PowerPoint PPTX podczas używania[Opcje DocxSave](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [Opcje PptxSave](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions)klasy, jak pokazano poniżej.
{{% blocks/products/pf/feature-page-code h3="Python kod do konwersji programu Excel na Word i PowerPoint" %}}
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

{{< blocks/products/pf/feature-page-options pairs="xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx" >}}
