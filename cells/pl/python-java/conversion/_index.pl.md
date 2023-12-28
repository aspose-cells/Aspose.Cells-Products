---
title: Microsoft Konwersja plików Excel przy użyciu Python via Java
description: Aspose.Cells for Python via Java biblioteka. Konwertuj EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL i inne formaty za pomocą zaledwie kilku linii kodu Python.
keywords: [Python Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Python]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konwersja formatu Excel za pośrednictwem Python" h2="Importuj i eksportuj pliki Excel w formacie arkusza kalkulacyjnego, Internetu, obrazu i formatu o stałym układzie" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Biblioteka Excel przyspiesza programowanie arkuszy kalkulacyjnych i procesy konwersji, obsługując jednocześnie popularne formaty, w tym XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS Umożliwia także eksport plików Excel do numerów PDF, XPS, HTML, MHTML, Zwykły Tekst i popularne formaty obrazów, takie jak TIFF, JPG, PNG, BMP i SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na XLSX, ODS, SXC i FODS" %}}
 Wzajemna konwersja formatu arkusza kalkulacyjnego wymaga jedynie załadowania arkusza kalkulacyjnego z instancją[zeszyt ćwiczeń](https://reference.aspose.com/cells/python/asposecells.api/Workbook) i zapisz ponownie w żądanym formacie, wybierając odpowiednią wartość z[ZapiszFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) wyliczenie.
{{% blocks/products/pf/feature-page-code h3="Python Kod do konwersji formatu pliku Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konwertuj Excel na PDF, XPS, HTML i MD" %}}
 Dostępne są wyspecjalizowane klasy kontrolujące proces konwersji dla określonych formatów wyjściowych, takich jak[Opcje zapisywania PDF](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) aby wyeksportować pliki Excel pod numerem PDF,[Opcje XpsSave](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) dla konwersji Excela na XPS,[Opcje HTMLSave](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) aby renderować Excel jako HTML i[Opcje zapisywania Markdown](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) do konwersji Excela na Markdown.
{{% blocks/products/pf/feature-page-code h3="Python Kod dla programu Excel do PDF i formatów internetowych" %}}

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
Programiści Python mogą z łatwością ładować i konwertować pliki JSON do Excela za pomocą zaledwie kilku linijek kodu. Podobnie dane Excel można wyeksportować do danych JSON.
{{% blocks/products/pf/feature-page-code h3="Python Kod do konwersji JSON na Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kod dla programu Excel do konwersji JSON" %}}
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
 Każdy arkusz pliku Excel można przekonwertować na różne formaty obrazów, zadzwoń[Opcje obrazu lub wydruku](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat, aby ustawić format obrazu.
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
Możliwe jest załadowanie dowolnego arkusza kalkulacyjnego i konwersja go do plików Word DOCX i PowerPoint PPTX podczas korzystania[Opcje DocxSave](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [Opcje PptxSave](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) klas, jak pokazano poniżej.
{{% blocks/products/pf/feature-page-code h3="Kod Python dla programu Excel do Word i konwersji PowerPoint" %}}
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
