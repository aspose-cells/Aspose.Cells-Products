---
title: Excel Dosyası Meta Verilerini C++ aracılığıyla yönetin
description: C++ kitaplığını kullanarak Excel dosyalarının meta verilerini görüntüleyin, ekleyin, düzenleyin, kaldırın veya çıkarın
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Belgesi Meta Verilerini C++ aracılığıyla yönetin" h2="C++ uygulamaları içindeki özel ve yerleşik Excel belge özelliklerini görüntüleyin, ekleyin, güncelleyin, kaldırın veya çıkarın." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Excel'de Meta Veri - Excel dosyası meta verileri nasıl görüntülenir, eklenir ve kaldırılır.[C++ Excel Kütüphanesi](/cells/tr/cpp/) kolaylaştırıcılar, yazar adı, başlık, belge istatistikleri vb. gibi yerleşik / sistem tanımlı özellikleri destekleyerek, bazen son dosyanın ne zaman değiştirildiğini veya kaydedildiğini kontrol etmek gibi özel / kullanıcı tanımlı özelliklerle birlikte kolay bir şekilde yapılır. ad/değer çiftleri. Süreci otomatikleştirmek için kütüphane, büyük meta veri Excel dosyalarının oluşturulmasını ve korunmasını destekler.[Çalışma kitabı](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)class Bir çalışma kitabını yola, akışa ve özel FileFormatType'a göre açar. Bu nedenle dosyayı daha sonraki işlemler için uygun yöntemle yükleyin. Aşağıda listelenen olasılıklardan birkaçı ve geliştiriciler, uygulama gereksinimlerine göre kodlarını kolayca geliştirebilirler.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Yerleşik Özellikleri Okuyun ve Güncelleyin" %}}

 Yerleşik özellikleri otomatikleştirmek için API şunu sağlar:[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) Elektronik tablonun tüm yerleşik belge özelliklerini temsil eden DocumentProperties koleksiyonunu döndüren yöntem. Tüm yerleşik özelliklere eriştikten sonra, GetTitle(), GetSubject() vb. gibi ilgili yöntemleri kullanarak ilgili özelliklere erişin. Özellikleri güncellemek için API, SetTitle, SetSubject, SetAuthor, SetComments vb. gibi yöntemleri sağlar.[yerleşik belge özelliği koleksiyonu](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) gerekli işlev için.

{{% blocks/products/pf/feature-page-code h3="C++ Okunacak Kod Sistem Tanımlı Özellikler" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Yerleşik Özellikleri Güncelleme Kodu" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Özel Tanımlı Özellikleri Görüntüleme ve Ekleme" %}}

Özel özelliklerin işlenmesi için API şunu sağlar:[Çalışma Kitabı::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) elektronik tablonun tüm özel belge özellikleri koleksiyonunu döndürür. İlk olarak bu yöntemle özel özelliklere erişen geliştiriciler, AddIDocumentProperty, AddLinkToContentProperty gibi özellikleri eklemek için ilgili yöntemleri kullanabilir ve benzer şekilde sırasıyla içeriğe ve bağlantılı aralığa bağlanan özel belge özellik değerini güncellemek için UpdateLinkedPropertyValue, UpdateLinkedRange'ı kullanabilir. Geliştiriciler ilgili yöntemi şuradan kullanabilir:[özel belge özelliklerinin toplanması](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Özel Özellikleri Görüntüleme Kodu" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Excel Dosyasına Meta Veri Ekleme Kodu" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
