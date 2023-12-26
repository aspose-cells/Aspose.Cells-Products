---
title:  Microsoft Konversi File Excel melalui C++
description: Aspose.Cells for C++ perpustakaan. Konversi EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG dan format lainnya hanya dengan beberapa baris kode C++.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konversi Dokumen Excel melalui C++" h2="Simpan Microsoft<sup>&reg;</sup> file Excel sebagai format spreadsheet, web, gambar, dan tata letak tetap" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Untuk aplikasi atau solusi pengonversi spreadsheet apa pun,**C++ Perpustakaan Excel** mempercepat proses pengkodean, otomatisasi, dan konversi saat menangani banyak file termasuk XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Ini juga memungkinkan untuk *mengonversi Excel ke 0 76193481**, XPS, HTML, MHTML, Biasa Teks dan gambar populer seperti JPG, TIFF, PNG, BMP dan SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Antar-konversi Format Excel Microsoft" %}}
 Mengonversi antar format spreadsheet hanya memerlukan pemuatan spreadsheet menggunakan[Buku Kerja](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) kelas dan menyimpannya kembali dalam format yang diperlukan menggunakan[Menyimpan](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) metode[Buku Kerja](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) kelas.
{{% blocks/products/pf/feature-page-code h3="C++ Contoh Kode Konversi Format File Excel" %}}

```cpp

Aspose::Cells::Startup();

// Load the source excel format.
Workbook wkb(u"src_excel_file.xls");
// Save in required output format.
wkb.Save(u"output_excel_format.xlsx", SaveFormat::Xlsx);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konversikan Format Excel ke PDF dengan Pengaturan Tingkat Kepatuhan" %}}
C++ Otomatisasi Excel API mendukung konversi Buku Kerja ke PDF serta mendukung pengaturan tingkat kepatuhan dan tanggal pembuatan. Pengembang dapat menggunakan[OpsiSimpan Pdf](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) bersama[Aspose::Cells::Render](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) untuk mengatur kepatuhan PDF. Untuk konversi, metode penyimpanan API memiliki PdfSaveOptions sebagai parameter dan jalur file keluaran tertentu.
{{% blocks/products/pf/feature-page-code h3="C++ Contoh Kode Konversi Excel ke PDF" %}}

```cpp

Aspose::Cells::Startup();

// Load the sample Excel file.
Workbook wkb(u"sample-convert-excel-to.pdf");
// Create pdf save options object.
PdfSaveOptions pdfSaveOptions;

// Set the compliance to PDF/A-1b.
pdfSaveOptions.SetCompliance(PdfCompliance::PdfA1b);

// or PdfCompliance::PdfA1a
// for normal PDF it will be PdfCompliance::None

// Save the Excel Document in PDF format
wkb.Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);

Aspose::Cells::Cleanup();

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Simpan Excel ke Gambar" %}}
**C++ Pengurai Excel** memiliki kemampuan untuk mengekspor data dalam bentuk gambar. Setiap lembar kerja dapat dikonversi ke format gambar yang berbeda termasuk BMP, JPEG, PNG dan GIF, diatur oleh[Render::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Untuk apa pun**Konversi Excel ke Gambar** kasus, pilih kasus yang relevan dari tautan.
{{% blocks/products/pf/feature-page-code h3="C++ Kode Konversi Excel ke Gambar" %}}

```cpp

Aspose::Cells::Startup();

// Load the XLSX.
Aspose::Cells::Workbook wkb(u"source-excel-file.xlsx");

// Access first worksheet.
Aspose::Cells::Worksheet wks = wkb.GetWorksheets().Get(0);

// Create image or print options object.
Aspose::Cells::Rendering::ImageOrPrintOptions imgOptions;

// Specify the image format. Below code is for JPEG
imgOptions.SetImageType(ImageType::Jpeg);

// For other images like GIF, BMP and PNG one can use ImageType::Gif, ImageType::Bmp and ImageType::Png respectively 

// Specify horizontal and vertical resolution
imgOptions.SetHorizontalResolution(200);
imgOptions.SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
Aspose::Cells::Rendering::SheetRender sr(wks, imgOptions);

// Get page count.
int pageCount = sr.GetPageCount();

std::string sb = "";
// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++) {
	sb = ""; 
	sb += "ImagesOutputDirectoryPath/";
	sb += "outputConvertingWorksheetToImageJPEG_";
	sb += std::to_string(i);
	sb += ".jpeg";
	// Get the output image path.
	U16String outputJPEG(sb.c_str());
	// Convert worksheet to image.
	sr.ToImage(i, outputJPEG);
}

Aspose::Cells::Cleanup();
	
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
