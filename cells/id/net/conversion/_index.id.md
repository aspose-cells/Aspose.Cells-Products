---
title:  Microsoft Konversi File Excel melalui C#
description: Aspose.Cells for .NET perpustakaan. Konversi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG dan format lainnya hanya dengan beberapa baris kode C#.
keywords: [C# Aspose.Cells., excel to pdf., excel to json., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konversi Format Excel via .NET" h2="Impor & ekspor file Excel sebagai format spreadsheet, web, gambar, dan tata letak tetap" >}}

{{% blocks/products/pf/feature-page-summary %}}
Perpustakaan Excel .NET mempercepat pemrograman spreadsheet dan proses konversi sekaligus mendukung format populer termasuk XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Ini juga memungkinkan untuk mengekspor file Excel ke PDF, XPS, HTML, MHTML, Biasa Teks dan format gambar populer seperti TIFF, JPG, PNG, BMP dan SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ubah Excel menjadi XLSX, ODS, SXC & FODS" %}}
 Antar-konversi format spreadsheet hanya memerlukan pemuatan spreadsheet dengan sebuah instance[Buku Kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook) dan menyimpan kembali dalam format yang diinginkan sambil memilih nilai yang sesuai[SimpanFormat](https://reference.aspose.com/cells/net/aspose.cells/saveformat) pencacahan.
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Konversi Format File Excel" %}}

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


{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke PDF, XPS, HTML & MD" %}}
 Kelas khusus tersedia untuk mengontrol proses konversi untuk format keluaran tertentu seperti[OpsiSimpan Pdf](https://reference.aspose.com/cells/net/aspose.cells/pdfsaveoptions) untuk mengekspor file Excel sebagai PDF,[XpsSaveOptions](https://reference.aspose.com/cells/net/aspose.cells/xpssaveoptions) untuk konversi Excel ke XPS,[HtmlSimpanOpsi](https://reference.aspose.com/cells/net/aspose.cells/htmlsaveoptions) untuk merender Excel sebagai HTML dan[Penurunan HargaSimpanOpsi](https://reference.aspose.com/cells/net/aspose.cells/markdownsaveoptions) untuk konversi Excel ke Penurunan Harga.
{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Excel hingga PDF dan Format Web" %}}

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

{{% blocks/products/pf/feature-page-section h2="Ubah JSON menjadi Excel & Excel menjadi JSON" %}}
 JSON data dapat diimpor ke dalam instance[Cells](https://reference.aspose.com/cells/net/aspose.cells/cells) kelas dengan bantuan[JsonUtility.ImportData](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/importdata) untuk pemrosesan lebih lanjut atau konversi sederhana ke format apa pun yang didukung. Demikian pula,[Lembar kerja](https://reference.aspose.com/cells/net/aspose.cells/worksheet) data dapat diekspor sebagai JSON dengan membuat a[Jangkauan](https://reference.aspose.com/cells/net/aspose.cells/range) atau sel dan memanggil[JsonUtility.ExportRangeToJson](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility/methods/exportrangetojson) metode.
{{% blocks/products/pf/feature-page-code h3="Kode C# untuk Konversi JSON ke Excel" %}}
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

{{% blocks/products/pf/feature-page-code h3="C# Kode Konversi Excel ke JSON" %}}
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

{{% blocks/products/pf/feature-page-section h2="Konversi Lembar Kerja Excel ke JPG, BMP, PNG & GIF" %}}
 Setiap lembar kerja file Excel dapat dikonversi ke format gambar berbeda yang diatur oleh[ImageOrPrintOptions.ImageType](https://reference.aspose.com/cells/net/aspose.cells.rendering/imageorprintoptions/properties/imagetype) Properti. Nilai defaultnya adalah `ImageFormat.Bmp`.
{{% blocks/products/pf/feature-page-code h3="C# Kode Konversi Excel ke Gambar" %}}
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

{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke Word & PowerPoint" %}}
Dimungkinkan untuk memuat spreadsheet apa pun dan mengonversinya menjadi file Word DOCX & PowerPoint PPTX saat menggunakan[Opsi DocxSave](https://reference.aspose.com/cells/net/aspose.cells/docxsaveoptions) & [PptxSimpanOpsi](https://reference.aspose.com/cells/net/aspose.cells/pptxsaveoptions) kelas seperti yang ditunjukkan di bawah ini.
{{% blocks/products/pf/feature-page-code h3="Kode C# untuk Konversi Excel ke Word & PowerPoint" %}}
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
