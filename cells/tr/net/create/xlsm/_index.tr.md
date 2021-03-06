---
title: C# aracılığıyla MS Excel XLSM Dosyaları oluşturun 
url: /tr/net/create-xlsm/ 
description: C# XLSM belgeleri oluşturmak için örnek kod. VB.NET, Asp.NET veya herhangi bir .NET tabanlı uygulama içinde MS Excel XLSM dosyaları oluşturmak için bu kodu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# aracılığıyla XLSM Belgeleri oluşturun" h2="Sunucu tarafı .NET API\'lerini kullanarak programlı olarak yerel ve yüksek performanslı MS Excel XLSM elektronik tablosu oluşturma." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Çalışan uygulama içinde dinamik olarak MS Excel XLSM dosyası oluşturmak kolaydır. MS Office gerektirmeden sıfırdan XLSM belgeleri oluşturmak için kullanacağız
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 .NET platformunu kullanarak e-tablo oluşturma, değiştirme ve dönüştürme için farklı özellikler sunan API. Geliştiriciler, veri yazmak, çizelgeler veya grafikler oluşturmak ve ayrıca elektronik tablolarda tablo oluşturmak için kodu kolayca geliştirebilir.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# aracılığıyla XLSM Nasıl Oluşturulur" %}}

{{% blocks/products/pf/agp/text %}}

 Geliştiricilerin, yalnızca birkaç kod satırında veri işleme için farklı raporlama uygulamaları çalıştırarak MS Excel XLSM elektronik tablosunu oluşturması, yüklemesi, değiştirmesi ve dönüştürmesi kolaydır.

{{% /blocks/products/pf/agp/text %}}

1. Ad alanını sınıf dosyanıza ekleyin1. Workbook sınıfı örneği oluşturun.1. Çalışma kitabının ilk çalışma sayfasına erişin.1. Çalışma sayfasının istediğiniz hücresini/hücrelerini alın ve değeri hücreye/hücrelere girin.1. Çalışma kitabını XLSM dosyası olarak kaydetmek için Kaydet yöntemini kullanın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Sistemin Microsoft Windows veya .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformları ile uyumlu bir işletim sisteminin yanı sıra Microsoft Visual Studio gibi geliştirme ortamına sahip olduğundan emin olun. 

{{% /blocks/products/pf/agp/text %}}

- olarak komut satırından yükleyin <code>nuget install Aspose.Cells</code> veya Visual Studio'nun Paket Yönetici Konsolu aracılığıyla <code>Install-Package Aspose.Cells</code>.- Alternatif olarak, çevrimdışı MSI yükleyicisini veya bir ZIP dosyasındaki tüm DLL'leri şu adresten alın: <a href="https://downloads.aspose.com/cells/net">İndirilenler</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Aşağıdaki kaynak kodu, C# kullanarak bir MS Excel XLSM dosyasının nasıl oluşturulacağını gösterir." offSpacer="" %}}

```cs

// Workbook sınıfı örneği oluşturun.
Workbook wkb = new Workbook();

// Çalışma kitabının ilk çalışma sayfasına erişin.
Worksheet sht = wkb.Worksheets[0];

// Çalışma sayfasının istediğiniz hücresini/hücrelerini alın.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// değeri hücre(ler)e girin.
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Çalışma Kitabını .xlsm dosyası olarak kaydedin.
wkb.Save("created_one.xlsm");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 MS Excel XLSM dosyalarını oluşturma, değiştirme, dönüştürme, işleme ve yazdırma yeteneği ile platformlar arası uygulamalar oluşturabilen bir Excel Elektronik Tablo Programlama Kitaplığı. .NET Excel API yalnızca elektronik tablo biçimleri arasında dönüştürme yapmakla kalmaz, aynı zamanda Excel dosyalarını resim, PDF, HTML, ODS ve daha fazlası olarak da işleyebilir, böylece endüstri standardı biçimlerde belge alışverişi yapmak için mükemmel bir seçimdir.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
XLSM uzantılı dosyalar, Makroları destekleyen bir Elektronik Tablo dosyası türüdür. Uygulama açısından, bir Makro, süreçleri otomatikleştirmek için kullanılan bir dizi talimattır. Tekrar tekrar gerçekleştirilen adımları kaydetmek için bir makro kullanılır ve makroyu tekrar çalıştırarak eylemleri gerçekleştirmeyi kolaylaştırır. Makrolar, Visual Basic Düzenleyici kullanılarak Excel Çalışma Kitabı içinden Microsoft'un Visual Basic for Applications (VBA) ile programlanır ve doğrudan oradan çalıştırılabilir/hata ayıklanabilir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Elektronik Tablo Oluşturma" subTitle="Aşağıda listelenen birkaçı dahil olmak üzere diğer Microsoft Excel formatlarını da oluşturabilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xls/" name="XLS" description="Microsoft Excel Elektronik Tablosu (Eski)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsx/" name="XLSX" description="XML Çalışma Kitabını Aç" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsb/" name="XLSB" description="Excel İkili Çalışma Kitabı" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsm/" name="XLSM" description="Makro Etkin E-tablo" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlt/" name="XLT" description="Excel 97 - 2003 Şablonu" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltx/" name="XLTX" description="Excel Şablonu" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltm/" name="XLTM" description="Excel Makro Etkin Şablon" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-csv/" name="CSV" description="Virgülle Ayrılmış Değerler" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-tsv/" name="TSV" description="Sekmeyle Ayrılmış Değerler" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-ods/" name="ODS" description="OpenDocument Elektronik Tablosu" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
