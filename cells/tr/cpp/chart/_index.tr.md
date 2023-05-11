---
title: C++ ile Excel Grafikleri Oluşturun ve Görsellere Dönüştürün
description: C++ kaynak kodu, C++ Kitaplığını kullanarak Microsoft Excel'de grafik veya diyagram çizmek ve dönüştürmek için
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Grafiklerini Oluşturun ve C++ aracılığıyla Görsellere Dönüştürün" h2="C++ tabanlı uygulamalarda Excel belge çizelgelerini görüntülere dönüştürün ve Pasta, Piramit, Çizgi ve Kabarcık çizelgeleri içeren çizelgeler oluşturun." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Excel grafiklerini kullanarak, doğru kararlar almak için büyük resmi görebilir ve verileri kolayca analiz edebilirsiniz.[C++ Excel Kitaplığı](/cells/tr/cpp/) tarafından listelenen farklı grafikler oluşturmayı destekler[enum Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) alan, çubuk, pasta, piramit, çizgi ve kabarcık çizelgeleri dahil. Ayrıca, çizelgelerin resimlere dönüştürülmesi için API,[Görüntüye yöntemi](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) gerekli görüntü biçimine.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel Grafikleri Oluşturun" %}}

 Excel grafiği oluşturma süreci, bir örneğini oluşturmaktır.[IWorkbook sınıfı](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ve istediğinizi seçin[Çalışma kağıdı](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43) . kullanarak grafiği ekleyin[yöntem ekle](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068)grafik türü de dahil olmak üzere ilgili parametrelerle. Grafiğe dizin aracılığıyla erişin ve[Eklemek](https://reference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) grafik için veri kaynağı.

{{% blocks/products/pf/feature-page-code h3="C++ Excel Grafikleri Oluşturma Kodu" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Grafikleri Görüntülere Dönüştür" %}}


Grafikleri dönüştürme işlemi için, önce yukarıdaki kodu kullanarak ilgili türde grafiği oluşturun veya ilgili sayfadan ona erişin. Görüntü için çıktı kaydetme yolunu tanımlayın ve dönüştürme için ToImage yöntemini kullanın.

 
{{% blocks/products/pf/feature-page-code h3="C++ Excel Grafiklerini Dönüştürmek İçin Kod" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
