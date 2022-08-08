---
title: Java İçinde Farklı Excel Dosyalarını Tek Bir Dosyada Birleştirin
url: /tr/java/merger/
description: Java kullanarak Excel dosyalarını birden çok sayfa veya tek sayfa halinde birleştirin. Excel belgelerini PDF, Görüntüler ve HTML ile birleştirin, birleştirin veya birleştirin.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosyasının Java aracılığıyla Birleştirilmesi" h2="Java kodunu kullanarak iki veya daha fazla Excel dosyasını tek bir elektronik tabloda birleştirin" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel Kitaplığı](/cells/java/) formüller, resimler, veriler, çizelgeler vb. gibi çeşitli içerik türleriyle çalışma kitaplarını tek bir elektronik tablo belgesinde birleştirmenin birden çok yolunu sunar. Desteklenen dosya biçimleri arasında XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV ve daha fazlası bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyalarını Görüntüler ve Grafiklerle Birleştirin" %}}
Görüntüleri ve çizelgeleri olan iki Excel dosyasını birleştirmenin en basit yolu, [Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) yöntem. Benzer türdeki Excel dosyalarını tek bir elektronik tabloda birleştirmeye izin verir.
{{% blocks/products/pf/feature-page-code h3="Java Excel Dosyalarını Birleştirme Kodu" %}}

```cs
// ilk Excel dosyasını yükle
var book1 = new Workbook("with-charts.xlsx");
// ikinci Excel dosyasını ayrı bir örneğe yükleyin
var book2 = new Workbook("with-images.xlsx");

// iki çalışma kitabını birleştir
book1.combine(book2);
// hedef çalışma kitabını kaydet 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Birden Fazla Excel Dosyasını Birleştirme" %}}
[CellsHelper.mergeDosyalar](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) yöntemi, bir Excel dosyasının verilerini, stilini ve formüllerini aynı formatta yeni bir elektronik tabloyla birleştirmeyi destekler. Önbelleğe almayı kullanırken birkaç dosyayı birleştirmenin etkili bir yoludur. 
{{% blocks/products/pf/feature-page-code h3="Java Birkaç Excel Dosyasını Birleştirme Kodu" %}}

```cs
// bir Dizi oluştur (uzunluk=2)
String[] files = new String[2];
// birleştirilecek dosya yollarını belirtin
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// sonucu kaydetmek için dosyaları birleştirin
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Çalışma Sayfalarını Kopyalayarak Excel Dosyalarını Birleştirme" %}}
[çalışma sayfası.kopya](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)bir kaynak çalışma sayfasından çalışma kitaplarının içinde veya arasında başka bir çalışma sayfasına veri kopyalamak ve biçimlendirmek için kullanılabilir. Yöntem, kaynak çalışma sayfası nesnesini parametre olarak alır.
{{% blocks/products/pf/feature-page-code h3="Java Çalışma Sayfalarını Çalışma Kitapları Arasında Kopyalama Kodu" %}}

```cs
// Bir Çalışma Kitabı oluşturun.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Başka bir Çalışma Kitabı oluşturun.
Workbook excelWorkbook1 = new Workbook();

// İlk kitabın ilk sayfasını ikinci kitaba kopyalayın.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Dosya 'yı kaydet.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}