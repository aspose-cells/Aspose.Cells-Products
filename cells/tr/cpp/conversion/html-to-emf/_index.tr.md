---
title: C++ uygulaması aracılığıyla HTML'yi EMF'ye dönüştürün 
weight: 8550
url: /tr/cpp/conversion/html-to-emf/ 
description: HTML belgesini EMF biçimine dönüştürmek için örnek C++ dönüştürme kodu. Programcılar, herhangi bir C++ Uygulamasında toplu HTML'den EMF'ye dönüştürme için bu kaynak kodunu kullanabilir.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++ aracılığıyla HTML\'yi EMF\'ye dönüştürün" h2="Microsoft Excel, OpenOffice veya Adobe Acrobat kurulumuna gerek kalmadan C++ kitaplığını kullanarak yüksek performanslı HTML\'den EMF\'ye dönüştürme." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="HTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanarak HTML\'yi EMF\'ye Dönüştürme" %}}

 HTML'yi EMF'ye dönüştürmek için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="C++ aracılığıyla HTML\'yi EMF\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 C++ geliştiricileri, HTML dosyasını yalnızca birkaç satır kodla kolayca EMF'ye dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. Factory::CreateIWorkbook kullanarak HTML dosyasını yükleyin.1. İlk çalışma sayfasını seçin.1. (EMF) seçeneklerini ayarlayın.1. Sayfanın her sayfasını yineleyin ve oluşturun.1. EMF dosyasını uyumlu programda açın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 C++ dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.- Projenizde başvurulan C++ DLL için Aspose.Cells.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="HTML\'den EMF\'ye C++ Dönüşüm Kaynak Kodu" offSpacer="" %}}

```cs
// Çıkış dizini yolu.
StringPtr outDir = new String("OutputDirectoryPath");

// HTML'yi yükleyin.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.html");

// İlk çalışma sayfasına erişin.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Görüntü veya yazdırma seçenekleri nesnesi oluşturun.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Görüntü biçimini belirtin.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetEmf());

// Yatay ve dikey çözünürlüğü belirtin
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Sayfayı belirtilen görüntü veya yazdırma seçeneklerine göre işleyin.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Sayfa sayısını alın.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Dize birleştirmeleri için dize oluşturucu nesnesi oluşturun.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Her sayfayı tek tek emf görüntüsüne dönüştürün.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageEMF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".emf"));

	// Çıktı görüntü yolunu alın.
	StringPtr outputEMF = sb->ToString();

	// Çalışma sayfasını emf görüntüsüne dönüştürün.
	sr->ToImage(i, outputEMF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="HTML\'den EMF\'ye Dönüştürme Canlı Demoları" sectionDescription="[HTML\'yi EMF\'ye Dönüştür](https://products.aspose.app/cells/conversion/html-to-emf) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece HTML dosyanızı yükleyin, anında EMF\'ye dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel Dosya Manipülasyon Kitaplığı" %}}

 Excel API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells, bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language), tarayıcılarda görüntülenmek üzere oluşturulmuş web sayfalarının uzantısıdır. Web dili olarak bilinen HTML, web sayfalarının bir parçası olarak görüntülenecek yeni bilgi gereksinimlerinin gereksinimleriyle gelişmiştir. En son varyant, dille çalışmak için çok fazla esneklik sağlayan HTML 5 olarak bilinir. HTML sayfaları, barındırıldığı sunucudan alınır veya yerel sistemden de yüklenebilir. Her HTML sayfası, formlar, metinler, resimler, animasyonlar, bağlantılar vb. gibi HTML öğelerinden oluşur. Bu öğeler, img, a, p gibi etiketlerle ve her etiketin başladığı ve bittiği diğer birkaç etiketle temsil edilir. Ayrıca, genel düzen gösterimi için JavaScript ve Stil Sayfaları (CSS) gibi komut dosyası dillerinde yazılmış uygulamaları da gömebilir.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" >}}

Gelişmiş meta dosya biçimi (EMF), grafik görüntüleri aygıttan bağımsız olarak depolar. EMF'nin meta dosyaları, herhangi bir çıktı aygıtında ayrıştırıldıktan sonra saklanan görüntüyü oluşturabilen, kronolojik sırayla değişken uzunluktaki kayıtlardan oluşur. Bu değişken uzunluklu kayıtlar, kapalı nesnelerin tanımları, çizim komutları ve görüntüyü doğru bir şekilde oluşturmak için kritik olan grafik özellikleri olabilir. Bir cihaz kendi grafik ortamını kullanarak bir EMF meta dosyasını açtığında, orijinal görüntünün oranları, boyutları, renkleri ve diğer grafik özellikleri, açılış cihazı platformundan bağımsız olarak aynı kalır.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca HTML\'yi aşağıda listelenen birkaç dosya biçimine de dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-bmp/" name="HTML\'DEN BMP\'YE" description="Bitmap Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-csv/" name="HTML\'den CSV\'ye" description="Virgülle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-dif/" name="DIF İÇİN HTML" description="Veri Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-gif/" name="HTML\'den GIF\'e" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-jpeg/" name="HTML\'den JPEG\'e" description="JPEG Resmi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-mhtml/" name="HTML\'den MHTML\'ye" description="Web Sayfası Arşiv Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-ods/" name="HTML\'den ODS\'ye" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-pdf/" name="HTML\'den PDF\'ye" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-png/" name="HTML\'den PNG\'ye" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-svg/" name="HTML\'den SVG\'ye" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tiff/" name="HTML\'den TIFF\'E" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-tsv/" name="HTML\'den TSV\'ye" description="Sekmeyle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xls/" name="HTML\'den XLS\'ye" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsb/" name="HTML\'den XLSB\'ye" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsm/" name="HTML\'den XLSM\'ye" description="Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xlsx/" name="HTML\'den XLSX\'e" description="OOXML Excel Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltm/" name="HTML\'den XLTM\'ye" description="Excel Makro Etkin Şablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xltx/" name="HTML\'den XLTX\'e" description="Office OpenXML Excel Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/html-to-xps/" name="HTML\'den XPS\'e" description="XML Kağıt Özellikleri" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}