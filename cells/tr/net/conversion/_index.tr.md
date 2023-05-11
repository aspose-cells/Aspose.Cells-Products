---
title:  Microsoft C# aracılığıyla Excel Dosya Dönüştürme
description: Yalnızca birkaç satırlık C# koduyla Excel XLS, XLSX, ODS, CSV'i PDF, XPS, HTML, JPEG, HTML ve diğer birçok popüler biçime dönüştürün .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Biçim Dönüştürme via .NET" h2="Excel dosyalarını elektronik tablo, web, resim ve sabit mizanpaj biçimleri olarak içe ve dışa aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel Kitaplığı, XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 0761934 gibi popüler biçimleri desteklerken elektronik tablo programlama ve dönüştürme işlemlerini hızlandırır 81. Excel dosyalarının PDF, XPS, HTML, MHTML, Düz olarak dışa aktarılmasına da izin verir. TIFF, JPG, PNG, BMP ve SVG gibi metin ve popüler resim biçimleri.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel\'i XLSX, ODS, SXC ve FODS\'e dönüştürün" %}}
 Elektronik tablo biçiminin karşılıklı dönüştürülmesi, yalnızca bir elektronik tablonun örneğinin yüklenmesini gerektirir.[Çalışma kitabı](https://reference.aspose.com/cells/net/aspose.cells/workbook) ve uygun değeri seçerek istenen formatta geri kaydetme[Biçimi Kaydet](https://reference.aspose.com/cells/net/aspose.cells/saveformat) numaralandırma.
{{% blocks/products/pf/feature-page-code h3="C# Excel Dosya Biçimi Dönüştürme Kodu" %}}

```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xls");
// save as XLSX, ODS, SXC & FODS formats
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel\'i PDF, XPS, HTML ve MD\'ye dönüştürün" %}}
 Aşağıdakiler gibi belirli çıktı biçimleri için dönüştürme sürecini kontrol etmek için özel sınıflar mevcuttur:[PdfKaydetmeSeçenekleri](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) Excel dosyalarını PDF olarak dışa aktarmak için,[XpsSaveSeçenekleri](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) Excel'den XPS'e dönüştürme için,[HtmlKaydetme Seçenekleri](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) Excel'i HTML olarak işlemek ve[MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) Excel'den Markdown'a dönüştürme için.
{{% blocks/products/pf/feature-page-code h3="C# Excel\'den PDF\'e Kod ve Web Formatları" %}}

```cs
// load template Excel file from disc
var book = new Aspose.Cells.Workbook("template.xlsx");
// save Excel in PDF/A-1a format
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// save Excel in XPS with 1 page per worksheet
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// save Excel in HTML with images as Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// save Excel in Markdown (MD) while retaining cell formatting
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON\'i Excel\'e ve Excel\'i JSON\'e dönüştürün" %}}
 JSON verileri bir örneğine alınabilir[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) yardımıyla sınıf[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) daha fazla işleme veya desteklenen biçimlerden herhangi birine basit dönüştürme için. Benzer şekilde,[Çalışma kağıdı](https://reference.aspose.com/cells/net/aspose.cells/worksheet) oluşturularak veriler JSON olarak dışa aktarılabilir.[Menzil](https://reference.aspose.com/cells/net/aspose.cells/range) veya hücreler ve arama[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) yöntem.
{{% blocks/products/pf/feature-page-code h3="C# JSON\'den Excel\'e Dönüştürme Kodu" %}}
```cs
// create a Workbook object
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// read JSON data from file
string jsonInput = File.ReadAllText("Data.json");
// set JsonLayoutOptions to treat Arrays as Table
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// import JSON data to worksheet starting at cell A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// save resultant file in XLSX format
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kodu Excel\'den JSON\'e Dönüştürme" %}}
```cs
// load XLSX file with an instance of Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// access CellsCollection of the worksheet containing data to be converted
var cells = workbook.Worksheets[0].Cells;
// create & set ExportRangeToJsonOptions for advanced options
var exportOptions = new Utility.ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// export range as JSON data
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// write data file to disc in JSON format
System.IO.File.WriteAllText("output.json", jsonData); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfalarını JPG, BMP, PNG ve GIF\'e Dönüştür" %}}
 Bir Excel dosyasının her çalışma sayfası, program tarafından ayarlanan farklı görüntü biçimlerine dönüştürülebilir.[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) mülk. Varsayılan değer `ImageFormat.Bmp`'dir.
{{% blocks/products/pf/feature-page-code h3="C# Excel\'den Görüntüye Dönüştürme Kodu" %}}
```cs
// load template spreadsheet
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// create & set an instance of ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// set output image format
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// create SheetRender for first worksheet in the collection
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// render worksheet to image
render.ToImage(0, "output.jpg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Excel\'i Word\'e Dönüştür & PowerPoint" %}}
 Kullanırken herhangi bir elektronik tabloyu yüklemek ve Word DOCX & PowerPoint PPTX dosyalarına dönüştürmek mümkündür.[DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) aşağıda gösterildiği gibi sınıflar.
{{% blocks/products/pf/feature-page-code h3="Excel\'den Word\'e ve PowerPoint\'e Dönüştürme için C# kodu" %}}
```cs
// load the template file
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// save spreadsheet as DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// save spreadsheet as PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
