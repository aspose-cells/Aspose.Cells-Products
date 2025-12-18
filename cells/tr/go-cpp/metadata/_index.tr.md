---
title: Go ile Excel Dosya Meta Verilerini Yönetme (C++)
description: C++ kütüphanesi aracılığıyla Go kullanarak Excel dosyalarının meta verilerini görüntüleyebilir, ekleyebilir, düzenleyebilir, kaldırabilir veya çıkarabilirsiniz.
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Go aracılığıyla C++ numaralı Excel Belge Meta Verilerini Yönetin" h2="C++ uygulamaları içinde özel ve yerleşik Excel belge özelliklerini görüntüleyin, ekleyin, güncelleyin, kaldırın veya çıkarın." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Excel'de Meta Veriler - Excel dosyası meta verilerini görüntüleme, ekleme ve kaldırma.[C++ Excel Kütüphanesi üzerinden gidin.](/cells/tr/go-cpp/)Bu kütüphane, yazar adı, başlık, belge istatistikleri gibi yerleşik/sistem tanımlı özellikleri destekleyerek, dosyanın en son ne zaman değiştirildiğini veya kaydedildiğini kontrol etmek gibi bazen ihtiyaç duyulan bilgilerin yanı sıra, ad/değer çiftleri biçiminde özel/kullanıcı tanımlı özellikleri de destekleyerek süreci kolaylaştırır. Süreci otomatikleştirmek için, kütüphane büyük meta veri Excel dosyalarının oluşturulmasını ve yönetilmesini destekler.[Çalışma kitabı](https://reference.aspose.com/cells/go-cpp/workbook/) Bu sınıf, dosya yoluna, akışa ve özel FileFormatType'a göre bir çalışma kitabını açar. Bu nedenle, daha fazla işlem için dosyayı uygun yöntemle yükleyin. Aşağıda listelenen olasılıklardan bazıları sayesinde geliştiriciler, uygulama gereksinimlerine göre kodlarını kolayca geliştirebilirler.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dahili Özellikleri Okuyun ve Güncelleyin" %}}

 Dahili özelliklerin otomatikleştirilmesi için API numaralı kod kullanılır.[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Elektronik tablonun tüm yerleşik belge özelliklerini temsil eden bir DocumentProperties koleksiyonu döndüren yöntem. Tüm yerleşik özelliklere eriştikten sonra, GetTitle(), GetSubject() vb. ilgili yöntemleri kullanarak ilgili özelliklere erişin. Özellikleri güncellemek için, API, SetTitle, SetSubject, SetAuthor, SetComments vb. yöntemler sağlar.[yerleşik belge özellik koleksiyonu](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) Gerekli işlev için.

{{% blocks/products/pf/feature-page-code h3="Sistem Tanımlı Özellikleri Okumak için C++ Kodunu Kullanın" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Dahili özellikleri güncellemek için C++ kodunu kullanın." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Özel Tanımlı Özellikleri Görüntüleyin ve Ekleyin" %}}

 Özel mülklerin yönetimi için API numaralı telefon hizmet vermektedir.[Çalışma Kitabı::ÖzelBelgeÖzellikleriniAl](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)Bu yöntem, elektronik tablonun tüm özel belge özelliklerini döndürür. Geliştiriciler, öncelikle bu yöntem aracılığıyla özel özelliklere erişerek, AddIDocumentProperty, AddLinkToContentProperty gibi özellikleri eklemek için ilgili yöntemleri kullanabilir ve benzer şekilde, içeriğe ve bağlantılı aralığa bağlanan özel belge özelliği değerini güncellemek için UpdateLinkedPropertyValue, UpdateLinkedRange yöntemlerini kullanabilirler. Geliştiriciler, ilgili yöntemi kullanabilirler.[özel belge özelliklerinin koleksiyonu](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Özel mülkleri görüntülemek için C++ kodunu kullanın." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Excel dosyasına meta veri eklemek için C++ kodunu kullanın." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}