---
title: C++ aracılığıyla Excel Dosyası Açıklamalarını Ekleme veya Kaldırma
description: C++ kitaplığıyla Excel ve OpenOffice elektronik tablolarının veri açıklaması yorumlarını ekleyin veya kaldırın.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosyası Ek Açıklamalarını C++ aracılığıyla yönetin" h2="C++ tabanlı uygulamalarda açıklama veya yorumlar için basit notlar ekleyin veya kaldırın." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++Excel API](/cells/tr/cpp/) Yorumlar ekleyerek, bunlara erişerek ve kaldırarak ek açıklamaları hücre düzeyinde yönetme desteği sağlar. API sağlar[Yorum](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) Ve[YorumKoleksiyonu](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) birlikte[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)Yorumları her yönüyle ele almak için. Desteklenen Excel biçimleri arasında ODS, XLS, XLSX, XLSB ve XLSM bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyalarındaki Veri Ek Açıklamaları" %}}
 Çalışma Sayfalarındaki Yorumları Değiştirme - MS Excel'de bir sayfanın kaç yoruma sahip olduğu sınırlı değildir. Uygulama ihtiyacı kadar ekleyebilirsiniz. Yorum ekleme işlemi şu şekildedir:[Çalışma kitabı](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) Mevcut bir dosyayı yüklemek için sınıf nesnesini kullanın ve yorumu eklemek istediğiniz çalışma sayfasını seçin. GetComments() işlevini kullanarak tüm yorumlarını alın. kullanarak yorumu ekleyin[Ekle(const char16_t* hücreAdı)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) yöntem. Hücre indeksini alın ve kullanın[SetNote](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) yorum eklemek için. Üstelik API tüm yorumları kaldırma özelliğine sahiptir. Yöntemlerden birkaçı[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) Tasarımcı e-tablosundaki tüm yorumları temizler. Dahası,***KaldırAt*** Belirtilen dizindeki veya belirtilen addaki öğeyi kaldırma yöntemi.

{{% blocks/products/pf/feature-page-code h3="C++ Excel Dosyasına Yorum Ekleme Kodu" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
