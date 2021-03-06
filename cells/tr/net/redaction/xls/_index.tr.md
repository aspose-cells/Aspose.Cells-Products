---
title: .NET aracılığıyla XLS belgesindeki metni arayın ve değiştirin 
weight: 7280
url: /tr/net/redaction/xls/ 
description: .NET Framework, .NET Core, Mono veya Xamarin Platformlarında XLS dosyasındaki hassas bilgileri yeniden düzenlemek için C# kaynak kodu.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# içinde XLS Biçimlerini Yeniden Düzenleyin" h2="Microsoft veya Adobe PDF gibi herhangi bir yazılım kullanmadan, sunucu tarafı Aspose.Cells for .NET API\'lerini kullanarak yerel ve yüksek performanslı XLS belgesine duyarlı redaksiyon bilgileri." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanarak XLS Dosyasını Düzeltme" %}}

 XLS dosyasını yeniden düzenlemek için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="C# içinde XLS Dosyalarını Düzeltme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Temel bir belge arama ve içerikteki, yorumlardaki veya meta verilerdeki metni aşağıdakilerle değiştirin:
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API'ler sadece birkaç satır kod ile yapılabilir.

{{% /blocks/products/pf/agp/text %}}

+ XLS dosyasını yükleyin.
+ Sayfayı seçin.
+ FindOptions nesnesi oluşturun.
+ Arama Seçeneklerini Ayarla
+ Her hücrede dolaşın ve Bul yöntemini kullanın.
+ Çalışma kitabını kaydedin.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 API'lerimiz tüm büyük platformlarda ve İşletim Sistemlerinde desteklenir. Aşağıdaki kodu çalıştırmadan önce lütfen sisteminizde aşağıdaki ön koşulların bulunduğundan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono veya Xamarin Platformları ile uyumlu bir işletim sistemi- Microsoft Visual Studio gibi geliştirme ortamı- Projenizde referans verilen Aspose.Cells for .NET DLL - Yukarıdaki İndir düğmesini kullanarak NuGet'ten yükleyin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLS Dosyalarını Düzelt - C#" offSpacer="" %}}

```cs
Workbook wb = new Workbook("e:\test2\Input.xls");
Worksheet sheet = wb.Worksheets[0];
FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.Contains;
opts.RegexKey = true;
Aspose.Cells.Cell cell = null;
do
{   //sadece tam kelimeyi bulun ve herhangi bir kelimenin bir parçasını değil.  
    cell = sheet.Cells.Find("\bKIM\b", cell, opts);
    if (cell != null)
    {
        string celltext = cell.Value.ToString();
        celltext = celltext.Replace("KIM", "^^^^^^^^^^");
        cell.PutValue(celltext);
    }
}
while (cell != null);

wb.Save("e:\test2\out1.xls");

// Tüm çalışma kitabında Bul/Değiştir.

Workbook wb = new Workbook("e:\test2\Input.xls");
wb.Replace("\bKIM\b", "^^^^^^^^", new ReplaceOptions() { RegexKey = true });  
wb.Save("e:\test2\output.xls");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Cells for .NET API hakkında" %}}

 Aspose.Cells API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi XLS Redaksiyon Canlı Demoları" sectionDescription="Şu anda sayfamızı ziyaret ederek XLS belgelerindeki içeriklerde, yorumlarda veya meta verilerde metin arayın ve değiştirin [Canlı Demolar web sitesi](https://products.aspose.app/cells/redaction). Canlı demo aşağıdaki avantajlara sahiptir" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece XLS dosyalarınızı yükleyin." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anında düzeltilecektir." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
XLS uzantılı dosyalar Excel İkili Dosya Formatını temsil eder. Bu tür dosyalar, Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi diğer benzer elektronik tablo programları tarafından oluşturulabilir. Excel tarafından kaydedilen dosya, her çalışma kitabının bir veya daha fazla çalışma sayfasına sahip olabileceği Çalışma Kitabı olarak bilinir. Veriler, çalışma sayfasında tablo biçiminde depolanır ve kullanıcılara gösterilir ve sayısal değerleri, metin verilerini, formülleri, harici veri bağlantılarını, görüntüleri ve çizelgeleri kapsayabilir. Microsoft Excel gibi uygulamalar, çalışma kitabı verilerini PDF, CSV, XLSX, TXT, HTML, XPS ve diğerleri dahil olmak üzere birkaç farklı biçime aktarmanıza olanak tanır. XLS dosya biçimi, Microsoft Excel 2007'nin piyasaya sürülmesiyle daha açık ve yapılandırılmış bir biçim olan XLSX ile değiştirildi. En son sürümler, XLS dosyalarının oluşturulması ve okunması için hala destek sağlıyor, ancak XLSX artık ilk kullanım tercihi. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Redaksiyon Formatları" subTitle="C# kullanarak, aşağıdakiler dahil olmak üzere farklı biçimlerde kolayca redaksiyon yapılabilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/ods/" name="ODS" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsb/" name="XLSB" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsm/" name="XLSM" description="Elektronik Tablo Dosyası" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}