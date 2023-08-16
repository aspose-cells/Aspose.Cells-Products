---
title: Excel'de yorum ekleme via .NET
description:  C# kaynak kodları, .NET Kitaplığı kullanılarak Microsoft Excel dosyalarına nasıl yorum ekleneceği.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel yorum ekleme via .NET" h2=".NET tabanlı uygulamalarda sunucu tarafı API\'lerini kullanarak Excel belgeleri oluşturun ve yorumlar ekleyin." >}}
{{% blocks/products/pf/feature-page-summary %}}

 Hücrelere yorum ekleyebilirsiniz. Bir hücrede açıklama olduğunda, hücrenin köşesinde bir gösterge görünür. Yorumlar, imlecinizi bir hücrenin üzerine getirdiğinizde görünür. Bu yorumlar, tartışma, özel talimatlar veya belge içeriğini işaretlemek için kullanılabilir.[.NET Excel Kitaplığı](/cells/tr/net/)Excel dosyalarına yorum eklemeyi destekler. Bunun için API,[Yorum](https://reference.aspose.com/cells/net/aspose.cells/comment) yorumlar için sınıf yapı taşı.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyasına yorum ekleme" %}}

 Excel API kullanarak yorum eklemek basittir. İşlem, Yarat[Çalışma kitabı sınıfı](https://reference.aspose.com/cells/net/aspose.cells/workbook) nesnesini seçin ve dizinini vererek ilk çalışma sayfasını veya ilgili sayfayı seçin. Kullanarak gerekli hücre verilerini ekleyin[PutValue yöntemi](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Kullanarak çalışma sayfasına yorum ekleyin.[Yorum Koleksiyonu](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) 'S[yöntem ekle](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Excel\'de Yorum Ekleme Kodu" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
