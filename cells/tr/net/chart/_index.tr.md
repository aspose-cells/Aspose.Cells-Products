---
title: Excel Grafikleri Oluşturma ve Görsellere Dönüştürme via .NET
description:  C# kaynak kodu, .NET Kitaplığını kullanarak Microsoft Excel'de grafik veya diyagram çizmek ve dönüştürmek için.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Grafikleri Oluşturma ve Dönüştürme via .NET" h2=".NET tabanlı uygulamalarda sunucu tarafı API\'lerini kullanarak Excel belge çizelgeleri oluşturun ve resimlere dönüştürün." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Grafik çizmek, kolay analiz için verileri grafiksel olarak görüntüleme sanatıdır.[.NET Excel Kitaplığı](/cells/tr/net/) Excel dosyaları içinde grafik çizmeyi destekler. API, içinde listelenen farklı grafik oluşturmayı destekler[ChartType Numaralandırma](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) pasta, piramit, çizgi ve kabarcık grafikler dahil. Ayrıca grafikleri resimlere dönüştürür. API bir sağlar[Grafik sınıfı](https://reference.aspose.com/cells/net/aspose.cells.charts) grafik yapı taşları için.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyasında Grafikler Oluşturun" %}}

 Excel API kullanarak grafikler oluşturmak basittir. İşlem, Yarat[Çalışma kitabı sınıfı](https://reference.aspose.com/cells/net/aspose.cells/workbook) nesnesini seçin ve dizinini vererek ilk çalışma sayfasını veya ilgili sayfayı seçin. Kullanarak gerekli hücre verilerini ekleyin[PutValue yöntemi](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Charts koleksiyonunu kullanarak çalışma sayfasına grafik ekleyin[yöntem ekle](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . belirtin[Grafik tipi](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)ChartType numaralandırmasından.
{{% blocks/products/pf/feature-page-code h3="C# Excel Grafikleri Oluşturma Kodu" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Excel Grafiklerini Görüntülere Dönüştür" %}}

 Grafikleri görüntülere dönüştürme işlemi, Excel dosyasını yüklemek için Workbook sınıfını kullanın, grafikleri içeren ilgili çalışma sayfasını seçin ve[ToImage yöntemi](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) dönüşüm için.

{{% blocks/products/pf/feature-page-code h3="C# Excel Grafiği Görüntüye Dönüştürmek İçin Kod" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
