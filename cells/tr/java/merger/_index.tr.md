---
title: Java'de Farklı Excel Dosyalarını Tek Bir Dosyada Birleştirin
description: Java'i kullanarak Excel dosyalarını birden çok sayfaya veya tek sayfaya birleştirin. Excel belgelerini PDF, Görseller ve HTML ile birleştirin, birleştirin veya birleştirin.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Birleştirme via Java" h2="Java kodunu kullanarak iki veya daha fazla Excel dosyasını tek bir e-tabloda birleştirin" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel Kütüphanesi](/cells/tr/java/)Formüller, resimler, veriler, grafikler vb. gibi çeşitli içerik türlerine sahip çalışma kitaplarını tek bir elektronik tablo belgesinde birleştirmenin birden çok yolunu sağlar. Desteklenen dosya formatları arasında XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV ve daha fazlası bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyalarını Görüntüler ve Grafiklerle Birleştirin" %}}
 Resim ve grafikler içeren iki Excel dosyasını birleştirmenin en basit yolu,[Çalışma kitabı.birleştirme](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) yöntem. Benzer türdeki Excel dosyalarını tek bir e-tabloda birleştirmenize olanak tanır.
{{% blocks/products/pf/feature-page-code h3="Java Excel Dosyalarını Birleştirme Kodu" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Birden Çok Excel Dosyasını Birleştir" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) yöntem, bir Excel dosyasının verilerini, stilini ve formüllerini aynı formatta yeni bir elektronik tabloyla birleştirmeyi destekler. Önbelleklemeyi kullanırken birden fazla dosyayı birleştirmenin etkili bir yoludur.
{{% blocks/products/pf/feature-page-code h3="Java Birkaç Excel Dosyasını Birleştirme Kodu" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Çalışma Sayfalarını Kopyalayarak Excel Dosyalarını Birleştirme" %}}
[Çalışma sayfası.kopya](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)), verileri ve biçimlendirmeyi kaynak çalışma sayfasından çalışma kitapları içindeki veya çalışma kitapları arasındaki başka bir çalışma sayfasına kopyalamak için kullanılabilir. Yöntem, kaynak çalışma sayfası nesnesini parametre olarak alır.
{{% blocks/products/pf/feature-page-code h3="Java Çalışma Sayfalarını Çalışma Kitapları Arasında Kopyalama Kodu" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Birleştirme Formatları" subTitle="Java\'i kullanarak, One ayrıca .. dahil olmak üzere diğer birçok dosya formatını da birleştirebilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Virgülle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Web Sayfası Arşiv Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="OpenDocument Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Sekmeyle Ayrılmış Değerler" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Metin belgesi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Excel İkili Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="İkili Excel Çalışma Kitabı Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Elektronik Tablo Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML Excel Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Excel Şablonu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Excel Makro Etkin Şablonu" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
