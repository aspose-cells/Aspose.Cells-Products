---
title: Python aracılığıyla Microsoft Excel Dosya Dönüştürme 
url: /tr/python/conversion/
description: Yalnızca birkaç satır Python koduyla Excel XLS, XLSX, ODS, CSV'yi PDF, XPS, HTML, JPEG, HTML ve diğer birçok popüler biçime dönüştürün.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python aracılığıyla Microsoft<sup>&reg;</sup> Excel Format Dönüştürme" h2="Excel dosyalarını elektronik tablo, web, resim ve sabit düzen biçimleri olarak içe ve dışa aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Excel Kitaplığı, XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS gibi popüler biçimleri desteklerken elektronik tablo programlama ve dönüştürme işlemlerini hızlandırır. Ayrıca Excel dosyalarını PDF, XPS, HTML, MHTML, Düz Metin ve TIFF, JPG, PNG, BMP ve SVG gibi popüler görüntü formatlarına aktarmanıza olanak tanır.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel\'i XLSX, ODS, SXC ve FODS\'ye dönüştürün" %}}
E-tablo formatının inter-dönüşümü, yalnızca bir e-tablonun örneğinin bulunduğu bir e-tablonun yüklenmesini gerektirir. [Çalışma kitabı](https://apireference.aspose.com/cells/python/asposecells.api/Workbook) ve uygun değeri seçerken istenen formatta geri kaydetme [Kaydet Formatı](https://apireference.aspose.com/cells/python/asposecells.api/saveformat) numaralandırma.
{{% blocks/products/pf/feature-page-code h3="Python Excel Dosya Biçimi Dönüştürme Kodu" %}}

```cs
// şablon dosyasını yükleyin
workbook = Workbook("Book1.xls")
  
// XLSX, ODS, SXC ve FODS formatları olarak kaydedin
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel\'i PDF, XPS, HTML ve MD\'ye dönüştürün" %}}
Aşağıdakiler gibi belirli çıktı biçimleri için dönüştürme sürecini kontrol etmek için özel sınıflar mevcuttur. [PdfSaveSeçenekleri](https://apireference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) Excel dosyalarını PDF olarak dışa aktarmak için, [XpsSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) Excel'den XPS'ye dönüştürme için, [HtmlSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) Excel'i HTML olarak işlemek ve [MarkdownSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) Excel'den Markdown'a dönüştürme. 
{{% blocks/products/pf/feature-page-code h3="Python Excel\'den PDF\'ye ve Web Formatları için Kod" %}}

```cs
// diskten şablon Excel dosyasını yükle
book = Workbook("template.xlsx")

// Excel'i PDF_A_1_B biçiminde kaydedin
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// Excel'i çalışma sayfası başına 1 sayfa olacak şekilde XPS'e kaydedin
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// Excel'i HTML'de görüntülerle Base64 olarak kaydedin
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// hücre biçimlendirmesini korurken Excel'i Markdown'da (MD) kaydedin
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON\'u Excel\'e ve Excel\'i JSON\'a Dönüştür" %}}
Python geliştiricileri, yalnızca birkaç satır kodla JSON dosyalarını kolayca yükleyebilir ve Excel'e dönüştürebilir. Benzer şekilde, Excel verileri JSON verilerine aktarılabilir.
{{% blocks/products/pf/feature-page-code h3="Python JSON\'dan Excel\'e Dönüştürme Kodu" %}}
```cs
//Kaynak json dosyanızı yükleyin
workbook = Workbook("Data.json")
//dosyayı xlsx biçiminde kaydet
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Excel\'den JSON\'a Dönüştürme Kodu" %}}
```cs
//Kaynak xlsx dosyanızı yükleyin
workbook = Workbook("input.xlsx")
//dosyayı json formatına kaydet
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfalarını JPG, BMP, PNG ve GIF\'e Dönüştürün" %}}
Bir Excel dosyasının her çalışma sayfası farklı görüntü biçimlerine dönüştürülebilir, çağrı [ResimVeyaYazdırSeçenekleri](https://apireference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat görüntü biçimini ayarlamak için. 
{{% blocks/products/pf/feature-page-code h3="Python Excel\'den Görüntüye Dönüştürme Kodu" %}}
```cs
// şablon elektronik tablosunu yükle
workbook = Workbook("template.xlsx")
// ImageOrPrintOptions örneğini oluştur ve ayarla
options = ImageOrPrintOptions()
// çıktı görüntü biçimini ayarla
options.setImageFormat(ImageFormat.getPng())
// koleksiyondaki ilk çalışma sayfası için SheetRender oluşturun
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// çalışma sayfasını resme dönüştür
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Excel\'i Word ve PowerPoint\'e Dönüştürün" %}}
Kullanırken herhangi bir elektronik tabloyu yüklemek ve Word DOCX ve PowerPoint PPTX dosyalarına dönüştürmek mümkündür. [DocxSaveOptions](https://apireference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSaveSeçenekleri](https://apireference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) aşağıda gösterildiği gibi sınıflar.
{{% blocks/products/pf/feature-page-code h3="Excel\'den Word\'e ve PowerPoint\'e Dönüştürme için Python kodu" %}}
```cs
// şablon dosyasını yükleyin
workbook = Workbook("template.xlsx")

// elektronik tabloyu DOCX olarak kaydet
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// elektronik tabloyu PPTX olarak kaydet
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}