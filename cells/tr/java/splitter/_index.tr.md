---
title: Java'de Excel Elektronik Tablosunu Çalışma Sayfalarına Bölün
description: Java Microsoft Excel dosyalarının Java Excel kitaplığı kullanılarak birden çok belgeye nasıl bölüneceğini açıklayan kaynak kodları
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Bölme via Java" h2="Excel elektronik tablosunu Java tabanlı uygulamalarda çalışma sayfalarına ayırın" >}}
{{% blocks/products/pf/feature-page-summary %}}
 Çeşitli senaryolar vardır, Excel dosyalarını, öğrenci verilerini içeren bir elektronik tablo gibi, her öğrenci için tek bir sayfanın tahsis edilmesiyle bölmeye ihtiyaç duyulduğunda. Ve her sayfayı öğrenciye göre ayrı bir dosya olarak bölmeye ihtiyaç vardır. via Java uygulamasını otomatikleştirmek için,[Java Excel API](/cells/tr/java/) Excel belgesini sayfalara bölmek için var. Desteklenen biçimler arasında XLS, XLSX, XLSB, XLSM, ODS bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Belgesini Birden Çok Dosyaya Böl" %}}

Excel dosyasını sayfalara bölmenin en basit yolu, Tüm sayfalara erişin, her sayfayı yineleyin ve istediğiniz biçimde tek tek kaydedin. Çalışma sayfasını yüklemek için API şunları sağlar:[Çalışma kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıf.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) yöntem toplam sayfa sayısını alır. Her sayfa boyunca yineleyin ve kullanın[getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) belirli bir sayfaya erişmek için. Seçili sayfa verilerini kullanarak yeni oluşturulan Workbook sınıfı nesnesine taşıyın.[Kopyalama yöntemi](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Son olarak gerekli biçimde kaydedin.

{{% blocks/products/pf/feature-page-code h3="Java Excel Dosyalarını Bölme Kodu" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfasını Bölmelere Böl" %}}

API ayrıca Excel çalışma sayfasını farklı bölmelere bölme işlevi de sağlar. İşlem, Workbook sınıfını kullanarak dosyayı yükleyin. Dizini sağlayarak ilk çalışma sayfasını veya gerekli herhangi bir sayfayı seçin. Parametre olarak ilgili hücre indeksine sahip setActiveCell'i çağırın. Ve son olarak split() yöntemini çağırarak çalışma sayfası penceresini farklı bölmelere ayırın.

{{% blocks/products/pf/feature-page-code h3="Java Excel Sayfasını Bölme Görünümüne Bölme Kodu" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
