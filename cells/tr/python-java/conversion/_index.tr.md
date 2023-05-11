---
title: Microsoft Python via Java Kullanarak Excel Dosya Dönüştürme
description: Yalnızca birkaç satırlık Python koduyla Excel XLS, XLSX, ODS, CSV'i PDF, XPS, HTML, JPEG, HTML ve diğer birçok popüler biçime dönüştürün .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Python aracılığıyla Excel Biçim Dönüştürme" h2="Excel dosyalarını elektronik tablo, web, resim ve sabit mizanpaj biçimleri olarak içe ve dışa aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel Kitaplığı, XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 0761934 gibi popüler biçimleri desteklerken elektronik tablo programlama ve dönüştürme işlemlerini hızlandırır 81. Excel dosyalarının PDF, XPS, HTML, MHTML, Düz olarak dışa aktarılmasına da izin verir. TIFF, JPG, PNG, BMP ve SVG gibi metin ve popüler resim biçimleri.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel\'i XLSX, ODS, SXC ve FODS\'e dönüştürün" %}}
 Elektronik tablo biçiminin karşılıklı dönüştürülmesi, yalnızca bir elektronik tablonun örneğinin yüklenmesini gerektirir.[Çalışma kitabı](https://reference.aspose.com/cells/python/asposecells.api/Workbook) ve uygun değeri seçerek istenen formatta geri kaydetme[Biçimi Kaydet](https://reference.aspose.com/cells/python/asposecells.api/saveformat) numaralandırma.
{{% blocks/products/pf/feature-page-code h3="Python Excel Dosya Biçimi Dönüştürme Kodu" %}}

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


{{% blocks/products/pf/feature-page-section h2="Excel\'i PDF, XPS, HTML ve MD\'ye dönüştürün" %}}
 Aşağıdakiler gibi belirli çıktı biçimleri için dönüştürme sürecini kontrol etmek için özel sınıflar mevcuttur:[PdfKaydetmeSeçenekleri](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) Excel dosyalarını PDF olarak dışa aktarmak için,[XpsSaveSeçenekleri](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) Excel'den XPS'e dönüştürme için,[HtmlKaydetme Seçenekleri](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) Excel'i HTML olarak işlemek ve[MarkdownSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) Excel'den Markdown'a dönüştürme için.
{{% blocks/products/pf/feature-page-code h3="Python Excel\'den PDF\'e Kod ve Web Formatları" %}}

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

{{% blocks/products/pf/feature-page-section h2="JSON\'i Excel\'e ve Excel\'i JSON\'e dönüştürün" %}}
Python geliştiricileri, JSON dosyalarını yalnızca birkaç satır kodla kolayca yükleyebilir ve Excel'e dönüştürebilir. Benzer şekilde, Excel verileri JSON verilerine dışa aktarılabilir.
{{% blocks/products/pf/feature-page-code h3="Python JSON\'den Excel\'e Dönüştürme Kodu" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kodu Excel\'den JSON\'e Dönüştürme" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfalarını JPG, BMP, PNG ve GIF\'e Dönüştür" %}}
 Bir Excel dosyasının her çalışma sayfası farklı görüntü formatlarına dönüştürülebilir.[ResimVeyaBaskıSeçenekleri](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions) .setImageFormat görüntü biçimini ayarlamak için.
{{% blocks/products/pf/feature-page-code h3="Python Excel\'den Görüntüye Dönüştürme Kodu" %}}
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

{{% blocks/products/pf/feature-page-section h2="Excel\'i Word\'e Dönüştür & PowerPoint" %}}
 Kullanırken herhangi bir elektronik tabloyu yüklemek ve Word DOCX & PowerPoint PPTX dosyalarına dönüştürmek mümkündür.[DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) aşağıda gösterildiği gibi sınıflar.
{{% blocks/products/pf/feature-page-code h3="Excel\'den Word\'e ve PowerPoint\'e Dönüştürme için Python kodu" %}}
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
