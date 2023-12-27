---
title:  Microsoft C++ ile Excel Dosya Dönüştürme
description: Aspose.Cells for C++ kütüphane. EXCEL, JSON, PDF, XML, HTML, TXT, TSV, CSV, SQL, JPG, PNG ve daha fazla formatı yalnızca birkaç satır C++ koduyla dönüştürün.
keywords: [C++ Aspose.Cells., excel to pdf., json to excel., txt to sql., csv to json., json to pdf., xml to excel and Convert files between various formats in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> C++ aracılığıyla Excel Belgesi Dönüştürme" h2="Microsoft<sup>&reg;</sup> Excel dosyalarını e-tablo, web, resim ve sabit düzen formatlarında kaydedin" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Herhangi bir elektronik tablo dönüştürücü uygulaması veya çözümü için,**C++ Excel Kütüphanesi** XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS dahil olmak üzere birden fazla dosyayı yönetirken kodlama, otomasyon ve dönüştürme süreçlerini hızlandırır. Ayrıca Excel'i *0'a dönüştürmeye de olanak tanır 76193481**, XPS, HTML, MHTML, Düz JPG, TIFF, PNG, BMP ve SVG gibi metinler ve popüler görseller.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel Formatlarının ara dönüşümü" %}}
 E-tablo formatları arasında dönüştürme yalnızca e-tablonun aşağıdakileri kullanarak yüklenmesini gerektirir:[Çalışma kitabı](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) sınıfını kullanarak gerekli formatta yeniden kaydedin.[Kaydetmek](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/save/) yöntemi[Çalışma kitabı](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) sınıf.
{{% blocks/products/pf/feature-page-code h3="C++ Excel Dosya Formatı Dönüştürme için Örnek Kod" %}}

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


{{% blocks/products/pf/feature-page-section h2="Uyumluluk Düzeyi Ayarları ile Excel Formatlarını PDF\'e Dönüştürün" %}}
C++ Excel Otomasyonu API, Çalışma Kitaplarının PDF'e dönüştürülmesini ve uyumluluk düzeyinin ve oluşturulma tarihinin ayarlanmasını destekler. Geliştiriciler kullanabilir[PdfKaydetmeSeçenekleri](https://reference.aspose.com/cells/cpp/aspose.cells/pdfsaveoptions/) ile birlikte[Aspose::Cells::Rendering](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/) PDF uyumluluğunu ayarlamak için. Dönüştürme için, parametre olarak PdfSaveOptions'a ve belirtilen çıktı dosyası yoluna sahip API kaydetme yöntemi.
{{% blocks/products/pf/feature-page-code h3="C++ Excel\'in PDF\'e Dönüştürülmesi için Örnek Kod" %}}

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

{{% blocks/products/pf/feature-page-section h2="Excel\'i Görüntülere Kaydet" %}}
**C++ Excel Ayrıştırıcı** Verileri görüntü biçiminde dışa aktarma özelliğine sahiptir. Her çalışma sayfası, BMP, JPEG, PNG ve GIF dahil olmak üzere farklı görüntü formatlarına dönüştürülebilir.[Oluşturma::ImageOrPrintOptions](https://reference.aspose.com/cells/cpp/aspose.cells.rendering/imageorprintoptions/) . Herhangi**Excel'i Görsellere Dönüştür** durumda, bağlantılardan ilgili durumu seçin.
{{% blocks/products/pf/feature-page-code h3="C++ Excel\'den Görüntüye Dönüştürme Kodu" %}}

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
