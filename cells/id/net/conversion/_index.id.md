---
title: Konversi Berkas Microsoft Excel melalui C# 
url: /id/net/conversion/
description: Konversi Excel XLS, XLSX, ODS, CSV ke PDF, XPS, HTML, JPEG, HTML, dan banyak format populer lainnya hanya dengan beberapa baris kode C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konversi Format Excel melalui .NET" h2="Impor & ekspor file Excel sebagai spreadsheet, web, gambar, dan format tata letak tetap" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Pustaka Excel mempercepat pemrograman spreadsheet dan proses konversi sambil mendukung format populer termasuk XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Hal ini juga memungkinkan untuk mengekspor file Excel ke PDF, XPS, HTML, MHTML, Teks Biasa dan format gambar populer seperti TIFF, JPG, PNG, BMP dan SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke XLSX, ODS, SXC & FODS" %}}
Antar-konversi format spreadsheet hanya memerlukan pemuatan spreadsheet dengan instance [buku kerja](https://apireference.aspose.com/cells/net/aspose.cells/workbook) dan menyimpan kembali dalam format yang diinginkan sambil memilih nilai yang sesuai dari [SimpanFormat](https://apireference.aspose.com/cells/net/aspose.cells/saveformat) pencacahan.
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Konversi Format File Excel" %}}

```cs
// memuat file template
var workbook = new Aspose.Cells.Workbook("template.xls");
// simpan sebagai format XLSX, ODS, SXC & FODS
workbook.Save("output.xlsx", Aspose.Cells.SaveFormat.Xlsx);
workbook.Save("output.ods", Aspose.Cells.SaveFormat.Ods);
workbook.Save("output.scx", Aspose.Cells.SaveFormat.Sxc);
workbook.Save("output.fods", Aspose.Cells.SaveFormat.Fods);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke PDF, XPS, HTML & MD" %}}
Kelas khusus tersedia untuk mengontrol proses konversi untuk format output tertentu seperti: [Opsi Simpan Pdf](https://apireference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) untuk mengekspor file Excel sebagai PDF, [XpsSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/xpssaveoptions) untuk konversi Excel ke XPS, [HtmlSimpanOpsi](https://apireference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) untuk membuat Excel sebagai HTML dan [Penurunan HargaSimpanOpsi](https://apireference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) untuk konversi Excel ke penurunan harga. 
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Excel ke PDF dan Format Web" %}}

```cs
// memuat file template Excel dari disk
var book = new Aspose.Cells.Workbook("template.xlsx");
// simpan Excel dalam format PDF/A-1a
book.Save("output.pdf", new Aspose.Cells.PdfSaveOptions() { Compliance = PdfComplianceVersion.PdfA1a });
// simpan Excel di XPS dengan 1 halaman per lembar kerja
book.Save("output.xps", new Aspose.Cells.XpsSaveOptions() { OnePagePerSheet = true });
// simpan Excel dalam HTML dengan gambar sebagai Base64
book.Save("output.html", new Aspose.Cells.HtmlSaveOptions() { ExportImagesAsBase64 = true });
// simpan Excel di Markdown (MD) sambil mempertahankan pemformatan sel
book.Save("output.md", new Aspose.Cells.MarkdownSaveOptions() { FormatStrategy = Cells.CellValueFormatStrategy.CellStyle });

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi JSON ke Excel & Excel ke JSON" %}}
Data JSON dapat diimpor ke instance dari [Cells](https://apireference.aspose.com/cells/net/aspose.cells/cells) kelas dengan bantuan [JsonUtility.ImportData](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) untuk pemrosesan lebih lanjut atau konversi sederhana ke salah satu format yang didukung. Demikian pula, [lembar kerja](https://apireference.aspose.com/cells/net/aspose.cells/worksheet) data dapat diekspor sebagai JSON dengan membuat a [Jangkauan](https://apireference.aspose.com/cells/net/aspose.cells/range) atau sel dan memanggil [JsonUtility.ExportRangeToJson](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) metode.
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Konversi JSON ke Excel" %}}
```cs
// membuat objek Buku Kerja
var workbook = new Cells.Workbook();
var worksheet = workbook.Worksheets[0];
// baca data JSON dari file
string jsonInput = File.ReadAllText("Data.json");
// atur JsonLayoutOptions untuk memperlakukan Array sebagai Tabel
var options = new Cells.Utility.JsonLayoutOptions();
options.ArrayAsTable = true;
// impor data JSON ke lembar kerja mulai dari sel A1
Cells.Utility.JsonUtility.ImportData(jsonInput, worksheet.Cells, 0, 0, options);
// simpan file yang dihasilkan dalam format XLSX
workbook.Save("output.xlsx", Cells.SaveFormat.Auto); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Konversi Excel ke JSON" %}}
```cs
// memuat file XLSX dengan instance Workbook
var workbook = new Workbook("template.xlsx", new LoadOptions(Cells.LoadFormat.Auto));
// akses CellsCollection dari lembar kerja yang berisi data yang akan dikonversi
var cells = workbook.Worksheets[0].Cells;
// buat & atur ExportRangeToJsonOptions untuk opsi lanjutan
var exportOptions = new Utility.ExportRangeToJsonOptions();
// buat rentang sel yang berisi data untuk diekspor
var range = cells.CreateRange(0, 0, cells.LastCell.Row + 1, cells.LastCell.Column + 1);
// rentang ekspor sebagai data JSON
string jsonData = Cells.Utility.JsonUtility.ExportRangeToJson(range, exportOptions);
// tulis file data ke disk dalam format JSON
System.IO.File.WriteAllText("output.json", jsonData); 

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan Lembar Kerja Excel ke JPG, BMP, PNG & GIF" %}}
Setiap lembar kerja dari file Excel dapat dikonversi ke format gambar yang berbeda yang diatur oleh: [ImageOrPrintOptions.ImageType](https://apireference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) Properti. Nilai defaultnya adalah `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Konversi Excel ke Gambar" %}}
```cs
// memuat lembar kerja template
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// buat & atur instance ImageOrPrintOptions
var options = new Aspose.Cells.Rendering.ImageOrPrintOptions();
options.OnePagePerSheet = true;
// atur format gambar keluaran
options.ImageType = Aspose.Cells.Drawing.ImageType.Jpeg;
// buat SheetRender untuk lembar kerja pertama dalam koleksi
var render = new Aspose.Cells.Rendering.SheetRender(workbook.Worksheets[0], options);
// render lembar kerja ke gambar
render.ToImage(0, "output.jpg");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke Word & PowerPoint" %}}
Dimungkinkan untuk memuat spreadsheet apa pun dan mengonversinya menjadi file Word DOCX & PowerPoint PPTX saat menggunakan [DocxSaveOptions](https://apireference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSimpanOpsi](https://apireference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) kelas seperti yang ditunjukkan di bawah ini.
{{% blocks/products/pf/feature-page-code h3="C# kode untuk Konversi Excel ke Word & PowerPoint" %}}
```cs
// memuat file template
var workbook = new Aspose.Cells.Workbook("template.xlsx");
// simpan spreadsheet sebagai DOCX
workbook.Save("output.docx", new Aspose.Cells.DocxSaveOptions());
// simpan spreadsheet sebagai PPTX
workbook.Save("output.pptx", new Aspose.Cells.PptxSaveOptions());

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}