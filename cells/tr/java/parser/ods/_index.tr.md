---
title: Java aracılığıyla ODS belgesinden metin ve resim ayıklayın 
weight: 4740
url: /tr/java/parser/ods/ 
description: JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment'daki ODS dosyasından metin ve resimleri çıkarmak için Java örnek kod.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ODS Biçimlerini Java içinde ayrıştırın" h2="Microsoft veya Adobe PDF gibi herhangi bir yazılım kullanmadan sunucu tarafı Aspose.Cells for Java API\'lerini kullanarak yerel ve yüksek performanslı ODS belgesi ayrıştırma." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Java Kullanarak ODS Dosyasını Ayrıştırma" %}}

 ODS dosyasını ayrıştırmak için kullanacağız
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API, zengin özelliklere sahip, güçlü ve kullanımı kolay bir ayrıştırma API for Java platformudur. En son sürümünü doğrudan adresinden indirebilirsiniz.
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

{{% blocks/products/pf/agp/feature-section-col title="Java içinde ODS Dosyalarını Ayrıştırma Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 ile temel bir belge ayrıştırma
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API'ler sadece birkaç satır kod ile yapılabilir. Microsoft Excel XLS, XLSX, XLSM, XLSB ve OpenDocument ODS dosyalarından metin ve görüntüleri ayrıştırın.

{{% /blocks/products/pf/agp/text %}}

+ Çalışma Kitabı sınıfını kullanarak ODS belgesini yükleyin.
+ getWorksheets().get yöntemini kullanarak gerekli sayfayı seçin.
+ getCells() kullanarak seçilen sayfanın tüm hücrelerini alın.
+ Her hücreyi yineleyin, metnini alın.
+ Her hücre değerini yazdırın veya bir bütün olarak görüntülemek için StringBuilder append() yöntemini kullanın

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java, tüm büyük platformlarda ve İşletim Sistemlerinde destekler. Lütfen aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.- Aspose.Cells for Java'in en son sürümünü doğrudan şu adresten edinin: [Uzman](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODS Dosyalarını Ayrıştırma - Java" offSpacer="" %}}

```cs
StringBuilder stringBuilder = new StringBuilder();
Workbook book = new Workbook(dir + "book1.ods");
Worksheet sheet = book.getWorksheets().get(0);
Cells cells = sheet.getCells();
Iterator iterator = cells.iterator();
while(iterator.hasNext())
{
Cell cell = (Cell)iterator.next();
stringBuilder.append(cell.getStringValue());
stringBuilder.append(" ");
}
System.out.println(stringBuilder.toString());  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Aspose.Cells for Java API hakkında" %}}

 Aspose.Cells API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi ODS Ayrıştırıcı Canlı Demoları" sectionDescription="Şu anda sayfamızı ziyaret ederek ODS belgelerinden metin ve resim ayıklayın. [Canlı Demolar web sitesi](https://products.aspose.app/cells/parser). Canlı demo aşağıdaki avantajlara sahiptir" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece ODS dosyalarınızı yükleyin." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anında ayrıştırılacaktır." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
ODS uzantılı dosyalar, kullanıcı tarafından düzenlenebilen OpenDocument Elektronik Tablo Belgesi formatı anlamına gelir. Veriler, ODF dosyası içinde satırlar ve sütunlar halinde saklanır. XML tabanlı bir biçimdir ve Açık Belge Biçimleri (ODF) ailesindeki birkaç alt türden biridir. Format, OASIS tarafından yayınlanan ve sürdürülen ODF 1.2 spesifikasyonlarının bir parçası olarak belirtilmiştir. Windows'taki bir dizi uygulama ve diğer işletim sistemleri, Microsoft Excel, NeoOffice ve LibreOffice dahil olmak üzere düzenleme ve manipülasyon için ODS dosyalarını açabilir. ODS dosyaları, farklı uygulamalar tarafından XLS, XLSX ve diğerleri gibi diğer elektronik tablo biçimlerine de dönüştürülebilir. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Ayrıştırma Belgeleri" subTitle="Java kullanılarak, dahil olmak üzere diğer biçimler kolayca ayrıştırılabilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xls/" name="XLS" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xlsb/" name="XLSB" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/parser/xlsm/" name="XLSM" description="Elektronik Tablo Dosyası" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}