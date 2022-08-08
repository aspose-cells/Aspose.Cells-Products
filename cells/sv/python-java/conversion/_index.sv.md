---
title: Microsoft Excel-filkonvertering via Python 
url: /sv/python/conversion/
description: Konvertera Excel XLS, XLSX, ODS, CSV till PDF, XPS, HTML, JPEG, HTML och många andra populära format med bara några rader med Python-kod.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel-formatkonvertering via Python" h2="Importera och exportera Excel-filer som kalkylblad, webb, bild och format med fast layout" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel Library snabbar upp kalkylarksprogrammering och konverteringsprocesser samtidigt som det stöder populära format inklusive XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Det gör det också möjligt att exportera Excel-filer till PDF, XPS, HTML, MHTML, vanlig text och populära bildformat som TIFF, JPG, PNG, BMP och SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till XLSX, ODS, SXC & FODS" %}}
Interkonvertering av kalkylarksformat kräver bara att ett kalkylblad laddas med en instans av [Arbetsbok](https://reference.aspose.com/cells/python/asposecells.api/Workbook) och spara tillbaka i önskat format samtidigt som du väljer lämpligt värde från [SaveFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) uppräkning.
{{% blocks/products/pf/feature-page-code h3="Python Kod för konvertering av Excel-filformat" %}}

```cs
// ladda mallfilen
workbook = Workbook("Book1.xls")
  
// spara som XLSX-, ODS-, SXC- och FODS-format
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till PDF, XPS, HTML och MD" %}}
Specialiserade klasser finns tillgängliga för att styra konverteringsprocessen för specifika utdataformat som t.ex [PdfSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) för att exportera Excel-filer som PDF, [XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) för konvertering av Excel till XPS, [HtmlSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) att rendera Excel som HTML och [MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) för Excel till Markdown-konvertering. 
{{% blocks/products/pf/feature-page-code h3="Python Kod för Excel till PDF- och webbformat" %}}

```cs
// ladda mall Excel-fil från skiva
book = Workbook("template.xlsx")

// spara Excel i formatet PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// spara Excel i XPS med 1 sida per kalkylblad
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// spara Excel i HTML med bilder som Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// spara Excel i Markdown (MD) samtidigt som du behåller cellformateringen
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera JSON till Excel & Excel till JSON" %}}
Python-utvecklare kan enkelt ladda och konvertera JSON-filer till Excel på bara några rader kod. På samma sätt kan Excel-data exporteras till JSON-data.
{{% blocks/products/pf/feature-page-code h3="Python Kod för JSON till Excel-konvertering" %}}
```cs
//Ladda din käll-json-fil
workbook = Workbook("Data.json")
//spara filen i xlsx-format
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kod för Excel till JSON-konvertering" %}}
```cs
//Ladda din käll-xlsx-fil
workbook = Workbook("input.xlsx")
//spara filen i json-format
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel-kalkylblad till JPG, BMP, PNG och GIF" %}}
Varje kalkylblad i en Excel-fil kan konverteras till olika bildformat, ring [ImageOrPrintOptions](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat för att ställa in bildformatet. 
{{% blocks/products/pf/feature-page-code h3="Python Kod för konvertering av Excel till bild" %}}
```cs
// ladda mallkalkylblad
workbook = Workbook("template.xlsx")
// skapa och ange en instans av ImageOrPrintOptions
options = ImageOrPrintOptions()
// ställ in bildformat för utdata
options.setImageFormat(ImageFormat.getPng())
// skapa SheetRender för det första kalkylbladet i samlingen
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// rendera kalkylblad till bild
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertera Excel till Word & PowerPoint" %}}
Det är möjligt att ladda vilket kalkylblad som helst och konvertera det till Word DOCX- och PowerPoint PPTX-filer medan du använder det [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) klasser som visas nedan.
{{% blocks/products/pf/feature-page-code h3="Python-kod för konvertering av Excel till Word och PowerPoint" %}}
```cs
// ladda mallfilen
workbook = Workbook("template.xlsx")

// spara kalkylblad som DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// spara kalkylblad som PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}