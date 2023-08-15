---
title: C++ 経由の Excel ファイルの注釈
description: C++ ライブラリを使用して Excel および OpenOffice スプレッドシートのデータ注釈コメントを追加または削除します。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Excel ファイルの注釈を C++ 経由で管理する" h2="C++ ベースのアプリケーション内の注釈またはコメントの簡単なメモを追加または削除します。" >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ エクセル API](/cells/ja/cpp/)コメントの追加、アクセス、削除によりセル レベルで注釈を管理するためのサポートを提供します。 APIが提供します[Iコメント](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment)そして[Iコメントコレクション](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection)同様に[GetIComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a)あらゆる面でコメントを処理します。サポートされている Excel 形式には、ODS、XLS、XLSX、XLSB、XLSM が含まれます。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Excel ファイル データの注釈" %}}
ワークシート内のコメントの操作 - MS Excel では、シートに含まれるコメントの数に制限はありません。アプリケーションに必要なだけ挿入できます。コメントを挿入するプロセスは、[Iワークブック](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)クラス オブジェクトを使用して既存のファイルをロードし、コメントを追加するワークシートを選択します。 getComments() を使用してすべてのコメントを取得します。を使用してコメントを追加します[追加](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(侵入_ptr< Aspose::Cells::Systems::String > cellName) メソッド。セルインデックスを取得して使用します[セットメモ](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_comment#a791b9d4e9bf3975709a7f93b5db09580)コメントを挿入するため。さらに、API はすべてのコメントを削除できます。いくつかの方法は、[ClearComments()](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) to デザイナー スプレッドシート内のすべてのコメントをクリアします。さらに、[削除場所](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(侵入_ptr< Aspose::Cells::Systems::String > name) メソッドを使用して、指定されたインデックスまたは指定された名前の要素を削除します。

{{% blocks/products/pf/feature-page-code h3="C++ Excel ファイル内にコメントを追加するコード" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
