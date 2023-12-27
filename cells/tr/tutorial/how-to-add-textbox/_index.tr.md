---
title: Aspose.Cells aracılığıyla TextBox nasıl eklenir?
weight: 7700
limit:
description: TextBox'ı nasıl ekleyeceğinizi öğrenin.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /tr/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells ile TextBox\'ı nasıl ekleyeceğinizi öğrenin" >}}

<p>
Bu derste, bir excel dosyasına TextBox ekleyeceğiz.
</p>

<p>
 kullanarak yeni bir çalışma kitabı oluşturarak başlayacağız.<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells kütüphane</a> ve TextBox'ı ekleyin.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: TextBox'un nasıl eklendiğini öğrenmek için lütfen aşağıdaki kodu kontrol edin.
//ExStepSummary:0: Aşağıdaki kod, TextBox'un nasıl ekleneceğini ve metnin nasıl ayarlanacağını gösterir.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Aşağıdaki kod, metnin renginin nasıl değiştirileceğini gösterir.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Aşağıdaki kod, TextBox'un dönüş açısının nasıl değiştirileceğini gösterir.
//ExStepImage:2:adım-3.png
//ExStart
//ExStep:0-
Aspose.Cells'i kullanarak;
Aspose.Cells kullanarak.Çizim;

Çalışma kitabı çalışma kitabı = yeni Çalışma Kitabı();
Çalışma sayfası sayfası = çalışma kitabı.Çalışma sayfaları[0];
Sheet.PageSetup.PrintGridlines = true;
Sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection şekilleri = sayfa.Şekiller;

//TextBox'ı ekleyip metni ayarladık
TextBox textBox = şekiller.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET, yazılım geliştiricilerin elektronik tablo dosyalarını kendi uygulamaları içinde değiştirmelerine ve işlemelerine olanak tanıyan bir programlama sınıfı kitaplığıdır.";

//ExStep:1-
//Metnin rengini değiştir
textBox.Font.Color = Renk.Mavi;

//ExStep:2-
//TextBox'ın dönüş açısını değiştir
textBox.RotationAngle = 90;

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