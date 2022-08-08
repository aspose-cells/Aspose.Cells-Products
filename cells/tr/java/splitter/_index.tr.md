---
title: Excel Elektronik Tablosunu Java içinde Çalışma Sayfalarına Böl
url: /tr/java/splitter/
description: Java Excel kitaplığı kullanılarak Microsoft Excel dosyalarının birden çok belgeye nasıl bölüneceğini açıklayan Java kaynak kodları
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosyasını Java aracılığıyla Bölme" h2="Java tabanlı uygulamalarda Excel elektronik tablosunu çalışma sayfalarına ayırın" >}}
{{% blocks/products/pf/feature-page-summary %}}
Her öğrenci için tek bir sayfa tahsisi ile öğrenci verilerini içeren bir elektronik tablo gibi Excel dosyalarını bölmek gerektiğinde, çeşitli senaryolar vardır. Ve her bir yaprağı öğrenciyi ayrı bir dosya olarak akıllıca bölmeye ihtiyaç vardır. Java uygulaması üzerinden otomatikleştirmek için, [Java Excel API](/cells/java/) Excel belgesini sayfa bazında bölmek için var mı? Desteklenen formatlar arasında XLS, XLSX, XLSB, XLSM, ODS bulunur. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Belgesini Birden Çok Dosyaya Böl" %}}

Excel dosyasını sayfaya bölmenin en basit yolu, Tüm sayfalara erişin, her bir sayfa boyunca yineleyin ve istediğiniz biçimde birer birer kaydedin. Çalışma sayfasını yüklemek için API şunları sağlar: [Çalışma kitabı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) sınıf. [getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) yöntem toplam sayfa sayısını alır. Her sayfada yineleyin ve kullanın [getWorksheets().get(sheetindex)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) belirli bir sayfaya erişmek için. Seçili sayfa verilerini kullanarak yeni oluşturulan Çalışma Kitabı sınıf nesnesine taşıyın. [Kopyalama yöntemi](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Son olarak gerekli formatta kaydedin.

{{% blocks/products/pf/feature-page-code h3="Java Excel Dosyalarını Bölmek İçin Kod" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Excel Çalışma Sayfasını Bölmelere Böl" %}}

API ayrıca Excel çalışma sayfasını farklı bölmelere ayırma işlevi de sağlar. İşlem, Dosyayı Workbook sınıfını kullanarak yükleyin. Dizini sağlayarak ilk çalışma sayfasını veya gerekli herhangi bir sayfayı seçin. Parametre olarak ilgili hücre indeksine sahip setActiveCell'i çağırın. Ve son olarak split() yöntemini çağırarak çalışma sayfası penceresini farklı bölmelere ayırın.

{{% blocks/products/pf/feature-page-code h3="Java Excel Sayfasını Bölme Görünümüne Bölme Kodu" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}