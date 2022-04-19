---
title: "Microsoft Excel fájlkonverzió a következőn keresztül: Python "
url: /hu/python/conversion/
description: Konvertálja az Excel XLS-t, XLSX-et, ODS-t, CSV-t PDF-, XPS-, HTML-, JPEG-, HTML- és sok más népszerű formátumba mindössze néhány soros Python-kóddal.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel formátum konvertálása a következőn keresztül: Python" h2="Excel-fájlok importálása és exportálása táblázat-, web-, kép- és rögzített elrendezésű formátumokba" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Az Excel Library felgyorsítja a táblázatkezelő programozási és átalakítási folyamatokat, miközben támogatja az olyan népszerű formátumokat, mint az XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Lehetővé teszi Excel fájlok exportálását PDF, XPS, HTML, MHTML, egyszerű szöveg és olyan népszerű képformátumokba, mint a TIFF, JPG, PNG, BMP és SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Az Excel konvertálása XLSX, ODS, SXC és FODS formátumba" %}}
A táblázatformátumok közötti konvertáláshoz csak egy példányt tartalmazó táblázatot kell betölteni [Munkafüzet](https://apireference.aspose.com/cells/python/asposecells.api/Workbook) és visszamenti a kívánt formátumba, miközben kiválasztja a megfelelő értéket [SaveFormat](https://apireference.aspose.com/cells/python/asposecells.api/saveformat) felsorolás.
{{% blocks/products/pf/feature-page-code h3="Python Kód az Excel fájlformátum konvertálásához" %}}

```cs
// töltse be a sablonfájlt
workbook = Workbook("Book1.xls")
  
// mentse XLSX, ODS, SXC és FODS formátumban
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Az Excel konvertálása PDF, XPS, HTML és MD formátumba" %}}
Speciális osztályok állnak rendelkezésre az átalakítási folyamat vezérlésére meghatározott kimeneti formátumokhoz, mint pl [PdfSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) Excel fájlok PDF formátumban történő exportálásához, [XpsSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) az Excel XPS konvertáláshoz, [HtmlSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) hogy az Excel HTML-ként jelenjen meg és [MarkdownSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) az Excelből Markdown konvertáláshoz. 
{{% blocks/products/pf/feature-page-code h3="Python Kód az Excel PDF- és webformátumokhoz" %}}

```cs
// sablon Excel fájl betöltése a lemezről
book = Workbook("template.xlsx")

// mentse az Excelt PDF_A_1_B formátumba
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// mentse az Excelt XPS-ben munkalaponként 1 oldallal
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// mentse az Excelt HTML-be képekkel Base64-ként
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// mentse az Excelt a Markdown (MD) programba, miközben megtartja a cellaformázást
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja a JSON-t Excel-be, az Excelt pedig JSON-ba" %}}
A(z) Python fejlesztői egyszerűen betölthetik és konvertálhatják a JSON-fájlokat Excel-be, mindössze néhány sornyi kóddal. Hasonlóképpen, az Excel-adatok exportálhatók JSON-adatokba.
{{% blocks/products/pf/feature-page-code h3="Python Kód a JSON-ból Excel-be való konvertáláshoz" %}}
```cs
//Töltse be a forrás json fájlt
workbook = Workbook("Data.json")
//mentse a fájlt xlsx formátumba
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kód az Excel JSON-ba konvertálásához" %}}
```cs
//Töltse be a forrás xlsx fájlt
workbook = Workbook("input.xlsx")
//mentse a fájlt json formátumba
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertálja az Excel munkalapokat JPG, BMP, PNG és GIF formátumba" %}}
Egy Excel-fájl minden munkalapja konvertálható különböző képformátumokba, hívja [ImageOrPrintOptions](https://apireference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat a képformátum beállításához. 
{{% blocks/products/pf/feature-page-code h3="Python Kód az Excel képpé konvertálásához" %}}
```cs
// sablon táblázat betöltése
workbook = Workbook("template.xlsx")
// hozzon létre és állítson be egy ImageOrPrintOptions példányt
options = ImageOrPrintOptions()
// állítsa be a kimeneti képformátumot
options.setImageFormat(ImageFormat.getPng())
// Hozzon létre SheetRendert a gyűjtemény első munkalapjához
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// munkalapot képpé renderelni
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Az Excel konvertálása Word és PowerPoint formátumba" %}}
Lehetőség van bármilyen táblázat betöltésére és Word DOCX és PowerPoint PPTX fájlokká konvertálására használat közben. [DocxSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) osztályok alább bemutatott módon.
{{% blocks/products/pf/feature-page-code h3="Python kód az Excel Word és PowerPoint konvertáláshoz" %}}
```cs
// töltse be a sablonfájlt
workbook = Workbook("template.xlsx")

// mentse a táblázatot DOCX-ként
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// mentse a táblázatot PPTX-ként
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}