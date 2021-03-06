---
title: C++ uygulaması aracılığıyla XLSM'yi JSON'a dönüştürün 
url: /tr/cpp/conversion/xlsm-to-json/ 
description: XLSM belgesi için JSON biçimine örnek C++ dönüştürme kodu. Programcılar, herhangi bir C++ Uygulamasında toplu XLSM'den JSON'a dönüştürme için bu kaynak kodunu kullanabilir.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C++ aracılığıyla XLSM\'yi JSON\'a dönüştürün" h2="Microsoft Excel, OpenOffice veya Adobe Acrobat kurulumuna ihtiyaç duymadan C++ kitaplığını kullanarak yüksek performanslı XLSM\'den JSON\'a dönüştürme." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="JSON" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanarak XLSM\'yi JSON\'a Dönüştürme" %}}

 XLSM'yi JSON'a dönüştürmek için kullanacağız
 [C++ için Aspose.Cells](https://products.aspose.com/cells/cpp) 
 C++ platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge işleme ve dönüştürme API olan API. En son sürümünü doğrudan indirebilirsiniz, sadece açın
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 paket yöneticisi, ara
 Aspose.Cells.Cpp 
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Emretmek" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C++ aracılığıyla XLSM\'yi JSON\'a Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 C++ geliştiricileri, yalnızca birkaç kod satırıyla XLSM dosyasını JSON'a kolayca dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. Factory::CreateIWorkbook kullanarak XLSM dosyasını yükleyin.1. Save() yöntemini çağırın.1. Çıktı dosyası yolunu (JSON) dosya uzantısıyla iletin.1. JSON dosyası belirtilen yola kaydedilecektir.1. JSON dosyasını uyumlu programda açın.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 C++ dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.- Projenizde başvurulan C++ DLL için Aspose.Cells.
- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.- Projenizde başvurulan C++ DLL için Aspose.Cells.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSM\'den JSON\'a C++ Dönüşüm Kaynak Kodu" offSpacer="" %}}

```cs
// XLSM'yi yükleyin.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsm");

// JSON formatında kaydedin.
wkb->Save(u"convertedFile.json", SaveFormat_Json);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="XLSM\'den JSON\'a Dönüşüm Canlı Demoları" sectionDescription="[XLSM\'yi JSON\'a Dönüştür](https://products.aspose.app/cells/conversion/xlsm-to-json) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece XLSM dosyanızı yükleyin, anında JSON\'a dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel Dosya Manipülasyon Kitaplığı" %}}

 Excel API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells, bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}

XLSM uzantılı dosyalar, Makroları destekleyen bir Elektronik Tablo dosyası türüdür. Uygulama açısından, bir Makro, süreçleri otomatikleştirmek için kullanılan bir dizi talimattır. Tekrar tekrar gerçekleştirilen adımları kaydetmek için bir makro kullanılır ve makroyu tekrar çalıştırarak eylemleri gerçekleştirmeyi kolaylaştırır. Makrolar, Visual Basic Düzenleyici kullanılarak Excel Çalışma Kitabı içinden Microsoft'un Visual Basic for Applications (VBA) ile programlanır ve doğrudan oradan çalıştırılabilir/hata ayıklanabilir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JSON" readMoreLink="https://docs.fileformat.com/web/json/" >}}

JSON (JavaScript Object Notation), verileri depolamak ve iletmek için insan tarafından okunabilen metin kullanan, veri paylaşımına yönelik açık standart bir dosya biçimidir. JSON dosyaları .json uzantısıyla depolanır. JSON, daha az biçimlendirme gerektirir ve XML için iyi bir alternatiftir. JSON, JavaScript'ten türetilmiştir ancak dilden bağımsız bir veri biçimidir. JSON'un oluşturulması ve ayrıştırılması birçok modern programlama dili tarafından desteklenir. application/json, JSON için kullanılan ortam türüdür.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}