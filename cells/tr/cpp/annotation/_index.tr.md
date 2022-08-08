---
title: C++ aracılığıyla Excel Dosyası Açıklamaları
url: /tr/cpp/annotation/
description: C++ kitaplığı ile Excel ve OpenOffice elektronik tablolarının veri açıklama yorumlarını ekleyin veya kaldırın.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Açıklamalarını C++ aracılığıyla yönetin" h2="C++ tabanlı uygulamalarda açıklama veya yorumlar için basit notlar ekleyin veya kaldırın." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) yorum ekleyerek, bunlara erişerek ve yorum kaldırarak ek açıklamaları hücre düzeyinde yönetme desteği sağlar. API sağlar [IYorum](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) ve [IYorum Koleksiyonu](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) birlikte [GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) yorumları her yönüyle ele almak için. Desteklenen Excel biçimleri arasında ODS, XLS, XLSX, XLSB ve XLSM bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyaları Veri Açıklamaları" %}}
Çalışma Sayfalarında Yorumları Manipüle Etme - MS Excel'de bir sayfada kaç yorum olduğu sınırlı değildir. Uygulama ihtiyacı kadar eklenebilir. Yorum ekleme işlemi, oluşturmaktır. [çalışma kitabı](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class nesnesini kullanarak mevcut bir dosyayı yükleyin ve yorumu eklemek istediğiniz çalışma sayfasını seçin. GetComments() kullanarak tüm yorumlarını alın. kullanarak yorumu ekleyin [Ekle](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(müdahaleci_ptr < Aspose::Cells::Systems::String > cellName) yöntemi. Hücre indeksini alın ve kullanın [setNot](https://reference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) yorum eklemek için. Ayrıca API, tüm yorumları kaldırabilir. Yöntemlerden birkaçı [Yorumları Temizle()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) Tasarımcı elektronik tablosundaki tüm yorumları temizler. Dahası, [RemoveAt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(müdahaleci_ptr< Aspose::Cells::Systems::String > name) yöntemi, belirtilen dizindeki veya belirtilen ada sahip öğeyi kaldırır.

{{% blocks/products/pf/feature-page-code h3="C++ Excel Dosyasına Yorum Ekleme Kodu" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}