---
title: Excel Çalışma Sayfası sayfasını C#'de akıllıca bölme
description: C# Excel dosyalarının Visual C#.NET uygulamalarında birden çok dosyaya nasıl bölüneceğini açıklayan kaynak kodları
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Bölme via .NET" h2=".NET tabanlı uygulamalarda C# kodunu kullanarak tek bir Excel belgesini farklı dosyalara bölme" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel Kütüphanesi](/cells/tr/net/) Excel belgesini .NET tabanlı uygulamalar içinde birden fazla elektronik tabloya bölme yeteneğine sahiptir. Desteklenen dosya formatları arasında XLS, XLSX, XLSB, XLSM, ODS bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Belgesini Birden Çok Dosyaya Bölme" %}}
Excel dosyalarını sayfalara ayırmanın en basit yolu, tüm sayfalara şu adresten erişmektir:[Çalışma sayfaları](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Her sayfayı yineleyerek ve[Kopyala](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) yöntem. Sonunda onu belirli bir yola kaydediyorum.

 + Excel dosyasını kullanarak tam yolu yükleyin[Çalışma kitabı sınıfı](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Her sayfada yineleme
+ Yeni bir Çalışma Kitabı sınıfı nesnesi oluşturun
 + Sayfayı şununla kopyala:[Kopyalama yöntemi](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Save() yöntemini çağırın ve ilgili SaveFormat'a sahip dosya adını (tam yol) iletin.

{{% blocks/products/pf/feature-page-code h3="C# Excel Dosyalarını Bölme Kodu" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfasını Bölmelere Böl" %}}

 Çalışma sayfası penceresini bölmelere bölmek için API şunu sağlar:[Bölünmüş yöntem](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) çalışma sayfasının bölünmüş görünümünü sağlayan çalışma sayfası sınıfının. Bölünmüş görünümü kaldırmak için API şunu sağlar:[RemoveSplit yöntemi](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Son olarak onu belirtilen yola kaydedin.

{{% blocks/products/pf/feature-page-code h3="C# Excel Çalışma Sayfası Penceresini Bölme Kodu" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Bölünmüş Pan Görünümünü Kaldırma Kodu" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
