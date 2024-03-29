---
title: C# EXCEL'den MYSQL'ye - EXCEL'den MYSQL'ye dönüştürücü
description: Aspose Excel'de. Aspose.Cells ile EXCEL'i hızlı ve kolay bir şekilde MYSQL'e dönüştürün. C# EXCEL'i MYSQL'e dönüştürün. C# EXCEL'i MYSQL'e kaydedin. C#'i kullanarak EXCEL'i MYSQL olarak kaydedin.
keywords: [Aspose Excel., C# Aspose.Cells., Convert EXCEL to MYSQL in C#., Save EXCEL to MYSQL using C#., C# EXCEL to MYSQL saveformat., EXCEL to MYSQL Converter., C# Save EXCEL as MYSQL]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#\'de EXCEL\'i MYSQL\'e dönüştürün" h2="EXCEL\'i MYSQL\'e dönüştürmek için yüksek hızlı C# kitaplığı. Bu, .NET Framework, .NET Core veya Mono Platformlarında EXCEL, MYSQL ve diğer birçok formatı içe ve dışa aktarmak için profesyonel bir yazılım çözümüdür." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="MYSQL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EXCEL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# kullanarak EXCEL\'i MYSQL\'e dönüştürün" %}}
 EXCEL'i MYSQL'ye nasıl dönüştürebilirim? Aspose.Cells for .NET kütüphanesi ile EXCEL'i programlı olarak birkaç satır kodla kolayca MYSQL'e dönüştürebilirsiniz.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)tüm Excel dosyalarını oluşturma, değiştirme, dönüştürme, işleme ve yazdırma becerisine sahip çapraz platform uygulamaları oluşturma yeteneğine sahiptir. .NET Excel API yalnızca elektronik tablo formatları arasında dönüştürme yapmakla kalmaz, aynı zamanda Excel dosyalarını, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT ve daha fazlasını görüntü olarak işleyebilir, böylece endüstri standardı formatlarda belge alışverişi yapmak için mükemmel bir seçim haline gelir. Açık[NuGet](https://www.nuget.org/packages/aspose.cells) paket yöneticisi, Aspose.Cells'i arayın ve yükleyin. Aşağıdaki komutu Paket Yönetici Konsolundan da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yönetici Konsolu Komutu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="EXCEL\'i C# aracılığıyla MYSQL\'e dönüştürme" %}}

{{% blocks/products/pf/agp/text %}}

EXCEL dosyalarını programlı olarak MYSQL'e dönüştürmeniz mi gerekiyor? .NET geliştiriciler EXCEL'i yalnızca birkaç satır kodla kolayca yükleyebilir ve MYSQL'e dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1.  'Aspose.Cells for .NET' komutunu yükleyin.
1.  C# projenize bir kütüphane referansı ekleyin (kütüphaneyi içe aktarın).
1.  EXCEL dosyasını bir Çalışma Kitabı örneğiyle yükleyin.
1.  Sütun adlarına ve değerlerine dayalı bir Insert ifadesi oluşturun.
1.  MYSQL veritabanına veri eklemek için ifadeleri yürütün.

{{% blocks/products/pf/agp/code-block title="EXCEL\'i MYSQL\'e Dönüştürmek için Örnek Kod - C#" offSpacer="" %}}

```cs
var connectionString = "server=localhost;port=3306;user=root;password=root;database=testdb;charset=utf8mb4;";
var tableName = "areas";
string excelFilePath = "MySQLData.xlsx";
string autoIncrementColumnName = "id";

Workbook workbook = new Workbook(excelFilePath);
Worksheet worksheet = workbook.Worksheets[0];

DataTable dataTable = worksheet.Cells.ExportDataTableAsString(0, 0, worksheet.Cells.MaxDataRow + 1, worksheet.Cells.MaxDataColumn + 1, true);

using (MySqlConnection connection = new MySqlConnection(connectionString))
{
    connection.Open();
    using (MySqlTransaction transaction = connection.BeginTransaction())
    {
        using (MySqlCommand cmd = new MySqlCommand())
        {
            cmd.Connection = connection;
            cmd.Transaction = transaction;

            foreach (DataRow dr in dataTable.Rows)
            {
                string columnNames = string.Join(", ", dataTable.Columns.Cast<DataColumn>()
                    .Select(c => $"`{c.ColumnName}`").Where(c => c != $"`{autoIncrementColumnName}`"));
                string valuesPlaceholders = string.Join(", ", dataTable.Columns.Cast<DataColumn>()
                    .Select((c, index) => $"@value{index + 1}")
                    .Where((val, index) => dataTable.Columns[index].ColumnName != autoIncrementColumnName));

                string insertCmd = $"INSERT INTO `{tableName}` ({columnNames}) VALUES ({valuesPlaceholders})";
                cmd.CommandText = insertCmd;

                cmd.Parameters.Clear();
                for (int i = 0; i < dataTable.Columns.Count; i++)
                {
                    if (dataTable.Columns[i].ColumnName != autoIncrementColumnName)
                    {
                        cmd.Parameters.AddWithValue($"@value{i + 1}", dr[i]);
                    }
                }

                cmd.ExecuteNonQuery();
            }
        }

        transaction.Commit();
    }
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="EXCEL\'i MYSQL\'e dönüştürmek için C# kütüphanesi" %}}

{{% blocks/products/pf/agp/text %}}

Sisteminize "Aspose.Cells for .NET" kurulumu için iki alternatif seçeneğiniz bulunmaktadır. Lütfen ihtiyaçlarınıza uygun olanı seçin ve adım adım talimatları izleyin:

{{% /blocks/products/pf/agp/text %}}

1.  Bir yükleme yapın[NuGet Paket](https://www.nuget.org/packages/Aspose.Cells/) . Görmek[Dokümantasyon](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Kütüphaneyi kullanarak yükleyin[Paket Yönetici Konsolu](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) Visual Studio IDE'de

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 .NET dönüşüm örnek kodunu çalıştırmadan önce aşağıdaki önkoşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows veya .NET, .NET Core, Windows Azure veya Mono Platformlarıyla uyumlu bir işletim sistemi..
-  Microsoft Visual Studio gibi geliştirme ortamı.
-  Projenizdeki Aspose.Cells for .NET DLL dosyasına referans ekleyin.

{{% /blocks/products/pf/agp/content %}}


{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="EXCEL\'i aşağıda listelenenlerden birkaçı dahil olmak üzere diğer birçok dosya formatına da dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-html/" name="HTML\'E EXCEL" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-md/" name="MD\'YE EXCEL" description="İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-mhtml/" name="MHTML\'E EXCEL" description="Web Sayfası Arşiv Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-ods/" name="ODS\'E EXCEL" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-pdf/" name="PDF\'E EXCEL" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-png/" name="PNG\'E EXCEL" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-svg/" name="SVG\'E EXCEL" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-tiff/" name="TIFF\'E EXCEL" description="Etiketli Resim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-tsv/" name="TSV\'E EXCEL" description="Sekmeyle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-txt/" name="TXT\'E EXCEL" description="Metin belgesi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xls/" name="XLS\'E EXCEL" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsb/" name="XLSB\'E EXCEL" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsm/" name="XLSM\'E EXCEL" description="Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlsx/" name="XLSX\'E EXCEL" description="OOXML Excel Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xlt/" name="XLT\'E EXCEL" description="Microsoft Excel Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xltm/" name="XLTM\'E EXCEL" description="Excel Makro Etkin Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xltx/" name="XLTX\'E EXCEL" description="Office OpenXML Excel Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xml/" name="Excel\'den XML\'e" description="Genişletilebilir İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-xps/" name="XPS\'E EXCEL" description="XML Kağıt Özellikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/excel-to-json/" name="JSON\'E EXCEL" description="JavaScript Nesnesi Gösterimi" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
