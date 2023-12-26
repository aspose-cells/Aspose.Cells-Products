---
title:  Microsoft Konversi File Excel via Java
description: Aspose.Cells for Java perpustakaan. Konversi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG dan format lainnya hanya dengan beberapa baris kode Java.
keywords: [Java Aspose.Cells., excel to pdf., excel to json., html to xps., csv to json., json to pdf., xml to excel and Convert files between various formats in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konversi File Excel via Java" h2="Simpan Microsoft dokumen Excel sebagai format spreadsheet, web, gambar, dan tata letak tetap" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Untuk apa pun**Konverter Excel** aplikasi atau solusi, Java Perpustakaan Excel mempercepat pemrograman spreadsheet dan proses konversi sambil menangani berbagai format termasuk XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, 076193 481. Ini juga memungkinkan untuk *mengonversi file Excel ke PDF**, XPS, HTML, MHTML, Teks Biasa dan format gambar populer seperti TIFF, JPG, PNG, BMP dan SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Antar-konversi Format Excel Microsoft" %}}
 Antar-konversi format spreadsheet hanya memerlukan pemuatan spreadsheet dengan sebuah instance[Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) dan menyimpan kembali dalam format yang diinginkan sambil memilih nilai yang sesuai[SimpanFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) pencacahan.
{{% blocks/products/pf/feature-page-code h3="Java Contoh Kode Konversi Format File Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke PDF, XPS, HTML & MD" %}}
 Kelas khusus tersedia untuk mengontrol proses konversi untuk format keluaran tertentu seperti[OpsiSimpan Pdf](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) untuk mengkonversi file Excel sebagai PDF,[XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) untuk mengekspor Excel sebagai XPS,[HtmlSimpanOpsi](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) untuk merender Excel sebagai HTML dan[Penurunan HargaSimpanOpsi](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) untuk konversi Excel ke Penurunan Harga.
{{% blocks/products/pf/feature-page-code h3="Java Contoh Kode untuk Excel hingga PDF dan Format Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Ubah JSON menjadi Excel dan Excel menjadi JSON" %}}
 Data JSON dapat diimpor ke dalam instance kelas Buku Kerja dengan bantuan[JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) untuk pemrosesan lebih lanjut atau konversi sederhana ke format apa pun yang didukung. Demikian pula, data Lembar Kerja dapat diekspor sebagai JSON dengan membuat a[Jangkauan](https://reference.aspose.com/cells/java/com.aspose.cells/range) atau sel dan memanggil[eksporRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) metode.
{{% blocks/products/pf/feature-page-code h3="Kode Java untuk Konversi JSON ke Excel" %}}
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

{{% blocks/products/pf/feature-page-code h3="Java Source Code Konversi Excel ke JSON" %}}
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

{{% blocks/products/pf/feature-page-section h2="Simpan Lembar Kerja Excel ke Gambar" %}}
 Setiap lembar kerja dapat dikonversi ke format gambar berbeda termasuk JPG, BMP, PNG & GIF, yang diatur oleh properti ImageType. Untuk apa pun**Konversi Excel ke Gambar** kasus, pilih kasus yang relevan dari tautan.
{{% blocks/products/pf/feature-page-code h3="Java Kode Konversi Excel ke Gambar" %}}
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

{{% blocks/products/pf/feature-page-section h2="Ubah Microsoft Excel ke Word dan PowerPoint" %}}
Dimungkinkan untuk memuat spreadsheet apa pun dan mengonversinya menjadi file Word DOCX & PowerPoint PPTX saat menggunakan[Opsi DocxSave](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSimpanOpsi](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) kelas seperti yang ditunjukkan di bawah ini.
{{% blocks/products/pf/feature-page-code h3="Java Kode Excel ke Word & PowerPoint Konversi" %}}
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
