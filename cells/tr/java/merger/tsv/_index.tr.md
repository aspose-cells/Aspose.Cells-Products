---
title:  TSV Dosyalarını Birleştir via Java
weight: 9260
description: JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Çalışma Zamanı Ortamı'nda TSV belgelerini birleştirmek için Java örnek kod.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TSV Formatlarını Java\'de Birleştir" h2="Sunucu tarafı Java API\'lerini kullanan yerel TSV belge birleştirme." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="TSV Dosyalarını Java Kullanarak Birleştirme" %}}

 TSV dosyasını birleştirmek için kullanacağız[Aspose.Cells for Java](https://products.aspose.com/cells/java) Zengin özelliklere sahip, güçlü ve kullanımı kolay bir API birleştirme platformu olan API for Java. En son sürümünü doğrudan adresinden indirebilirsiniz.[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) ve aşağıdaki yapılandırmaları pom.xml dosyasına ekleyerek Maven tabanlı projenize kurun.

{{% blocks/products/pf/agp/code-block title="Depo" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="TSV Dosyalarını Java\'de Birleştirme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Birleştiren ve birleştiren temel bir belge[Aspose.Cells for Java](https://products.aspose.com/cells/java) API'ler yalnızca birkaç satır kodla yapılabilir.

{{% /blocks/products/pf/agp/text %}}

+ İlk TSV dosyasını Workbook sınıfının bir örneğiyle yükleyin.
+ İkinci TSV belgesini Workbook sınıfının bir örneğiyle yükleyin.
+ Combine() yöntemini kullanarak dosyaları birleştirin.
+ birleştirilmiş TSV dosyasını belirtilen yola kaydedin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java tüm önemli platformları ve İşletim Sistemlerini destekler. Lütfen aşağıdaki önkoşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Çalışma Zamanı Ortamı ile uyumlu bir işletim sistemi.
-  Aspose.Cells for Java'in en son sürümünü doğrudan şu adresten edinin:
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSV Dosyalarını Birleştir - Java" offSpacer="" %}}

```cs
// Open the first TSV file.
Workbook tsvFile1 = new Workbook("chartsFileWithPath.tsv");

// Define the second source book.
// Open the second TSV file.
Workbook tsvFile2 = new Workbook("pictureFileWithPath.tsv");

// Combining the two workbooks
tsvFile1.combine(tsvFile2);

// Save the target book file.
tsvFile1.save("combinedFileWithPath.tsv");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi TSV Birleşme Canlı Demoları" sectionDescription=" TSV belgemizi hemen ziyaret ederek birleştirin[Canlı Demolar web sitesi](https://products.aspose.app/cells/merger). Canlı demo aşağıdaki avantajlara sahiptir" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API\'i indirmenize gerek yok." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="TSV dosyalarınızı yüklemeniz yeterli." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anında birleştirilecek ve birleştirilecektir." >}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Cells for Java API Hakkında" %}}

 Aspose.Cells API, Microsoft Excel formatlarını oluşturmak, düzenlemek, dönüştürmek ve farklı formatlara dönüştürmek için kullanılabilir. Ayrıca yazılım uygulamalarında kapsamlı grafik oluşturma, ölçeklenebilir raporlama ve güvenilir hesaplamalar için de kullanılabilir. Aspose.Cells bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}


        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
Sekmeyle Ayrılmış Değerler (TSV) dosya biçimi, düz metin biçiminde sekmelerle ayrılmış verileri temsil eder. CSV'e benzer dosya formatı, farklı uygulamalar arasında içe ve dışa aktarma amacıyla verilerin yapılandırılmış bir şekilde düzenlenmesi için kullanılır. Format öncelikle Elektronik Tablo uygulamalarında ve veritabanlarında veri içe/dışa aktarma ve alışverişi için kullanılır. TSV dosyasındaki her kayıt, her alan değerinin bir sekme karakteriyle ayrıldığı tek satırlık bir metin dosyasında bulunur. TSV dosya biçimi için ortam türü, metin/sekmeyle ayrılmış değerlerdir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Birleştirme Formatları" subTitle="Java\'i kullanarak, One ayrıca .. dahil olmak üzere diğer birçok dosya formatını da birleştirebilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Virgülle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Web Sayfası Arşiv Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Metin belgesi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML Excel Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Excel Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Excel Makro Etkin Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltx/" name="XLTX" description="Office OpenXML Excel Şablonu" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
