---
title: XLSM belgesini C++ aracılığıyla koruyun ve kilitleyin 
weight: 8770
url: /tr/cpp/protect/xlsm/ 
description: C++ Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment'da parola kullanarak XLSM dosyasını kilitlemek için örnek kod.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSM Dosyalarını C++ aracılığıyla şifreleyin" h2=".NET Kitaplığı kullanarak XLSM biçimi de dahil olmak üzere Excel elektronik tablolarını parolayla koruyun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp/" installationsDocsLink="https://docs.aspose.com/cells/cpp/" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanılarak XLSM Dosyasının Güvenliği Nasıl Sağlanır" %}}

 XLSM dosyasını korumak için kullanacağız
 [C++ için Aspose.Cells](https://products.aspose.com/cells/cpp) 
 C++ platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge şifreleme API olan API. En son sürümünü doğrudan indirebilirsiniz, sadece açın
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 paket yöneticisi, ara
 **Aspose.Cells.Cpp** 
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSM Dosyalarını C++ aracılığıyla Koruma Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells API'lerini kullanan belge koruması, yalnızca birkaç satır kodla yapılabilir.

{{% /blocks/products/pf/agp/text %}}

1. IWorkbook sınıfını kullanarak XLSM dosyasını yükleyin1. ProtectionType ve Password ile Protect(..) yöntemini kullanın1. Korumalı XLSM dosyasını Save() yöntemiyle kaydedin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 C++ için Aspose.Cells, tüm büyük platformlarda ve İşletim Sistemlerinde destekler. Lütfen aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.- Projenizde başvurulan C++ DLL için Aspose.Cells.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Emretmek" offSpacer="" %}}

```cs

// Kaynak yolu.
StringPtr srcDir = new String("SourcePath\");

// Çıkış yolu.
StringPtr outDir = new String("OutputPath\");

// XLSM dosyasını yükle
intrusive_ptr<IWorkbook> workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sourceFile.xlsm")));

// Koruma türünü belirterek çalışma kitabını koruyun
workbook->Protect(ProtectionType::ProtectionType_All, new String("12345"));

// XLSM dosyasını kaydedin
workbook->Save(outDir->StringAppend(new String("output.xlsm")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="C++ API için yaklaşık Aspose.Cells" %}}

 Aspose.Cells API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="XLSM\'yi Korumak için Ücretsiz Uygulama" sectionDescription="için canlı demolarımızı kontrol edin [XLSM dosyalarını şifrele](https://products.aspose.app/cells/protect/xlsm) aşağıdaki faydaları ile." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Hiçbir şey indirmenize veya kurmanıza gerek yok" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Kod yazmaya veya derlemeye gerek yok" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece XLSM dosyasını yükleyin ve \"Kilidi Aç\" düğmesine basın" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ortaya çıkan XLSM dosyasını bağlantıdan indirin" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
XLSM uzantılı dosyalar, Makroları destekleyen bir Elektronik Tablo dosyası türüdür. Uygulama açısından, bir Makro, süreçleri otomatikleştirmek için kullanılan bir dizi talimattır. Tekrar tekrar gerçekleştirilen adımları kaydetmek için bir makro kullanılır ve makroyu tekrar çalıştırarak eylemleri gerçekleştirmeyi kolaylaştırır. Makrolar, Visual Basic Düzenleyici kullanılarak Excel Çalışma Kitabı içinden Microsoft'un Visual Basic for Applications (VBA) ile programlanır ve doğrudan oradan çalıştırılabilir/hata ayıklanabilir.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Koruma Belgeleri" subTitle="C++ kullanılarak, dahil olmak üzere diğer dosyalar korunabilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/ods/" name="ODS" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xls/" name="XLS" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsb/" name="XLSB" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/protect/xlsx/" name="XLSX" description="OOXML Excel Dosyası" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}