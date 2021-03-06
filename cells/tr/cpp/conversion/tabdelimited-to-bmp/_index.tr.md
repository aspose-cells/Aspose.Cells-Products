---
title: C++ uygulaması aracılığıyla TABDELIMITED'i BMP'ye dönüştürün 
url: /tr/cpp/conversion/tabdelimited-to-bmp/ 
description: TABDELIMITED belgesi için BMP biçimine örnek C++ dönüştürme kodu. Programcılar bu kaynak kodunu herhangi bir C++ Uygulamasında toplu TABDELIMITED'den BMP'ye dönüştürmek için kullanabilirler.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TABDELIMITED\'i C++ aracılığıyla BMP\'ye dönüştürün" h2="Microsoft Excel, OpenOffice veya Adobe Acrobat kurulumuna ihtiyaç duymadan C++ kitaplığını kullanarak yüksek performanslı TABDELIMITED\'den BMP\'ye dönüştürme." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TABDELIMITED" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanarak TABDELIMITED\'i BMP\'ye Dönüştürme" %}}

 TABDELIMITED'i BMP'ye dönüştürmek için kullanacağız
 [C++ için Aspose.Cells](https://products.aspose.com/cells/cpp) 
 C++ platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge işleme ve dönüştürme API olan API. En son sürümünü doğrudan indirebilirsiniz, sadece açın
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 paket yöneticisi, ara
 Aspose.Cells.Cpp 
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Emretmek" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++ üzerinden TABDELIMITED\'i BMP\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 C++ geliştiricileri, TABDELIMITED dosyasını yalnızca birkaç satır kodla kolayca BMP'ye dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. TABDELIMITED dosyasını Factory::CreateIWorkbook kullanarak yükleyin.1. İlk çalışma sayfasını seçin.1. (BMP) seçeneklerini ayarlayın.1. Sayfanın her sayfasını yineleyin ve oluşturun.1. BMP dosyasını uyumlu programda açın.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 C++ dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.- Projenizde başvurulan C++ DLL için Aspose.Cells.
- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.- Projenizde başvurulan C++ DLL için Aspose.Cells.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TABDELIMITED - BMP C++ Dönüşüm Kaynak Kodu" offSpacer="" %}}

```cs
// Çıkış dizini yolu.
StringPtr outDir = new String("OutputDirectoryPath");

// TABDELIMITED'i yükleyin.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.tabdelimited");

// İlk çalışma sayfasına erişin.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Görüntü veya yazdırma seçenekleri nesnesi oluşturun.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Görüntü biçimini belirtin.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetBmp());

// Yatay ve dikey çözünürlüğü belirtin
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Sayfayı belirtilen görüntü veya yazdırma seçeneklerine göre işleyin.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Sayfa sayısını alın.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Dize birleştirmeleri için dize oluşturucu nesnesi oluşturun.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Her sayfayı tek tek bmp görüntüye dönüştürün.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageBMP_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".bmp"));

	// Çıktı görüntü yolunu alın.
	StringPtr outputBMP = sb->ToString();

	// Çalışma sayfasını bmp görüntüsüne dönüştürün.
	sr->ToImage(i, outputBMP);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TABDELIMITED\'den BMP\'ye Dönüşüm Canlı Demoları" sectionDescription="[TABDELIMITED\'yi BMP\'ye dönüştür](https://products.aspose.app/cells/conversion/tabdelimited-to-bmp) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" TABDELIMITED dosyanızı yüklemeniz yeterlidir, anında BMP\'ye dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel Dosya Manipülasyon Kitaplığı" %}}

 Excel API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells, bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" >}}

.BMP uzantısına sahip dosyalar, bitmap dijital görüntüleri depolamak için kullanılan Bitmap Görüntü dosyalarını temsil eder. Bu görüntüler grafik bağdaştırıcısından bağımsızdır ve aygıttan bağımsız bit eşlem (DIB) dosya biçimi olarak da adlandırılır. Bu bağımsızlık, dosyayı Microsoft Windows ve Mac gibi birden çok platformda açma amacına hizmet eder. BMP dosya formatı, verileri hem monokrom hem de çeşitli renk derinliklerine sahip renkli formatta iki boyutlu dijital görüntüler olarak saklayabilir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}