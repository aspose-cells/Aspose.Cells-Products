---
title: Konversi Berkas Microsoft Excel melalui Python 
url: /id/python/conversion/
description: Konversi Excel XLS, XLSX, ODS, CSV ke PDF, XPS, HTML, JPEG, HTML, dan banyak format populer lainnya hanya dengan beberapa baris kode Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konversi Format Excel melalui Python" h2="Impor & ekspor file Excel sebagai spreadsheet, web, gambar, dan format tata letak tetap" >}}

{{% blocks/products/pf/feature-page-summary %}}
Python Pustaka Excel mempercepat pemrograman spreadsheet dan proses konversi sambil mendukung format populer termasuk XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Hal ini juga memungkinkan untuk mengekspor file Excel ke PDF, XPS, HTML, MHTML, Teks Biasa dan format gambar populer seperti TIFF, JPG, PNG, BMP dan SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke XLSX, ODS, SXC & FODS" %}}
Antar-konversi format spreadsheet hanya memerlukan pemuatan spreadsheet dengan instance [buku kerja](https://reference.aspose.com/cells/python/asposecells.api/Workbook) dan menyimpan kembali dalam format yang diinginkan sambil memilih nilai yang sesuai dari [SimpanFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) pencacahan.
{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Konversi Format File Excel" %}}

```cs
// memuat file template
workbook = Workbook("Book1.xls")
  
// simpan sebagai format XLSX, ODS, SXC & FODS
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.scx", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke PDF, XPS, HTML & MD" %}}
Kelas khusus tersedia untuk mengontrol proses konversi untuk format output tertentu seperti: [Opsi Simpan Pdf](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) untuk mengekspor file Excel sebagai PDF, [XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) untuk konversi Excel ke XPS, [HtmlSimpanOpsi](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) untuk membuat Excel sebagai HTML dan [Penurunan HargaSimpanOpsi](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) untuk konversi Excel ke penurunan harga. 
{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Excel ke PDF dan Format Web" %}}

```cs
// memuat file template Excel dari disk
book = Workbook("template.xlsx")

// simpan Excel dalam format PDF_A_1_B
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// simpan Excel di XPS dengan 1 halaman per lembar kerja
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// simpan Excel dalam HTML dengan gambar sebagai Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// simpan Excel di Markdown (MD) sambil mempertahankan pemformatan sel
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi JSON ke Excel & Excel ke JSON" %}}
Python pengembang dapat dengan mudah memuat & mengonversi file JSON ke Excel hanya dalam beberapa baris kode. Demikian pula, data Excel dapat diekspor ke data JSON.
{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Konversi JSON ke Excel" %}}
```cs
//Muat file json sumber Anda
workbook = Workbook("Data.json")
//simpan file ke format xlsx
workbook.save("output.xlsx")

```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Konversi Excel ke JSON" %}}
```cs
//Muat file xlsx sumber Anda
workbook = Workbook("input.xlsx")
//simpan file ke format json
workbook.save("Data.json")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konversikan Lembar Kerja Excel ke JPG, BMP, PNG & GIF" %}}
Setiap lembar kerja dari file Excel dapat dikonversi ke format gambar yang berbeda, panggil [Opsi GambarAtauCetak](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat untuk mengatur format gambar. 
{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Konversi Excel ke Gambar" %}}
```cs
// memuat lembar kerja template
workbook = Workbook("template.xlsx")
// buat & atur instance ImageOrPrintOptions
options = ImageOrPrintOptions()
// atur format gambar keluaran
options.setImageFormat(ImageFormat.getPng())
// buat SheetRender untuk lembar kerja pertama dalam koleksi
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// render lembar kerja ke gambar
sr.toImage(0, "output.jpg")

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke Word & PowerPoint" %}}
Dimungkinkan untuk memuat spreadsheet apa pun dan mengonversinya menjadi file Word DOCX & PowerPoint PPTX saat menggunakan [DocxSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSimpanOpsi](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) kelas seperti yang ditunjukkan di bawah ini.
{{% blocks/products/pf/feature-page-code h3="Python kode untuk Konversi Excel ke Word & PowerPoint" %}}
```cs
// memuat file template
workbook = Workbook("template.xlsx")

// simpan spreadsheet sebagai DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// simpan spreadsheet sebagai PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}