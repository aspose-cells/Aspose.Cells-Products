---
title: Excel Çalışma Sayfası sayfasını C# içinde akıllıca ayırın
url: /tr/net/splitter/
description: Microsoft Excel dosyalarının Visual C#.NET uygulamalarında birden çok dosyaya nasıl bölüneceğini açıklayan C# kaynak kodları
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosyasını .NET aracılığıyla Bölme" h2=".NET tabanlı uygulamalarda C# kodunu kullanarak tek Excel belgesini farklı dosyalara bölün" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel Kitaplığı](/cells/net/) .NET tabanlı uygulamalarda Excel belgesini birden çok elektronik tabloya bölebilir. Desteklenen dosya biçimleri arasında XLS, XLSX, XLSB, XLSM, ODS bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Belgesini Birden Çok Dosyaya Böl" %}}
Excel dosyalarını akıllıca bölmenin en basit yolu, Tüm sayfalara [çalışma sayfaları](https://apireference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Her sayfada yineleme ve [kopyala](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) yöntem. Sonunda belirtilen bir yola kaydetme. 

+ Kullanarak Excel dosyasını tam yolla yükleyin [çalışma kitabı sınıfı](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
+ Her sayfada yineleme
+ Yeni bir Çalışma Kitabı sınıfı nesnesi oluşturun
+ Sayfayı şu yolla kopyalayın: [Kopyalama yöntemi](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Save() yöntemini çağırın ve ilgili SaveFormat'a sahip dosya adını (tam yol) iletin.

{{% blocks/products/pf/feature-page-code h3="C# Excel Dosyalarını Bölmek İçin Kod" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfasını Bölmelere Böl" %}}

Çalışma sayfası penceresini bölmelere bölmek için API şunları sağlar: [Bölme yöntemi](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) Çalışma sayfasının bölünmüş görünümünü sağlayan çalışma sayfası sınıfının. Bölünmüş görünümü kaldırmak için API şunları sağlar: [RemoveSplit yöntemi](https://apireference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Sonunda belirtilen bir yola kaydedin. 

{{% blocks/products/pf/feature-page-code h3="C# Excel Çalışma Sayfası Penceresini Bölmek İçin Kod" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Bölünmüş Pan Görünümü Kaldırmak için C# Kodu" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
