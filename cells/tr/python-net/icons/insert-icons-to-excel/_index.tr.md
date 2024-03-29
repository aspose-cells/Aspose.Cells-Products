---
title:  Python via .Net'i kullanarak SVG görseli/Simgeyi Excel'e ekleyin
weight: 200
description: Python via .Net kaynak kodu, Excel'e SVG resim/Simge eklemek için.
keywords: [Python via .NET Aspose.Cells., Python via .NET add SVG images/Icons into Excel., Python via .NET insert SVG images/Icons into Excel., Python via .NET create SVG images/Icons in Excel]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Python via .Net\'i kullanarak SVG görseli/Simgeyi Excel\'e ekleyin" h2="Microsoft veya Open Office, Adobe PDF vb. gibi herhangi bir yazılım olmadan Aspose.Cells\' API\'i kullanarak SVG görsellerini/Simgelerini ekleyin." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/cells/aspose_cells-for-python-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/python-net" installationsDocsLink="https://docs.aspose.com/cells/python-net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-net/" learnAsLink="https://docs.aspose.com/cells/python-net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content %}}

Herhangi bir cihazda görüntülerin uzatıldığını ve sıkıştırıldığını görmek istemiyor musunuz?

Yakınlaştırıldığında görüntünün bulanık olmasını istemiyor musunuz?

Yüksek çözünürlükte görüntünün bozulmasını istemiyor musunuz?

Belki SVG iyi bir seçimdir. SVG görseller her yakınlaştırma seviyesinde harika görünür ve çözünürlükten bağımsızdır. Svg görsellerinin yüksek aslına uygunluğu nedeniyle Excel kullanıcıları arasında oldukça popülerdir.

Excel'i kullandığınızda aşağıdaki sorunlarla karşılaşabilirsiniz:

+ Hedef Excel dosyası doğrudan manuel olarak değiştirilemez ve onu işlemek için bir program gerekir.
+ Aynı Excel dosyasına çok sayıda svg resmi ekleyin.
+ Svg resimlerini çok sayıda farklı Excel dosyasına ekleyin.

 Bu sorunları çözmek için, kullanmanızı öneririz.[Aspose.Cells](https://products.aspose.com/cells/)kütüphane.Excel dosyalarını işlemek için birçok ortak arayüz içerir ve çok kullanışlı bir araçtır.

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="SVG Excel Kullanarak Excel Dosyasına SVG resim/Simge Nasıl Eklenir" %}}

![](/cells/tr/net/icons/insert-icons-to-excel/sample.png)

Microsoft Excel bize svg eklemenin üç yolunu sunar:

+  **Yerel SVG resim/simge ekleyin**

SVG dosyasını belgedeki belirli bir konuma sürükleyip bırakmanız yeterlidir. Veya şeritten "*Ekle -> Resim -> Bu Cihaz...*" yolunu seçebilirsiniz.

+  **Ön ayarlı SVG resim/Simge ekle**

Microsoft Excel seçmemiz için bize önceden ayarlanmış svg resimleri sağladı. Şeritten "*Ekle -> Resim -> Hazır Görüntüler...*" yolunu seçerek seçim iletişim kutusunu açabilirsiniz. Svg dosyalarının çoğu Stok Görüntüler'deki "Simgeler" seçeneğinin altındadır.

+  **Web'den SVG resim/Simge ekleyin**

Yukarıdaki yöntemlerden hiçbiri ihtiyacınızı karşılayamıyorsa Microsoft Excel üzerinden de istediğiniz sonuçları internetten arayabilirsiniz. "*Ekle -> Resim -> Çevrimiçi Resimler...*" seçeneğini seçerek seçim diyalogunu açabilirsiniz. " şeritten gelen yol.

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python via .Net Kullanarak Excel Dosyasına SVG resim/Simge Nasıl Eklenir" %}}

 Excel dosyasına SVG resim/Simge eklemek için şunu kullanacağız:
 [Aspose.Cells for Python .Net aracılığıyla](https://pypi.org/project/aspose-cells-python/) 
 API, zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge işleme aracıdır. .Net platformu üzerinden API for Python. API, Excel dosyası oluşturma, işleme, dönüştürme ve görüntüleme sağlar. Üstelik Microsoft Office veya Excel uygulamalarına güvenmeden. Aşağıdaki komutu kullanarak konsoldan kurulum yapabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Emretmek" offSpacer="true" %}}

```cs

> pip install aspose-cells-python

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Python via .Net\'i kullanarak SVG görsellerini/Simgelerini Excel dosyasına ekleme adımları" %}}

{{% blocks/products/pf/agp/text %}}

Aşağıdaki iş akışını kendi ortamınızda denemek için Aspose.Cells'e ihtiyacınız vardır.

{{% /blocks/products/pf/agp/text %}}

+ Bir Çalışma Kitabı nesnesinin başlatılması.(veya->XLSX dosyasını tam yolla yükleyin.)
+ Dizini aracılığıyla Çalışma Sayfasını seçin.
 + Shapecollection'ın eklentisini kullanın[yöntem](https://reference.aspose.com/cells/python-net/aspose.cells.drawing/shapecollection/) Seçilen çalışma sayfasına bir simge eklemek için.
+ Çalışma kitabını XLSX formatında kaydedin.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Python .Net aracılığıyla platformdan bağımsızdır API ve herhangi bir platformda kullanılabilir (Windows, Linux), sadece sistemin aşağıdaki özelliklere sahip olduğundan emin olun:[Python](https://www.python.org/downloads/) 3.7 veya daha yüksek.
 
{{% /blocks/products/pf/agp/text %}}

-  Python via .Net betiklerini çalıştırabilen herhangi bir işletim sistemi (Windows, Linux gibi)
-  Aspose.Cells for Python'i .Net aracılığıyla yükleyin<a href="https://pypi.org/project/aspose-cells-python/">pypi</a> , komutu şu şekilde kullanın:<code>$ pip install aspose-cells-python</code>.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="SVG resim/simge ekle - Python via .Net" offSpacer="" %}}

{{< gist "aspose-cells-gists" "7bb30376b4d40cdfd596286870fb9752" "InsertIconsIntoWorksheet.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Aspose.Cells API Hakkında" %}}

Aspose.Cells API çapraz platform uygulamaları oluşturma yeteneğine sahip, Microsoft Excel formatlarını farklı formatlara (görüntü olarak, PDF, HTML, ODS ve daha fazlası) oluşturmak, düzenlemek, dönüştürmek ve işlemek için kullanılabilir. Ayrıca, kapsamlı grafikler için kullanılabilir, yazılım uygulamaları içinde ölçeklenebilir raporlama ve güvenilir hesaplamalar. Böylece, endüstri standardı formatlarda belge alışverişi yapmak için mükemmel bir seçim haline gelir. Aspose.Cells'in bağımsız bir API olması ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmemesi önemlidir.

{{% /blocks/products/pf/agp/content %}}



<!-- aboutfile Ends -->
<!--
{{< blocks/products/pf/agp/other-supported-section title="Other Supported Splitting Formats" subTitle="Using Python via .NET, One can also split large file into chunks of many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/ods/" name="ODS" description="OpenDocument Spreadsheet File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xls/" name="XLS" description="Excel Binary Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsb/" name="XLSB" description="Binary Excel Workbook File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/splitter/xlsm/" name="XLSM" description="Spreadsheet File" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

-->

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
