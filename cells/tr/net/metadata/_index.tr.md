---
title: .NET C# aracılığıyla Excel Dosya Meta Verilerini Yönetin

description: Yalnızca birkaç satır C# koduyla Excel dosyalarının meta verilerini görüntüleyin, ekleyin, düzenleyin, kaldırın veya çıkarın
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Meta Verilerini .NET aracılığıyla yönetin" h2="Sunucu tarafı .NET API\'lerini kullanarak yerleşik ve özel Excel dosya özelliklerini görüntüleyin, ekleyin, güncelleyin, kaldırın veya çıkarın." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/net/) ad-değer çifti biçimindeki kullanıcı tanımlı (özel) özelliklerin yanı sıra başlık, yazar adı, belge istatistikleri vb. gibi sistem tanımlı (yerleşik) özelliklerin yönetimini destekler. Orada [çalışma kitabı sınıfı](https://reference.aspose.com/cells/net/aspose.cells/workbook) dosyaları yüklemek için ve [Çalışma SayfasıKoleksiyon](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) çalışma sayfalarının toplanmasıyla da ilgilenir. [çalışma sayfası sınıfı](https://reference.aspose.com/cells/net/aspose.cells/worksheet) tek çalışma sayfasını temsil etmek için. Bu sınıflarla birlikte BuiltInDocumentProperties, CustomDocumentProperties, meta veri yönetimi için süreci basitleştirir. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Yerleşik Özellikleri Yönetme" %}}

Sistem tanımlı özellikleri yönetmek için API şunları sağlar: [YerleşikDocumentÖzellikler](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties)ve programcılar yerleşik bir özelliğe kolayca erişebilir ve değerini güncelleyebilir. Uygulama gereksinimlerine bağlı olarak geliştiriciler, dizin veya özellik adını şu adresten kullanabilir: [DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Yerleşik Özellikleri Yönetmek için Kod" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Özel Tanımlı Özellikleri Yönetme" %}}

Kullanıcı tanımlı özellikleri yönetmek için API şunları sağlar: [CustomDocumentProperties](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties)ve geliştiriciler, önceden eklenmiş özelliklere kolayca erişebilir ve yeni özellikler ekleyebilir. Özel özellikler eklemek için, [Yöntem ekle](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) ile ilgili [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class özelliği ekler ve yeni özellik için bir referans olarak döndürür. [Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) nesne. DocumentProperty sınıfı, belge özelliğinin adını, değerini ve türünü şu şekilde almak için kullanılır: [DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) bunlardan birini döndüren [Emlak Tipi](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) numaralandırma değerleri. 
 
{{% blocks/products/pf/feature-page-code h3="C# Excel Dosyasına Meta Veri Ekleme Kodu" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Excel Dosyasındaki Özel Özelliği Kaldırma Kodu" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
