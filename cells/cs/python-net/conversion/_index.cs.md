---
title: Microsoft Převod souborů Excel pomocí Python via NET
description: Aspose.Cells for Python prostřednictvím knihovny NET. Převeďte formáty EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL a další formáty s několika řádky kódu Python.
keywords: [Python Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Python]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Převod formátu Excel přes Python" h2="Importujte a exportujte soubory Excel jako tabulkový procesor, web, obrázky a formáty s pevným rozložením" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Knihovna Excel zrychluje programování tabulek a procesy převodu a zároveň podporuje oblíbené formáty včetně XLS, XLSX, XLSM, XLSB, XLTX, 076163181, 076163181, 76163481, 1733 07648 81. Umožňuje také exportovat soubory Excel do PDF, XPS, HTML, MHTML, Plain Textové a oblíbené formáty obrázků, jako jsou TIFF, JPG, PNG, BMP a SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Převést Excel na XLSX, ODS, SXC a FODS" %}}
 Vzájemná konverze formátu tabulky vyžaduje pouze načtení tabulky s instancí[pracovní sešit](https://reference.aspose.com/cells/python-net/aspose.cells/workbook/) a uložení zpět v požadovaném formátu při výběru vhodné hodnoty z[UložitFormát](https://reference.aspose.com/cells/python-net/aspose.cells/saveformat/) výčet.
{{% blocks/products/pf/feature-page-code h3="Python Kód pro převod formátu souboru Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Převést Excel na PDF, XPS, HTML a MD" %}}
 K dispozici jsou specializované třídy pro řízení procesu převodu pro konkrétní výstupní formáty, jako je např[Možnosti PdfSave](https://reference.aspose.com/cells/python-net/aspose.cells/pdfsaveoptions/) exportovat soubory Excel jako PDF,[XpsSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/xpssaveoptions/) pro převod Excel na XPS,[HtmlSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/htmlsaveoptions/) vykreslit Excel jako HTML a[MarkdownSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/markdownsaveoptions/) pro převod Excel na Markdown.
{{% blocks/products/pf/feature-page-code h3="Python Kód pro Excel na PDF a webové formáty" %}}

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

{{% blocks/products/pf/feature-page-section h2="Převeďte JSON na Excel a Excel na JSON" %}}
Python vývojáři mohou snadno načíst a převést soubory JSON do Excelu v několika řádcích kódu. Podobně lze data aplikace Excel exportovat do dat JSON.
{{% blocks/products/pf/feature-page-code h3="Python Kód pro převod JSON na Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kód pro Excel na JSON Převod" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Převést pracovní listy aplikace Excel do formátu JPG, BMP, PNG a GIF" %}}
 Každý list souboru Excel lze převést do různých obrazových formátů, volejte[ImageOrPrintOptions](https://reference.aspose.com/cells/python-net/aspose.cells.rendering/imageorprintoptions/).setImageFormat pro nastavení formátu obrázku.
{{% blocks/products/pf/feature-page-code h3="Python Kód pro převod Excelu na obrázek" %}}
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

{{% blocks/products/pf/feature-page-section h2="Převeďte Excel do Wordu a PowerPoint" %}}
Je možné načíst jakoukoli tabulku a převést ji na soubory Word DOCX a PowerPoint PPTX při používání[DocxSaveOptions](https://reference.aspose.com/cells/python-net/aspose.cells/docxsaveoptions/) & [Možnosti PptxSave](https://reference.aspose.com/cells/python-net/aspose.cells/pptxsaveoptions/) třídy, jak je ukázáno níže.
{{% blocks/products/pf/feature-page-code h3="Python kód pro Excel do Wordu a PowerPoint převod" %}}
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
