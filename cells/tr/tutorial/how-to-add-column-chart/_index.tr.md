---
title: Aspose.Cells aracılığıyla sütun grafiği nasıl eklenir?
weight: 7700
limit:
description: Sütun grafiğini nasıl ekleyeceğinizi öğrenin.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /tr/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells ile sütun grafiğini nasıl ekleyeceğinizi öğrenin" >}}

<p>
Bu derste bir excel dosyasına sütun grafiği ekleyeceğiz.
</p>

<p>
 kullanarak yeni bir çalışma kitabı oluşturarak başlayacağız.<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells kütüphane</a> ve sütun grafiği ekleyin.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Sütun grafiğinin nasıl ekleneceğini öğrenmek için lütfen aşağıdaki kodu kontrol edin.
//ExStepSummary:0: Aşağıdaki kod sütun grafiğinin nasıl ekleneceğini gösterir.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Aşağıdaki kod, açıklamanın sola nasıl taşınacağını ve açıklamanın yazı tipi renginin nasıl ayarlanacağını gösterir.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Aşağıdaki kod, bir grafiğin başlığının nasıl ayarlanacağını ve yazı tipi renginin mavi olarak nasıl değiştirileceğini gösterir.
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

//Sütun grafiği ekle
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Grafik grafiği = grafikler[indeks];

//ExStep:1-
//Lejantı sola taşıyın ve efsanenin yazı tipi rengini ayarlayın
chart.Legend.Font.Color = Renk.Mavi;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//Grafiğin başlığını belirledik ve yazı tipi rengini mavi olarak değiştirdik
chart.Title.Text = "Meyve Fiyatı Sütun Tablosu";
chart.Title.Font.Color = Renk.Mavi;

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