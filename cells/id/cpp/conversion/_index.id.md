---
title: Konversi Berkas Microsoft Excel melalui C++ 

description: Konversikan Excel XLS, XLSX, ODS, CSV ke PDF, XPS, HTML, JPEG, dan format lainnya hanya dengan beberapa baris kode C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Konversi Dokumen Excel melalui C++" h2="Simpan file Microsoft<sup>&reg;</sup> Excel sebagai spreadsheet, web, gambar, dan format tata letak tetap" >}}

{{% blocks/products/pf/feature-page-summary %}}
Untuk aplikasi atau solusi pengonversi spreadsheet, **C++ Pustaka Excel** mempercepat proses pengkodean, otomatisasi, dan konversi sambil menangani banyak file termasuk XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS. Ini juga memungkinkan untuk **mengonversi Excel ke PDF**, XPS, HTML, MHTML, Teks Biasa dan gambar populer seperti JPG, TIFF, PNG, BMP, dan SVG.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Inter-konversi Format Microsoft Excel" %}}
Antar-konversi format spreadsheet hanya memerlukan pemuatan spreadsheet dengan instance [ intrusive_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) pointer dan simpan kembali dalam format yang diinginkan menggunakan [Menyimpan](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) metode dari [Kelas IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Contoh Kode untuk Konversi Format File Excel" %}}

```cs

// Muat format excel sumber.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Simpan dalam format output yang diperlukan.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Konversi Format Excel ke PDF dengan Pengaturan Tingkat Kepatuhan" %}}
C++ Otomatisasi Excel API mendukung konversi Buku Kerja ke PDF serta mendukung pengaturan tingkat kepatuhan dan tanggal pembuatan. Pengembang dapat menggunakan [Opsi Simpan IPdf](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) bersama [Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) untuk mengatur kepatuhan PDF. Untuk konversi, API simpan metode yang memiliki PdfSaveOptions sebagai parameter dan jalur file keluaran yang ditentukan. 
{{% blocks/products/pf/feature-page-code h3="C++ Contoh Kode untuk Konversi Excel ke PDF" %}}

```cs
// Muat contoh file Excel.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Buat objek opsi simpan pdf.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Setel kepatuhan ke PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// atau PdfCompliance_PdfA1a 
// untuk PDF normal akan menjadi PdfCompliance_None

// Simpan Dokumen Excel dalam format PDF
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Simpan Excel ke Gambar" %}}
**C++ Excel Parser** memiliki kemampuan untuk mengekspor data dalam bentuk gambar. Setiap lembar kerja dapat dikonversi ke format gambar yang berbeda termasuk BMP, JPEG, PNG dan GIF, diatur oleh [Rendering::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Untuk setiap kasus **Konversi Excel ke Gambar**, pilih kasus yang relevan dari tautan.
{{% blocks/products/pf/feature-page-code h3="C++ Kode untuk Konversi Excel ke Gambar" %}}

```cs
// Jalur direktori keluaran.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Muat XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Akses lembar kerja pertama.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Buat objek opsi gambar atau cetak.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Tentukan format gambar. Kode di bawah ini untuk JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Untuk gambar lain seperti GIF, BMP, dan PNG, masing-masing dapat menggunakan GetGif(), GetBmp() dan GetPng() 

// Tentukan resolusi horizontal dan vertikal
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render lembar sesuai dengan gambar atau opsi cetak yang ditentukan.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Dapatkan jumlah halaman.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Buat objek pembuat string untuk rangkaian string.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render setiap halaman ke gambar jpeg satu per satu.
for (int i = 0; i < pageCount; i++){
	// Hapus pembuat string dan buat jalur gambar keluaran dengan rangkaian string.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Dapatkan jalur gambar keluaran.
	StringPtr outputJPEG = sb->ToString();
	// Ubah lembar kerja menjadi gambar.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
