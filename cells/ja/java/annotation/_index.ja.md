---
title: JavaによるExcelファイルの注釈
url: /ja/java/annotation/
description: Javaライブラリを使用してExcelおよびOpenOfficeスプレッドシートのデータ注釈を追加または削除します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してMicrosoft<sup>＆reg; </sup>Excelファイル注釈を管理する" h2="注釈用の簡単なメモを挿入するか、Javaベースのアプリケーション内のExcelスプレッドシートのセルレベルのコメントを削除します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) コメントを追加、アクセス、削除することにより、セルレベルで注釈を管理するためのサポートを提供します。 APIは提供します [コメント](https://reference.aspose.com/cells/java/com.aspose.cells/Comment)、 [CommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CommentCollection)、 [ThreadedComment](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) と [ThreadedCommentCollection](https://reference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) すべての面でコメントを処理するため。
サポートされているファイル形式には、ODS、XLS、XLSX、XLSB、XLSMがあります。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excelファイルのデータ注釈" %}}
ワークシートでのコメントの管理-MSExcelでシートに含まれるコメントの数に制限はありません。アプリケーション要件と同じ数を追加できます。コメントを追加するプロセスは、作成することです [ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) オブジェクトをクラス化するか、Workbookクラスを使用して既存のファイルをロードします。 getComments（）を使用してすべてのコメントにアクセスします。セルインデックスを取得して使用する [setNote](https://reference.aspose.com/cells/java/com.aspose.cells/comment#Note) コメントを挿入するため。さらに、APIはすべてのコメントを削除できます。 

{{% blocks/products/pf/feature-page-code h3="JavaExcelファイル内にコメントを追加するコード" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="JavaExcelファイル内のコメントを削除するコード" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}