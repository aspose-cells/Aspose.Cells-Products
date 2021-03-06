---
title: C++ uygulamasıyla TABDELIMITED'i PDF'ye dönüştürün 
url: /tr/cpp/conversion/tabdelimited-to-pdf/ 
description: TABDELIMITED belgesi için PDF biçimine örnek C++ dönüştürme kodu. Programcılar bu kaynak kodunu herhangi bir C++ Uygulamasında toplu TABDELIMITED'den PDF'ye dönüştürmek için kullanabilirler.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TABDELIMITED\'i C++ aracılığıyla PDF\'ye dönüştürün" h2="Microsoft Excel, OpenOffice veya Adobe Acrobat kurulumuna ihtiyaç duymadan C++ kitaplığını kullanarak yüksek performanslı TABDELIMITED\'den PDF\'ye dönüştürme." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TABDELIMITED" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanarak TABDELIMITED\'i PDF\'ye Dönüştürme" %}}

 TABDELIMITED'i PDF'ye dönüştürmek için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="TABDELIMITED\'i C++ aracılığıyla PDF\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 C++ geliştiriciler, TABDELIMITED dosyasını yalnızca birkaç satır kodla kolayca PDF'ye dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. TABDELIMITED dosyasını Factory::CreateIWorkbook kullanarak yükleyin.1. Save() yöntemini çağırın.1. Çıktı dosyası yolunu (PDF) dosya uzantısıyla iletin.1. PDF dosyası belirtilen yola kaydedilecektir.1. PDF dosyasını uyumlu programda açın.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 C++ dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.- Projenizde başvurulan C++ DLL için Aspose.Cells.
- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.- Projenizde başvurulan C++ DLL için Aspose.Cells.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TABDELIMITED\'den PDF\'ye C++ Dönüştürme Kaynak Kodu" offSpacer="" %}}

```cs
// TABDELIMITED'i yükleyin.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tabdelimited");

// PDF formatında kaydedin.
wkb->Save(u"convertedFile.pdf", SaveFormat_Pdf);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="TABDELIMITED\'den PDF\'ye Dönüştürme Canlı Demoları" sectionDescription="[TABDELIMITED\'i PDF\'ye dönüştür](https://products.aspose.app/cells/conversion/tabdelimited-to-pdf) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" TABDELIMITED dosyanızı yüklemeniz yeterlidir, anında PDF\'ye dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="C++ Excel Dosya Manipülasyon Kitaplığı" %}}

 Excel API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells, bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TABDELIMITED" readMoreLink="/{{tabdelimited_url}}" >}}

{{tabdelimited}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

Taşınabilir Belge Formatı (PDF), Adobe tarafından 1990'larda oluşturulmuş bir belge türüdür. Bu dosya biçiminin amacı, belgelerin ve diğer başvuru malzemelerinin uygulama yazılımı, donanım ve İşletim Sisteminden bağımsız bir biçimde temsil edilmesi için bir standart getirmekti. PDF dosyaları, uzantılar/eklentiler aracılığıyla Adobe Acrobat Reader/Writer'da ve Chrome, Safari, Firefox gibi çoğu modern tarayıcıda açılabilir. Ticari olarak satılan yazılım paketlerinin çoğu, herhangi bir ek yazılım bileşenine gerek duymadan belgelerinin PDF dosya formatına dönüştürülmesini de sağlar. Bu nedenle, PDF dosya formatı, kaynak belgenin bir parçası haline gelebilecek metin, resimler, köprüler, form alanları, zengin medya, dijital imzalar, ekler, meta veriler, Jeo-uzamsal özellikler ve 3B nesneler gibi bilgileri içerme yeteneğine sahiptir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}