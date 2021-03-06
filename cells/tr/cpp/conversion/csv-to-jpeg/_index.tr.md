---
title: C++ uygulaması aracılığıyla CSV'yi JPEG'e dönüştürün 
weight: 1280
url: /tr/cpp/conversion/csv-to-jpeg/ 
description: CSV belgesi için JPEG formatına örnek C++ dönüştürme kodu. Programcılar, herhangi bir C++ Uygulamasında toplu CSV'den JPEG'e dönüştürme için bu kaynak kodunu kullanabilir.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++ aracılığıyla CSV\'yi JPEG\'e dönüştürün" h2="Microsoft Excel, OpenOffice veya Adobe Acrobat kurulumuna ihtiyaç duymadan C++ kitaplığını kullanarak yüksek performanslı CSV\'den JPEG\'e dönüştürme." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanarak CSV\'yi JPEG\'e Dönüştürme" %}}

 CSV'yi JPEG'e dönüştürmek için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="C++ aracılığıyla CSV\'yi JPEG\'e Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 C++ geliştiricileri, yalnızca birkaç satır kodla CSV dosyasını kolayca JPEG'e dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. Factory::CreateIWorkbook'u kullanarak CSV dosyasını yükleyin.1. İlk çalışma sayfasını seçin.1. (JPEG) seçeneklerini ayarlayın.1. Sayfanın her sayfasını yineleyin ve oluşturun.1. JPEG dosyasını uyumlu programda açın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 C++ dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.- Projenizde başvurulan C++ DLL için Aspose.Cells.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="CSV\'den JPEG\'e C++ Dönüştürme Kaynak Kodu" offSpacer="" %}}

```cs
// Çıkış dizini yolu.
StringPtr outDir = new String("OutputDirectoryPath");

// CSV'yi yükleyin.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.csv");

// İlk çalışma sayfasına erişin.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Görüntü veya yazdırma seçenekleri nesnesi oluşturun.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Görüntü biçimini belirtin.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetJpeg());

// Yatay ve dikey çözünürlüğü belirtin
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Sayfayı belirtilen görüntü veya yazdırma seçeneklerine göre işleyin.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Sayfa sayısını alın.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Dize birleştirmeleri için dize oluşturucu nesnesi oluşturun.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Her sayfayı tek tek jpeg görüntüsüne dönüştürün.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageJPEG_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".jpeg"));

	// Çıktı görüntü yolunu alın.
	StringPtr outputJPEG = sb->ToString();

	// Çalışma sayfasını jpeg görüntüsüne dönüştürün.
	sr->ToImage(i, outputJPEG);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="CSV\'den JPEG\'e Dönüştürme Canlı Demoları" sectionDescription="[CSV\'yi JPEG\'e Dönüştür](https://products.aspose.app/cells/conversion/csv-to-jpeg) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece CSV dosyanızı yükleyin, anında JPEG\'e dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel Dosya Manipülasyon Kitaplığı" %}}

 Excel API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells, bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

CSV (Virgülle Ayrılmış Değerler) uzantılı dosyalar, virgülle ayrılmış değerlere sahip veri kayıtlarını içeren düz metin dosyalarını temsil eder. CSV dosyasındaki her satır, dosyada bulunan kayıt kümesinden yeni bir kayıttır. Bu tür dosyalar, bir depolama sisteminden diğerine veri aktarımı amaçlandığında oluşturulur. Tüm uygulamalar virgülle ayrılmış kayıtları tanıyabildiğinden, bu tür veri dosyalarının veri tabanına aktarılması çok rahat bir şekilde yapılır. Microsoft Excel veya OpenOffice Calc gibi hemen hemen tüm elektronik tablo uygulamaları, fazla çaba harcamadan CSV'yi içe aktarabilir. Bu tür dosyalardan içe aktarılan veriler, kullanıcıya sunulmak üzere bir elektronik tablonun hücrelerinde düzenlenir.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}

JPEG, kayıplı sıkıştırma yöntemi kullanılarak kaydedilen bir görüntü formatı türüdür. Sıkıştırmanın bir sonucu olarak çıktı görüntüsü, depolama boyutu ve görüntü kalitesi arasında bir dengedir. Kullanıcılar, istenen kalite seviyesine ulaşmak için sıkıştırma seviyesini ayarlayabilir ve aynı zamanda depolama boyutunu küçültebilir. Görüntüye 10:1 sıkıştırma uygulanırsa görüntü kalitesi ihmal edilebilir düzeyde etkilenir. Sıkıştırma değeri ne kadar yüksek olursa, görüntü kalitesindeki bozulma o kadar yüksek olur. JPEG görüntü dosyası formatı, Joint Photographic Experts Group tarafından standartlaştırıldı ve dolayısıyla JPEG adı verildi. Format, fotoğrafik görüntülerin web üzerinde depolanması ve iletilmesi seçimi olmuştur. Hemen hemen tüm İşletim sistemlerinde artık, genellikle JPG uzantısıyla da saklanan JPEG görüntülerinin görselleştirilmesini destekleyen görüntüleyiciler var. Web tarayıcıları bile JPEG resimlerin görselleştirilmesini destekler.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca CSV\'yi aşağıda listelenen birkaç dosya biçimi de dahil olmak üzere birçok başka dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-bmp/" name="CSV\'DEN BMP\'YE" description="Bitmap Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-dif/" name="CSV\'DEN DIF\'E" description="Veri Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-emf/" name="CSV\'DEN EMF\'YE" description="Gelişmiş Meta Dosyası Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-gif/" name="CSV\'den GIF\'e" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-html/" name="CSV\'den HTML\'ye" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-mhtml/" name="CSV\'den MHTML\'ye" description="Web Sayfası Arşiv Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-ods/" name="CSV\'den ODS\'ye" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-pdf/" name="CSV\'den PDF\'ye" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-png/" name="CSV\'den PNG\'ye" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-svg/" name="CSV\'den SVG\'ye" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tiff/" name="CSV\'DEN TIFF\'E" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tsv/" name="CSV\'den TSV\'ye" description="Sekmeyle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xls/" name="CSV\'den XLS\'ye" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsb/" name="CSV\'den XLSB\'ye" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsm/" name="CSV\'den XLSM\'ye" description="Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsx/" name="CSV\'den XLSX\'e" description="OOXML Excel Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltm/" name="CSV\'den XLTM\'ye" description="Excel Makro Etkin Şablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltx/" name="CSV\'den XLTX\'e" description="Office OpenXML Excel Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xps/" name="CSV\'den XPS\'ye" description="XML Kağıt Özellikleri" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}