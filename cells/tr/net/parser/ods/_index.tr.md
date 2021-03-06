---
title: .NET aracılığıyla ODS belgesinden metin ve resim ayıklayın 
weight: 6970
url: /tr/net/parser/ods/ 
description: .NET Framework, .NET Core, Mono veya Xamarin Platformlarında ODS dosyasından metin ve resim çıkarmak için C# kaynak kodu.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ODS Biçimlerini C# içinde ayrıştırın" h2="Microsoft veya Adobe PDF gibi herhangi bir yazılım kullanmadan sunucu tarafı Aspose.Cells for .NET API\'lerini kullanarak yerel ve yüksek performanslı ODS belgesi ayrıştırma." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanarak ODS Dosyasını Ayrıştırma" %}}

 ODS dosyasını ayrıştırmak için kullanacağız
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 C# platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge işleme API olan API. Açık
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 paket yöneticisi, ara
 **Aspose.Cells** 
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Emretmek" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# içinde ODS Dosyalarını Ayrıştırma Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 ile temel bir belge ayrıştırma
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API'ler sadece birkaç satır kod ile yapılabilir. Microsoft Excel XLS, XLSX, XLSM, XLSB ve OpenDocument ODS dosyalarından metin ve görüntüleri ayrıştırın.

{{% /blocks/products/pf/agp/text %}}

+ ODS belgesini yükleyin.
+ Sayfayı seçin.
+ Resmi ve resim türünü alın.
+ Resmi kaydedin.
+ Belgeyi kaydet

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 API'lerimiz tüm büyük platformlarda ve İşletim Sistemlerinde desteklenir. Aşağıdaki kodu çalıştırmadan önce lütfen sisteminizde aşağıdaki ön koşulların bulunduğundan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono veya Xamarin Platformları ile uyumlu bir işletim sistemi- Microsoft Visual Studio gibi geliştirme ortamı- Projenizde referans verilen Aspose.Cells for .NET DLL - Yukarıdaki İndir düğmesini kullanarak NuGet'ten yükleyin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODS Dosyalarını Ayrıştırma - C#" offSpacer="" %}}

```cs
    // Çalışma Sayfalarından görüntüleri ayıklayın 
    // bir şablon Excel dosyası açın
    Workbook workbook = new Workbook("sampleExtractImagesFromWorksheets.ods");
    
    // ilk çalışma sayfasını al
    Worksheet worksheet = workbook.Worksheets[0];
    
    // ilk çalışma sayfasındaki ilk Resmi al
    Aspose.Cells.Drawing.Picture pic = worksheet.Pictures[0];
    
    // çıktı görüntü dosyası yolunu ayarla
    string picformat = pic.ImageType.ToString();
                
    // Not: Görüntü yolunu belirtmeden önce görüntü biçimini değerlendirebilirsiniz.
    // ImageOrPrintOptions'ı tanımla
    Aspose.Cells.Rendering.ImageOrPrintOptions printoption = new  Aspose.Cells.Rendering.ImageOrPrintOptions();
    
    // görüntü biçimini belirtin
    printoption.ImageType =  Aspose.Cells.Drawing.ImageType.Jpeg;
                
    // görüntüyü kaydet
    pic.ToImage("outputExtractImagesFromWorksheets.jpg", printoption);  

    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Cells for .NET API hakkında" %}}

 Aspose.Cells API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi ODS Ayrıştırıcı Canlı Demoları" sectionDescription="Şu anda sayfamızı ziyaret ederek ODS belgelerinden metin ve resim ayıklayın. [Canlı Demolar web sitesi](https://products.aspose.app/cells/parser). Canlı demo aşağıdaki avantajlara sahiptir" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece ODS dosyalarınızı yükleyin." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anında ayrıştırılacaktır." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
ODS uzantılı dosyalar, kullanıcı tarafından düzenlenebilen OpenDocument Elektronik Tablo Belgesi formatı anlamına gelir. Veriler, ODF dosyası içinde satırlar ve sütunlar halinde saklanır. XML tabanlı bir biçimdir ve Açık Belge Biçimleri (ODF) ailesindeki birkaç alt türden biridir. Format, OASIS tarafından yayınlanan ve sürdürülen ODF 1.2 spesifikasyonlarının bir parçası olarak belirtilmiştir. Windows'taki bir dizi uygulama ve diğer işletim sistemleri, Microsoft Excel, NeoOffice ve LibreOffice dahil olmak üzere düzenleme ve manipülasyon için ODS dosyalarını açabilir. ODS dosyaları, farklı uygulamalar tarafından XLS, XLSX ve diğerleri gibi diğer elektronik tablo biçimlerine de dönüştürülebilir. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Ayrıştırma Formatları" subTitle="C# kullanılarak, dahil olmak üzere diğer biçimler kolayca ayrıştırılabilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xls/" name="XLS" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsb/" name="XLSB" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/parser/xlsm/" name="XLSM" description="Elektronik Tablo Dosyası" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}