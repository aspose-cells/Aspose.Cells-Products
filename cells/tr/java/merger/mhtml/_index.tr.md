---
title: MHTML Dosyalarını Java ile Birleştir 
weight: 4420
url: /tr/java/merger/mhtml/ 
description: JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment'da MHTML belgelerini birleştirmek için Java örnek kod.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java içindeki MHTML Biçimlerini Birleştir" h2="Sunucu tarafı Java API\'lerini kullanan yerel MHTML belgesi birleştirme." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java Kullanarak MHTML Dosyalarını Birleştirme" %}}

 MHTML dosyasını birleştirmek için kullanacağız
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 Zengin özelliklere sahip, güçlü ve kullanımı kolay bir birleştirme API for Java platformu olan API. En son sürümünü doğrudan adresinden indirebilirsiniz.
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

{{% blocks/products/pf/agp/feature-section-col title="Java İçindeki MHTML Dosyalarını Birleştirme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 İle birleşen ve birleştirilen temel bir belge
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API'ler sadece birkaç satır kod ile yapılabilir.

{{% /blocks/products/pf/agp/text %}}

+ İlk MHTML dosyasını Workbook sınıfının bir örneğiyle yükleyin.
+ İkinci MHTML belgesini Workbook sınıfının bir örneğiyle yükleyin.
+ Combine() yöntemini kullanarak dosyaları birleştirin.
+ birleştirilmiş MHTML dosyasını belirtilen yola kaydedin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java, tüm büyük platformlarda ve İşletim Sistemlerinde destekler. Lütfen aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.- Aspose.Cells for Java'in en son sürümünü doğrudan şu adresten edinin: [Uzman](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="MHTML Dosyalarını Birleştir - Java" offSpacer="" %}}

```cs
// İlk MHTML dosyasını açın.
Workbook mhtmlFile1 = new Workbook("chartsFileWithPath.mhtml");

// İkinci kaynak kitabı tanımlayın.
// İkinci MHTML dosyasını açın.
Workbook mhtmlFile2 = new Workbook("pictureFileWithPath.mhtml");

// İki çalışma kitabını birleştirmek
mhtmlFile1.combine(mhtmlFile2);

// Hedef kitap dosyasını kaydedin.
mhtmlFile1.save("combinedFileWithPath.mhtml");  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Cells for Java API hakkında" %}}

 Aspose.Cells API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi MHTML Birleşme Canlı Demoları" sectionDescription="MHTML belgelerini hemen şimdi ziyaret ederek birleştirin [Canlı Demolar web sitesi](https://products.aspose.app/cells/merger). Canlı demo aşağıdaki avantajlara sahiptir" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Sadece MHTML dosyalarınızı yükleyin." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anında birleştirilir ve birleştirilir." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}
MHTML uzantılı dosyalar, bir dizi farklı uygulama tarafından oluşturulabilen bir web sayfası arşiv biçimini temsil eder. Bu biçim, web HTML kodunu ve ilgili kaynakları tek bir dosyada kaydettiği için arşiv biçimi olarak bilinir. Bu kaynaklar, resimler, uygulamalar, animasyonlar, ses dosyaları vb. gibi web sayfasına bağlı her şeyi içerir. MHTML dosyaları, Internet Explorer ve Microsoft Word gibi çeşitli uygulamalarda açılabilir. Microsoft Windows, Windows'ta sorunlara neden olan herhangi bir uygulamanın kullanımı sırasında gözlemlenen sorunların senaryolarını kaydetmek için MHTML dosya biçimini kullanır. MHTML dosya formatı, düz metin e-posta ile ilgili spesifikasyonlar olan message/rfc822'de tanımlanan spesifikasyonlara benzer sayfa içeriklerini kodlar. Formatın gerçek özellikleri, RFC 2557 tarafından detaylandırıldığı gibidir. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Birleştirme Formatları" subTitle="Java kullanarak One, aşağıdakiler de dahil olmak üzere diğer birçok dosya biçimini birleştirebilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Virgülle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Sekmeyle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Metin belgesi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML Excel Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Excel Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Excel Makro Etkin Şablon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltx/" name="XLTX" description="Office OpenXML Excel Şablonu" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}