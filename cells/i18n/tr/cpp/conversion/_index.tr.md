---
title: C++ aracılığıyla Microsoft Excel Dosya Dönüştürme 
url: /tr/cpp/conversion/
description: Yalnızca birkaç satır C++ koduyla Excel XLS, XLSX, ODS, CSV'yi PDF, XPS, HTML, JPEG ve diğer biçimlere dönüştürün.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C++ aracılığıyla Microsoft<sup>&reg;</sup> Excel Belgesi Dönüştürme" h2="Microsoft<sup>&reg;</sup> Excel dosyalarını elektronik tablo, web, resim ve sabit düzen biçimleri olarak kaydedin" >}}

{{% blocks/products/pf/feature-page-summary %}}
Herhangi bir elektronik tablo dönüştürücü uygulaması veya çözümü için **C++ Excel Kitaplığı**, XLSX, XLS, XLSM, XLSB, XLTX, XLTM, CSV, SpreadsheetML, ODS dahil olmak üzere birden fazla dosyayı işlerken kodlama, otomasyon ve dönüştürme işlemlerini hızlandırır. Ayrıca **Excel'i PDF'ye**, XPS, HTML, MHTML, Düz Metin ve JPG, TIFF, PNG, BMP ve SVG gibi popüler resimlere dönüştürmeye olanak tanır.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Microsoft Excel Formatlarının Ara Dönüşümü" %}}
E-tablo formatının inter-dönüşümü, yalnızca bir e-tablonun örneğinin bulunduğu bir e-tablonun yüklenmesini gerektirir. [ müdahaleci_ptr<Aspose::Cells::IWorkbook>](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) işaretçi ve kullanarak istenen biçimde geri kaydetme [Kaydetmek](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) yöntemi [IWorkbook sınıfı](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook).
{{% blocks/products/pf/feature-page-code h3="C++ Excel Dosya Biçimi Dönüşümü için Örnek Kod" %}}

```cs

// Kaynak excel biçimini yükleyin.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"src_excel_file.xls");

// Gerekli çıktı biçiminde kaydedin.
wkb->Save(u"output_excel_format.xlsx", SaveFormat_Xlsx);


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="xls-to-xlsx xlsx-to-xlsm xlsx-to-ods xlsx-to-csv xlsm-to-xls" >}}


{{% blocks/products/pf/feature-page-section h2="Uyumluluk Düzeyi Ayarları ile Excel Formatlarını PDF\'ye Dönüştürün" %}}
C++ Excel Otomasyonu API, Çalışma Kitaplarının PDF'ye dönüştürülmesini ve ayrıca uyumluluk düzeyi ve oluşturma tarihinin ayarlanmasını destekler. Geliştiriciler kullanabilir [IPdfSaveSeçenekleri](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_pdf_save_options) ile birlikte [Aspose::Cells::Oluşturma](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.rendering) PDF uyumluluğunu ayarlamak için Dönüştürme için, parametre olarak PdfSaveOptions'a sahip API kaydetme yöntemi ve belirtilen çıktı dosyası yolu. 
{{% blocks/products/pf/feature-page-code h3="C++ Excel\'den PDF\'ye Dönüştürme için Örnek Kod" %}}

```cs
// Örnek Excel dosyasını yükleyin.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sample-convert-excel-to.pdf");

// pdf kaydetme seçenekleri nesnesi oluşturun.
intrusive_ptr<Aspose::Cells::IPdfSaveOptions> pdfSaveOptions = Factory::CreateIPdfSaveOptions();

// Uyumluluğu PDF/A-1b olarak ayarlayın.
pdfSaveOptions->SetCompliance(Aspose::Cells::Rendering::PdfCompliance_PdfA1b);

// veya PdfCompliance_PdfA1a 
// normal PDF için PdfCompliance_None olacaktır

// Excel Belgesini PDF formatında kaydedin
wkb->Save(u"output-converted-excel-workbook-to.pdf", pdfSaveOptions);



```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="PDF" >}}

{{% blocks/products/pf/feature-page-section h2="Excel\'i Görüntülere Kaydet" %}}
**C++ Excel Ayrıştırıcı**, verileri görüntü biçiminde dışa aktarma özelliğine sahiptir. Her çalışma sayfası, BMP, JPEG, PNG ve GIF gibi farklı görüntü biçimlerine dönüştürülebilir. [Oluşturma::IImageOrPrintOptions](https://apireference.aspose.com/cells/cpp/class/aspose.cells.rendering.i_image_or_print_options). Herhangi bir **Excel'i Görüntülere Dönüştür** vakası için bağlantılardan ilgili vakayı seçin.
{{% blocks/products/pf/feature-page-code h3="C++ Excel\'den Görüntüye Dönüştürme Kodu" %}}

```cs
// Çıkış dizini yolu.
StringPtr outDir = new String("ImagesOutputDirectoryPath");

// XLSX'i yükleyin.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"source-excel-file.xlsx");

// İlk çalışma sayfasına erişin.
intrusive_ptr<Aspose::Cells::IWorksheet> wks = wkb->GetIWorksheets()->GetObjectByIndex(0);

// Görüntü veya yazdırma seçenekleri nesnesi oluşturun.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Görüntü biçimini belirtin. Aşağıdaki kod JPEG içindir
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// GIF, BMP ve PNG gibi diğer resimler için sırasıyla GetGif(), GetBmp() ve GetPng() kullanılabilir 

// Yatay ve dikey çözünürlüğü belirtin
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Sayfayı belirtilen görüntü veya yazdırma seçeneklerine göre işleyin.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(wks, imgOptions);

// Sayfa sayısını alın.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Dize birleştirmeleri için dize oluşturucu nesnesi oluşturun.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Her sayfayı tek tek jpeg görüntüsüne dönüştürün.
for (int i = 0; i < pageCount; i++){
	// Dize oluşturucuyu temizleyin ve dize bitiştirmeleriyle çıktı görüntüsü yolu oluşturun.
	sb->Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));
	// Çıktı görüntü yolunu alın.
	StringPtr outputJPEG = sb->ToString();
	// Çalışma sayfasını resme dönüştürün.
	sr->ToImage(i, outputJPEG);
}

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xls-to-png csv-to-jpeg tsv-to-png xlsb-to-png xlsx-to-png ods-to-png spreadsheetml-to-bmp tabdelimited-to-gif xlsm-to-bmp xlt-to-gif xltm-to-png xltx-to-gif" >}}