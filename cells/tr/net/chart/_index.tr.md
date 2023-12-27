---
title: Excel Grafikleri Oluşturma ve Görsellere Dönüştürme via .NET
description:  .NET Kütüphanesini kullanarak Microsoft Excel'de grafik veya diyagram çizmek ve dönüştürmek için C# kaynak kodu.
keywords: [C# Aspose.Cells., c# Convert chart to image., c# Save chart to image., c# chart to image., create charts in c#., insert charts in c#., manage charts in c#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Grafikleri Oluşturma ve Dönüştürme via .NET" h2=".NET tabanlı uygulamalardaki sunucu tarafı API\'lerini kullanarak Excel belge grafikleri oluşturun ve görüntülere dönüştürün." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Grafik çizmek, kolay analiz için verileri grafiksel olarak gösterme sanatıdır.[.NET Excel Kütüphanesi](/cells/tr/net/) Excel dosyalarındaki grafiklerin çizilmesini destekler. API, listelenen farklı grafik oluşturmayı destekler[ChartType Sayımı](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) pasta, piramit, çizgi ve kabarcık grafikleri dahil. Üstelik grafikleri görsellere de dönüştürüyor. API şunları sağlar:[Grafik sınıfı](https://reference.aspose.com/cells/net/aspose.cells.charts) grafik yapı taşları için.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyasında Grafikler Oluşturun" %}}

 Excel API'i kullanarak grafikler oluşturmak basittir. Süreç şu: Yarat[Çalışma kitabı sınıfı](https://reference.aspose.com/cells/net/aspose.cells/workbook)nesneyi seçin ve ilk çalışma sayfasını veya ilgili sayfayı indeksini sağlayarak seçin. Gerekli hücre verilerini kullanarak ekleyin[PutValue yöntemi](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Charts koleksiyonunu kullanarak çalışma sayfasına grafik ekleyin[Yöntem ekle](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Belirtin[Grafik tipi](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) ChartType numaralandırmasından.
{{% blocks/products/pf/feature-page-code h3="C# Excel Grafikleri Oluşturma Kodu" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Excel Grafiklerini Görsellere Dönüştürün" %}}

 Grafikleri görsellere dönüştürme işlemi şu şekildedir: Excel dosyasını yüklemek için Workbook sınıfını kullanın, grafikleri içeren ilgili çalışma sayfasını seçin ve[ToImage yöntemi](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) dönüşüm için.

{{% blocks/products/pf/feature-page-code h3="C# Excel Grafiği Görüntüye Dönüştürme Kodu" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
