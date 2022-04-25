---
title: Excel Grafikleri Oluşturma ve .NET aracılığıyla Görüntülere Dönüştürme
url: /tr/net/chart/
description: .NET Kitaplığı'nı kullanarak Microsoft Excel'de grafik veya diyagram çizmek ve dönüştürmek için C# kaynak kodu. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Grafikleri Oluşturma ve .NET ile Dönüştürme" h2=".NET tabanlı uygulamalarda sunucu tarafı API\'lerini kullanarak Excel belge çizelgeleri oluşturun ve görüntülere dönüştürün." >}}
{{% blocks/products/pf/feature-page-summary %}}
Grafik çizme, kolay analiz için verileri grafik olarak görüntüleme sanatıdır. [.NET Excel Kitaplığı](/cells/net/) Excel dosyaları içinde çizim çizelgelerini destekler. API, aşağıda listelenen farklı grafik oluşturmayı destekler: [ChartType Numaralandırma](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) pasta, piramit, çizgi ve kabarcık grafikleri dahil. Ayrıca, çizelgeleri görüntülere de dönüştürür. API sağlar [Grafikler sınıfı](https://apireference.aspose.com/cells/net/aspose.cells.charts) grafik yapı taşları için.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyasında Grafikler Oluşturun" %}}

Excel API kullanarak grafikler oluşturmak basittir. İşlem, Oluştur [çalışma kitabı sınıfı](https://apireference.aspose.com/cells/net/aspose.cells/workbook) nesne ve dizinini sağlayarak ilk çalışma sayfasını veya ilgili sayfayı seçin. kullanarak gerekli hücre verilerini ekleyin. [PutValue yöntemi](https://apireference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). Charts koleksiyonunu kullanarak çalışma sayfasına grafik ekleyin. [Yöntem ekle](https://apireference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add). Belirtin [Grafik türü](https://apireference.aspose.com/cells/net/aspose.cells.charts/charttype) ChartType numaralandırmasından.
{{% blocks/products/pf/feature-page-code h3="C# Excel Grafikleri Oluşturmak için Kod" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Excel Grafiklerini Görüntülere Dönüştür" %}}

Grafikleri görüntülere dönüştürme işlemi, Excel dosyasını yüklemek için Çalışma Kitabı sınıfını kullanın, çizelgeleri içeren ilgili çalışma sayfasını seçin ve [ToImage yöntemi](https://apireference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) dönüşüm için.

{{% blocks/products/pf/feature-page-code h3="C# Excel Grafiği Görüntüye Dönüştürmek için Kod" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}