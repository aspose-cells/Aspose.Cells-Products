---
title: C++ uygulaması aracılığıyla XLS'yi XLSB'ye dönüştürün 
weight: 9080
url: /tr/cpp/conversion/xls-to-xlsb/ 
description: XLS belgesi için XLSB biçimine örnek C++ dönüştürme kodu. Programcılar, herhangi bir C++ Uygulamasında toplu XLS'den XLSB'ye dönüştürme için bu kaynak kodunu kullanabilir.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++ aracılığıyla XLS\'yi XLSB\'ye dönüştürün" h2="Microsoft Excel, OpenOffice veya Adobe Acrobat kurulumuna gerek kalmadan C++ kitaplığını kullanarak yüksek performanslı XLS\'den XLSB\'ye dönüştürme." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanarak XLS\'yi XLSB\'ye Dönüştürme" %}}

 XLS'yi XLSB'ye dönüştürmek için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="C++ aracılığıyla XLS\'yi XLSB\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 C++ geliştiricileri, XLS dosyasını yalnızca birkaç kod satırıyla kolayca XLSB'ye dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. Factory::CreateIWorkbook kullanarak XLS dosyasını yükleyin.1. Save() yöntemini çağırın.1. Çıktı dosyası yolunu (XLSB) dosya uzantısıyla iletin.1. XLSB dosyası belirtilen yola kaydedilecektir.1. XLSB dosyasını uyumlu programda açın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 C++ dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.- Projenizde başvurulan C++ DLL için Aspose.Cells.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS - XLSB C++ Dönüşüm Kaynak Kodu" offSpacer="" %}}

```cs
// XLS'yi yükleyin.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xls");

// XLSB formatında kaydedin.
wkb->Save(u"convertedFile.xlsb", SaveFormat_Xlsb);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLS\'den XLSB\'ye Dönüştürme Canlı Demoları" sectionDescription="[XLS\'yi XLSB\'ye dönüştür](https://products.aspose.app/cells/conversion/xls-to-xlsb) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece XLS dosyanızı yükleyin, anında XLSB\'ye dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel Dosya Manipülasyon Kitaplığı" %}}

 Excel API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells, bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

XLS uzantılı dosyalar Excel İkili Dosya Formatını temsil eder. Bu tür dosyalar, Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi diğer benzer elektronik tablo programları tarafından oluşturulabilir. Excel tarafından kaydedilen dosya, her çalışma kitabının bir veya daha fazla çalışma sayfasına sahip olabileceği Çalışma Kitabı olarak bilinir. Veriler, çalışma sayfasında tablo biçiminde depolanır ve kullanıcılara gösterilir ve sayısal değerleri, metin verilerini, formülleri, harici veri bağlantılarını, görüntüleri ve çizelgeleri kapsayabilir. Microsoft Excel gibi uygulamalar, çalışma kitabı verilerini PDF, CSV, XLSX, TXT, HTML, XPS ve diğerleri dahil olmak üzere birkaç farklı biçime aktarmanıza olanak tanır. XLS dosya biçimi, Microsoft Excel 2007'nin piyasaya sürülmesiyle daha açık ve yapılandırılmış bir biçim olan XLSX ile değiştirildi. En son sürümler, XLS dosyalarının oluşturulması ve okunması için hala destek sağlıyor, ancak XLSX artık ilk kullanım tercihi.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

XLSB dosya biçimi, Excel çalışma kitabı içeriğini belirten bir kayıtlar ve yapılar topluluğu olan Excel İkili Dosya Biçimi'ni belirtir. İçerik, yapılandırılmamış veya yarı yapılandırılmış sayı tabloları, metin veya hem sayılar hem de metin, formüller, harici veri bağlantıları, çizelgeler ve resimler içerebilir. (Açık XML dosya biçimine dayanan) XLSX'in aksine, XLSB ikili Excel çalışma kitabı dosyasını temsil eder. XLSB dosyaları daha hızlı okunabilir ve yazılabilir, bu da onları büyük dosyalarla çalışmak için kullanışlı hale getirir. XLSX (ve daha önce XLS), çalışma kitaplarını kaydetmek için en yaygın kullanıcı tarafından seçilen dosya biçimleri olduğundan, XLSB nadiren çalışma kitaplarını depolamak için kullanılır. Microsoft Office 2007 ve üzeri ile açılabilir.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca XLS\'yi aşağıda listelenen birkaç dosya biçimi de dahil olmak üzere birçok başka dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-bmp/" name="XLS\'DEN BMP\'YE" description="Bitmap Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-csv/" name="XLS\'den CSV\'ye" description="Virgülle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-dif/" name="FARK İÇİN XLS" description="Veri Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-emf/" name="EMF\'YE XLS" description="Gelişmiş Meta Dosyası Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-gif/" name="GIF\'E XLS" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-html/" name="XLS\'den HTML\'ye" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-jpeg/" name="XLS\'den JPEG\'e" description="JPEG Resmi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-mhtml/" name="XLS\'den MHTML\'ye" description="Web Sayfası Arşiv Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-ods/" name="ODS\'YE XLS" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-pdf/" name="XLS\'DEN PDF\'E" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-png/" name="PNG\'ye XLS" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-svg/" name="XLS\'DEN SVG\'YE" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tiff/" name="XLS\'DEN TIFF\'E" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-tsv/" name="XLS\'den TSV\'ye" description="Sekmeyle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsm/" name="XLS\'DEN XLSM\'YE" description="Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xlsx/" name="XLS\'DEN XLSX\'E" description="OOXML Excel Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltm/" name="XLS\'DEN XLTM\'YE" description="Excel Makro Etkin Şablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xltx/" name="XLS\'DEN XLTX\'E" description="Office OpenXML Excel Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/xls-to-xps/" name="XLS\'DEN XPS\'E" description="XML Kağıt Özellikleri" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}