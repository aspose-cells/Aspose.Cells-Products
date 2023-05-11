---
title: Excel Grafikleri Oluşturun ve Görsellere Dönüştürün via Java
description:  Java kaynak kodu, Java Kitaplığını kullanarak Microsoft Excel'de grafik veya diyagram çizmek ve dönüştürmek için.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Grafikleri Dönüştürme ve Oluşturma via Java" h2="Java tabanlı uygulamalarda sunucu tarafı API\'lerini kullanarak Excel belge grafiklerini görüntülere dönüştürün ve çeşitli grafikler oluşturun." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Verileri grafikler aracılığıyla analiz etmek daha büyük resmi gösterir ve daha net içgörülerle daha bilinçli kararlar vermek kolaydır.[Java Excel Kitaplığı](/cells/tr/java/) tarafından listelenen farklı grafik oluşturmayı destekler.[Grafik tipi](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) pasta, piramit, çizgi ve kabarcık grafikler dahil. Ayrıca grafikleri resimlere dönüştürür. API bir sağlar[Grafik sınıfı](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)tek bir Excel grafiğini temsil etmek için.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Excel Grafiklerini Görüntülere Dönüştür" %}}

 Grafikleri JPG, PNG, TIFF, BMP vb. dahil olmak üzere resimlere dönüştürme işlemi,[Çalışma kitabı](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) Excel dosyasını yüklemek için sınıfı seçin, ilgili[çalışma sayfası](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) grafikleri içerir veya her çalışma sayfasındaki her grafiği yineler. Tanımlamak[ResimVeyaBaskıSeçenekleri](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) ve kullanarak Grafiğin çıktı görüntüsünü oluşturun[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Excel Grafiği Görüntüye Dönüştürmek İçin Kod" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Excel Dosyasında Grafikler Oluşturun" %}}

 Excel API'i kullanarak grafikler oluşturmak basittir, çünkü API, farklı türde grafikler için Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection vb. İşlem, Çalışma Kitabı sınıf nesnesi oluşturun ve ilk çalışma sayfasını veya ilgili sayfayı dizini sağlayarak seçin. Grafiğin veri kaynağı için, kullanarak çalışma sayfası hücrelerine değerler ekleyin.[değer ayarla](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)yöntem. ChartCollection koleksiyonunu kullanın[yöntem ekle](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) grafiği eklemek için, ChartType numaralandırmasıyla grafiğin türünü tanımlayın. Dizinini geçirerek ChartCollection koleksiyonundan yeni Chart nesnesine erişin. Kullan[Seri Koleksiyonu](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) grafiğin veri kaynağını belirtmek için grafik nesnesi.

{{% blocks/products/pf/feature-page-code h3="Java Excel Grafikleri Oluşturma Kodu" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
