---
title: Konversi Berkas Microsoft Excel melalui Java 
url: /id/java/conversion/
description: Konversi Excel XLS, XLSX, ODS, CSV ke PDF, XPS, HTML, JPEG, HTML, dan banyak format populer lainnya hanya dengan beberapa baris kode Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konversi File Excel melalui Java" h2="Simpan dokumen Microsoft Excel sebagai spreadsheet, web, gambar, dan format tata letak tetap" >}}

{{% blocks/products/pf/feature-page-summary %}}
Untuk aplikasi atau solusi **Konverter Excel**, Java Pustaka Excel mempercepat pemrograman spreadsheet dan proses konversi sambil menangani berbagai format termasuk XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Ini juga memungkinkan untuk **mengonversi file Excel ke PDF**, XPS, HTML, MHTML, Teks Biasa dan format gambar populer seperti TIFF, JPG, PNG, BMP, dan SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inter-konversi Format Microsoft Excel" %}}
Antar-konversi format spreadsheet hanya memerlukan pemuatan spreadsheet dengan instance [buku kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) dan menyimpan kembali dalam format yang diinginkan sambil memilih nilai yang sesuai dari [SimpanFormat](https://reference.aspose.com/cells/java/com.aspose.cells/SaveFormat) pencacahan.
{{% blocks/products/pf/feature-page-code h3="Java Contoh Kode untuk Konversi Format File Excel" %}}

```cs
// memuat file sumber
var wkb = new Workbook("sourceFile.xls");
// simpan sebagai format XLSX, ODS, SXC & FODS
wkb.save("xlsx-output.xlsx", SaveFormat.XLSX);
wkb.save("ods-output.ods", SaveFormat.ODS);
wkb.save("scx-output.scx", SaveFormat.SXC);
wkb.save("fods-output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-json xlsx-to-pdf xlsx-to-html xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke PDF, XPS, HTML & MD" %}}
Kelas khusus tersedia untuk mengontrol proses konversi untuk format output tertentu seperti: [Opsi Simpan Pdf](https://reference.aspose.com/cells/java/com.aspose.cells/PdfSaveOptions) untuk mengonversi file Excel menjadi PDF, [XpsSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/XpsSaveOptions) untuk mengekspor Excel sebagai XPS, [HtmlSimpanOpsi](https://reference.aspose.com/cells/java/com.aspose.cells/HtmlSaveOptions) untuk membuat Excel sebagai HTML dan [Penurunan HargaSimpanOpsi](https://reference.aspose.com/cells/java/com.aspose.cells/MarkdownSaveOptions) untuk konversi Excel ke penurunan harga. 
{{% blocks/products/pf/feature-page-code h3="Java Contoh Kode untuk Excel ke PDF dan Format Web" %}}

```cs
// memuat file template Excel dari disk
var bk = new Workbook("source-file.xlsx");

// konversi Excel ke PDF menggunakan Java
// Buat opsi PDF
PdfSaveOptions options = new PdfSaveOptions();
options.setCompliance(PdfCompliance.PDF_A_1_A);

bk.save("excel-to-pdf.pdf", options);
// simpan Excel di XPS
bk.save("output.xps", new XpsSaveOptions());
// simpan Excel dalam HTML
bk.save("output.html", new HtmlSaveOptions());
// simpan Excel di Markdown (MD)
bk.save("output.md", new MarkdownSaveOptions());

// seseorang dapat mengatur opsi penyimpanan yang relevan sebagai pilihannya sebelum menyimpan ke dalam format yang relevan

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi JSON ke Excel dan Excel ke JSON" %}}
Data JSON dapat diimpor ke instance kelas Workbook dengan bantuan [JSONUtility.importData](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility#importData) untuk pemrosesan lebih lanjut atau konversi sederhana ke salah satu format yang didukung. Demikian pula, data Lembar Kerja dapat diekspor sebagai JSON dengan membuat a [Jangkauan](https://reference.aspose.com/cells/java/com.aspose.cells/range) atau sel dan memanggil [exportRangeToJson](https://reference.aspose.com/cells/java/com.aspose.cells/jsonutility) metode.
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Konversi JSON ke Excel" %}}
```cs
Workbook workbook = new Workbook(path + "source-file.xlsx");
Worksheet wks = workbook.getWorksheets().get(0);
		
// Baca File
File file = new File(path + "source-data.json");
BufferedReader bufferedReader = new BufferedReader(new FileReader(file));
String jsonInput = "";
String tempString;
while ((tempString = bufferedReader.readLine()) != null) {
	jsonInput = jsonInput + tempString; 
}
bufferedReader.close();
							
// Setel JsonLayoutOptions
JsonLayoutOptions options = new JsonLayoutOptions();
options.setIgnoreArrayTitle(true);
options.setArrayAsTable(true);

// Impor Data JSON
JSONUtility.importData(jsonInput, wks.getCells(), 0, 0, options);

// Simpan file Excel
workbook.save(path + "excel-to-json.out.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Kode Sumber untuk Konversi Excel ke JSON" %}}
```cs
// memuat file XLSX dengan instance Workbook
Workbook workbook = new Workbook("sourceFile.xlsx");
// akses CellsCollection dari lembar kerja yang berisi data yang akan dikonversi
Cells cells = workbook.getWorksheets().get(0).getCells();
// buat & atur ExportRangeToJsonOptions untuk opsi lanjutan
ExportRangeToJsonOptions exportOptions = new ExportRangeToJsonOptions();
// buat rentang sel yang berisi data untuk diekspor
Range range = cells.createRange(0, 0, cells.getLastCell().getRow() + 1, cells.getLastCell().getColumn() + 1);
// rentang ekspor sebagai data JSON
String jsonData = JsonUtility.exportRangeToJson(range, exportOptions);
// tulis data ke disk dalam format JSON
BufferedWriter writer = new BufferedWriter(new FileWriter("output.json"));
writer.write(jsonData);
writer.close();    

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Simpan Lembar Kerja Excel ke Gambar" %}}
Setiap lembar kerja dapat dikonversi ke format gambar yang berbeda termasuk JPG, BMP, PNG & GIF, diatur oleh properti ImageType. Untuk setiap kasus **Konversi Excel ke Gambar**, pilih kasus yang relevan dari tautan.
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Konversi Excel ke Gambar" %}}
```cs
// memuat lembar kerja template
var wkb = new Workbook("template.xlsx");

// Buat objek untuk ImageOptions
ImageOrPrintOptions imgOptions = new ImageOrPrintOptions();

// Setel jenis gambar
imgOptions.setImageType(ImageType.PNG);

// Dapatkan lembar kerja pertama.
Worksheet sheet = wkb.getWorksheets().get(0);

// Buat objek SheetRender untuk lembar target
SheetRender sr = new SheetRender(sheet, imgOptions);
for (int j = 0; j < sr.getPageCount(); j++) {
	// Menghasilkan gambar untuk lembar kerja
	sr.toImage(j, dataDir + "WToImage-out" + j + ".png");
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi Microsoft Excel ke Word dan PowerPoint" %}}
Dimungkinkan untuk memuat spreadsheet apa pun dan mengonversinya menjadi file Word DOCX & PowerPoint PPTX saat menggunakan [DocxSaveOptions](https://reference.aspose.com/cells/java/com.aspose.cells/DocxSaveOptions) & [PptxSimpanOpsi](https://reference.aspose.com/cells/java/com.aspose.cells/PptxSaveOptions) kelas seperti yang ditunjukkan di bawah ini.
{{% blocks/products/pf/feature-page-code h3="Java Kode untuk Konversi Excel ke Word & PowerPoint" %}}
```cs
// memuat file template
var wkb = new Workbook("template.xlsx");
// simpan spreadsheet sebagai DOCX
wkb.save("output.docx", new DocxSaveOptions());
// simpan spreadsheet sebagai PPTX
wkb.save("output.pptx", new PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}