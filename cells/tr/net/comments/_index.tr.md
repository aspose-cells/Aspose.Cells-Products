---
title: .NET aracılığıyla Excel'e yorum ekleyin

description: .NET Kitaplığı kullanılarak Microsoft Excel dosyalarına nasıl yorum ekleneceğini gösteren C# kaynak kodları. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel yorumları .NET aracılığıyla ekleme" h2=".NET tabanlı uygulamalarda sunucu tarafı API\'lerini kullanarak Excel belgeleri oluşturun ve yorumlar ekleyin." >}}
{{% blocks/products/pf/feature-page-summary %}}

Hücrelere yorum ekleyebilirsiniz. Bir hücrenin yorumu olduğunda, hücrenin köşesinde bir gösterge belirir. İmlecinizi bir hücrenin üzerine getirdiğinizde yorumlar görünür. Bu yorumlar tartışma, özel talimatlar veya belge içeriğinin işaretlenmesi için kullanılabilir. [.NET Excel Kitaplığı](/cells/net/) Excel dosyalarına yorum eklemeyi destekler. Bunun için API, [Yorum](https://reference.aspose.com/cells/net/aspose.cells/comment) yorum yapı taşı sınıfı.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyasına yorum ekleme" %}}

Excel API kullanarak yorum eklemek basittir. İşlem, Oluştur [çalışma kitabı sınıfı](https://reference.aspose.com/cells/net/aspose.cells/workbook) nesne ve dizinini sağlayarak ilk çalışma sayfasını veya ilgili sayfayı seçin. kullanarak gerekli hücre verilerini ekleyin. [PutValue yöntemi](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index). kullanarak çalışma sayfasına yorum ekleyin. [YorumKoleksiyon](https://reference.aspose.com/cells/net/aspose.cells/commentcollection)'s [Yöntem ekle](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Excel\'de Yorum Ekleme Kodu" %}}

{{< gist "aspose-cells-gists" "88c9872508ec3150c552eb5155edf06e" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
