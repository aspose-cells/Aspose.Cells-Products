---
title: Java aracılığıyla Excel Dosyası Açıklamaları
url: /tr/java/annotation/
description: Java kitaplığı ile Excel ve OpenOffice elektronik tablolarının veri açıklamalarını ekleyin veya kaldırın.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel Dosya Açıklamalarını Java aracılığıyla yönetin" h2="Açıklama için basit notlar ekleyin veya Java tabanlı uygulamalarda Excel elektronik tablo hücre düzeyindeki yorumları silin." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) yorum ekleyerek, bunlara erişerek ve silerek ek açıklamaları hücre düzeyinde yönetme desteği sağlar. API sağlar [Yorum](https://apireference.aspose.com/cells/java/com.aspose.cells/Comment), [YorumKoleksiyon](https://apireference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [DişliYorum](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) ve [DişliYorumKoleksiyon](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) yorumları her yönüyle ele almak için.
Desteklenen dosya biçimleri arasında ODS, XLS, XLSX, XLSB ve XLSM bulunur.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel Dosyaları Veri Açıklamaları" %}}
Çalışma Sayfalarında Yorumları Yönetme - MS Excel'de bir sayfada kaç yorum olacağı konusunda herhangi bir sınırlama yoktur. Uygulama gereksinimi kadar ekleme yapılabilir. Yorum ekleme işlemi, oluştur [Çalışma kitabı](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) Sınıf nesnesi veya Workbook sınıfını kullanarak mevcut bir dosyayı yükleyin. getComments() kullanarak tüm yorumlarına erişin. Hücre indeksini alın ve kullanın [setNot](https://apireference.aspose.com/cells/java/com.aspose.cells/comment#Note) yorum eklemek için. Ayrıca API, tüm yorumları kaldırabilir. 

{{% blocks/products/pf/feature-page-code h3="Java Excel Dosyasına Yorum Ekleme Kodu" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Excel Dosyasındaki Yorumları Kaldırma Kodu" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}