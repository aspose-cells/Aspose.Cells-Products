---
title: Java aracılığıyla XLS'yi MD'ye dönüştürün 
url: /tr/java/conversion/xls-to-md/ 
description: XLS formatı için MD dosyasına örnek Java dönüştürme kodu. Programcılar, Excel ve OpenOffice elektronik tablolarını herhangi bir Web veya Masaüstü Java tabanlı Uygulamada MD'ye aktarmak için bu örnek kodu kullanabilir.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java aracılığıyla XLS\'yi MD\'ye dönüştürün" h2="Şirket içi Java kitaplığını kullanarak tek veya birden çok sayfayı MD\'ye dönüştürmek için XLS\'den MD\'ye Java dönüştürme." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="MD" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java Kullanarak XLS\'yi MD\'ye Dönüştürme" %}}

 XLS'yi MD'ye dönüştürmek için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="Java aracılığıyla XLS\'yi MD\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Java geliştiricileri, yalnızca birkaç satır kodla XLS dosyasını kolayca MD'ye dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. XLS dosyasını Workbook sınıfının bir örneğiyle yükleyin1. Workbook.save yöntemini çağırın1. MD uzantısı ve SaveFormat ile çıktı yolunu parametre olarak iletin1. Ortaya çıkan MD dosyası için belirtilen yolu kontrol edin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Java dönüştürme kaynak kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.- Aspose.Cells for Java'in en son sürümünü doğrudan Maven'den alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS - MD Java Dönüşüm Kaynak Kodu" offSpacer="" %}}

```cs
// XLS dosyasını bir Çalışma Kitabı örneğine yükleyin
Workbook book = new Workbook("template.xls");
// XLS'yi MD olarak kaydet
book.save("output.md", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLS\'den MD\'ye Dönüştürme Canlı Demoları" sectionDescription="[XLS\'yi MD\'ye dönüştür](https://products.aspose.app/cells/conversion/xls-to-md) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece XLS dosyanızı yükleyin, anında MD\'ye dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="Java Elektronik Tablo Manipülasyon Kitaplığı" %}}

 Excel API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells, bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}

XLS uzantılı dosyalar Excel İkili Dosya Formatını temsil eder. Bu tür dosyalar, Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi diğer benzer elektronik tablo programları tarafından oluşturulabilir. Excel tarafından kaydedilen dosya, her çalışma kitabının bir veya daha fazla çalışma sayfasına sahip olabileceği Çalışma Kitabı olarak bilinir. Veriler, çalışma sayfasında tablo biçiminde depolanır ve kullanıcılara gösterilir ve sayısal değerleri, metin verilerini, formülleri, harici veri bağlantılarını, görüntüleri ve çizelgeleri kapsayabilir. Microsoft Excel gibi uygulamalar, çalışma kitabı verilerini PDF, CSV, XLSX, TXT, HTML, XPS ve diğerleri dahil olmak üzere birkaç farklı biçime aktarmanıza olanak tanır. XLS dosya biçimi, Microsoft Excel 2007'nin piyasaya sürülmesiyle daha açık ve yapılandırılmış bir biçim olan XLSX ile değiştirildi. En son sürümler, XLS dosyalarının oluşturulması ve okunması için hala destek sağlıyor, ancak XLSX artık ilk kullanım tercihi.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MD" readMoreLink="https://docs.fileformat.com/word-processing/md/" >}}

Markdown dil lehçeleriyle oluşturulan metin dosyaları .MD veya .MARKDOWN dosya uzantısıyla kaydedilir. MD dosyaları, satır içi metin sembollerini de içeren ve girintiler, tablo biçimlendirmesi, yazı tipleri ve başlıklar gibi bir metnin nasıl biçimlendirilebileceğini tanımlayan Markdown dilini kullanan düz metin biçiminde kaydedilir. MD dosyaları, Markdown adlı bir programla HTML'ye dönüştürülebilir. Markdown dili John Gruber tarafından yayınlandı.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca XLS\'yi aşağıda listelenen birkaç dosya biçimi de dahil olmak üzere birçok başka dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-bmp/" name="XLS\'DEN BMP\'YE" description="Bitmap Görüntüsü" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-csv/" name="XLS\'den CSV\'ye" description="Virgülle Ayrılmış Değerler" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-dif/" name="FARK İÇİN XLS" description="Veri Değişim Formatı" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-emf/" name="EMF\'YE XLS" description="Gelişmiş Meta Dosyası Formatı" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-gif/" name="GIF\'E XLS" description="Grafik Değişim Formatı" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-html/" name="XLS\'den HTML\'ye" description="Hiper Metin İşaretleme Dili" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-jpeg/" name="XLS\'den JPEG\'e" description="JPEG Resmi" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-mhtml/" name="XLS\'den MHTML\'ye" description="Web Sayfası Arşiv Formatı" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-ods/" name="ODS\'YE XLS" description="OpenDocument Elektronik Tablo Dosyası" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-pdf/" name="XLS\'DEN PDF\'E" description="Taşınabilir Döküman Formatı" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-png/" name="PNG\'ye XLS" description="taşınabilir Ağ Grafikleri" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-svg/" name="XLS\'DEN SVG\'YE" description="ölçeklendirilebilir Vektör Grafiği" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-tiff/" name="XLS\'DEN TIFF\'E" description="Etiketli Görüntü Formatı" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-tsv/" name="XLS\'den TSV\'ye" description="Sekmeyle Ayrılmış Değerler" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-txt/" name="XLS\'den TXT\'ye" description="Metin belgesi" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsb/" name="XLS\'DEN XLSB\'YE" description="İkili Excel Çalışma Kitabı Dosyası" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsm/" name="XLS\'DEN XLSM\'YE" description="Elektronik Tablo Dosyası" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlsx/" name="XLS\'DEN XLSX\'E" description="OOXML Excel Dosyası" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xlt/" name="XLS\'den XLT\'ye" description="Microsoft Excel Şablonu" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xltm/" name="XLS\'DEN XLTM\'YE" description="Excel Makro Etkin Şablon" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xltx/" name="XLS\'DEN XLTX\'E" description="Office OpenXML Excel Şablonu" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-xps/" name="XLS\'DEN XPS\'E" description="XML Kağıt Özellikleri" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/xls-to-json/" name="XLS\'DEN JSON\'A" description="JavaScript Nesnesi Gösterimi" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}