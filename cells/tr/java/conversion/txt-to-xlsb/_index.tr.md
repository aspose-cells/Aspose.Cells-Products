---
title: Java aracılığıyla TXT'yi XLSB'ye dönüştürün 
weight: 3360
url: /tr/java/conversion/txt-to-xlsb/ 
description: TXT biçimi için XLSB dosyasına örnek Java dönüştürme kodu. Programcılar, Excel ve OpenOffice elektronik tablolarını herhangi bir Web veya Masaüstü Java tabanlı Uygulamada XLSB'ye aktarmak için bu örnek kodu kullanabilir.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java aracılığıyla TXT\'yi XLSB\'ye dönüştürün" h2="Şirket İçi Java kitaplığını kullanarak tek veya birden çok sayfayı XLSB\'ye dönüştürmek için TXT\'den XLSB\'ye Java dönüştürme." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TXT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java Kullanarak TXT\'yi XLSB\'ye Dönüştürme" %}}

 TXT'yi XLSB'ye dönüştürmek için kullanacağız
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 Zengin özelliklere sahip, güçlü ve kullanımı kolay bir dönüşüm API for Java platformu olan API. En son sürümünü doğrudan adresinden indirebilirsiniz.
 [Uzman](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 ve pom.xml dosyasına aşağıdaki konfigürasyonları ekleyerek Maven tabanlı projenize kurun.

{{% blocks/products/pf/agp/code-block title="depo" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Bağımlılık" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Java aracılığıyla TXT\'yi XLSB\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Java geliştiricileri, yalnızca birkaç satır kodla TXT dosyasını kolayca XLSB'ye dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. TXT dosyasını Workbook sınıfının bir örneğiyle yükleyin1. Workbook.save yöntemini çağırın1. XLSB uzantısı ve SaveFormat ile çıktı yolunu parametre olarak iletin1. Ortaya çıkan XLSB dosyası için belirtilen yolu kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Java dönüştürme kaynak kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.- Aspose.Cells for Java'in en son sürümünü doğrudan Maven'den alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TXT\'den XLSB\'ye Java Dönüşüm Kaynak Kodu" offSpacer="" %}}

```cs
// TXT dosyasını bir Çalışma Kitabı örneğine yükleyin
Workbook book = new Workbook("template.txt");
// TXT'yi XLSB olarak kaydet
book.save("output.xlsb", SaveFormat.AUTO);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TXT\'den XLSB\'ye Dönüşüm Canlı Demoları" sectionDescription="[TXT\'yi XLSB\'ye Dönüştür](https://products.aspose.app/cells/conversion/txt-to-xlsb) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece TXT dosyanızı yükleyin, anında XLSB\'ye dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="Java Elektronik Tablo Manipülasyon Kitaplığı" %}}

 Excel API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells, bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TXT" readMoreLink="https://docs.fileformat.com/word-processing/txt/" >}}

.TXT uzantılı bir dosya, satırlar şeklinde düz metin içeren bir metin belgesini temsil eder. Bir metin belgesindeki paragraflar satır başlarıyla tanınır ve dosya içeriğinin daha iyi düzenlenmesi için kullanılır. Standart bir metin belgesi, farklı işletim sistemlerinde herhangi bir metin düzenleyicide veya kelime işlemci uygulamasında açılabilir. Böyle bir dosyada bulunan tüm metinler insan tarafından okunabilir biçimdedir ve karakter dizisiyle temsil edilir.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

XLSB dosya biçimi, Excel çalışma kitabı içeriğini belirten bir kayıtlar ve yapılar topluluğu olan Excel İkili Dosya Biçimi'ni belirtir. İçerik, yapılandırılmamış veya yarı yapılandırılmış sayı tabloları, metin veya hem sayılar hem de metin, formüller, harici veri bağlantıları, çizelgeler ve resimler içerebilir. (Açık XML dosya biçimine dayanan) XLSX'in aksine, XLSB ikili Excel çalışma kitabı dosyasını temsil eder. XLSB dosyaları daha hızlı okunabilir ve yazılabilir, bu da onları büyük dosyalarla çalışmak için kullanışlı hale getirir. XLSX (ve daha önce XLS), çalışma kitaplarını kaydetmek için en yaygın kullanıcı tarafından seçilen dosya biçimleri olduğundan, XLSB nadiren çalışma kitaplarını depolamak için kullanılır. Microsoft Office 2007 ve üzeri ile açılabilir.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca TXT\'yi aşağıda listelenen birkaç dosya formatına da dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-bmp/" name="TXT\'DEN BMP\'YE" description="Bitmap Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-csv/" name="TXT\'den CSV\'ye" description="Virgülle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-dif/" name="TXT\'DEN DIF\'E" description="Veri Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-emf/" name="TXT\'DEN EMF\'YE" description="Gelişmiş Meta Dosyası Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-gif/" name="TXT\'DEN GIF\'E" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-html/" name="TXT\'den HTML\'ye" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-jpeg/" name="TXT\'den JPEG\'e" description="JPEG Resmi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-mhtml/" name="TXT\'DEN MHTML\'YE" description="Web Sayfası Arşiv Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-ods/" name="TXT\'DEN ODS\'YE" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-pdf/" name="TXT\'DEN PDF\'E" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-png/" name="TXT\'den PNG\'ye" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-svg/" name="TXT\'DEN SVG\'YE" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-tiff/" name="TXT\'DEN TIFF\'E" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-tsv/" name="TXT\'den TSV\'ye" description="Sekmeyle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xlm/" name="TXT\'DEN XLM\'YE" description="Excel Makro Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xls/" name="TXT\'DEN XLS\'YE" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xlsx/" name="TXT\'DEN XLSX\'E" description="OOXML Excel Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xlt/" name="TXT\'DEN XLT\'YE" description="Microsoft Excel Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xltm/" name="TXT\'DEN XLTM\'YE" description="Excel Makro Etkin Şablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xltx/" name="TXT\'DEN XLTX\'E" description="Office OpenXML Excel Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-xps/" name="TXT\'DEN XPS\'E" description="XML Kağıt Özellikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/txt-to-json/" name="TXT\'DEN JSON\'A" description="JavaScript Nesnesi Gösterimi" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}