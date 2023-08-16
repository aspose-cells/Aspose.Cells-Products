---
title: Excel Dosyası Meta Verilerini Yönet via .NET C#
description: Yalnızca birkaç satırlık C# koduyla Excel dosyalarının meta verilerini görüntüleyin, ekleyin, düzenleyin, kaldırın veya ayıklayın
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Yönet Microsoft<sup>&reg;</sup> Excel Dosyası Meta Verileri via .NET" h2="Sunucu tarafı .NET API\'lerini kullanarak yerleşik ve özel Excel dosya özelliklerini görüntüleyin, ekleyin, güncelleyin, kaldırın veya çıkarın." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Excel API](/cells/tr/net/) başlık, yazar adı, belge istatistikleri gibi sistem tanımlı (yerleşik) özelliklerin yanı sıra ad-değer çifti biçiminde kullanıcı tanımlı (özel) özelliklerin yönetimini destekler. Orada[Çalışma kitabı sınıfı](https://reference.aspose.com/cells/net/aspose.cells/workbook) dosyaları yüklemek için ve[Çalışma Sayfası Koleksiyonu](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection)çalışma sayfalarının toplanmasıyla ilgilenir ve[Çalışma sayfası sınıfı](https://reference.aspose.com/cells/net/aspose.cells/worksheet) tek çalışma sayfasını temsil etmek için. Bu sınıflar olan BuiltInDocumentProperties ile birlikte CustomDocumentProperties, meta veri yönetimi için süreci basitleştirir.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Yerleşik Özellikleri Yönetme" %}}

 Sistem tanımlı özellikleri yönetmek için API şunları sağlar:[Yerleşik Belge Özellikleri](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) ve programcılar yerleşik bir özelliğe kolayca erişebilir ve değerini güncelleyebilir. Uygulama gereksinimine bağlı olarak geliştiriciler, dizin veya özellik adını[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Yerleşik Özellikleri Yönetmek İçin Kod" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Özel Tanımlı Özellikleri Yönetme" %}}

 API, kullanıcı tanımlı özellikleri yönetmek için şunları sağlar:[Özel Belge Özellikleri](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) ve geliştiriciler, önceden eklenmiş özelliklere kolayca erişebilir ve yeni özellikler ekleyebilir. Özel özellikler eklemek için,[yöntem ekle](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) ile ilgili[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) class, özelliği ekler ve yeni özellik için bir başvuru döndürür.[Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty)nesne. DocumentProperty sınıfı, belge özelliğinin adını, değerini ve türünü şu şekilde almak için kullanılır:[DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) bu birini döndürür[Emlak Tipi](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) numaralandırma değerleri.
 
{{% blocks/products/pf/feature-page-code h3="C# Excel Dosyasına Meta Veri Ekleme Kodu" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Excel Dosyasındaki Özel Özelliği Kaldırma Kodu" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
