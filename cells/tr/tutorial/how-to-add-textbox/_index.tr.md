---
title: Aspose.Cells aracılığıyla TextBox nasıl eklenir?
weight: 7700
limit:
description: TextBox'u nasıl ekleyeceğinizi öğrenin.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /tr/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aspose.Cells ile TextBox\'u nasıl ekleyeceğinizi öğrenin" >}}

<p>
Bu eğitimde, bir excel dosyasına TextBox ekleyeceğiz.
</p>

<p>
 Kullanarak yeni bir çalışma kitabı oluşturarak başlayacağız.<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells kitaplık</a> ve TextBox'u ekleyin.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: TextBox'u nasıl ekleyeceğinizi öğrenmek için lütfen aşağıdaki kodu kontrol edin.
//ExStepSummary:0: Aşağıdaki kod, TextBox'ın nasıl ekleneceğini ve metnin nasıl ayarlanacağını gösterir.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Aşağıdaki kod, metnin renginin nasıl değiştirileceğini gösterir.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Aşağıdaki kod, TextBox'ın dönüş açısının nasıl değiştirileceğini gösterir.
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

//TextBox ekleyin ve metni ayarlayın
Metin Kutusu metin Kutusu = şekiller.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET, yazılım geliştiricilerin elektronik tablo dosyalarını kendi uygulamalarında değiştirmelerine ve işlemelerine olanak tanıyan bir programlama sınıfı kitaplığıdır.";

//ExStep:1-
//metnin rengini değiştir
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