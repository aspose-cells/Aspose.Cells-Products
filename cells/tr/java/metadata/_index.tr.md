---
title: Excel Dosyası Meta Verilerini Yönetin via Java
description: Yalnızca birkaç satırlık Java koduyla Excel dosyalarının meta verilerini görüntüleyin, ekleyin, düzenleyin, kaldırın veya ayıklayın
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Yönet Microsoft<sup>&reg;</sup> Excel Dosyası Meta Verileri via Java" h2="Sunucu tarafı Java API\'lerini kullanarak özel ve yerleşik Excel dosya özelliklerini görüntüleyin, ekleyin, güncelleyin, silin veya çıkarın." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/tr/java/) başlık, yazar adı, belge istatistikleri gibi yerleşik (sistem tanımlı) özelliklerin yanı sıra ad/değer çifti biçimindeki özel (kullanıcı tanımlı) özelliklerin yönetimini destekler. Orada[Çalışma kitabı sınıfı](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) dosyaları yüklemek için ve[Çalışma Sayfası Koleksiyonu](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) çalışma sayfalarının toplanmasıyla ilgilenir ve[Çalışma sayfası sınıfı](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) tek çalışma sayfasını temsil etmek için. Yerleşik ve özel özelliklere erişmek için, BuiltInDocumentProperties, CustomDocumentProperties meta veri yönetimi için süreci basitleştirir.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Sistem Tanımlı Özellikleri Yönetme" %}}

 Yerleşik özellikleri yönetmek için API şunları sağlar:[Yerleşik Belge Özellikleri](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) ve programcılar yerleşik bir özelliğe kolayca erişebilir ve değerini güncelleyebilir. Uygulama gereksinimine bağlı olarak geliştiriciler, dizin veya özellik adını[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Sistem Tanımlı Özellikleri Yönetmek İçin Kod" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Özel Tanımlı Meta Veri Ekleme ve Kaldırma" %}}

API, özel özellikleri işlemek için şunları sağlar:[Özel Belge Özellikleri](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) ve geliştiriciler, kullanarak mevcut özelliklere kolayca erişebilir ve yeni özellikler ekleyebilir.[yöntem ekle](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) ile ilgili[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) class, özelliği ekler ve yeni özellik için bir başvuru döndürür.[Properties.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) nesne. DocumentProperty sınıfı, belge özelliğinin adını, değerini ve türünü şu şekilde almak için kullanılır:[DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) bu birini döndürür[Emlak Tipi](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) numaralandırma değerleri.
 
{{% blocks/products/pf/feature-page-code h3="Java Excel Dosyasına Meta Veri Ekleme Kodu" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Excel Dosyasındaki Özel Özelliği Silme Kodu" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
