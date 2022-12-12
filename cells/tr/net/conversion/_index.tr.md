---
title: C# aracılığıyla Microsoft Excel Dosya Dönüştürme 

description: Yalnızca birkaç satır C# koduyla Excel XLS, XLSX, ODS, CSV'yi PDF, XPS, HTML, JPEG, HTML ve diğer birçok popüler biçime dönüştürün.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1=".NET aracılığıyla Microsoft<sup>&reg;</sup> Excel Format Dönüştürme" h2="Excel dosyalarını elektronik tablo, web, resim ve sabit düzen biçimleri olarak içe ve dışa aktarın" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Excel Kitaplığı, XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS gibi popüler biçimleri desteklerken elektronik tablo programlama ve dönüştürme işlemlerini hızlandırır. Ayrıca Excel dosyalarını PDF, XPS, HTML, MHTML, Düz Metin ve TIFF, JPG, PNG, BMP ve SVG gibi popüler görüntü formatlarına aktarmanıza olanak tanır.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel\'i XLSX, ODS, SXC ve FODS\'ye dönüştürün" %}}
E-tablo formatının inter-dönüşümü, yalnızca bir e-tablonun örneğinin bulunduğu bir e-tablonun yüklenmesini gerektirir. [Çalışma kitabı](https://reference.aspose.com/cells/net/aspose.cells/workbook) ve uygun değeri seçerken istenen formatta geri kaydetme [Kaydet Formatı](https://reference.aspose.com/cells/net/aspose.cells/saveformat) numaralandırma.
{{% blocks/products/pf/feature-page-code h3="C# Excel Dosya Biçimi Dönüştürme Kodu" %}}

```cs
// şablon dosyasını yükleyin
var workbook = new Aspose.Cells.Workbook("template.xls");
// XLSX, ODS, SXC ve FODS formatları olarak kaydedin
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel\'i PDF, XPS, HTML ve MD\'ye dönüştürün" %}}
Aşağıdakiler gibi belirli çıktı biçimleri için dönüştürme sürecini kontrol etmek için özel sınıflar mevcuttur. [PdfSaveSeçenekleri](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) Excel dosyalarını PDF olarak dışa aktarmak için, [XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) Excel'den XPS'ye dönüştürme için, [HtmlSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) Excel'i HTML olarak işlemek ve [MarkdownSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) Excel'den Markdown'a dönüştürme. 
{{% blocks/products/pf/feature-page-code h3="C# Excel\'den PDF\'ye ve Web Formatları için Kod" %}}

```cs
// diskten şablon Excel dosyasını yükle
var book = new Aspose.Cells.Workbook("template.xlsx");
// Excel'i PDF/A-1a formatında kaydedin
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// Excel'i çalışma sayfası başına 1 sayfa olacak şekilde XPS'e kaydedin
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// Excel'i HTML'de görüntülerle Base64 olarak kaydedin
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// hücre biçimlendirmesini korurken Excel'i Markdown'da (MD) kaydedin
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON\'u Excel\'e ve Excel\'i JSON\'a Dönüştür" %}}
JSON verileri bir örneğine aktarılabilir [Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) yardımıyla sınıf [JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) daha fazla işleme veya desteklenen formatlardan herhangi birine basit dönüştürme için. Benzer şekilde, [Çalışma kağıdı](https://reference.aspose.com/cells/net/aspose.cells/worksheet) veriler oluşturularak JSON olarak dışa aktarılabilir. [Menzil](https://reference.aspose.com/cells/net/aspose.cells/range) veya hücreler ve arama [JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) yöntem.
{{% blocks/products/pf/feature-page-code h3="C# JSON\'dan Excel\'e Dönüştürme Kodu" %}}
```cs
// bir Çalışma Kitabı nesnesi oluştur
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// dosyadan JSON verilerini oku
string jsonInput = File.ReadAllText("Data.json");
// JsonLayoutOptions'ı Dizileri Tablo olarak ele alacak şekilde ayarlayın
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// A1 hücresinden başlayarak JSON verilerini çalışma sayfasına aktarın
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// sonuçtaki dosyayı XLSX formatında kaydedin
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Excel\'den JSON\'a Dönüştürme Kodu" %}}
```cs
// XLSX dosyasını bir Çalışma Kitabı örneğiyle yükleyin
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// dönüştürülecek verileri içeren çalışma sayfasının CellsCollection'ına erişin
var cells = workbook.Worksheets[0].Cells;
// gelişmiş seçenekler için ExportRangeToJsonOptions oluşturun ve ayarlayın
var exportOptions = new Utility.ExportRangeToJsonOptions();
// dışa aktarılacak verileri içeren bir hücre aralığı oluşturun
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// aralığı JSON verileri olarak dışa aktar
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// veri dosyasını JSON formatında diske yaz
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfalarını JPG, BMP, PNG ve GIF\'e Dönüştürün" %}}
Bir Excel dosyasının her çalışma sayfası, program tarafından belirlenen farklı görüntü biçimlerine dönüştürülebilir. [ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) Emlak. Varsayılan değer `ImageFormat.Bmp` şeklindedir.
{{% blocks/products/pf/feature-page-code h3="C# Excel\'den Görüntüye Dönüştürme Kodu" %}}
```cs
// şablon elektronik tablosunu yükle
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// ImageOrPrintOptions örneğini oluştur ve ayarla
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// çıktı görüntü biçimini ayarla
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// koleksiyondaki ilk çalışma sayfası için SheetRender oluşturun
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// çalışma sayfasını resme dönüştür
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Excel\'i Word ve PowerPoint\'e Dönüştürün" %}}
Kullanırken herhangi bir elektronik tabloyu yüklemek ve Word DOCX ve PowerPoint PPTX dosyalarına dönüştürmek mümkündür. [DocxSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSaveSeçenekleri](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) aşağıda gösterildiği gibi sınıflar.
{{% blocks/products/pf/feature-page-code h3="Excel\'den Word\'e ve PowerPoint\'e Dönüştürme için C# kodu" %}}
```cs
// şablon dosyasını yükleyin
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// elektronik tabloyu DOCX olarak kaydet
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// elektronik tabloyu PPTX olarak kaydet
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
