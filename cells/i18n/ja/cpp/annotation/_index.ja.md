---
title: C++によるExcelファイルの注釈
url: /ja/cpp/annotation/
description: C++ライブラリを使用してExcelおよびOpenOfficeスプレッドシートのデータ注釈コメントを追加または削除します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C++を介してMicrosoft<sup>＆reg; </sup>Excelファイル注釈を管理する" h2="C++ベースのアプリケーション内の注釈またはコメントの簡単なメモを追加または削除します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) コメントを追加、アクセス、削除することにより、セルレベルで注釈を管理するためのサポートを提供します。 APIは提供します [IComment](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) と [ICommentCollection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) と同様 [GetIComments（）](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) すべての面でコメントを処理するため。サポートされているExcel形式には、ODS、XLS、XLSX、XLSB、およびXLSMが含まれます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excelファイルのデータ注釈" %}}
ワークシートでのコメントの操作-MSExcelでシートに含まれるコメントの数に制限はありません。アプリケーションに必要なだけ挿入できます。コメントを挿入するプロセスは、作成することです [IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) クラスオブジェクトを使用して既存のファイルをロードし、コメントを追加するワークシートを選択します。 getComments（）を使用してすべてのコメントを取得します。を使用してコメントを追加します [追加](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)（intrusive_ptr < Aspose::Cells::Systems::String > cellName）メソッド。セルインデックスを取得して使用する [setNote](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) コメントを挿入するため。さらに、APIはすべてのコメントを削除することができます。いくつかの方法は [ClearComments（）](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) toデザイナースプレッドシートのすべてのコメントをクリアします。さらに、 [RemoveAt](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)（intrusive_ptr< Aspose::Cells::Systems::String > name）指定されたインデックスまたは指定された名前の要素を削除するメソッド。

{{% blocks/products/pf/feature-page-code h3="C++Excelファイル内にコメントを追加するコード" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}