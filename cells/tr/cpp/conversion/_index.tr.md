---
title:  Microsoft C++ aracılığıyla Excel Dosya Dönüştürme
description: Yalnızca birkaç satırlık C++ koduyla Excel XLS, XLSX, ODS, CSV'i PDF, XPS, HTML, JPEG ve diğer biçimlere dönüştürün.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> C++ aracılığıyla Excel Belge Dönüştürme" h2="Microsoft<sup>&reg;</sup> Excel dosyalarını elektronik tablo, web, resim ve sabit mizanpaj biçimleri olarak kaydedin" >}}

{{% blocks/products/pf/feature-page-summary %}}
 Herhangi bir elektronik tablo dönüştürücü uygulaması veya çözümü için,**C++ Excel Kitaplığı** XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS dahil birden çok dosyayı işlerken kodlama, otomasyon ve dönüştürme işlemlerini hızlandırır. PDF**, XPS, HTML, MHTML, Düz JPG, TIFF, PNG, BMP ve SVG gibi metin ve popüler görseller.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel Formatlarının Ara Dönüşümü" %}}
 Elektronik tablo biçiminin karşılıklı dönüştürülmesi, yalnızca bir elektronik tablonun örneğinin yüklenmesini gerektirir.[ müdahaleci_ptr<Aspose::Cells::IWorkbook>](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) işaretçi ve kullanarak istenen formatta geri kaydetme[Kaydetmek](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) yöntemi[IWorkbook sınıfı](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Excel Dosya Biçimi Dönüştürme için Örnek Kod" %}}

```cs

// Load the source excel format.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Save in required output format.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Uyumluluk Seviyesi Ayarları ile Excel Formatlarını PDF\'e Dönüştürün" %}}
 C++ Excel Otomasyonu API, Çalışma Kitaplarının PDF'e dönüştürülmesini ve ayrıca uyumluluk düzeyi ve oluşturma tarihi ayarını destekler. Geliştiriciler kullanabilir[IPdfSaveSeçenekleri](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) ile birlikte[Aspose::Cells::Oluşturma](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) PDF uyumluluğunu ayarlamak için. Dönüştürme için, parametre olarak PdfSaveOptions'a sahip API kaydetme yöntemi ve belirtilen çıktı dosyası yolu.
{{% blocks/products/pf/feature-page-code h3="C++ Excel\'den PDF\'e Dönüşüm için Örnek Kod" %}}

```cs
// Load the sample Excel file.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// Create pdf save options object.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Set the compliance to PDF/A-1b.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// or PdfCompliance_PdfA1a 
// for normal PDF it will be PdfCompliance_None

// Save the Excel Document in PDF format
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Excel\'i Görüntülere Kaydet" %}}
**C++ Excel Ayrıştırıcı** verileri görüntü biçiminde dışa aktarma yeteneğine sahiptir. Her çalışma sayfası, BMP, JPEG, PNG ve GIF dahil olmak üzere farklı görüntü formatlarına dönüştürülebilir.[İşleme::IImageOrPrintOptions](https://reference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options) . Herhangi**Excel'i Görüntülere Dönüştür** durumda, bağlantılardan ilgili vakayı seçin.
{{% blocks/products/pf/feature-page-code h3="C++ Excel\'den Görüntüye Dönüştürme Kodu" %}}

```cs
// Output directory path.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// Load the XLSX.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// Access first worksheet.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Create image or print options object.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Specify the image format. Below code is for JPEG
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// For other images like GIF, BMP and PNG one can use GetGif(), GetBmp() and GetPng() respectively 

// Specify horizontal and vertical resolution
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Render the sheet with respect to specified image or print options.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Get page count.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Create string builder object for string concatenations.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Render each page to jpeg image one by one.
for (int i = 0; i < pageCount; i++){
	// Clear string builder and create output image path with string concatenations.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Get the output image path.
	StringPtr outputJPEG = sb->ToString();
	// Convert worksheet to image.
	sr->ToImage(i, outputJPEG);
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}
