---
title: C#'de Excel Çalışma Sayfası sayfasını akıllıca bölün
description: C# kaynak kodları, Microsoft Excel dosyalarının Visual C#.NET uygulamalarında birden çok dosyaya nasıl bölüneceğini açıklar
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Bölme via .NET" h2=".NET tabanlı uygulamalarda C# kodunu kullanarak tek bir Excel belgesini farklı dosyalara bölün" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel Kitaplığı](/cells/tr/net/) .NET tabanlı uygulamalarda Excel belgesini birden çok elektronik tabloya bölme yeteneğine sahiptir. Desteklenen dosya biçimleri arasında XLS, XLSX, XLSB, XLSM, ODS bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Belgesini Birden Çok Dosyaya Böl" %}}
 Excel dosyalarını sayfa bazında bölmenin en basit yolu, tüm sayfalara üzerinden erişmektir.[çalışma sayfaları](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Her sayfayı yineleyerek ve[kopyala](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) yöntem. Sonunda belirtilen bir yola kaydediyor.

 + Kullanarak Excel dosyasını tam yolla yükleyin[Çalışma kitabı sınıfı](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Her sayfa boyunca yineleyin
+ Yeni bir Çalışma Kitabı sınıfı nesnesi oluşturun
 + Sayfayı şununla kopyala:[Kopyalama yöntemi](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Save() yöntemini çağırın ve ilgili SaveFormat'a sahip dosya adını (tam yol) iletin.

{{% blocks/products/pf/feature-page-code h3="C# Excel Dosyalarını Bölme Kodu" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfasını Bölmelere Böl" %}}

 Çalışma sayfası penceresini bölmelere bölmek için API şunları sağlar:[Bölünmüş yöntem](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split)çalışma sayfasının bölünmüş görünümünü sağlayan çalışma sayfası sınıfının. Bölünmüş görünümü kaldırmak için API sağlar[RemoveSplit yöntemi](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Sonunda belirtilen bir yola kaydedin.

{{% blocks/products/pf/feature-page-code h3="C# Excel Çalışma Sayfası Penceresini Bölmek İçin Kod" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Bölünmüş Pan Görünümünü Kaldırma Kodu" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
