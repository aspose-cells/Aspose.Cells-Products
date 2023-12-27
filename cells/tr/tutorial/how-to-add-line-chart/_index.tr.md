---
title: Aspose.Cells aracılığıyla çizgi grafiği nasıl eklenir?
weight: 7700
limit:
description: Çizgi grafiğinin nasıl ekleneceğini öğrenin.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /tr/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells\'i kullanarak çizgi grafiğini nasıl ekleyeceğinizi öğrenin" >}}

<p>
Bu derste bir excel dosyasına çizgi grafiği ekleyeceğiz.
</p>

<p>
 kullanarak yeni bir çalışma kitabı oluşturarak başlayacağız.<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells kütüphane</a> ve çizgi grafiği ekleyin.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Çizgi grafiğin nasıl ekleneceğini öğrenmek için lütfen aşağıdaki kodu kontrol edin.
//ExStepSummary:0: Aşağıdaki kod, çizgi grafiğinin nasıl ekleneceğini, seri veri aralığının nasıl ayarlanacağını ve kategori veri aralığının nasıl ayarlanacağını gösterir.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Aşağıdaki kod, açıklamanın en alta nasıl taşınacağını ve açıklamanın yazı tipi renginin nasıl ayarlanacağını gösterir.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Aşağıdaki kod, veri etiketlerine nasıl erişileceğini, kategori adlarının nasıl açılacağını ve konumun nasıl ayarlanacağını gösterir.
//ExStepImage:2:adım-3.png
//ExStart
//ExStep:0-
Aspose.Cells'i kullanarak;
Aspose.Cells kullanarak.Çizim;

Çalışma kitabı çalışma kitabı = yeni Çalışma Kitabı();
Çalışma sayfası sayfası = çalışma kitabı.Çalışma sayfaları[0];
sayfa.Name = "Grafik Sayfası";
Cells hücreler = sayfa.Cells;
hücreler["A1"].Değer = "Meyve";
hücreler["A2"].Değer = "elma";
hücreler["A3"].Değer = "turuncu";
hücreler["A4"].Değer = "yaban mersini";
hücreler["A5"].Değer = "kivi";

hücreler["B1"].Değer = "Fiyat";
hücreler["B2"].Değer = 10;
hücreler["B3"].Değer = 5;
hücreler["B4"].Değer = 20;
hücreler["B5"].Değer = 8;

Sheet.PageSetup.PrintGridlines = true;
Sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection çizelgeleri = sayfa.Charts;

//Çizgi grafiği ekleyin, seri veri aralığını ayarlayın ve kategori veri aralığını ayarlayın
int index = page.Charts.Add(ChartType.Line, 6, 0, 19, 5);
Grafik grafiği = sayfa.Charts[index];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Lejantı aşağıya taşıyın ve efsanenin yazı tipi rengini ayarlayın
chart.Legend.Font.Color = Renk.Mavi;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
//Veri etiketlerine erişin, kategori adlarını açın ve konumu ayarlayın
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = doğru;
dataLabels.Position = LabelPositionType.Center;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Aspose.Cells kurulumu</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Editör</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}