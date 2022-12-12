---
title: Excel Dosya Birleştirmesi API .NET C#

description: Excel ve OpenOffice elektronik tablo dosyalarını yalnızca birkaç satır C# koduyla birleştirin.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosyasının .NET aracılığıyla Birleştirilmesi" h2="C# kodunu kullanarak 2 veya daha fazla Excel dosyasını tek bir e-tabloda birleştirin" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel Kitaplığı](/cells/net/) formüller, veriler, resimler, çizelgeler vb. gibi çeşitli içerik türleriyle çalışma kitaplarını tek bir elektronik tablo dosyasında birleştirmenin birden çok yolunu sunar. Desteklenen dosya biçimleri arasında XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV ve daha fazlası bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyalarını Görüntüler ve Grafiklerle Birleştirin" %}}
Görüntüleri ve çizelgeleri olan 2 Excel dosyasını birleştirmenin en basit yolu, [Workbook.Combine](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) yöntem. Benzer türdeki Excel dosyalarını tek bir elektronik tabloda birleştirmeye izin verir.
{{% blocks/products/pf/feature-page-code h3="C# Excel Dosyalarını Birleştirme Kodu" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Birden Fazla Excel Dosyasını Birleştirme" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) yöntemi, bir Excel dosyasının verilerini, stilini ve formüllerini aynı formatta yeni bir elektronik tabloyla birleştirmeyi destekler. Önbelleğe almayı kullanırken birkaç dosyayı birleştirmenin etkili bir yoludur. 
{{% blocks/products/pf/feature-page-code h3="C# Birkaç Excel Dosyasını Birleştirme Kodu" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Çalışma Sayfalarını Kopyalayarak Excel Dosyalarını Birleştirme" %}}
[Çalışma Sayfası.Kopyala](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) kaynak çalışma sayfasından çalışma kitaplarının içinde veya arasında başka bir çalışma sayfasına veri ve biçimlendirme kopyalamak için kullanılabilir. Yöntem, kaynak çalışma sayfası nesnesini parametre olarak alır.
{{% blocks/products/pf/feature-page-code h3="C# Çalışma Sayfalarını Excel Dosyalarına Kopyalamak için Kod" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
