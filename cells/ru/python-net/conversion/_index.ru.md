---
title: Microsoft Преобразование файлов Excel с помощью Python via NET
description: Aspose.Cells for Python через библиотеку NET. Конвертируйте форматы EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL и другие с помощью всего нескольких строк кода Python.
keywords: [Python Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Python]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Преобразование формата Excel через Python" h2="Импортируйте и экспортируйте файлы Excel в форматах электронных таблиц, веб-страниц, изображений и с фиксированным макетом." >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Библиотека Excel ускоряет процессы программирования и преобразования электронных таблиц, поддерживая популярные форматы, включая XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07619348 1. Он также позволяет экспортировать файлы Excel в PDF, XPS, HTML, MHTML, Plain. Текстовые и популярные форматы изображений, такие как TIFF, JPG, PNG, BMP и SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Преобразуйте Excel в XLSX, ODS, SXC и FODS." %}}
 Для взаимного преобразования формата электронной таблицы требуется только загрузка электронной таблицы с экземпляром[Рабочая тетрадь](https://reference.aspose.com/cells/python-net/aspose.cells/workbook/) и сохранить обратно в желаемом формате, выбрав подходящее значение из[СохранитьФормат](https://reference.aspose.com/cells/python-net/aspose.cells/saveformat/) перечисление.
{{% blocks/products/pf/feature-page-code h3="Python Код для преобразования формата файла Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Преобразование Excel в PDF, XPS, HTML и MD" %}}
 Доступны специализированные классы для управления процессом преобразования для определенных выходных форматов, таких как[PDFSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/pdfsaveoptions/) для экспорта файлов Excel как PDF,[XpsSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/xpssaveoptions/) для преобразования Excel в XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/htmlsaveoptions/) для отображения Excel как HTML и[МаркдаунСохранитьПараметры](https://reference.aspose.com/cells/python-net/aspose.cells/markdownsaveoptions/) для преобразования Excel в Markdown.
{{% blocks/products/pf/feature-page-code h3="Python Код для Excel для PDF и веб-форматов" %}}

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

{{% blocks/products/pf/feature-page-section h2="Преобразовать JSON в Excel и Excel в JSON" %}}
Разработчики Python могут легко загружать и конвертировать файлы JSON в Excel всего за несколько строк кода. Аналогичным образом данные Excel можно экспортировать в данные JSON.
{{% blocks/products/pf/feature-page-code h3="Python Код для преобразования JSON в Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Код Python для преобразования Excel в JSON" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Преобразование листов Excel в JPG, BMP, PNG и GIF" %}}
 Каждый лист файла Excel можно преобразовать в разные форматы изображений, позвоните[Параметры изображения или печати](https://reference.aspose.com/cells/python-net/aspose.cells.rendering/imageorprintoptions/).setImageFormat для установки формата изображения.
{{% blocks/products/pf/feature-page-code h3="Python Код для преобразования Excel в изображения" %}}
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

{{% blocks/products/pf/feature-page-section h2="Конвертировать Excel в Word и PowerPoint" %}}
Можно загрузить любую электронную таблицу и преобразовать ее в файлы Word DOCX и PowerPoint PPTX при использовании[Параметры сохранения документа](https://reference.aspose.com/cells/python-net/aspose.cells/docxsaveoptions/) & [PptxSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/pptxsaveoptions/) классы, как показано ниже.
{{% blocks/products/pf/feature-page-code h3="Код Python для преобразования Excel в Word и PowerPoint" %}}
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
