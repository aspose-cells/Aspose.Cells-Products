---
title: Excel Grafikleri Oluşturun ve C++ ile Görüntülere Dönüştürün
url: /tr/cpp/chart/
description: C++ Kitaplığı'nı kullanarak Microsoft Excel'de grafik veya diyagram çizmek ve dönüştürmek için C++ kaynak kodu
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Grafikleri Oluşturun ve C++ aracılığıyla Görüntülere Dönüştürün" h2="C++ tabanlı uygulamalarda Excel belge çizelgelerini görüntülere dönüştürün ve Pasta, Piramit, Çizgi ve Kabarcık çizelgeleri gibi çizelgeler oluşturun." >}}

{{% blocks/products/pf/feature-page-summary %}}

Excel çizelgelerini kullanarak, doğru kararlar almak için daha büyük resmi görebilir ve verileri kolayca analiz edebilirsiniz. [C++ Excel Kitaplığı](/cells/cpp/) tarafından listelenen farklı grafikler oluşturmayı destekler [enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) alan, çubuk, pasta, piramit, çizgi ve kabarcık grafikleri dahil. Ayrıca, çizelgelerin resimlere dönüştürülmesi için API, bir [ToImage yöntemi](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) gerekli görüntü formatına dönüştürün.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel Grafikleri Oluşturun" %}}

Excel grafiği oluşturma işlemi, bir örneğini oluşturmaktır. [IWorkbook sınıfı](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ve istediğinizi seçin [Çalışma kağıdı](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). kullanarak grafiği ekleyin [Yöntem ekle](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) grafik türü de dahil olmak üzere ilgili parametrelerle. Grafiğe dizin aracılığıyla erişin ve [Ekle](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) grafik için veri kaynağı.

{{% blocks/products/pf/feature-page-code h3="C++ Excel Grafikleri Oluşturmak için Kod" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Grafikleri Görüntülere Dönüştür" %}}


Çizelgeleri dönüştürmek için önce yukarıdaki kodu kullanarak ilgili türden bir tablo oluşturun ya da ilgili sayfadan ona ulaşın. Görüntü için çıktı kaydetme yolunu tanımlayın ve dönüştürme için ToImage yöntemini kullanın.

 
{{% blocks/products/pf/feature-page-code h3="C++ Excel Grafiklerini Dönüştürmek için Kod" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}