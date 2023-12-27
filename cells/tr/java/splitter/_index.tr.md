---
title: Java'de Excel Elektronik Tablosunu Çalışma Sayfalarına Bölün
description: Java Excel kitaplığını kullanarak Microsoft Excel dosyalarının birden çok belgeye nasıl bölüneceğini açıklayan kaynak kodları
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Bölme via Java" h2="Java tabanlı uygulamalarda Excel elektronik tablosunu çalışma sayfalarına bölme" >}}
{{% blocks/products/pf/feature-page-summary %}}
Excel dosyalarını, öğrenci verilerini içeren bir elektronik tablo gibi bölmek gerektiğinde, her öğrenci için tek bir sayfa tahsis edilmesi gereken çeşitli senaryolar vardır. Ve her öğrenci sayfasını ayrı bir dosya halinde akıllıca bölmek gerekir. Otomatikleştirmek için via Java uygulamasını,[JavaExcel API](/cells/tr/java/) Excel belgesini sayfalar halinde bölmek için oradadır. Desteklenen formatlar arasında XLS, XLSX, XLSB, XLSM, ODS bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Belgesini Birden Çok Dosyaya Bölme" %}}

 Excel dosyasını sayfalara bölmenin en basit yolu, Tüm sayfalara erişmek, her sayfayı yinelemek ve istediğiniz formatta birer birer kaydetmektir. Çalışma sayfasını yüklemek için API şunu sağlar:[Çalışma kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıf.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) yöntem toplam sayfa sayısını alır. Her sayfayı yineleyin ve kullanın[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) Belirli bir sayfaya erişmek için. Seçilen sayfa verilerini kullanarak yeni oluşturulan Çalışma Kitabı sınıfı nesnesine taşıyın.[Kopyalama yöntemi](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Son olarak gerekli formatta kaydedin.

{{% blocks/products/pf/feature-page-code h3="Java Excel Dosyalarını Bölme Kodu" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfasını Bölmelere Böl" %}}

API ayrıca Excel çalışma sayfasını farklı bölmelere bölme işlevini de sağlar. İşlem, dosyayı Workbook sınıfını kullanarak yüklemektir. Dizinini sağlayarak ilk çalışma sayfasını veya gerekli herhangi bir sayfayı seçin. Parametre olarak ilgili hücre indeksine sahip setActiveCell'i çağırın. Ve son olarak split() yöntemini çağırarak çalışma sayfası penceresini farklı bölmelere bölün.

{{% blocks/products/pf/feature-page-code h3="Java Excel Sayfasını Bölme Görünümüne Bölme Kodu" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
