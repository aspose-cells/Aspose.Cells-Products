---
title: C# SqlServer'dan EXCEL'e - SqlServer'dan EXCEL'ye dönüştürücü
description: Aspose Excel'de. Aspose.Cells ile SqlServer'ı hızlı ve kolay bir şekilde EXCEL'e dönüştürün. C# SqlServer'ı EXCEL'e dönüştürün. C# SqlServer'ı EXCEL'e kaydedin. C#'i kullanarak SqlServer'ı EXCEL olarak kaydedin.
keywords: [Aspose Excel., C# Aspose.Cells., Convert SqlServer to EXCEL in C#., Save SqlServer to EXCEL using C#., C# SqlServer to EXCEL saveformat., SqlServer to EXCEL Converter., C# Save SqlServer as EXCEL]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#\'de SqlServer\'ı EXCEL\'e dönüştürün" h2="SqlServer\'ı EXCEL\'e dönüştürmek için yüksek hızlı C# kütüphanesi. Bu, .NET Framework, .NET Core veya Mono Platformlarında EXCEL, SqlServer ve diğer birçok formatı içe ve dışa aktarmak için profesyonel bir yazılım çözümüdür." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SqlServer" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EXCEL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanarak SqlServer\'ı EXCEL\'e Dönüştürün" %}}
 SqlServer'ı EXCEL'e nasıl dönüştürebilirim? Aspose.Cells for .NET kütüphanesi ile SqlServer'ı programlı olarak birkaç satır kodla kolayca EXCEL'e dönüştürebilirsiniz.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)tüm Excel dosyalarını oluşturma, değiştirme, dönüştürme, işleme ve yazdırma becerisine sahip çapraz platform uygulamaları oluşturma yeteneğine sahiptir. .NET Excel API yalnızca elektronik tablo formatları arasında dönüştürme yapmakla kalmaz, aynı zamanda Excel dosyalarını, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT ve daha fazlasını görüntü olarak işleyebilir, böylece endüstri standardı formatlarda belge alışverişi yapmak için mükemmel bir seçim haline gelir. Açık[NuGet](https://www.nuget.org/packages/aspose.cells) paket yöneticisi, Aspose.Cells'i arayın ve yükleyin. Aşağıdaki komutu Paket Yönetici Konsolundan da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yönetici Konsolu Komutu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="SqlServer\'ı C# aracılığıyla EXCEL\'e dönüştürme" %}}

{{% blocks/products/pf/agp/text %}}

SqlServer verilerini programlı olarak EXCEL'e dönüştürmeniz mi gerekiyor? .NET geliştiriciler SqlServer'ı yalnızca birkaç satır kodla kolayca yükleyebilir ve EXCEL'e dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1.  'Aspose.Cells for .NET' komutunu yükleyin.
1.  C# projenize bir kütüphane referansı ekleyin (kütüphaneyi içe aktarın).
1.  Bir DataTable nesnesi elde etmek için SqlServer veritabanındaki verileri sorgulayın.
1.  Yeni bir Çalışma Kitabı oluşturun ve bir DataTable nesnesinden verileri içe aktarın.
1. Workbook.Save yöntemini çağırarak verileri xlsx formatında kaydedin.

{{% blocks/products/pf/agp/code-block title="SqlServer\'ı EXCEL\'e Dönüştürmek için Örnek Kod - C#" offSpacer="" %}}

```cs
var connectionString = "Server=localhost;Database=SqlServerTestDataBase;User ID=root;Password=admin;Trusted_Connection=False;";
var tableName = "countrylanguage";

string query = $"SELECT * FROM {tableName}";

using (SqlConnection connection = new SqlConnection(connectionString))
{
    connection.Open();
    SqlCommand cmd = new SqlCommand(query, connection);
    SqlDataAdapter adapter = new SqlDataAdapter(cmd);

    DataTable dataTable = new DataTable();
    adapter.Fill(dataTable);

    Workbook workbook = new Workbook();
    Worksheet worksheet = workbook.Worksheets[0];
    worksheet.Cells.ImportData(dataTable, 0, 0, new ImportTableOptions() { InsertRows = true });
    workbook.Save("SQLServerData.xlsx");
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="SqlServer\'ı EXCEL\'e dönüştürmek için C# kitaplığı" %}}

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


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
