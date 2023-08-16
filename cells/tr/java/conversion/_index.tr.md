---
title:  Microsoft Excel Dosya Dönüştürme via Java
description: Yalnızca birkaç satırlık Java koduyla Excel XLS, XLSX, ODS, CSV'i PDF, XPS, HTML, JPEG, HTML ve diğer birçok popüler biçime dönüştürün .
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosyaları Dönüştürme via Java" h2="Microsoft Excel belgelerini elektronik tablo, web, resim ve sabit mizanpaj biçimleri olarak kaydedin" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Herhangi**Excel dönüştürücü**uygulama veya çözüm, Java Excel Kitaplığı, XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 076 dahil olmak üzere birden çok biçimi işlerken elektronik tablo programlama ve dönüştürme işlemlerini hızlandırır 193481. Ayrıca *Excel dosyalarını PDF'e dönüştürmeye** olanak tanır, XPS, HTML, MHTML, Düz Metin ve TIFF, JPG, PNG, BMP ve SVG gibi popüler resim biçimleri.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel Formatlarının Ara Dönüşümü" %}}
 Elektronik tablo biçiminin karşılıklı dönüştürülmesi, yalnızca bir elektronik tablonun örneğinin yüklenmesini gerektirir.[Çalışma kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ve uygun değeri seçerek istenen formatta geri kaydetme[Biçimi Kaydet](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) numaralandırma.
{{% blocks/products/pf/feature-page-code h3="Java Excel Dosya Biçimi Dönüştürme için Örnek Kod" %}}

```cs
// load the source file
var wkb = new Workbook("sourceFile.xls");
// save as XLSX, ODS, SXC & FODS formats
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Excel\'i PDF, XPS, HTML ve MD\'ye dönüştürün" %}}
 Aşağıdakiler gibi belirli çıktı biçimleri için dönüştürme sürecini kontrol etmek için özel sınıflar mevcuttur:[PdfKaydetmeSeçenekleri](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) Excel dosyalarını PDF olarak dönüştürmek için,[XpsSaveSeçenekleri](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) Excel'i XPS olarak dışa aktarmak için,[HtmlKaydetme Seçenekleri](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) Excel'i HTML olarak işlemek ve[MarkdownSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) Excel'den Markdown'a dönüştürme için.
{{% blocks/products/pf/feature-page-code h3="Java Excel\'den PDF\'e ve Web Formatlarına Örnek Kod" %}}

```cs
// load template Excel file from disc
var bk = new Workbook("source-file.xlsx");

// convert Excel to PDF using Java
// Create PDF options
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// save Excel in XPS
bk.save("output.xps", new XpsSaveOptions());
// save Excel in HTML
bk.save("output.html", new HtmlSaveOptions());
// save Excel in Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// one can set relevant save options as of his choice before saving into relevant format
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="JSON\'i Excel\'e ve Excel\'i JSON\'e dönüştürün" %}}
 JSON verileri, Workbook sınıfının bir örneğine şu yardımla alınabilir:[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) daha fazla işleme veya desteklenen biçimlerden herhangi birine basit dönüştürme için. Benzer şekilde, Çalışma Sayfası verileri, bir dosya oluşturularak JSON olarak dışa aktarılabilir.[Menzil](https://reference.aspose.com/cells/java/com.aspose.cells/range) veya hücreler ve arama[exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) yöntem.
{{% blocks/products/pf/feature-page-code h3="Java JSON\'den Excel\'e Dönüştürme Kodu" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Read File
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Set JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Import JSON Data
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Save Excel file
workbook.save(path + "excel-to-json.out.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Excel için Kaynak Kodu JSON\'e Dönüştürme" %}}
```cs
// load XLSX file with an instance of Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// access CellsCollection of the worksheet containing data to be converted
Cells cells = workbook.getWorksheets().get(0).getCells();
// create & set ExportRangeToJsonOptions for advanced options
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// create a range of cells containing data to be exported
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// export range as JSON data
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// write data to disc in JSON format
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfalarını Görüntülere Kaydet" %}}
 Her çalışma sayfası, ImageType özelliği tarafından ayarlanan JPG, BMP, PNG ve GIF dahil olmak üzere farklı resim biçimlerine dönüştürülebilir. Herhangi**Excel'i Görüntülere Dönüştür** durumda, bağlantılardan ilgili vakayı seçin.
{{% blocks/products/pf/feature-page-code h3="Java Excel\'den Görüntüye Dönüştürme Kodu" %}}
```cs
// load template spreadsheet
var wkb = new Workbook("template.xlsx");

// Create an object for ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Set the image type
imgOptions.setImageType(ImageType.PNG);

// Get the first worksheet.
Worksheet sheet = wkb.getWorksheets().get(0);

// Create a SheetRender object for the target sheet
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Generate an image for the worksheet
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel\'i Word\'e ve PowerPoint\'e dönüştürün" %}}
 Kullanırken herhangi bir elektronik tabloyu yüklemek ve Word DOCX & PowerPoint PPTX dosyalarına dönüştürmek mümkündür.[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions)aşağıda gösterildiği gibi sınıflar.
{{% blocks/products/pf/feature-page-code h3="Java Excel\'den Word\'e Dönüştürme Kodu ve PowerPoint" %}}
```cs
// load the template file
var wkb = new Workbook("template.xlsx");
// save spreadsheet as DOCX
wkb.save("output.docx", new DocxSaveOptions());
// save spreadsheet as PPTX
wkb.save("output.pptx", new PptxSaveOptions());
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
