---
title: Go ile Excel Grafikleri Oluşturun ve C++ üzerinden Görüntülere Dönüştürün
description: C++ kaynak koduna giderek Microsoft Excel'de grafik veya diyagram çizmek ve dönüştürmek için C++ Kütüphanesi aracılığıyla Go'yu kullanın.
keywords: [Go via C++ Aspose.Cells., Go via C++ Convert chart to image., Go via C++ Save chart to image., Go via C++ chart to image., create charts in Go via C++., insert charts in Go via C++., manage charts in Go via C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Go ile C++ aracılığıyla Excel Grafikleri Oluşturun ve Görüntülere Dönüştürün" h2="Go üzerinden C++ tabanlı uygulamalarla Excel dokümanlarındaki grafikleri resimlere dönüştürün ve pasta, piramit, çizgi ve baloncuk grafikleri de dahil olmak üzere grafikler oluşturun." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Excel grafiklerini kullanarak, genel tabloyu görebilir ve doğru kararlar almak için verileri kolayca analiz edebilirsiniz.[C++ Excel Kütüphanesi üzerinden gidin.](/cells/tr/go-cpp/) Listelenen farklı grafiklerin oluşturulmasını destekler.[enum Aspose::Cells::Grafikler::GrafikTipi
](https://reference.aspose.com/cells/go-cpp/charttype/) Alan, çubuk, pasta, piramit, çizgi ve baloncuk grafikleri dahil olmak üzere çeşitli grafikler mevcuttur. Ayrıca, grafiklerin görüntülere dönüştürülmesi için API numaralı hizmet sunulmaktadır.[ToImage](https://reference.aspose.com/cells/go-cpp/chart/toimage_string/) Yöntemi gerekli görüntü formatına dönüştürün.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel Grafikleri Oluşturma" %}}

 Excel grafiği oluşturma süreci, öncelikle bir Excel örneği oluşturmakla başlar.[Çalışma kitabı sınıfı](https://reference.aspose.com/cells/go-cpp/workbook/) ve istediğinizi seçin[Çalışma sayfası](https://reference.aspose.com/cells/go-cpp/worksheet/) Grafiği aşağıdaki yöntemle ekleyin:[Yöntem ekle](https://reference.aspose.com/cells/go-cpp/chartcollection/addfloatingchart/) Grafik türü de dahil olmak üzere ilgili parametrelerle birlikte. Grafiğe dizin üzerinden erişin ve[Eklemek](https://reference.aspose.com/cells/go-cpp/seriescollection/add_string_bool_bool/)Grafik için veri kaynağı.

{{% blocks/products/pf/feature-page-code h3="Excel grafikleri oluşturmak için C++ kodunu kullanın." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "create-excel-chart.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Grafikleri Görüntülere Dönüştür" %}}


Grafikleri dönüştürme işlemi şu şekildedir: Öncelikle yukarıdaki kodu kullanarak ilgili türde bir grafik oluşturun veya ilgili sayfadan erişin. Görüntü için çıktı kaydetme yolunu tanımlayın ve dönüştürme için ToImage yöntemini kullanın.


{{% blocks/products/pf/feature-page-code h3="Excel grafiklerini dönüştürmek için C++ kodunu kullanın." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "convert-excel-chart-to-image.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{< /blocks/products/pf/feature-page-wrap >}}