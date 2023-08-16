---
title: Excel Dosyası Meta Verilerini C++ aracılığıyla yönetin
description: C++ kitaplığını kullanarak Excel dosyalarının meta verilerini görüntüleyin, ekleyin, düzenleyin, kaldırın veya ayıklayın
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Document Metadata\'yı C++ aracılığıyla yönetin" h2="C++ uygulamalarında özel ve yerleşik Excel belge özelliklerini görüntüleyin, ekleyin, güncelleyin, kaldırın veya çıkarın." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Excel'de meta veriler - Excel dosyası meta verileri nasıl görüntülenir, eklenir ve kaldırılır.[C++ Excel Kitaplığı](/cells/tr/cpp/) En son dosyanın ne zaman değiştirildiğini veya kaydedildiğini kontrol etmek gibi bazen ihtiyaç duyulan yazar adı, başlık, belge istatistikleri vb. ad/değer çiftleri. Süreci otomatikleştirmek için kitaplık, büyük meta veri Excel dosyalarının oluşturulmasını ve sürdürülmesini destekler.[CreateIWorkbook yöntemi](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) ile ilgili[Fabrika Sınıfı](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory)Yola, akışa ve özel FileFormatType'a göre bir Çalışma Kitabı açın. Bu nedenle, daha fazla işlem için dosyayı uygun yöntemle yükleyin. Aşağıda listelenen olasılıklardan birkaçı ve geliştiriciler, uygulama gereksinimlerine göre kodlarını kolayca geliştirebilirler.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Yerleşik Özellikleri Okuyun ve Güncelleyin" %}}

 Yerleşik özellikleri otomatikleştirmek için API şunları sağlar:[GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) elektronik tablonun tüm yerleşik belge özelliklerini temsil eden bir DocumentProperties koleksiyonu döndüren yöntem. Tüm yerleşik özelliklere eriştikten sonra, ilgili özelliklere GetTitle(), GetSubject() vb. ilgili yöntemi kullanarak erişin. Özellikleri güncellemek için API, SetTitle, SetSubject, SetAuthor, SetComments vb.[yerleşik belge özellik koleksiyonu](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) Gerekli işlev için.

{{% blocks/products/pf/feature-page-code h3="C++ Sistem Tanımlı Özellikleri Okuma Kodu" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Yerleşik Özellikleri Güncelleme Kodu" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Özel Tanımlı Özellikleri Görüntüleyin ve Ekleyin" %}}

API, özel özellikleri işlemek için şunları sağlar:[IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) elektronik tablonun tüm özel belge özellikleri koleksiyonunu döndürür. Öncelikle bu yöntemle özel özelliklere erişen geliştiriciler, AddIDocumentProperty, AddLinkToContentProperty gibi özellikler eklemek için ilgili yöntemleri kullanabilir ve benzer şekilde sırasıyla içeriğe ve bağlantılı aralığa bağlanan özel belge özelliği değerini güncellemek için UpdateLinkedPropertyValue, UpdateLinkedRange'i kullanabilir. Geliştiriciler ilgili yöntemi şu adresten kullanabilir:[özel belge özelliklerinin toplanması](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Özel Özellikleri Görüntülemek İçin Kod" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Excel Dosyasına Meta Veri Ekleme Kodu" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
