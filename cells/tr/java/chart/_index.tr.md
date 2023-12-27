---
title: Excel Grafikleri Oluşturun ve Görsellere Dönüştürün via Java
description:  Java Kütüphanesini kullanarak Microsoft Excel'de grafik veya diyagram çizmek ve dönüştürmek için Java kaynak kodu.
keywords: [Java Aspose.Cells., Java Convert chart to image., Java Save chart to image., Java chart to image., create charts in Java., insert charts in Java., manage charts in Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Grafiklerini Dönüştürme ve Oluşturma via Java" h2="Java tabanlı uygulamalardaki sunucu tarafı API\'lerini kullanarak Excel belge grafiklerini görüntülere dönüştürün ve çeşitli grafikler oluşturun." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Verileri grafikler aracılığıyla analiz etmek büyük resmi gösterir ve daha net içgörülerle daha bilinçli kararlar vermek kolaydır.[Java Excel Kütüphanesi](/cells/tr/java/) tarafından listelenen farklı grafik oluşturma çizimini destekler[Grafik tipi](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) pasta, piramit, çizgi ve kabarcık grafikleri dahil. Üstelik grafikleri görsellere de dönüştürüyor. API şunları sağlar:[Grafik sınıfı](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) tek bir Excel grafiğini temsil etmek için.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel Grafiklerini Görsellere Dönüştürün" %}}

 Grafikleri JPG, PNG, TIFF, BMP vb. dahil olmak üzere resimlere dönüştürme işlemi şu şekildedir:[Çalışma kitabı](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) Excel dosyasını yüklemek için ilgili sınıfı seçin[çalışma sayfası](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) grafikleri içeren veya her çalışma sayfasındaki her grafiği yineleyen. Tanımlamak[Görüntü Veya Yazdırma Seçenekleri](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) ve kullanarak Grafiğin çıktı görüntüsünü oluşturun[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Excel Grafiği Görüntüye Dönüştürme Kodu" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Excel Dosyasında Grafikler Oluşturun" %}}

Excel API'i kullanarak grafik oluşturmak basittir; API, farklı türde grafikler için Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection vb. gibi farklı sınıflar sağlar. İşlem, Workbook sınıfı nesnesini oluşturun ve ilk çalışma sayfasını veya ilgili sayfayı indeksini sağlayarak seçin. Grafiğin veri kaynağı için, aşağıdakileri kullanarak çalışma sayfası hücrelerine değerler ekleyin:[setValue](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) yöntem. ChartCollection koleksiyonunu kullanın[yöntem ekle](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) Grafiği eklemek için ChartType numaralandırmasıyla grafiğin türünü tanımlayın. Dizinini ileterek ChartCollection koleksiyonundan yeni Chart nesnesine erişin. Kullan[SeriKoleksiyon](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) Grafiğin veri kaynağını belirtmek için grafik nesnesi.

{{% blocks/products/pf/feature-page-code h3="Java Excel Grafikleri Oluşturma Kodu" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
