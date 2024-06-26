---
title: SQL oluştur - Python'de SQL dosyası oluşturun
description: Aspose Excel'de. Python Excel'de. Python Aspose.Cells ile hızlı ve kolay bir şekilde SQL Dosyası oluşturun. Python Excel Kütüphanesini kullanarak SQL dosyası oluşturun. Python Excel Kitaplığı'nda SQL oluşturun. Python SQL Oluşturucu.
keywords: [Aspose Python Excel., Python Aspose.Cells., Python Create SQL file., Generate SQL file in Python Excel Library., Create SQL file using Python Excel Library., Write data to SQL file via Python Excel Library., Create a SQL file in Python Excel Library., Python Generate a SQL file., Python SQL Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Python Excel Kitaplığında SQL Dosyası Oluşturun" h2="SQL dosyası oluşturmak için yüksek hızlı Python Excel kitaplığı. Bu, XLSX, PDF ve diğer birçok formatı Python kullanarak içe ve dışa aktarmak için profesyonel bir yazılım çözümüdür." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SQL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Python" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/pythonjava" installationsDocsLink="https://docs.aspose.com/cells/pythonjava" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/python-java/" learnAsLink="https://docs.aspose.com/cells/pythonjava" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Python Excel Kitaplığını Kullanarak SQL Dosyası Oluşturun" %}}

 SQL dosyası nasıl oluşturulur? Aspose.Cells for Python via Java excel kütüphanesi ile birkaç satır kod ile programlı olarak kolayca SQL dosyası oluşturabilirsiniz.[Aspose.Cells for Python](https://pypi.org/project/aspose-cells)tüm Excel dosyalarını oluşturma, değiştirme, dönüştürme, işleme ve yazdırma becerisine sahip çapraz platform uygulamaları oluşturma yeteneğine sahiptir. Python Excel API yalnızca elektronik tablo formatları arasında dönüştürme yapmakla kalmaz, aynı zamanda Excel dosyalarını, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT ve daha fazlasını görüntü olarak işleyebilir, böylece endüstri standardı formatlarda belge alışverişi yapmak için mükemmel bir seçim haline gelir.

{{% /blocks/products/pf/agp/content %}}



{{% blocks/products/pf/agp/content h2="Python Excel Kitaplığında SQL Nasıl Oluşturulur" %}}

{{% blocks/products/pf/agp/text %}}

 Geliştiricilerin, veri işleme için farklı raporlama uygulamalarını çalıştırarak SQL dosyalarını yalnızca birkaç satır kodla oluşturması, yüklemesi, değiştirmesi ve dönüştürmesi kolaydır.

{{% /blocks/products/pf/agp/text %}}

1.  Asposecell'leri kod dosyanıza aktarın.
1.  Çalışma Kitabı sınıfı örneği oluşturun.
1.  Çalışma kitabının ilk çalışma sayfasına erişin.
1. Çalışma sayfasının istenen hücresini/hücrelerini alın ve değeri hücreye/hücrelere girin.
1.  Çalışma kitabını SQL dosyası olarak kaydetmek için Kaydet yöntemini kullanın.

{{% blocks/products/pf/agp/code-block title="Örnek kod, Python excel kitaplığında SQL dosyasının nasıl oluşturulacağını gösterir." offSpacer="" %}}

```cs

import jpype
import asposecells
jpype.startJVM()
from asposecells.api import Workbook, FileFormatType

# Create Workbook object.
workbook = Workbook(FileFormatType.SQL)

# Access the first worksheet of the workbook.
worksheet = workbook.getWorksheets().get(0)

# Get the desired cell(s) of the worksheet and input the value into the cell(s).
worksheet.getCells().get("A1").putValue("ColumnA")
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

# Save the workbook as SQL file.
workbook.save("output.sql")

jpype.shutdownJVM()

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Python SQL Dosyası Oluşturmak için Excel Kitaplığı" %}}

{{% blocks/products/pf/agp/text %}}

Sisteminize "Aspose.Cells for Python via Java" kurulumu için üç seçenek bulunmaktadır. Lütfen ihtiyaçlarınıza uygun olanı seçin ve adım adım talimatları izleyin:

{{% /blocks/products/pf/agp/text %}}

1.  Aspose.Cells for Python via Java'i Windows'e yükleyin. Bkz.[Dokümantasyon](https://docs.aspose.com/cells/python-java/getting-started/#windows)
1.  Linux'ta Aspose.Cells for Python via Java'i yükleyin. Görmek[Dokümantasyon](https://docs.aspose.com/cells/python-java/getting-started/#linux)
1.  MacOS'ta Aspose.Cells for Python via Java'i yükleyin. Görmek[Dokümantasyon](https://docs.aspose.com/cells/python-java/getting-started/#macos)

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Cells for Python via Java platformdan bağımsızdır API ve herhangi bir platformda kullanılabilir (Windows, Linux ve MacOS), sadece sistemin Java 1.8 veya daha yüksek bir sürüme sahip olduğundan emin olun,[Python](https://www.python.org/downloads/) 3,5 veya daha yüksek.

{{% /blocks/products/pf/agp/text %}}

-  Java'i kurun ve PATH ortam değişkenine ekleyin, örneğin:<code>PATH=C:\Program Files\Java\jdk1.8.0_131;</code>.
-  Aspose.Cells for Python via Java'i şuradan yükleyin:<a href="https://pypi.org/project/aspose-cells/">pypi</a> , komutu şu şekilde kullanın:<code>$ pip install aspose-cells</code>.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SQL" readMoreLink="https://docs.fileformat.com/database/sql/" >}}.sql uzantılı bir dosya, ilişkisel veritabanlarıyla çalışacak kodları içeren Yapılandırılmış Sorgu Dili (SQL) dosyasıdır. Veritabanlarında CRUD (Oluşturma, Okuma, Güncelleme ve Silme) işlemleri için SQL ifadeleri yazmak için kullanılır. SQL dosyaları, masaüstü ve web tabanlı veritabanlarıyla çalışırken yaygındır. SQL'in Java Kalıcı Sorgu Dili (JPQL), LINQ, HTSQL, 4D QL ve diğerleri gibi çeşitli alternatifleri vardır. SQL dosyaları, Microsoft SQL Server'ın sorgu editörleri, MySQL ve Windows işletim sistemindeki Notepad gibi diğer düz metin editörleri tarafından açılabilir.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Elektronik Tablo Oluşturma" subTitle="Ayrıca aşağıda listelenenlerden birkaçı dahil olmak üzere diğer Microsoft Excel formatlarını da oluşturabilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xls/" name="XLS" description="Microsoft Excel Elektronik Tablosu (Eski)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsx/" name="XLSX" description="XML Çalışma Kitabını Aç" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsb/" name="XLSB" description="Excel İkili Çalışma Kitabı" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlsm/" name="XLSM" description="Makro-etkin Elektronik Tablo" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xlt/" name="XLT" description="Excel 97 - 2003 Şablonu" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltx/" name="XLTX" description="Excel Şablonu" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/xltm/" name="XLTM" description="Excel Makro Etkin Şablonu" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/csv/" name="CSV" description="Virgülle Ayrılmış Değerler" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/tsv/" name="TSV" description="Sekmeyle Ayrılmış Değerler" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/ods/" name="ODS" description="OpenDocument Elektronik Tablosu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/pdf/" name="PDF" description="Taşınabilir Döküman Formatı" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/python-java/create/html/" name="HTML" description="Hiper Metin İşaretleme Dili" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
