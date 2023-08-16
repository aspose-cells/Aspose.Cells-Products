---
title: Aspose.Cells üzerinden sütun grafiği nasıl eklenir
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
Bu eğitimde, bir excel dosyasına sütun grafiği ekleyeceğiz.
</p>

<p>
 Kullanarak yeni bir çalışma kitabı oluşturarak başlayacağız.<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells kitaplık</a> ve sütun grafiği ekleyin.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Sütun grafiğini nasıl ekleyeceğinizi öğrenmek için lütfen aşağıdaki kodu kontrol edin.
//ExStepSummary:0: Aşağıdaki kod, sütun grafiğinin nasıl ekleneceğini gösterir.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Aşağıdaki kod, lejandın sola nasıl taşınacağını ve lejandın yazı tipi renginin nasıl ayarlanacağını gösterir.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Aşağıdaki kod, grafiğin başlığının nasıl ayarlanacağını ve yazı tipi renginin maviye nasıl değiştirileceğini gösterir.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
Aspose.Cells kullanarak;
Aspose.Cells kullanarak.Çizim;

Çalışma kitabı çalışma kitabı = yeni Çalışma Kitabı();
Çalışma sayfası sayfası = çalışma kitabı.Çalışma Sayfaları[0];
sheet.Name = "ChartSheet";
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

sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ChartCollection çizelgeleri = sayfa.Grafikler;

//sütun grafiği ekle
int indeks = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Grafik grafiği = çizelgeler[dizin];

//ExStep:1-
//Efsanı sola taşı ve lejandın yazı tipi rengini ayarla
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//Bir grafiğin başlığını ayarlayın ve yazı tipi rengini mavi olarak değiştirin
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