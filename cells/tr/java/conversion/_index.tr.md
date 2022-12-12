---
title: Java aracılığıyla Microsoft Excel Dosya Dönüştürme 

description: Yalnızca birkaç satır Java koduyla Excel XLS, XLSX, ODS, CSV'yi PDF, XPS, HTML, JPEG, HTML ve diğer birçok popüler biçime dönüştürün.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosyalarını Java ile Dönüştürme" h2="Microsoft Excel belgelerini elektronik tablo, web, resim ve sabit düzen biçimleri olarak kaydedin" >}}

{{% blocks/products/pf/feature-page-summary %}}
Herhangi bir **Excel dönüştürücü** uygulaması veya çözümü için Java Excel Kitaplığı, XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS dahil olmak üzere birden çok biçimi işlerken e-tablo programlama ve dönüştürme işlemlerini hızlandırır. Ayrıca **Excel dosyalarını PDF'ye**, XPS, HTML, MHTML, Düz Metin ve TIFF, JPG, PNG, BMP ve SVG gibi popüler görüntü formatlarına dönüştürmeye olanak tanır.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel Formatlarının Ara Dönüşümü" %}}
E-tablo formatının inter-dönüşümü, yalnızca bir e-tablonun örneğinin bulunduğu bir e-tablonun yüklenmesini gerektirir. [Çalışma kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ve uygun değeri seçerken istenen formatta geri kaydetme [Kaydet Formatı](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) numaralandırma.
{{% blocks/products/pf/feature-page-code h3="Java Excel Dosya Biçimi Dönüşümü için Örnek Kod" %}}

```cs
// kaynak dosyayı yükle
var wkb = new Workbook("sourceFile.xls");
// XLSX, ODS, SXC ve FODS formatları olarak kaydedin
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel\'i PDF, XPS, HTML ve MD\'ye dönüştürün" %}}
Aşağıdakiler gibi belirli çıktı biçimleri için dönüştürme sürecini kontrol etmek için özel sınıflar mevcuttur. [PdfSaveSeçenekleri](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) Excel dosyalarını PDF olarak dönüştürmek için, [XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) Excel'i XPS olarak dışa aktarmak için, [HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) Excel'i HTML olarak işlemek ve [MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) Excel'den Markdown'a dönüştürme. 
{{% blocks/products/pf/feature-page-code h3="Java Excel\'den PDF\'ye ve Web Formatları için Örnek Kod" %}}

```cs
// diskten şablon Excel dosyasını yükle
var bk = new Workbook("source-file.xlsx");

// Java kullanarak Excel'i PDF'ye dönüştürün
// PDF seçenekleri oluşturun
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// Excel'i XPS'e kaydet
bk.save("output.xps", new XpsSaveOptions());
// Excel'i HTML'ye kaydet
bk.save("output.html", new HtmlSaveOptions());
// Excel'i Markdown'a (MD) kaydedin
bk.save("output.md", new MarkdownSaveOptions());

// İlgili formata kaydetmeden önce ilgili kaydetme seçeneklerini kendi seçimine göre ayarlayabilir

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON\'u Excel\'e ve Excel\'i JSON\'a dönüştürün" %}}
JSON verileri, aşağıdakilerin yardımıyla Workbook sınıfının bir örneğine aktarılabilir: [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) daha fazla işleme veya desteklenen formatlardan herhangi birine basit dönüştürme için. Benzer şekilde, Çalışma Sayfası verileri bir dosya oluşturularak JSON olarak dışa aktarılabilir. [Menzil](https://reference.aspose.com/cells/java/com.aspose.cells/range) veya hücreler ve arama [ihracatRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) yöntem.
{{% blocks/products/pf/feature-page-code h3="Java JSON\'dan Excel\'e Dönüştürme Kodu" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Dosyayı Oku
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// JsonLayoutOptions'ı ayarlayın
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// JSON Verilerini İçe Aktar
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Excel dosyasını kaydet
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Excel\'den JSON\'a Dönüştürme için Kaynak Kodu" %}}
```cs
// XLSX dosyasını bir Çalışma Kitabı örneğiyle yükleyin
Workbook workbook = new Workbook("sourceFile.xlsx");
// dönüştürülecek verileri içeren çalışma sayfasının CellsCollection'ına erişin
Cells cells = workbook.getWorksheets().get(0).getCells();
// gelişmiş seçenekler için ExportRangeToJsonOptions oluşturun ve ayarlayın
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// dışa aktarılacak verileri içeren bir hücre aralığı oluşturun
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// aralığı JSON verileri olarak dışa aktar
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// JSON formatında diske veri yaz
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfalarını Resimlere Kaydet" %}}
Her çalışma sayfası, ImageType özelliği tarafından belirlenen JPG, BMP, PNG ve GIF gibi farklı görüntü biçimlerine dönüştürülebilir. Herhangi bir **Excel'i Görüntülere Dönüştür** vakası için bağlantılardan ilgili vakayı seçin.
{{% blocks/products/pf/feature-page-code h3="Java Excel\'den Görüntüye Dönüştürme Kodu" %}}
```cs
// şablon elektronik tablosunu yükle
var wkb = new Workbook("template.xlsx");

// ImageOptions için bir nesne oluşturun
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Görüntü türünü ayarlayın
imgOptions.setImageType(ImageType.PNG);

// İlk çalışma sayfasını alın.
Worksheet sheet = wkb.getWorksheets().get(0);

// Hedef sayfa için bir SheetRender nesnesi oluşturun
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Çalışma sayfası için bir resim oluşturun
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel\'i Word ve PowerPoint\'e Dönüştürün" %}}
Kullanırken herhangi bir elektronik tabloyu yüklemek ve Word DOCX ve PowerPoint PPTX dosyalarına dönüştürmek mümkündür. [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveSeçenekleri](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) aşağıda gösterildiği gibi sınıflar.
{{% blocks/products/pf/feature-page-code h3="Java Excel\'den Word\'e ve PowerPoint\'e Dönüştürme Kodu" %}}
```cs
// şablon dosyasını yükleyin
var wkb = new Workbook("template.xlsx");
// elektronik tabloyu DOCX olarak kaydet
wkb.save("output.docx", new DocxSaveOptions());
// elektronik tabloyu PPTX olarak kaydet
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
