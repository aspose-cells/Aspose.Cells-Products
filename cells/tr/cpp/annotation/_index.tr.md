---
title: C++ aracılığıyla Excel Dosya Ek Açıklamaları
description: C++ kitaplığı ile Excel ve OpenOffice elektronik tablolarının veri açıklama yorumlarını ekleyin veya kaldırın.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Ek Açıklamalarını C++ aracılığıyla yönetin" h2="C++ tabanlı uygulamalarda açıklama veya yorumlar için basit notlar ekleyin veya kaldırın." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/tr/cpp/) yorumlar ekleyerek, bunlara erişerek ve yorumları kaldırarak ek açıklamaları hücre düzeyinde yönetme desteği sağlar. API sağlar[BenYorum](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment) Ve[Yorum Koleksiyonu](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) birlikte[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)tüm yönleriyle yorumları işlemek için. Desteklenen Excel biçimleri arasında ODS, XLS, XLSX, XLSB ve XLSM bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyaları Veri Açıklamaları" %}}
 Çalışma Sayfalarındaki Yorumların Değiştirilmesi - MS Excel'de bir sayfanın yorum sayısı sınırlı değildir. Uygulama ihtiyacı kadar ekleme yapılabilir. Yorum ekleme süreci, oluşturmaktır[IÇalışma Kitabı](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) varolan bir dosyayı yüklemek için class nesnesini kullanın ve yorumu eklemek istediğiniz çalışma sayfasını seçin. GetComments() kullanarak tüm yorumlarını alın. kullanarak yorumu ekleyin[Eklemek](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384) (intrusive_ptr< Aspose::Cells::Systems::String > hücreAdı) yöntemi. Hücre dizinini alın ve kullanın[not ayarla](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580) yorum eklemek için. Ayrıca API tüm yorumları silme özelliğine sahiptir. yöntemlerden birkaçı[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) Tasarımcı elektronik tablosundaki tüm yorumları temizler. Dahası,[KaldırAt](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusive_ptr< Aspose::Cells::Systems::String > name) belirtilen bir dizindeki veya belirtilen ada sahip öğeyi kaldırmak için yöntem.

{{% blocks/products/pf/feature-page-code h3="C++ Excel Dosyasına Yorum Ekleme Kodu" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
