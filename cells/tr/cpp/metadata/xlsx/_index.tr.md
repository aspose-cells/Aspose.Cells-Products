---
title:  XLSX Belge Meta Verilerini C++ aracılığıyla Düzenleyin veya Görüntüleyin
weight: 8970
description: C++ Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Çalışma Zamanı Ortamı'ndaki XLSX dosya meta verilerini düzenlemek veya görüntülemek için örnek kod.
keywords: [C++ Aspose.Cells., C++ view xlsx metadata., C++ add xlsx metadata., C++ insert xlsx metadata., C++ edit xlsx metadata., C++ remove xlsx metadata., C++ extract xlsx metadata., C++ modify xlsx metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="XLSX Meta Verilerini C++ aracılığıyla çıkarın" h2="Sunucu tarafı API\'lerini kullanarak XLSX dosyalarına meta veriler eklemek, düzenlemek, kaldırmak veya meta verileri çıkarmak için kendi C++ uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanılarak XLSX Meta Verisi Nasıl Alınır?" %}}

XLSX meta verisini çıkarmak için şunu kullanacağız:
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 Zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge meta veri çıkarma platformu olan API API for C++ platformu. En son sürümünü doğrudan indirebilirsiniz, sadece açın
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 paket yöneticisi, ara
 **Aspose.Cells.Cpp** 
 ve yükleyin. Aşağıdaki komutu Paket Yönetici Konsolundan da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Emretmek" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSX\'in Meta Verilerini C++ aracılığıyla Çıkarma Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 XLSX dosyasının ne zaman alındığı, işlendiği, zaman damgası vb. dahil olmak üzere XLSX dosyasında saklanan yararlı bilgilere erişin.

{{% /blocks/products/pf/agp/text %}}

+ MetadataOptions'ı kullanarak seçenekler oluşturun
+ WorkbookMetadata'yı kullanarak XLSX dosyasını yükleyin
+ GetCustomDocumentProperties() ve Add ile yeni özellikler ekleyin
+ XLSX belgesini kaydet

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ tüm önemli platformları ve İşletim Sistemlerini destekler. Lütfen aşağıdaki önkoşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Çalışma Zamanı Ortamı ile uyumlu bir işletim sistemi.
-  Projenizdeki Aspose.Cells for C++ DLL dosyasına referans ekleyin.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSX - C++\'in Meta Verilerini Çıkarın" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

//Load the sample excel file
MetadataOptions options(MetadataType::Document_Properties);
WorkbookMetadata meta(u"c:\\book1.xlsx", options);
//Add a new custom property
meta.GetCustomDocumentProperties().Add(u"test", u"test");
//Save the output excel file
meta.Save(u"c:\\book2.xlsx");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Cells for C++ API Hakkında" %}}

 Aspose.Cells API, Microsoft Excel formatlarını oluşturmak, düzenlemek, dönüştürmek ve farklı formatlara dönüştürmek için kullanılabilir. Ayrıca yazılım uygulamalarında kapsamlı grafik oluşturma, ölçeklenebilir raporlama ve güvenilir hesaplamalar için de kullanılabilir. Aspose.Cells bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılım gerektirmez.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi Uygulama aracılığıyla XLSX\'in Meta Verilerini Çıkarın" sectionDescription=" XLSX belgesinin Meta Verilerini bizim kullanarak görüntüleyin ve düzenleyin.[Canlı Demolar](https://products.aspose.app/cells/metadata) aşağıdaki avantajlarla." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Hiçbir şey indirmenize veya kurmanıza gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece XLSX dosyanızı yükleyin ve belge özelliklerini düzenleyin" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ortaya çıkan dosyanın indirme bağlantısını anında alın" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
XLSX, Microsoft tarafından Microsoft Office 2007 sürümüyle tanıtılan Microsoft Excel belgeleri için iyi bilinen bir formattır. OOXML standardı ECMA-376'nın 2. Kısmında özetlenen Açık Paketleme Kurallarına göre düzenlenen yapıya dayalı olarak yeni format şu şekildedir: bir dizi XML dosyası içeren bir zip paketi. Temel yapı ve dosyalar, .xlsx dosyasının sıkıştırması açılarak incelenebilir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Meta Veri Formatları" subTitle="C++\'i kullanarak, One ayrıca aşağıdakiler de dahil olmak üzere diğer birçok formatın meta verilerini işleyebilir:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/ods/" name="ODS" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xls/" name="XLS" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsm/" name="XLSM" description="Elektronik Tablo Dosyası" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
