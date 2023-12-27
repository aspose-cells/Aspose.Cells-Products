---
title:  Microsoft Excel Dosyası Dönüştürme via Java
description: Aspose.Cells for Java kütüphane. EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG ve daha fazla formatı yalnızca birkaç satır Java koduyla dönüştürün.
keywords: [Java Aspose.Cells., excel to pdf., excel to json., html to xps., csv to json., json to pdf., xml to excel and Convert files between various formats in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosyalarını Dönüştürme via Java" h2="Microsoft Excel belgesini elektronik tablo, web, resim ve sabit düzen formatlarında kaydedin" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Herhangi**Excel dönüştürücü** uygulama veya çözüm, Java Excel Kitaplığı, XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 07619 dahil olmak üzere birden fazla formatı işlerken elektronik tablo programlama ve dönüştürme süreçlerini hızlandırır 3481. Ayrıca *Excel dosyalarını PDF**'e dönüştürmenize de olanak tanır, XPS, HTML, MHTML, Düz Metin ve TIFF, JPG, PNG, BMP ve SVG gibi popüler resim formatları.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel Formatlarının ara dönüşümü" %}}
 Elektronik tablo formatının karşılıklı dönüştürülmesi yalnızca aşağıdaki örneğin bulunduğu bir elektronik tablonun yüklenmesini gerektirir:[Çalışma kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) ve uygun değeri seçerken istenilen formatta tekrar kaydetme[Formatı Kaydet](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) numaralandırma.
{{% blocks/products/pf/feature-page-code h3="Java Excel Dosya Formatı Dönüştürme için Örnek Kod" %}}

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
 Belirli çıktı formatları için dönüştürme sürecini kontrol etmek amacıyla özel sınıflar mevcuttur:[PdfKaydetmeSeçenekleri](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) Excel dosyalarını PDF olarak dönüştürmek için,[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) Excel'i XPS olarak dışa aktarmak için,[HtmlSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) Excel'i HTML olarak işlemek ve[İşaretlemeKaydetSeçenekleri](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) Excel'den Markdown'a dönüşüm için.
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
 JSON verileri Workbook sınıfının bir örneğine aşağıdakilerin yardımıyla aktarılabilir:[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) daha fazla işlem yapmak veya desteklenen formatlardan herhangi birine basit bir şekilde dönüştürmek için. Benzer şekilde, Çalışma Sayfası verileri bir oluşturularak JSON olarak dışa aktarılabilir.[Menzil](https://reference.aspose.com/cells/java/com.aspose.cells/range) veya hücreleri çağırıp[ihracatRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) yöntem.
{{% blocks/products/pf/feature-page-code h3="Java JSON\'i Excel\'e Dönüştürme Kodu" %}}
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

{{% blocks/products/pf/feature-page-code h3="Java Excel Kaynak Kodundan JSON\'e Dönüşüm" %}}
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

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfalarını Görsellere Kaydetme" %}}
 Her çalışma sayfası, ImageType özelliği tarafından ayarlanan JPG, BMP, PNG ve GIF dahil olmak üzere farklı görüntü formatlarına dönüştürülebilir. Herhangi**Excel'i Görsellere Dönüştür** durumda, bağlantılardan ilgili durumu seçin.
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

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel\'i Word\'e ve PowerPoint\'i dönüştürün" %}}
Kullanırken herhangi bir elektronik tabloyu yükleyip Word DOCX & PowerPoint PPTX dosyalarına dönüştürmek mümkündür.[DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) Aşağıda gösterildiği gibi sınıflar.
{{% blocks/products/pf/feature-page-code h3="Java Excel\'den Word\'e Kod ve PowerPoint Dönüştürme" %}}
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
