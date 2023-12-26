---
title: Microsoft Konversi File Excel Menggunakan Python via Java
description: Aspose.Cells for Python via Java perpustakaan. Konversi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL dan format lainnya hanya dengan beberapa baris kode Python.
keywords: [Python Aspose.Cells., excel to pdf., json to excel., excel to json., csv to json., json to html., xml to excel and Convert files between various formats in Python]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konversi Format Excel melalui Python" h2="Impor & ekspor file Excel sebagai format spreadsheet, web, gambar, dan tata letak tetap" >}}

{{% blocks/products/pf/feature-page-summary %}}
Perpustakaan Excel Python mempercepat pemrograman spreadsheet dan proses konversi sekaligus mendukung format populer termasuk XLS, XLSX, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Ini juga memungkinkan untuk mengekspor file Excel ke PDF, XPS, HTML, MHTML, Biasa Teks dan format gambar populer seperti TIFF, JPG, PNG, BMP dan SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ubah Excel menjadi XLSX, ODS, SXC & FODS" %}}
 Antar-konversi format spreadsheet hanya memerlukan pemuatan spreadsheet dengan sebuah instance[Buku Kerja](https://reference.aspose.com/cells/python/asposecells.api/Workbook) dan menyimpan kembali dalam format yang diinginkan sambil memilih nilai yang sesuai[SimpanFormat](https://reference.aspose.com/cells/python/asposecells.api/saveformat) pencacahan.
{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Konversi Format File Excel" %}}

```cs
// load the template file
workbook = Workbook("Book1.xls")
  
// save as XLSX, ODS, SXC & FODS formats
workbook.save("output.xlsx", SaveFormat.XLSX);
workbook.save("output.ods", SaveFormat.ODS);
workbook.save("output.sxc", SaveFormat.SXC);
workbook.save("output.fods", SaveFormat.FODS);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsx-to-tsv xlsx-to-fods xlsx-to-sxc xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke PDF, XPS, HTML & MD" %}}
 Kelas khusus tersedia untuk mengontrol proses konversi untuk format keluaran tertentu seperti[OpsiSimpan Pdf](https://reference.aspose.com/cells/python/asposecells.api/PdfSaveOptions) untuk mengekspor file Excel sebagai PDF,[XpsSaveOptions](https://reference.aspose.com/cells/python/asposecells.api/XpsSaveOptions) untuk konversi Excel ke XPS,[HtmlSimpanOpsi](https://reference.aspose.com/cells/python/asposecells.api/HtmlSaveOptions) untuk merender Excel sebagai HTML dan[Penurunan HargaSimpanOpsi](https://reference.aspose.com/cells/python/asposecells.api/MarkdownSaveOptions) untuk konversi Excel ke Penurunan Harga.
{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Excel hingga PDF dan Format Web" %}}

```cs
// load template Excel file from disc
book = Workbook("template.xlsx")

// save Excel in PDF_A_1_B format
pdfOptions = PdfSaveOptions()
pdfOptions.setCompliance(PdfCompliance.PDF_A_1_B)
book.save("output.pdf", pdfOptions);

// save Excel in XPS with 1 page per worksheet
xpsOptions = XpsSaveOptions()
xpsOptions.setOnePagePerSheet(True)
book.save("output.xps", xpsOptions);

// save Excel in HTML with images as Base64
htmlOptions = HtmlSaveOptions()
htmlOptions.setExportImagesAsBase64(True)
book.save("output.html", htmlOptions);

// save Excel in Markdown (MD) while retaining cell formatting
mdOptions = MarkdownSaveOptions()
mdOptions.setFormatStrategy(CellValueFormatStrategy.CELL_STYLE)
book.save("output.md", mdOptions);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="XPS PDF" beforeslug="convert" >}}

{{% blocks/products/pf/feature-page-section h2="Ubah JSON menjadi Excel & Excel menjadi JSON" %}}
Pengembang Python dapat dengan mudah memuat & mengonversi file JSON ke Excel hanya dalam beberapa baris kode. Demikian pula, data Excel dapat diekspor ke data JSON.
{{% blocks/products/pf/feature-page-code h3="Kode Python untuk Konversi JSON ke Excel" %}}
```cs
//Load your source json file
workbook = Workbook("Data.json")
//save file to xlsx format
workbook.save("output.xlsx")
```
{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kode Konversi Excel ke JSON" %}}
```cs
//Load your source xlsx file
workbook = Workbook("input.xlsx")
//save file to json format
workbook.save("Data.json")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="json-to-xlsx json-to-ods json-to-csv json-to-dif json-to-html csv-to-json xls-to-json ods-to-json" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi Lembar Kerja Excel ke JPG, BMP, PNG & GIF" %}}
 Setiap lembar kerja file Excel dapat dikonversi ke format gambar yang berbeda, sebut saja[Opsi GambarAtauCetak](https://reference.aspose.com/cells/python/asposecells.api/ImageOrPrintOptions).setImageFormat untuk mengatur format gambar.
{{% blocks/products/pf/feature-page-code h3="Python Kode Konversi Excel ke Gambar" %}}
```cs
// load template spreadsheet
workbook = Workbook("template.xlsx")
// create & set an instance of ImageOrPrintOptions
options = ImageOrPrintOptions()
// set output image format
options.setImageFormat(ImageFormat.getPng())
// create SheetRender for first worksheet in the collection
sheet = workbook.getWorksheets().get(0)
sr = SheetRender(sheet, options)
// render worksheet to image
sr.toImage(0, "output.jpg")
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xlsx-to-jpg xlsx-to-png xlsx-to-bmp ods-to-gif ods-to-svg ods-to-png ods-to-gif ods-to-bmp sxc-to-jpg mhtml-to-svg xlt-to-svg xls-to-emf fods-to-emf" afterslug="rendering" >}}

{{% blocks/products/pf/feature-page-section h2="Konversi Excel ke Word & PowerPoint" %}}
Dimungkinkan untuk memuat spreadsheet apa pun dan mengonversinya menjadi file Word DOCX & PowerPoint PPTX saat menggunakan[Opsi DocxSave](https://reference.aspose.com/cells/python/asposecells.api/DocxSaveOptions) & [PptxSimpanOpsi](https://reference.aspose.com/cells/python/asposecells.api/PptxSaveOptions) kelas seperti yang ditunjukkan di bawah ini.
{{% blocks/products/pf/feature-page-code h3="Kode Python untuk Konversi Excel ke Word & PowerPoint" %}}
```cs
// load the template file
workbook = Workbook("template.xlsx")

// save spreadsheet as DOCX
docxOptions = DocxSaveOptions()
workbook.save("output.docx", docxOptions)

// save spreadsheet as PPTX
pptxOptions = PptxSaveOptions()
workbook.save("output.pptx", pptxOptions)
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-pptx xlsx-to-pptx xlsb-to-pptx xlsm-to-pptx html-to-pptx mhtml-to-pptx ods-to-pptx tsv-to-pptx csv-to-pptx json-to-pptx numbers-to-pptx prn-to-pptx xlt-to-pptx xltx-to-pptx xltm-to-pptx ots-to-pptx sxc-to-pptx png-to-pptx jpg-to-pptx txt-to-pptx xls-to-docx xlsx-to-docx xlsb-to-docx xlsm-to-docx html-to-docx mhtml-to-docx ods-to-docx tsv-to-docx csv-to-docx json-to-docx numbers-to-docx prn-to-docx xlt-to-docx xltx-to-docx xltm-to-docx ots-to-docx sxc-to-docx png-to-docx jpg-to-docx txt-to-docx" >}}
