---
title: Aspose.Cells üzerinden şekiller nasıl eklenir
weight: 7700
limit:
description: Nasıl şekil ekleyeceğinizi öğrenin.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /tr/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells ile şekil eklemeyi öğrenin" >}}

<p>
Bu eğitimde, bir excel dosyasına şekiller ekleyeceğiz.
</p>

<p>
 Kullanarak yeni bir çalışma kitabı oluşturarak başlayacağız.<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells kitaplık</a> ve şekiller ekleyin.
</p>

<br />
{{< app/cells/tutorial >}}
//Özet: Şekillerin nasıl ekleneceğini öğrenmek için lütfen aşağıdaki kodu kontrol edin.
//ExStepSummary:0: Aşağıdaki kod, dikdörtgen şeklinin nasıl ekleneceğini gösterir.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Aşağıdaki kod, çizgi şeklinin nasıl ekleneceğini gösterir.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Aşağıdaki kod oval şeklin nasıl ekleneceğini gösterir.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
Aspose.Cells kullanarak;
Aspose.Cells kullanarak.Çizim;





Çalışma kitabı çalışma kitabı = yeni Çalışma Kitabı();
Çalışma sayfası sayfası = çalışma kitabı.Çalışma Sayfaları[0];
sheet.PageSetup.PrintGridlines = true;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection şekilleri = levha.Shapes;

//dikdörtgen şekli ekle
şekiller.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//çizgi şekli ekle
şekiller.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//oval şekil ekle
şekiller.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
çalışma kitabı
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