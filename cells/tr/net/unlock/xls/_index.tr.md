---
title: .NET aracılığıyla XLS belgesinin kilidini açın 
weight: 4260
url: /tr/net/unlock/xls/ 
description: .NET Framework, .NET Core, Mono veya Xamarin Platformlarında parola korumalı XLS dosyasının kilidini açmak için C# kaynak kodu.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# üzerinden XLS Elektronik Tablosunun kilidini açın" h2=".NET kitaplığını kullanarak XLS\'den korumayı kaldırın." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanarak XLS Dosyasının Kilidini Açma" %}}

 Koruma XLS dosyasını kaldırmak için kullanacağız
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 C# platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge koruması API olan API. Açık
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 paket yöneticisi, ara
 **Aspose.Cells** 
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# üzerinden XLS\'nin kilidini açın" %}}

{{% blocks/products/pf/agp/text %}}

 ihtiyacın var
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 aşağıdaki iş akışını yürütmek için projenizde başvurulan

{{% /blocks/products/pf/agp/text %}}

1. Korumalı XLS dosyasının yolu ile Çalışma Kitabı sınıfını örnekleyin1. Korumayı kaldırmak için varsayılanı veya herhangi bir Çalışma Sayfasını alın1. Worksheet.Unprotect yöntemiyle Çalışma Sayfası korumasını kaldırın1. Workbook.Unprotect yöntemiyle Çalışma Kitabı korumasını kaldırın1. Sonucu XLS formatında kaydet
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET, tüm büyük işletim sistemlerinde desteklenir. Sadece aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono veya Xamarin Platformları ile uyumlu bir işletim sistemi- Microsoft Visual Studio gibi geliştirme ortamı- Projenizde referans verilen Aspose.Cells for .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Emretmek" offSpacer="" %}}

```cs

// korumalı XLS dosyasıyla bir Çalışma Kitabı nesnesinin örneğini oluşturun
var workbook = new Aspose.Cells.Workbook("protected.xls");

// Excel dosyasındaki varsayılan çalışma sayfasına erişin
var worksheet = workbook.Worksheets[0];

// parola olmadan çalışma sayfasının korumasını kaldır
worksheet.Unprotect();

// çalışma kitabının korumasını parola ile kaldır
workbook.Unprotect("password");

// sonucu XLS formatında geri kaydedin
workbook.Save("unprotected.xls", Aspose.Cells.SaveFormat.Auto);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Cells for .NET API hakkında" %}}

 Aspose.Cells API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="XLS Kilidini Açmak için Ücretsiz Uygulama" sectionDescription="için canlı demolarımızı kontrol edin [XLS dosyalarının kilidini aç](https://products.aspose.app/cells/unlock/xls) aşağıdaki faydaları ile." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Hiçbir şey indirmenize veya kurmanıza gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Kod yazmaya veya derlemeye gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece XLS dosyasını yükleyin ve \"Kilidi Aç\" düğmesine basın" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ortaya çıkan XLS dosyasını bağlantıdan indirin" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
XLS uzantılı dosyalar Excel İkili Dosya Formatını temsil eder. Bu tür dosyalar, Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi diğer benzer elektronik tablo programları tarafından oluşturulabilir. Excel tarafından kaydedilen dosya, her çalışma kitabının bir veya daha fazla çalışma sayfasına sahip olabileceği Çalışma Kitabı olarak bilinir. Veriler, çalışma sayfasında tablo biçiminde depolanır ve kullanıcılara gösterilir ve sayısal değerleri, metin verilerini, formülleri, harici veri bağlantılarını, görüntüleri ve çizelgeleri kapsayabilir. Microsoft Excel gibi uygulamalar, çalışma kitabı verilerini PDF, CSV, XLSX, TXT, HTML, XPS ve diğerleri dahil olmak üzere birkaç farklı biçime aktarmanıza olanak tanır. XLS dosya biçimi, Microsoft Excel 2007'nin piyasaya sürülmesiyle daha açık ve yapılandırılmış bir biçim olan XLSX ile değiştirildi. En son sürümler, XLS dosyalarının oluşturulması ve okunması için hala destek sağlıyor, ancak XLSX artık ilk kullanım tercihi.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Kilit Açma Formatları" subTitle="C# kullanarak, dahil olmak üzere farklı biçimlerin korumasını / kilidinin açılmasını kolayca kaldırabilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="ODS" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsb/" name="XLSB" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsm/" name="XLSM" description="Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsx/" name="XLSX" description="OOXML Excel Dosyası" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}