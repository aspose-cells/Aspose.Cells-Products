---
title: Excel Grafikleri Oluşturun ve Java ile Görüntülere Dönüştürün

description: Java Kitaplığı'nı kullanarak Microsoft Excel'de grafik veya diyagram çizmek ve dönüştürmek için Java kaynak kodu. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Grafikleri Dönüştürme ve Java ile Oluşturma" h2="Java tabanlı uygulamalarda sunucu tarafı API\'lerini kullanarak çeşitli grafikler oluşturmanın yanı sıra Excel belge çizelgelerini resimlere dönüştürün." >}}


{{% blocks/products/pf/feature-page-summary %}}

Verileri grafikler aracılığıyla analiz etmek büyük resmi gösterir ve daha net bilgilerle daha bilinçli kararlar almak kolaydır. [Java Excel Kitaplığı](/cells/java/) tarafından listelenen farklı grafik oluşturmayı destekler [Grafik türü](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) pasta, piramit, çizgi ve kabarcık grafikleri dahil. Ayrıca, çizelgeleri görüntülere de dönüştürür. API sağlar [Grafikler sınıfı](https://reference.aspose.com/cells/java/com.aspose.cells/Chart) tek bir Excel grafiğini temsil etmek için.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel Grafiklerini Görüntülere Dönüştür" %}}

Grafikleri JPG, PNG, TIFF, BMP vb. dahil resimlere dönüştürme işlemi, [Çalışma kitabı](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) Excel dosyasını yüklemek için ilgili sınıfı seçin [çalışma masası](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) çizelgeleri içeren veya her çalışma sayfasındaki her çizelgeyi yineleyin. Tanımlamak [ResimVeyaYazdırSeçenekleri](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) ve kullanarak Grafiğin çıktı görüntüsünü oluşturun [Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Excel Grafiği Görüntüye Dönüştürmek için Kod" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Excel Dosyasında Grafikler Oluşturun" %}}

API, farklı grafik türleri için Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection vb. gibi farklı sınıflar sağladığından, Excel API kullanarak grafikler oluşturmak basittir. İşlem, Çalışma Kitabı sınıfı nesnesi oluşturun ve dizinini sağlayarak ilk çalışma sayfasını veya ilgili sayfayı seçin. Grafiğin veri kaynağı için, aşağıdakileri kullanarak çalışma sayfası hücrelerine değerler ekleyin: [setValue](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) yöntem. ChartCollection koleksiyonunu kullanın [yöntem ekle](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) grafiği eklemek için ChartType numaralandırmasıyla grafiğin türünü tanımlayın. Dizini ileterek ChartCollection koleksiyonundan yeni Chart nesnesine erişin. Kullan [SeriKoleksiyon](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) grafiğin veri kaynağını belirtmek için grafik nesnesi.

{{% blocks/products/pf/feature-page-code h3="Java Excel Grafikleri Oluşturmak için Kod" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
