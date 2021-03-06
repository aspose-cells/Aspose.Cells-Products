---
title: C++ aracılığıyla ODS belgesinin kilidini açın 
weight: 1190
url: /tr/cpp/unlock/ods/ 
description: C++ Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment'da parola korumalı ODS dosyasının kilidini açmak için örnek kod.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ODS Dosyalarının kilidini C++ üzerinden açın" h2="C++ Kitaplığı\'nı kullanarak ODS dosyası da dahil olmak üzere Excel elektronik tablolarından korumayı kaldırın." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanarak ODS Dosyasının Korumasını Kaldırma" %}}

 ODS dosyasının kilidini açmak için kullanacağız
 [C++ için Aspose.Cells](https://products.aspose.com/cells/cpp) 
 C++ platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge koruması API olan API. En son sürümünü doğrudan indirebilirsiniz, sadece açın
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

{{% blocks/products/pf/agp/feature-section-col title="C++ üzerinden ODS\'nin kilidini açın" %}}

{{% blocks/products/pf/agp/text %}}

 ihtiyacın var
 [aspose.cells.dll](https://downloads.aspose.com/cells/cpp) 
 aşağıdaki iş akışını yürütmek için projenizde başvurulan

{{% /blocks/products/pf/agp/text %}}

1. CreateIWorkbook'u kullanarak ODS kilitli dosyasını yükleyin.1. Kilidi açmak için Unprotect() işlevini çağırın.1. SetPassword kullanarak parolayı NULL olarak ayarlayın.1. ODS dosyasını belirtilen bir konuma kaydedin.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 C++ için Aspose.Cells, tüm büyük platformlarda ve İşletim Sistemlerinde destekler. Lütfen aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.- Projenizde başvurulan C++ DLL için Aspose.Cells.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Emretmek" offSpacer="" %}}

```cs

// Kaynak dizin yolu.
StringPtr srcDir = new String("SourceDirectory\\");

// Çıkış dizini yolu.
StringPtr outDir = new String("OutputDirectory\\");

// ODS dosyasını yükle
intrusive_ptr<IWorkbook> workbook = Factory::CreateIWorkbook(srcDir->StringAppend(new String("sampleExcelFileProtected.ods")));

// Çalışma kitabının korumasını kaldır
workbook->Unprotect(new String("12345"));

// Şifreyi null olarak ayarla
workbook->GetISettings()->SetPassword(NULL);

// ODS dosyasını kaydedin
workbook->Save(outDir->StringAppend(new String("sampleExcelFileUnprotected_out.ods")));


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="C++ API için yaklaşık Aspose.Cells" %}}

 Aspose.Cells API, Microsoft Excel biçimlerini oluşturmak, düzenlemek, dönüştürmek ve farklı biçimlere dönüştürmek için kullanılabilir. Ayrıca, yazılım uygulamalarında kapsamlı çizelgeleme, ölçeklenebilir raporlama ve güvenilir hesaplamalar için kullanılabilir. Aspose.Cells bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ODS\'nin Kilidini Açmak için Ücretsiz Uygulama" sectionDescription="için canlı demolarımızı kontrol edin [ODS dosyalarının kilidini aç](https://products.aspose.app/cells/unlock/ods) aşağıdaki faydaları ile." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Hiçbir şey indirmenize veya kurmanıza gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Kod yazmaya veya derlemeye gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece ODS dosyasını yükleyin ve \"Kilidi Aç\" düğmesine basın" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ortaya çıkan ODS dosyasını bağlantıdan indirin" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
ODS uzantılı dosyalar, kullanıcı tarafından düzenlenebilen OpenDocument Elektronik Tablo Belgesi formatı anlamına gelir. Veriler, ODF dosyası içinde satırlar ve sütunlar halinde saklanır. XML tabanlı bir biçimdir ve Açık Belge Biçimleri (ODF) ailesindeki birkaç alt türden biridir. Format, OASIS tarafından yayınlanan ve sürdürülen ODF 1.2 spesifikasyonlarının bir parçası olarak belirtilmiştir. Windows'taki bir dizi uygulama ve diğer işletim sistemleri, Microsoft Excel, NeoOffice ve LibreOffice dahil olmak üzere düzenleme ve manipülasyon için ODS dosyalarını açabilir. ODS dosyaları, farklı uygulamalar tarafından XLS, XLSX ve diğerleri gibi diğer elektronik tablo biçimlerine de dönüştürülebilir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Kilit Açma Formatları" subTitle="C++ kullanarak, dahil olmak üzere farklı biçimlerin korumasını / kilidinin açılmasını kolayca kaldırabilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xls/" name="XLS" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsb/" name="XLSB" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsm/" name="XLSM" description="Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsx/" name="XLSX" description="OOXML Excel Dosyası" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}