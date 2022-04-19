---
title: Převod souborů Microsoft Excel prostřednictvím Python 
url: /cs/python/conversion/
description: Převeďte Excel XLS, XLSX, ODS, CSV do PDF, XPS, HTML, JPEG, HTML a mnoha dalších oblíbených formátů pomocí pouhých několika řádků kódu Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konverze formátu Microsoft<sup>&reg;</sup> Excel prostřednictvím Python" h2="Importujte a exportujte soubory Excel jako tabulkový procesor, web, obrázky a formáty s pevným rozložením" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Knihovna Excel urychluje programování tabulek a procesy převodu a zároveň podporuje oblíbené formáty včetně XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Umožňuje také exportovat soubory Excel do PDF, XPS, HTML, MHTML, prostého textu a populárních obrazových formátů, jako jsou TIFF, JPG, PNG, BMP a SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Převeďte Excel do XLSX, ODS, SXC & FODS" %}}
Vzájemná konverze formátu tabulky vyžaduje pouze načtení tabulky s instancí [pracovní sešit](https://apireference.aspose.com/cells/python/asposecells.api/Workbook) a uložení zpět v požadovaném formátu při výběru vhodné hodnoty z [UložitFormát](https://apireference.aspose.com/cells/python/asposecells.api/saveformat) výčet.
{{% blocks/products/pf/feature-page-code h3="Python Kód pro převod formátu souboru aplikace Excel" %}}

```cs
// načtěte soubor šablony
workbook = Workbook("Book1.xls")
  
// uložit jako formáty XLSX, ODS, SXC a FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Převeďte Excel do PDF, XPS, HTML a MD" %}}
K dispozici jsou specializované třídy pro řízení procesu převodu pro konkrétní výstupní formáty, jako je např [Možnosti PdfSave](https://apireference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) exportovat soubory Excel jako PDF, [XpsSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) pro převod Excel na XPS, [HtmlSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) vykreslit Excel jako HTML a [MarkdownSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) pro převod Excel na Markdown. 
{{% blocks/products/pf/feature-page-code h3="Python Kód pro formáty Excel do PDF a webové" %}}

```cs
// načíst soubor šablony Excel z disku
book = Workbook("template.xlsx")

// uložit Excel ve formátu PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// uložit Excel v XPS s 1 stránkou na list
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// uložit Excel v HTML s obrázky jako Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// uložit Excel v Markdown (MD) při zachování formátování buněk
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte JSON na Excel a Excel na JSON" %}}
Vývojáři Python mohou snadno načíst a převést soubory JSON do Excelu pomocí několika řádků kódu. Podobně lze data z Excelu exportovat do dat JSON.
{{% blocks/products/pf/feature-page-code h3="Python Kód pro převod JSON do Excelu" %}}
```cs
//Načtěte zdrojový soubor json
workbook = Workbook("Data.json")
//uložit soubor ve formátu xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kód pro převod Excelu na JSON" %}}
```cs
//Načtěte zdrojový soubor xlsx
workbook = Workbook("input.xlsx")
//uložit soubor ve formátu json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte pracovní listy aplikace Excel do formátu JPG, BMP, PNG a GIF" %}}
Každý list souboru Excel lze převést do různých obrazových formátů, volejte [ImageOrPrintOptions](https://apireference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat pro nastavení formátu obrázku. 
{{% blocks/products/pf/feature-page-code h3="Python Kód pro převod Excelu na obrázek" %}}
```cs
// načíst šablonu tabulky
workbook = Workbook("template.xlsx")
// vytvořit a nastavit instanci ImageOrPrintOptions
options = ImageOrPrintOptions()
// nastavit výstupní formát obrázku
options.setImageFormat(ImageFormat.getPng())
// vytvořte SheetRender pro první list v kolekci
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// vykreslit pracovní list do obrázku
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Převeďte Excel do Wordu a PowerPointu" %}}
Při používání je možné načíst jakoukoli tabulku a převést ji na soubory Word DOCX & PowerPoint PPTX [DocxSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [Možnosti PptxSave](https://apireference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) třídy, jak je ukázáno níže.
{{% blocks/products/pf/feature-page-code h3="Python kód pro převod Excelu na Word a PowerPoint" %}}
```cs
// načtěte soubor šablony
workbook = Workbook("template.xlsx")

// uložit tabulku jako DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// uložit tabulku jako PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}