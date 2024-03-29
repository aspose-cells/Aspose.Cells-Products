---
title:  ODS'i C# aracılığıyla Bayt Dizisine dönüştürün
weight: 7690
description: C# ODS'in Bayt Dizisine dönüşümü için örnek kod. VB.NET, Asp.NET veya herhangi bir .NET tabanlı uygulamada Excel ODS'den Bayt Dizisine dönüşüm için bu kodu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ODS\'i C# aracılığıyla bayt dizisine dönüştürün" h2="Yerel ve yüksek performanslı Microsoft Excel ODS\'den bayt dizisine dönüştürme veya sunucu tarafı .NET API\'lerini kullanarak e-tablo veri işleme için tam tersi." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Bayt Dizisi veri işleme veya depolama için faydalıdır. ODS dosyasını Byte Array'e ve ayrıca bir dosyaya dönüştürebilirsiniz.**ODS'e Bayt Dizisi** C# dilini kullanarak belge. ODS'i bayt dizisine dönüştürmek için şunu kullanacağız:
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API, .NET platformunu kullanarak belge işleme ve dönüştürme için farklı özellikler sunar.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ODS\'i C# aracılığıyla Bayt Dizisine Dönüştürme" %}}

{{% blocks/products/pf/agp/text %}}

 Geliştiricilerin yalnızca birkaç satır kodla daha fazla düzenleme görevi için ODS dosyalarını bayt dizisine yüklemesi ve dönüştürmesi kolaydır.

{{% /blocks/products/pf/agp/text %}}

1.  Ad alanını sınıf dosyanıza ekleyin
1.  ODS dosyasını çalışma kitabını kullanarak yükle
1.  MemoryStream nesnesini başlat
1.  Akış verilerini bayt dizisine dönüştürün
1.  Verileri ihtiyacınıza göre işleyin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

Sistemin Microsoft Windows veya .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformları ile uyumlu bir işletim sisteminin yanı sıra Microsoft Visual Studio gibi geliştirme ortamına sahip olduğundan emin olun.

{{% /blocks/products/pf/agp/text %}}

-  Komut satırından şu şekilde yükleyin:<code>nuget install Aspose.Cells</code> veya Visual Studio'nun Paket Yönetici Konsolu aracılığıyla<code>Install-Package Aspose.Cells</code>.
-  Alternatif olarak, çevrimdışı MSI yükleyicisini veya ZIP dosyasındaki tüm DLL'leri adresinden edinin.<a href="https://downloads.aspose.com/cells/net">İndirilenler</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod, ODS\'den C# bayt dizisine dönüşümü gösterir" offSpacer="" %}}

```cs
Workbook workbook = new Workbook("sourceFile.ods");

//Save the workbook in memory stream
MemoryStream ms = new MemoryStream();

workbook.Save(ms, SaveFormat.Ods);

//Read bytes from memory stream
byte[] byte_array = new byte[ms.Length];
ms.Read(byte_array, 0, byte_array.Length);

// Process the memory stream byte array data as of your requirement 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

      
     {{% blocks/products/pf/agp/content h2="" %}}

Tüm Excel dosyalarını oluşturma, değiştirme, dönüştürme, işleme ve yazdırma becerisine sahip, platformlar arası uygulamalar oluşturabilen bir Excel Elektronik Tablo Programlama Kitaplığı. .NET Excel API yalnızca elektronik tablo formatları arasında dönüştürme yapmakla kalmaz, aynı zamanda ODS, PDF, HTML, ODS ve daha fazlasını içeren Excel dosyalarını da işleyebilir, böylece endüstri standardı formatlarda belge alışverişi yapmak için mükemmel bir seçim haline gelir.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
.ods uzantılı dosyalar, kullanıcı tarafından düzenlenebilen OpenDocument Elektronik Tablo Belgesi biçimini ifade eder. Veriler ODF dosyasında satırlar ve sütunlar halinde saklanır. XML tabanlı formattır ve Açık Belge Formatları (ODF) ailesindeki çeşitli alt türlerden biridir. Format, OASIS tarafından yayınlanan ve sürdürülen ODF 1.2 spesifikasyonlarının bir parçası olarak belirtilmiştir. Windows'deki bir dizi uygulamanın yanı sıra diğer işletim sistemleri, Microsoft Excel, NeoOffice ve LibreOffice dahil olmak üzere ODS dosyalarını düzenleme ve manipülasyon için açabilir. ODS dosyaları ayrıca farklı uygulamalarla XLS, XLSX ve diğerleri gibi diğer elektronik tablo formatlarına da dönüştürülebilir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

           {{< /blocks/products/pf/agp/about-file-section >}}


<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Aşağıda listelenenlerden birkaçı dahil olmak üzere diğer dosya formatlarını da bayt dizisine veya tam tersi şekilde dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-byte-array/" name="XLS Bayt Dizisine" description="Microsoft Excel Elektronik Tablosu (Eski)" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-byte-array/" name="XLSX Bayt Dizisine" description="XML Çalışma Kitabını Aç" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsb-to-byte-array/" name="XLSB Bayt Dizisine" description="Excel İkili Çalışma Kitabı" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsm-to-byte-array/" name="XLSM Bayt Dizisine" description="Makro-etkin Elektronik Tablo" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlt-to-byte-array/" name="XLT Bayt Dizisine" description="Excel 97 - 2003 Şablonu" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltx-to-byte-array/" name="XLTX Bayt Dizisine" description="Excel Şablonu" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltm-to-byte-array/" name="XLTM Bayt Dizisine" description="Excel Makro Etkin Şablonu" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/csv-to-byte-array/" name="CSV Bayt Dizisine" description="Virgülle Ayrılmış Değerler" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/tsv-to-byte-array/" name="TSV Bayt Dizisine" description="Sekmeyle Ayrılmış Değerler" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/ods-to-byte-array/" name="ODS Bayt Dizisine" description="OpenDocument Elektronik Tablosu" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-pdf/" name="XLS ila PDF" description="Taşınabilir Döküman Formatı" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-html/" name="XLS ila HTML" description="Hiper Metin İşaretleme Dili" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-pdf/" name="XLSX ila XPS" description="Microsoft Excel OOXML Excel Dosyası" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-html/" name="XLSX ila HTML" description="OOXML Excel Dosyası" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-svg/" name="XLSX ila SVG" description="ölçeklendirilebilir Vektör Grafiği" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-jpeg/" name="XLS ila JPEG" description="JPEG Resim" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
